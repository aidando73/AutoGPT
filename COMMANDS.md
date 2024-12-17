```bash
git submodule update --init --recursive
cd autogpt_platform

cp supabase/docker/.env.example .env
docker compose up -d --build

say 'done'; osascript -e 'display notification "done" with title "done"'

cd frontend
cp .env.example .env
npm install; imdone
npm run dev
```
