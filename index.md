# James Franke

I am a PhD Candiate at the University of Chicago forcusing on climate change impacts. I used models, remote sensing, and deep learning to try to better understand what parts of the world are most vunerable to climate change. 

[research in progress](/menu1.md) [publications](/menu2.md)

## Header and Footer

```html
Last modified: {{ fill fd_mtime }}.
```

(cf. `src/_html_parts/page_foot.html`) which will then replace these braces with the content of a dictionary of variables at the key `fd_mtime`.
This dictionary of variables is accessed locally by pages through `@def varname = value` and globally through the `config.md` page via the same syntax.

There's a few other such functions of the form `{{fname p₁ p₂}}` as well as support for conditional blocks. If you wander through the `src/_html_parts/` folder and its content, you should be able to see those in action.
