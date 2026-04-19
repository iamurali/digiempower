# IndexNow setup

IndexNow lets Bing, Yandex, and other participating search engines re-crawl updated URLs the moment they change, instead of waiting for their crawler to re-visit.

## Key

Key file at repo root: [`f9f3120bd64614a5681c89153502ab53.txt`](./f9f3120bd64614a5681c89153502ab53.txt)
Key value (same as filename): `f9f3120bd64614a5681c89153502ab53`

Once deployed, the file must be reachable at:
`https://www.digiempowerindia.onprotal.in/f9f3120bd64614a5681c89153502ab53.txt`

## Submit a URL (after any content update)

```bash
curl "https://api.indexnow.org/indexnow?url=https%3A%2F%2Fwww.digiempowerindia.onprotal.in%2F&key=f9f3120bd64614a5681c89153502ab53"
```

## Submit a batch

```bash
curl -X POST "https://api.indexnow.org/indexnow" \
  -H "Content-Type: application/json; charset=utf-8" \
  -d '{
    "host": "www.digiempowerindia.onprotal.in",
    "key": "f9f3120bd64614a5681c89153502ab53",
    "keyLocation": "https://www.digiempowerindia.onprotal.in/f9f3120bd64614a5681c89153502ab53.txt",
    "urlList": [
      "https://www.digiempowerindia.onprotal.in/"
    ]
  }'
```

## Rotating the key

To rotate, generate a new 32-character hex string, rename the `.txt` file and update this doc. Use `python -c "import secrets; print(secrets.token_hex(16))"`.
