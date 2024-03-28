```bash
pnpm install
pnpm run build
docker build -t theapp .
docker run --env-file .env -p 3000:3000 theapp
```