Nette bootstrap form renderer with tabs support
=============================

Simple nette bootstrap form renderer inspired by tomaj/nette-bootstrap-form


Installation
------------

```sh
composer require duse/nette-bootstrap-tabs-form
```

Usage
-----

```php
use Duse\Form\Renderer\BootstrapTabsRenderer;
use Nette\Application\UI\Form;

$form = new Form;
$form->setRenderer(new BootstrapTabsRenderer);
```

