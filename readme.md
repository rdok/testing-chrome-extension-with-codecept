### Installation
```bash
git clone git@github.com:rdok/testing-browsers-extension-with-codeception.git
cd testing-browsers-extension-with-codeception/
composer install
java -jar selenium-server-standalone*
./vendor/bin/codecept run --env chrome
./vendor/bin/codecept run --env firefox
```