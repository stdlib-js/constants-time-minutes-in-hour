<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Minutes in an Hour

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Number of minutes in an hour.



<section class="usage">

## Usage

```javascript
import MINUTES_IN_HOUR from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-time-minutes-in-hour@esm/index.mjs';
```
The previous example will load the latest bundled code from the esm branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/constants-time-minutes-in-hour/tags). For example,

```javascript
import MINUTES_IN_HOUR from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-time-minutes-in-hour@v0.2.1-esm/index.mjs';
```

#### MINUTES_IN_HOUR

Number of minutes in an hour.

```javascript
var bool = ( MINUTES_IN_HOUR === 60 );
// returns true
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   The value is a generalization and does **not** take into account inaccuracies due to daylight savings conventions, crossing timezones, or other complications with time and dates. 

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import randu from 'https://cdn.jsdelivr.net/gh/stdlib-js/random-base-randu@esm/index.mjs';
import roundn from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-roundn@esm/index.mjs';
import MINUTES_IN_HOUR from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-time-minutes-in-hour@esm/index.mjs';

var h;
var m;
var i;

function hrs2mins( hrs ) {
    return hrs * MINUTES_IN_HOUR;
}

for ( i = 0; i < 10; i++ ) {
    h = roundn( randu()*20.0, -2 );
    m = hrs2mins( h );
    console.log( '%d hours => %d minutes', h, m );
}

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-time-minutes-in-hour.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-time-minutes-in-hour

[test-image]: https://github.com/stdlib-js/constants-time-minutes-in-hour/actions/workflows/test.yml/badge.svg?branch=v0.2.1
[test-url]: https://github.com/stdlib-js/constants-time-minutes-in-hour/actions/workflows/test.yml?query=branch:v0.2.1

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-time-minutes-in-hour/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-time-minutes-in-hour?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-time-minutes-in-hour.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-time-minutes-in-hour/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-time-minutes-in-hour/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-time-minutes-in-hour/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-time-minutes-in-hour/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-time-minutes-in-hour/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-time-minutes-in-hour/main/LICENSE

</section>

<!-- /.links -->
