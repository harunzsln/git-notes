# git başlatmak için
git init

# git'e dosyaları ekle
git add .
git add insert.sql delete.sql update.sql

# commit yap
git commit -m "İlk commit"

# remote repository eklemek için
git branch -M master
git remote add origin <github url>
git push -u origin master

# bir kez ekledikten sonra sadece
git push origin master

# origindeki değişiklikleri çekmek için
git pull origin master

denemek icin ekleme yaptim