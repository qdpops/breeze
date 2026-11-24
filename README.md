# Breeze skin for Roundcube

Read-only mirror of `skins/breeze` from [qdpops/roundcube-skin-breeze](https://github.com/qdpops/roundcube-skin-breeze), published for Composer. Issues and pull requests go to the main repository.

```bash
composer require qdpops/breeze
```

Composer also installs the companion plugin [`qdpops/tw-folders`](https://github.com/qdpops/tw-folders). Then in `config/config.inc.php`:

```php
$config['skin'] = 'breeze';
$config['plugins'][] = 'tw_folders';
$config['prettydate'] = false;
```

Roundcube 1.6, GPL-3.0-or-later.
