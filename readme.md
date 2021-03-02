###### change repo

git remote set-url origin http://newserver/myproject.git

git remote -v (to check)

###### icons in project

https://icomoon.io/app/

- daarna style.css + svgxuse.js + symbol-defs.svg kopiëren
- <svg class="icon icon-search">
    <use xlink:href="./icons/symbol-defs.svg#icon-search"></use>
  </svg>
  - wrappen met parent element en stijlen met color en font-size
