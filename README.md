# PayAdvance — Web App Files

## ไฟล์ทั้งหมด
- `index.html`   — Landing Page + Register + Admin Login
- `worker.html`  — หน้าคนงานเบิกเงิน (เข้าได้ที่ /COMP0001)
- `admin.html`   — Admin Dashboard (เข้าได้ที่ /admin/COMP0001)
- `_redirects`   — กำหนด URL routing สำหรับ Cloudflare Pages
- `README.md`    — ไฟล์นี้

## ก่อน Upload ต้องแก้ไข GAS_URL ใน 3 ไฟล์

หา `วาง_WEB_APP_URL_ของ_APPS_SCRIPT_ที่นี่` แล้วแทนที่ด้วย Web App URL จาก Apps Script
ต้องแก้ใน: index.html, worker.html, admin.html

## URL Structure
- Landing / Register: https://payadvance.pages.dev/
- Worker:             https://payadvance.pages.dev/COMP0001
- Admin:              https://payadvance.pages.dev/admin/COMP0001
