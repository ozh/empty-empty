# test/test

> composer require test/test

Composer package with no code and no dependency

## Why ?

Testing purposes.

Also, I found that an easy way to regenerate a `composer.lock` file and its `content-hash` was to do:

```bash
composer require test/test
composer remove test/test
```

(before this feature is added to Composer 2.0)
