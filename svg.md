Работа с SVG
---
1. Оптимизация svg
    - Онлайн версия [svgomg](ttps://jakearchibald.github.io/svgomg/)
    - Node.js версия `npm install svgomg` ([npm](https://www.npmjs.com/package/svgo))
    - webpack loader `npm install svgo svgo-loader --save-dev` ([svgo-loader](https://www.npmjs.com/package/svgo-loader))

2. Простые способы вставки:
    - `<img src="logo.svg"></img>`
    - `background-image: url('logo.svg')`
    - Генерирование шрифта [Fontello](http://fontello.com/)

3. Сложные способы вставки:
    - Спрайты - собираем иконки в бандл [svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader#examples) +
    [Демо](https://github.com/kisenka/svg-sprite-loader/tree/master/examples/browser-sprite)
    - `<object type="image/svg+xml" data="logo.svg">Логотип</object>` - компонентный подход

4. Сладенькое:
    - currentColor
    - [SVG Referenced Parameter Variables](https://dev.w3.org/SVG/modules/ref/master/SVGRefPrimer.html)
    ([ref2](https://dev.w3.org/SVG/modules/ref/master/ref2.js))
    - [pointer-events](https://codepen.io/MartijnCuppens/full/MBjqbM)
    - [Иконка с датой](https://shkspr.mobi/blog/2018/02/this-svg-always-shows-todays-date/)
    - [Адаптивные иконки]('https://medium.com/9elements/building-a-responsive-image-e4c6229fa1f6')
    - [CI Дизайн](https://blog.github.com/2018-04-12-driving-changes-from-designs/)
    - [Изоляция событий](https://bugzilla.mozilla.org/show_bug.cgi?id=294932#fromHistory)

PS:
- Большой справочник по работе с svg https://svgontheweb.com/ru/
- Большой интерактивный учебник работы с svg https://css-tricks.com/lodge/svg/