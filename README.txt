ExamShield - website tinh cho Vercel

Upload index.html va vercel.json vao thu muc goc cua repository.
Khong can package.json, npm, Vite, src hoac assets.

Neu Vercel van chay vite build:
Project > Settings > Build and Deployment
- Framework Preset: Other
- Build Command: bat Override va de trong
- Output Directory: .
- Install Command: bat Override va de trong
Sau do Redeploy khong dung cache.
