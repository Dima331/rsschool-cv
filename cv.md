1. Dmitriy Barkov
1. Contacts
   * phone: +375447390162 
   * telegram: @Dimbar95 
   * email: dimbar331@gmail.com
1. Hello, my name is Dmitry. My goal is to become a professional front-end developer who would work at interesting and unusual projects.
I have some experience working collectively on a project. I like when several professionals in their fields work together, discussing all the nuances together. I also want to be a professional and be responsible for my part of the work. I want to create unique things, make interesting layouts. And I like to make layouts until they become perfect. I like to see how websites are made, how people make layouts, what ways they do it. I have finished several online courses, at the same time I have experience in self-education. And I realized: to be good, you have to force yourself to work.
If you are interested in cooperating with me, you can easily find me on the links below or write me an e-mail, send the contact form.
1. My skills: html/pug, bem, css/sass,postcss,  php, mysql, js, webpack/gulp, vuejs, git, jquery.
1. Code example:
```javascript
    (function () {
        $(".dish__title").on("click", function (event) {
            event.preventDefault()
            
            var width = $(window).width()
            var thisElement = $(this)
            var minusPx;
            if (width < 930 && width > 800) {
                closeBlock()
                width = width - 300
                changeWidth(thisElement, width)

            } else if (width <= 800 && width > 600) {
                closeBlock()
                width = width - 240
                changeWidth(thisElement, width)
            }
            else if (width <= 600) {
                width = width - 60
                changeWidth(thisElement, width)

                if ($(this).parent(".dish").hasClass("dish_absolute")) {
                    $(this).parent(".dish").removeClass("dish_absolute")
                } else {
                    $(this).parent(".dish").addClass("dish_absolute")
                }
            }
            else {
                closeBlock()
                minusPx = 102
                changeWidth(thisElement, undefined, minusPx)
            }
        })

        function changeWidth(thisElement, width = 630, minusPx = 72) {
            $(thisElement).siblings(".dish__text").width(width)
            $(thisElement).siblings(".dish__text").children(".dish__text-info").width(width - minusPx)
            if ($(thisElement).siblings(".dish__text").width() > 0) {
                $(thisElement).siblings(".dish__text").width(0)
            }
        }
        function closeBlock() {
            $(".dish__text").each(function () {
                $(".dish__text").width(0)
            })
        }

        $(".dish__text-close").on("click", function () {
            closeBlock()
            $(".dish").each(function () {
                $(this).removeClass("dish_absolute")
            })
        })
    })()
```
1. My experience:
 * Web-developer at BelMAPE since 2017.
    - [test.belmapo.by](https://test.belmapo.by)
    - [de.belmapo.by/](https://de.belmapo.by)
 * Graduation projects at loftschool.com courses: 
    - [chocolate](https://dima331.github.io/cho-cco/dist/)
    - [burgers](https://dima331.github.io/sity/) 
    - [template beginner](https://dima331.github.io/loft-beginner/)
    - [template](https://dima331.github.io/testDev/)
    - [template CV](https://dima331.github.io/port/build/)
 * Web-developer from 04.2018 to 11.2018 at [loftschool.com](https://loftschool.com/).
 * Developed [softwines.by](https://softwines.by).