# Тест проект newman


## Запуск newman 
    https://www.npmjs.com/package/newman#junitxml-reporter

## Репорт newman-reporter
    https://www.npmjs.com/package/newman-reporter-html


#### Кастомизация report:
    https://github.com/postmanlabs/newman-reporter-html/blob/develop/lib/template-default.hbs
#### Allure report

    https://www.npmjs.com/package/newman-reporter-allure
    install:
    npm install -g newman-reporter-allure
    Usage
    newman run <Collection> -e <Environment> -r allure
    $ newman run <Collection> -e <Environment> -r allure --reporter-allure-export <allure-results-out-dir>
    Generating and Serving Allure report
    allure serve
    allure generate --clean

## Установка
	npm install -g newman
	npm install -g newman-reporter-html
	This installs Newman globally on your system allowing you to run it from anywhere.
	If you want to install it locally, Just remove the -g flag.
	brew install newman

## Запуск тестов
    newman run C:\test\test_collection.postman_collection.json -e C:\test\test_newman_env.postman_environment.json

примеры коллекций в ../projectDir/test/resources/*.json
