Чан Дык Зюи - 336201 - P32202
Варианты №№1-4: https://www.figma.com/file/5EGZWDsnJEomjvuHDuG6TJ/Untitled

-> No2:

```
body
    header(shared UI)
        div.container
            div.menu
                ul.menu-list
                    li.menu-list__item*5 >a.menu-list__item__link page-checked

    main (unique content for each page)
        section.hero
            div.container
                div.row
                    div.hero__name-box
                        p.hero__name
                    div.hero__des-box
                        p.hero__des
        section.about
            div.container--fluid
                div.about-box
                    h1.about__title, title
                    div.about__item
                        p.about__item*3
        section.skills
            div.container, skill-box
                h1.skills__title, title
                p.skills__des
                div.row
                    div.col-3 *4
                        div.skill-item
                            img.skill-item__image
                            p.skill-item__des
                            div.skill-item__rating
                                span.fa *5 (fa-star) checked
        section.portfolio
            div.container
                h1.portfolio__title title
                div.portfolio-item*3
                    img.portfolio-item__image
                    a.portfolio-item__link

        section.contacts
            div.container--fluid
                h1.contacts__title title
                p.contacts__des
                button.btn
    footter(shared UI)
        section.app-footter
            ul.app-footter__social-list>li*4>a>i
            p.app-footter__des
```
