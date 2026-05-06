kifech tsoba aandek


1. Clone the repo:

git clone https://github.com/username/nom-repo.git

2. open floder:

cd nom-repo

3. create your branch:

git checkout -b ismek

4. import the laravel component:

composer install

5. creat .env file:

cp .env.example .env

6. generate key:

php artisan key:generate

7. relatione db in .env file:

DB_DATABASE=nom_base
DB_USERNAME=root
DB_PASSWORD=

8. start migrations:

php artisan migrate

9. start serveur:

php artisan serve

10. repeat this if yo do any thing :

git add .
git commit -m "mon travail"
git push -u origin ismek
