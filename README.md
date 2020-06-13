# empty/empty

> composer require empty/empty

Composer package with no code and no dependency

## Why ?

Testing purposes.

Also, I found that an easy way to regenerate a `composer.lock` file and its `content-hash` was to do:

```bash
composer require empty/empty
composer remove empty/empty
```

(alternative: `composer update nothing`)
