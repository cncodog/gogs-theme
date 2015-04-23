# A Gogs style.
This is a super lightweight css styling for [gogs](https://github.com/gogits/gogs).

## Installation
1- Download and place the `custom.css` in `$GOPATH/src/github.com/gogits/gogspublic/css/`
2- Add a link tag in `$GOPATH/src/github.com/gogits/gogs/templates/ng/base/head.tmpl`:
```HTML
        <link rel="stylesheet" href="{{AppSubUrl}}/ng/fonts/octicons.css">
        <link rel="stylesheet" href="{{AppSubUrl}}/css/github.min.css">
        <!-- JUST AFTER ALL CSS IMPORTS -->
        <link rel="stylesheet" href="{{AppSubUrl}}/css/custom.css">
```
3- Enjoy

## Screen shots
![](http://kolore-project.appspot.com/admin/file_serve/AMIfv97xnye-CZmlT8eK6Db949HhU41LXlrdiN3JvEOCJT0YPYVwmPzKtSSf2rO2fnzQR-EmYfBvDzeSSex6CNSvPTElo1Zak6gLg3MY3cHf7J22wxecIv0mKVil-Ts7Md4wCbL21N247spgneiu4IT361zisQhQ9ZPrsjKLF6HKo4FE8D0rKYo)
![](http://lh3.googleusercontent.com/3k7ZXmuFoSfjlRuAZBucgaXHK_pA33FiBMCiKqwOLzujwYrIJmpSS5c3NbdtNLS2LT903Gx6SMF9Ps3oIolt6WHz2Q=s1600)
![](http://kolore-project.appspot.com/admin/file_serve/AMIfv95NK5Gid4ZBnEBWbNO8DSZjzHq3rx0bmeJUbt5WZBwnWWtOlTklgK6PlxsBvsqpFKmRsBoRx4Y_kYiGXnZ7mAX9EHUPfwXeX1Xutc6yb7EmI9Z-yWi4Bg1dj9ii8BGQrX3pwfkH738Ro50s19NQR2V6jow-kXyX0zeyieXvsuTcCqbgve4)

## Contributing

I’d :heart: to receive contributions to this project. It doesn’t matter if it’s just a typo, or if you’re proposing an overhaul of the entire project, I’ll gladly take a look at your changes. Fork at will! :grinning:.

## License

Go nuts. See [LICENSE](http://opensource.org/licenses/MIT) (MIT).
