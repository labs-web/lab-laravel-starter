# lab-laravel-starter

## Travail a faire
 
Creation d'une application laravel avec des packages que nous utillisons

## Packages

- Laravel ui adminlte
    - https://infyom.com/open-source/laravel-ui-adminlte/docs

- Flash
  - https://github.com/laracasts/flash

- Laravel/collective
  - https://github.com/LaravelCollective/html


## Realisation

```bash
composer create-project laravel/laravel laravel-starter
```

```bash

composer require infyomlabs/laravel-ui-adminlte

```
```bash

php artisan ui adminlte --auth

```

<!-- TODO : Ajouter une explication sur comment utiliser run build ou run dev -->

```bash
npm install
npm run build
```

```bash
composer require laracasts/flash

```
A copie dans fichier config/app.php

```Json
'providers' => [
    Laracasts\Flash\FlashServiceProvider::class,
],

'aliases' => [
    'Flash' => Laracasts\Flash\Flash::class,
],
```

```bash
composer require laravelcollective/html

```

```Json
'providers' => [
    Collective\Html\HtmlServiceProvider::class,
],

'aliases' => [
  'Form' => Collective\Html\FormFacade::class,
  'Html' => Collective\Html\HtmlFacade::class,],
```





## Extension
- Markdown All in One
  - yzhang.markdown-all-in-one

- Todo Tree
  - Gruntfuggly.todo-tree





