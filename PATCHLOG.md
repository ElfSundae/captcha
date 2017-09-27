# Patch Log

:warning: To use this patched package, you should **replace** `mews/captcha` to `elfsundae/laravel-captcha` in your app's `composer.json` file.

:warning: The default routes have been removed, you may define your own [#87](https://github.com/mewebstudio/captcha/issues/87), [dd2fdee](https://github.com/ElfSundae/laravel-captcha/commit/dd2fdee9ca714f9015d738d3ce8edda3240bcf1d)

```php
Route::get('captcha/{config?}', '\Mews\Captcha\CaptchaController@getCaptcha');
```

## [Unreleased]

- Change publish tag to "captcha" [02f3d0b](https://github.com/ElfSundae/laravel-captcha/commit/02f3d0b6de4ae03005face03dc9d1924e1a409cd)
- Use `Str` static methods instead of `$str` instance in `Captcha.php` [b7c826b](https://github.com/ElfSundae/laravel-captcha/commit/b7c826b3e01aa34d6c198675be548d72fdb57b42)

## 2.2.0 (2017-09-11)

- :warning: Change package name to `elfsundae/laravel-captcha`
- :warning: Remove default routes [dd2fdee](https://github.com/ElfSundae/laravel-captcha/commit/dd2fdee9ca714f9015d738d3ce8edda3240bcf1d)
- Support Laravel package auto-discovery [5cd0328](https://github.com/ElfSundae/laravel-captcha/commit/5cd03281c58ad9242ed0b1799ba75105f8c3990a)
- Fix getting fonts list on Laravel 5.5 [e17da3e](https://github.com/ElfSundae/laravel-captcha/commit/e17da3e36bb39b20f388943f136593271efd1361)
- Use Contracts instead of Laravel implementation [4ba5d2b](https://github.com/ElfSundae/laravel-captcha/commit/4ba5d2b9823d022f5105cdf350719560d5ade9fd)
- Fix Travis CI configuration
