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

