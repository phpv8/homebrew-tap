phpv8/homebrew-tap
====================

This is a [homebrew](http://brew.sh/) [tap](https://docs.brew.sh/Taps) with various formulae for phpv8 and it dependencies.

See [phpv8/ppa-packaging](https://github.com/phpv8/ppa-packaging) repository for Ubuntu PPA packaging.

Just `brew tap phpv8/tap` and then `brew install <formula>`.

If the formula conflicts with one from another tap, you can `brew install phpv8/tap/<formula>`.

You can also install via URL: `brew install https://raw.github.com/php/homebrew-tap/master/Formula/<formula>.rb`


## Provided tools:

### [V8 JavaScript engine](https://developers.google.com/v8) 

V8 is a Google's high performance, open source, JavaScript engine. 

Available formulae:
 - `v8@6.6`

This formula family is based on [v8](https://github.com/Homebrew/homebrew-core/blob/master/Formula/v8.rb) formula from
[homebrew-core](https://github.com/Homebrew/homebrew-core), but diverge from it to fit [php-v8](https://github.com/phpv8/php-v8)
needs and stay on a bleeding edge. This is keg-only, co-installable formula, so you can install it alongside system `v8`
or any other `v8@*` formulae.

All `v8@*` formula build vanilla V8 JavaScript Engine as component with icu support (via external file for now)
without debug flag set.

## License

Formulae under [phpv8/tap](https://github.com/phpv8/homebrew-tap) licensed under the [MIT license](http://opensource.org/licenses/MIT).
