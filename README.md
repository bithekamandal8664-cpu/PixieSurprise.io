```bash
git clone https://github.com/bithekamandal8664-cpu/PixieSurprise.io
cd PixieSurprise.io
python -m http.server 8000
cloudflared tunnel --url http://localhost:8000
```
