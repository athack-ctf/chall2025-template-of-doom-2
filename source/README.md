# Running This Challenge

Build
```
docker build -t athack-ctf/chall2025-template-of-doom-2:latest .
```

Run
```
docker run -d --name template-of-doom-2 \
  --hostname template-of-doom-2 \
  -p 52047:5000 \
  athack-ctf/chall2025-template-of-doom-2:latest
```