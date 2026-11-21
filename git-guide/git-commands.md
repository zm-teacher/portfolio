![Git surati](../images/git.png)

# Git komandalari qo'llanmasi

## 1. git init
**Ta'rifi:** Loyihada yangi Git repository yaratadi.  
**Vazifasi:** O'zgarishlarni kuzatish uchun `.git` bazasini yaratadi.  
**Qachon ishlatiladi:** Yangi lokal loyihani versiya boshqaruviga ulaganda.  
**Misol:** `git init`

## 2. git config
**Ta'rifi:** Git foydalanuvchi sozlamalarini belgilaydi.  
**Vazifasi:** Commit va identifikatsiya ma'lumotlarini saqlaydi.  
**Qachon ishlatiladi:** Birinchi o'rnatishda yoki hisobni almashtirganda.  
**Misollar:** `git config --global user.name "Ismingiz"`; `git config --global user.email "you@example.com"`

## 3. git status
**Ta'rifi:** Repositorydagi joriy holatni ko'rsatadi.  
**Vazifasi:** O'zgartrilgan, qo'shilgan va kuzatilmaydigan fayllarni ajratadi.  
**Qachon ishlatiladi:** Commitdan oldin va o'zgartirish holatini tekshirganda.  
**Misol:** `git status`

## 4. git add
**Ta'rifi:** Fayllarni commit uchun staging sohasiga qo'shadi.  
**Vazifasi:** Keyingi commitga kiritiladigan o'zgarishlarni belgilaydi.  
**Qachon ishlatiladi:** Fayllarni tayyorlashda.  
**Misollar:** `git add README.md`; `git add .`

## 5. git commit
**Ta'rifi:** Staged o'zgarishlarni repository tarixiga saqlaydi.  
**Vazifasi:** Loyiha holatining nomli nusxasini yaratadi.  
**Qachon ishlatiladi:** Bir ozgarish guruhi tugaganda.  
**Misol:** `git commit -m "Foydalanuvchi qo'llanmasini qo'shish"`

## 6. git log
**Ta'rifi:** Commitlar tarixini ko'rsatadi.  
**Vazifasi:** Muallif, sana va commit xabarlarini tekshiradi.  
**Qachon ishlatiladi:** O'tgan o'zgarishlarni qidirganda.  
**Misollar:** `git log`; `git log --oneline --graph --decorate`

## 7. git diff
**Ta'rifi:** Fayllardagi farqlarni ko'rsatadi.  
**Vazifasi:** Commitdan oldin o'zgarishlarni tekshiradi.  
**Qachon ishlatiladi:** Kuzatilgan yoki staged kodni solishtirganda.  
**Misollar:** `git diff`; `git diff --staged`

## 8. git branch
**Ta'rifi:** Branchlarni ko'rish, yaratish yoki o'chirishni boshqaradi.  
**Vazifasi:** Loyiha tarixining parallel yo'llarini ajratadi.  
**Qachon ishlatiladi:** Yangi funksiya yoki hujjat ustida mustaqil ishlaganda.  
**Misollar:** `git branch`; `git branch feature-guide`; `git branch -d feature-guide`

## 9. git switch
**Ta'rifi:** Boshqa branchga o'tadi.  
**Vazifasi:** Ishchi fayllarni tanlangan branch holatiga almashtiradi.  
**Qachon ishlatiladi:** Branchlar orasida ishlashni almashtirganda.  
**Misollar:** `git switch main`; `git switch -c new-guide`

## 10. git merge
**Ta'rifi:** Bir branchdagi commitlarni joriy branchga birlashtiradi.  
**Vazifasi:** Alohida ishlangan o'zgarishlarni bir tarixga jamlaydi.  
**Qachon ishlatiladi:** Mustaqil ish tugagach.  
**Misol:** `git switch main`; `git merge feature-guide`

> Bu qo'llanmadagi mashqlar uchun mavzuli branchlar bir-biriga merge qilinmaydi.

## 11. git remote
**Ta'rifi:** Masofaviy repository manzillarini boshqaradi.  
**Vazifasi:** Lokal va GitHub repositorylari o'rtasida bog'lanish yaratadi.  
**Qachon ishlatiladi:** Loyiha nusxasini serverga bog'lab, almashganda.  
**Misollar:** `git remote -v`; `git remote add origin https://github.com/user/repo.git`

## 12. git clone
**Ta'rifi:** Masofaviy repositoryning to'liq nusxasini yuklaydi.  
**Vazifasi:** Fayllar va Git tarixini yangi papkaga beradi.  
**Qachon ishlatiladi:** Yangi kompyuterda yoki mavjud loyihani yuklab olishda.  
**Misol:** `git clone https://github.com/user/repo.git`

## 13. git revert va git reset
**Ta'rifi:** Hozirgi holatga yoki eski commitga qaytish usullarini beradi.  
**Vazifasi:** `git revert` yangi teskari commit yaratadi; `git reset` ko'rsatilgan holatga yoyishni boshqaradi.  
**Qachon ishlatiladi:** Xato o'zgarishni bekor qilishda.  
**Misollar:** `git revert HEAD`; `git reset --soft HEAD~1`; `git reset --hard HEAD~1`

**Diqqat:** `git reset --hard` saqlanmagan o'zgarishlarni o'chirishi mumkin. Ishlatishdan oldin ehtiyot bo'ling.

## Qo'llanma bo'yicha savol-javob

**1. Git nima uchun ishlatiladi?**  
Git kod va fayllarning o'zgarishlari tarixini saqlaydi.

**2. Commit nima?**  
Staging sohirasidagi o'zgarishlarning belgilangan vaqtdagi saqlangan nusxasi.

**3. Branch qanday yordam beradi?**  
Asosiy loyihani o'zgartirmasdan yangi xususiyat ustida parallel ishlash imkonini beradi.

**4. `.gitignore` nima qiladi?**  
Keraksiz yoki maxfiy fayllarning Gitga qo'shilishini oldini oladi.

**5. Push va pull orasidagi farq nima?**  
Push lokal commitlarni serverga yuboradi, pull esa serverdagi yangilanishlarni lokalga olib keladi.

## Tez tekshiruvlar
- Repository holati: `git status`
- Qisqa tarix: `git log --oneline`
- Branch ro'yxati: `git branch`
- Masofaviy manzillar: `git remote -v`
