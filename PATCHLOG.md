# Patch Log

## 2.1.5-patch1 (2017-09-11)

- :warning: Change package name to `elfsundae/laravel-captcha`
  You should **replace** `mews/captcha` to `elfsundae/laravel-captcha` in your app's `composer.json` file
- :warning: Remove default routes, you may define your own [#87](https://github.com/mewebstudio/captcha/issues/87), [dd2fdee](https://github.com/ElfSundae/laravel-captcha/commit/dd2fdee9ca714f9015d738d3ce8edda3240bcf1d)

    ```php
    Route::get('captcha/{config?}', '\Mews\Captcha\CaptchaController@getCaptcha');
    ```

- Add Laravel package auto-discovery [5cd0328](https://github.com/ElfSundae/laravel-captcha/commit/5cd03281c58ad9242ed0b1799ba75105f8c3990a)
- Fix getting fonts list on Laravel 5.5 [e17da3e](https://github.com/ElfSundae/laravel-captcha/commit/e17da3e36bb39b20f388943f136593271efd1361)
