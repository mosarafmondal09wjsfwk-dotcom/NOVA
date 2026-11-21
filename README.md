# NOVA
- `web/` — Gemini + Supabase ওয়েব অ্যাপ। `cd web/backend && npm install && cp .env.example .env` (key বসান) `&& npm start`। Supabase এ `web/supabase/schema.sql` চালান।
- `android/` — NOVA Android অ্যাপ (WebView + ভয়েস)। GitHub এ আপলোড করে Actions → Build APK → Run workflow।
- `.env` কখনো GitHub এ যাবে না (`.gitignore` এ আছে)।

## APK বানানোর ধাপ (ফোন/কম্পিউটার থেকে)
1. এই ZIP খুলে পুরো ফোল্ডারটি GitHub repository-তে আপলোড করুন (`.github` ফোল্ডারসহ, কাঠামো যেমন আছে তেমন)।
2. GitHub → **Actions** → **Build APK** → **Run workflow**।
3. শেষ হলে **nova-debug-apk** artifact ডাউনলোড করে `app-debug.apk` ইনস্টল করুন।
4. কোনো error এলে লগের লাল অংশটি কপি করে পাঠান।
