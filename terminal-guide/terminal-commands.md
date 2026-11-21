![Terminal surati](../images/terminal.png)

# Terminal qo'llanmasi

## 1. pwd
**Ta'rifi:** Joriy ish papkasini ko'rsatadi.  
**Vazifasi:** Terminal qaysi katalogda ekanini aniqlaydi.  
**Qachon:** Yangi buyruqdan oldin joylashuvni tekshirishda.  
**Misollar:** PowerShell: `Get-Location`; Bash: `pwd`

## 2. ls va Get-ChildItem
**Ta'rifi:** Papkadagi fayl va papkalarni ko'rsatadi.  
**Vazifasi:** Fayllar ro'yxatini ko'rib, nom va turini ajratadi.  
**Qachon:** Loyiha tarkibini tekshirganda.  
**Misollar:** PowerShell: `Get-ChildItem`; Git Bash: `ls`

## 3. cd
**Ta'rifi:** Joriy katalogni almashtiradi.  
**Vazifasi:** Terminalni boshqa papkaga o'tkazadi.  
**Qachon:** Loyiha papkasiga kirishda yoki undan chiqishda.  
**Misollar:** `cd ..`; `cd portfolio`

## 4. New-Item
**Ta'rifi:** Windows PowerShellda yangi fayl yoki papka yaratadi.  
**Vazifasi:** Bo'sh fayl yoki katalogni tez yaratadi.  
**Qachon:** Loyiha fayli yoki papkasini yaratishda.  
**Misollar:** Fayl: `New-Item README.md -ItemType File`; Papka: `New-Item src -ItemType Directory`

## 5. mkdir
**Ta'rifi:** Yangi papka yaratadi.  
**Vazifasi:** Loyiha tuzilmasida bo'limlarni ajratadi.  
**Qachon:** Resurs, test yoki kod papkasini qo'shganda.  
**Misol:** `mkdir images`

## 6. touch
**Ta'rifi:** Yangi bo'sh fayl yaratadi.  
**Vazifasi:** Windows PowerShell ekvivalenti `New-Item -ItemType File`.  
**Qachon:** Bo'sh Markdown yoki matn faylini yaratishda.  
**Misollar:** PowerShell: `New-Item test.txt -ItemType File`; Git Bash: `touch test.txt`
