kifech tsoba aandek


1. Clone الـ repo
git clone https://github.com/username/nom-repo.git

2. ادخل للفولدر
cd nom-repo

3. نشئ برانشتك
git checkout -b ismek

4. جيب الـ vendor
composer install

5. نشئ ملف .env
cp .env.example .env

6. ولّد الـ key
php artisan key:generate

7. اضبط قاعدة البيانات في .env
DB_DATABASE=nom_base
DB_USERNAME=root
DB_PASSWORD=

8. شغّل الـ migrations
php artisan migrate

9. شغّل الـ serveur
php artisan serve

10. بعد ما تشتغل صب لبرانشتك
git add .
git commit -m "mon travail"
git push -u origin ismek
