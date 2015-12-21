# WhitestormJS
[![Build Status](https://travis-ci.org/sasha240100/WhitestormJS.svg)](https://travis-ci.org/sasha240100/WhitestormJS)
[![npm](http://wsbadge.herokuapp.com/npm/v/whitestormjs.svg)](https://www.npmjs.com/package/whitestormjs) [![bower](http://wsbadge.herokuapp.com/bower/v/whitestormjs.svg)](https://github.com/sasha240100/WhitestormJS) [![Gitter](http://wsbadge.herokuapp.com/badge/GITTER-JOIN_CHAT_%E2%86%92-1dce73.svg)](https://gitter.im/sasha240100/WhitestormJS)

[![Issues](http://wsbadge.herokuapp.com/npm/dt/whitestormjs.svg)](https://www.npmjs.com/package/whitestormjs)
[![Author](http://wsbadge.herokuapp.com/badge/Author-Alexander%20Buzin-red.svg)](https://github.com/sasha240100)


----------------------------------------------------------------------------------------------------------------


#####Code style check:   [![Codacy Badge](https://api.codacy.com/project/badge/8f5d1eab0569415b983bf0c1b7323d68)](https://www.codacy.com/app/siteprogcom/WhitestormJS) 
[![bitHound Overall Score](https://www.bithound.io/github/sasha240100/WhitestormJS/badges/score.svg)](https://www.bithound.io/github/sasha240100/WhitestormJS)


----------------------------------------------------------------------------------------------------------------

**WhitestormJS** is a library which combines [**Three.js**](https://github.com/mrdoob/three.js/) and [**Cannon.js**](https://github.com/schteppe/cannon.js/). It makes WebGL development *easy*.

WhitestormJS is [hosted by jsDelivr](http://www.jsdelivr.com/projects/whitestormjs). You can link to the latest [minified version](https://cdn.jsdelivr.net/whitestormjs/latest/whitestorm.min.js), [full version](https://cdn.jsdelivr.net/whitestormjs/latest/whitestorm.js), or [download both](https://cdn.jsdelivr.net/whitestormjs/latest/whitestormjs.zip).

![WhitestormJS](https://raw.githubusercontent.com/sasha240100/WhitestormJS/master/logos/logo-big.png)

## Installation
[![forthebadge](http://forthebadge.com/images/badges/uses-js.svg)](https://github.com/search?l=JavaScript&q=%23javasript&ref=searchresults&type=Repositories&utf8=%E2%9C%93)

\* It is advised to download your own copies of the following libraries, as large changes can break backwards compatibility.

Include [Three.js](http://threejs.org/build/three.min.js), [Wagner](http://spite.github.io/wagner/Wagner.js), and [Cannon.js](http://schteppe.github.io/cannon.js/build/cannon.min.js) libraries.
Include a script tag linking the [WhitestormJS](https://cdn.jsdelivr.net/whitestormjs/latest/whitestorm.min.js) library in your `head` or after your `body`:

```html
<script src="three.js"></script>
<script src="cannon.js"></script>
<script src="wagner.js"></script>
<!-- WhitestormJS library -->
<script src="{path_to_lib}/whitestorm.js"></script>
```

After adding these libraries, you can configure your game:
```javascript
var GAME = new WHS.init({
    anaglyph: false, // Anaglyph effect.
    helper: false, // Cannon.js shape helper
    stats: "fps", // fps, ms, mb or false if not need.
    wagner: WAGNER, // wagner library variable
    gravity: { // Physic gravity.
        x: 0,
        y: -200,
        z: 0
    }
});
```

[![Join the chat at https://gitter.im/sasha240100/WhitestormJS](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/sasha240100/WhitestormJS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Structure
![Whitestorm.js structure](https://raw.githubusercontent.com/sasha240100/WhitestormJS/master/development/coggle/WhitestormJS.png)

## Examples:
 * [FPS](http://192.241.128.187/current/examples/fps.html)  (First person example with Wagner effects and terrain.)
 * [Basic](http://192.241.128.187/current/examples/basic.html)  (Basic "Hello world!" example.)
 * [Material](http://192.241.128.187/current/examples/basic_material.html)  (Basic example with material.)
 * [Object/Icosahedron](http://192.241.128.187/current/examples/basic_object.html)  (Icosahedron from *Three.js* example.)
 * [Object/Model](http://192.241.128.187/current/examples/basic_model.html)  (Teapot model with *Three.js* JSONLoader.)
 * [Object/Wall](http://192.241.128.187/current/examples/stone_wall.html)  (Stone wall (basic).)

### Author:
@sasha240100 [![forthebadge](http://wsbadge.herokuapp.com/twitter/url/http/alexbuzin.me.svg?style=social)](https://twitter.com/intent/tweet?text=Check+this+developer:&url=http%3A%2F%2Falexbuzin.me)

#### Changelog: [Look here](https://github.com/sasha240100/WhitestormJS/blob/master/CHANGELOG.md)

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](https://alexbuzin.me/)

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Лицензия Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />Произведение «<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">WhitestormJS 3D-Library</span>» созданное автором по имени <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/sasha240100" property="cc:attributionName" rel="cc:attributionURL">Alexander Buzin</a>, публикуется на условиях <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">лицензии Creative Commons «Attribution-NonCommercial-NoDerivatives» («Атрибуция — Некоммерческое использование — Без производных произведений») 4.0 Всемирная</a>.<br />Основано на произведении с <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/sasha240100/WhitestormJS" rel="dct:source">https://github.com/sasha240100/WhitestormJS</a>.<br />Разрешения, выходящие за рамки данной лицензии, могут быть доступны на странице <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/sasha240100/WhitestormJS" rel="cc:morePermissions">https://github.com/sasha240100/WhitestormJS</a>.
