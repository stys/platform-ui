# Modular UI framework for Play 2.x in spirit of BEM

Work in progress.

The goal is to develop a set of abstract UI components to use in twirl templates and
remove explicit HTML markup from client templates. Design is based on the concepts of BEM.
A cleaner separation of markup and styling should be achieved.

```
menu(List("navigation"), Map("id" -> "navbar")) {
    menu__item() {
        link(Map(
            title -> "Home"
            url -> "google.com"
        ))
    }
}
```
