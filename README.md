# BioTest Online — yangi versiya

## Nimalar ishlaydi
- O‘quvchi testga kiradi, bir necha marta ishlashi mumkin. Har bir urinish alohida saqlanadi.
- O‘qituvchi parol bilan kirib barcha urinishlar, boshlash/tugatish va sahifa ko‘rinishidagi o‘zgarishlarni ko‘radi.
- DOCX, DOC, TXT fayldan yangi test yuklash; avtomatik yangi test sifatida qo‘shiladi.
- Javob kalitlari o‘qituvchi tomonidan tasdiqlanadi; keyin natijalar qayta hisoblanadi.
- Reyting va CSV eksport.

## Internetga joylash
1. Ushbu papkani private GitHub repositoryga joylang.
2. PostgreSQL baza yarating (masalan, Render Postgres yoki Neon).
3. Render Web Service -> repository -> Build `npm install` -> Start `npm start`.
4. Environment: `ADMIN_PASSWORD` (uzun maxfiy parol), `DATABASE_URL` (Postgres ulanish satri). Kerak bo‘lsa `PGSSL=false` (faqat SSLsiz mahalliy bazada).
5. Deploy bo‘lgach Render bergan HTTPS manzilni o‘quvchilarga yuboring. O‘qituvchi kabinetiga parolingiz bilan kiring.

## Fayl formatiga talab
Savollar yangi satrda `1. Savol matni`, `2. Savol matni`; variantlar `A) javob`, `B) javob`, `C) javob`, `D) javob`. Faylni yuklagach savollarni tekshiring va kalitni belgilang. Rang/bold asosida avtomatik javob tanlash mavjud emas.

## Birinchi test
Manba DOC dan avtomatik ajratilgan savollar ichida ayrimlari buzilgan; to‘liq A-D variantlari bo‘lmagan savol kiritilmadi. Avvalgi demodagi 24 ta taxminiy kalit ham tekshirilishi kerak. Ishonchli baholash uchun o‘qituvchi barcha kalitlarni tasdiqlashi shart.

## Muhim
- Faqat sahifa yashirilishi, fokus va qaytish qayd etiladi; boshqa dastur ishlatilganini yoki ko‘chirishni aniqlamaydi.
- O‘quvchi ismni o‘zi kiritadi, shaxsni tasdiqlash yo‘q.
- Saytni internetga joylash uchun sizning hosting va baza hisoblaringizda amallar bajarilishi zarur; bu ZIP o‘zi ommaga ochiq havola emas.
- Ommaviy ishga tushirishdan oldin o‘quvchilarga kuzatuv haqida xabar bering, maxfiylik siyosati va ma’lumot saqlash muddatini belgilang.
