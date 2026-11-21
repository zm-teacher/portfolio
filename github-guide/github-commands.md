![Github surati](../images/github.png)

# GitHub qo'llanmasi

## 1. GitHub hisobidan foydalanish
**Ta'rifi:** GitHub loyihalarni saqlash va hamkorlik uchun ishlatiladi.  
**Vazifasi:** Remote repositorylar va jamoaviy ishlarni boshqaradi.  
**Qachon:** Repozitoriyani internetda saqlaganda yoki jamoada ishlaganda.  
**Misol:** GitHub saytida hisobga kirish.

## 2. Repository yaratish
**Ta'rifi:** Loyiha uchun GitHubdagi masofaviy joy.  
**Vazifasi:** Kod, fayl, tarix va hujjatlarni saqlaydi.  
**Qachon:** Yangi loyihani ulashganda.  
**Misol:** **New repository** tugmasini bosish va nom berish.

## 3. README.md
**Ta'rifi:** Loyihaning asosiy tushuntiruvchi sahifasi.  
**Vazifasi:** Maqsad, tuzilma va ishga tushirishni ko'rsatadi.  
**Qachon:** Har bir repositoryni hujjatlashda.  
**Misol:** Repository ildizida `README.md` yaratish.

## 4. .gitignore
**Ta'rifi:** Kuzatilmasin kerak bo'lgan fayllarni belgilaydi.  
**Vazifasi:** Maxfiy va vaqtinchalik fayllarni historydan saqlaydi.  
**Qachon:** SSH kalitlari, loglar yoki build papkalarida.  
**Misol:** `.gitignore` ichiga `secret.txt` yozish.

## 5. git remote
**Ta'rifi:** Lokal repositoryni GitHub manziliga bog'laydi.  
**Vazifasi:** Masofaviy repository nomini va URLini saqlaydi.  
**Qachon:** `git init` qilingan loyihani GitHubga ulashda.  
**Misollar:** `git remote -v`; `git remote add origin <repo-url>`

## 6. git push
**Ta'rifi:** Lokal commitlarni GitHubga yuboradi.  
**Vazifasi:** Branchning masofaviy nusxasini yangilaydi.  
**Qachon:** Ishni GitHub bilan sinxronlashda.  
**Misol:** `git push origin main`

## 7. git pull
**Ta'rifi:** Masofaviy o'zgarishlarni yuklab joriy branchga qo'shadi.  
**Vazifasi:** Jamoaning so'nggi commitlarini oladi.  
**Qachon:** Ishni boshlashdan oldin yoki remote yangilanganda.  
**Misol:** `git pull origin main`

## 8. Issue
**Ta'rifi:** Vazifa, xato yoki taklifni kuzatish vositasi.  
**Vazifasi:** Muammo muallifi, izoh, teg va holatini boshqaradi.  
**Qachon:** Loyihaga vazifa yoki bug qo'shganda.  
**Misol:** GitHub **Issues > New issue** orqali issue ochish.

## 9. Pull Request
**Ta'rifi:** Bitta branchdagi o'zgarishni boshqa branchga taklif qiladi.  
**Vazifasi:** Kodni ko'rib chiqish, muhokama qilish va birlashtirishni boshqaradi.  
**Qachon:** Feature yoki hujjat ishlash tugaganda.  
**Misol:** GitHubda **Compare & pull request** tugmasi.

## 10. Fork
**Ta'rifi:** Boshqa foydalanuvchi repositorysining mustaqil nusxasi.  
**Vazifasi:** Asl loyihaga ruxsatsiz o'zgartirishsiz o'rganish va taklif qilish imkonini beradi.  
**Qachon:** Boshqa loyihaga hissa qo'shganda.  
**Misol:** Asosiy repository sahifasida **Fork**.

## 11. Clone
**Ta'rifi:** GitHub repositorysini lokal kompyuterga nusxalash.  
**Vazifasi:** Barcha fayl va commit tarixini oladi.  
**Qachon:** Loyiha ustida lokal ishlash kerak bo'lganda.  
**Misol:** `git clone https://github.com/user/repo.git`

## 12. Branch boshqaruvi
**Ta'rifi:** GitHubda loyihaning parallel tarixi.  
**Vazifasi:** Xususiyatlarni alohida yaratish va ko'rib chiqish imkonini beradi.  
**Qachon:** Oddiy loyihada feature yoki guide branchlari ustida ishlaganda.  
**Misol:** Branch dropdown orqali yangi branch ochish.

## 13. GitHub Actions
**Ta'rifi:** Repository ichida avtomatik ishlarni ishga tushiradi.  
**Vazifasi:** Test, build yoki deploy jarayonlarini avtomatlashtiradi.  
**Qachon:** Kod har push yoki PR bo'lganda tekshirilganda.  
**Misol:** `.github/workflows/test.yml` faylini yaratish.

## 14. GitHub Pages
**Ta'rifi:** Repositorydan statik veb-sayt joylashtirish xizmati.  
**Vazifasi:** HTML, CSS va JavaScript saytini URL orqali ko'rsatadi.  
**Qachon:** Portfolioni yoki hujjat saytini nashr qilishda.  
**Misol:** **Settings > Pages > Deploy from branch**.

## 15. Release
**Ta'rifi:** Loyiha versiyasining nashr qilishga tayyor paketini yaratish.  
**Vazifasi:** Teg, versiya izohi va yuklanadigan fayllarni saqlaydi.  
**Qachon:** Muhim ishlov berilgan versiya tayyor bo'lganda.  
**Misol:** **Releases > Draft a new release**.

## Repository yaratishning 5 bosqichi
1. GitHubga kirib **New repository**ni ochish.
2. Repository nomi va ko'rinish (Public yoki Private)ni tanlash.
3. Kerak bo'lsa `README.md` va `.gitignore`ni yaratish.
4. Lokal loyihani remote repositoryga bog'lash.
5. `git push -u origin main` buyrugi bilan birinchi commitlarni yuborish.

## Qo'llanma bo'yicha savol-javob

**1. Git va GitHub farqi nima?**  
Git lokal versiya boshqaruv vositasi, GitHub esa repositorylarni internetda saqlovchi xizmat.

**2. Pull Request nima uchun kerak?**  
O'zgarishni ko'rib chiqish, muhokama va tasdiqdan o'tkazish uchun.

**3. Forkning Pull Requestdan farqi nima?**  
Fork repo nusxasi; Pull Request nusxadagi o'zgarishni asl repoga taklif qiladi.

**4. Issue qanday ishlatiladi?**  
Xato, vazifa yoki taklifni nom va izoh bilan kuzatish uchun.

**5. GitHub Actions nima qiladi?**  
Push, PR yoki jadval bo'yicha test, build va boshqa ishlarni avtomatlashtiradi.
