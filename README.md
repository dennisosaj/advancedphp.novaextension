![advanced PHP Logo]() 

# advanced PHP 🔥

advanced PHP provides syntax highlighting for special PHP writing. It is also fully compatible with HTML, you don't need to switch between syntaxes.

## Why, though? 🤔

Nova is a pretty editor with rich features, but it seems in lacking for language supports. Because I'm a long time Sublime Text 3 user I wanted to get some fresh air and started looking into Nova. Unfortunately all my projects looked horrible with the standard PHP-HTML syntax, so I started building this Extension. 

Nova is still fresh and can't compete in terms of extensions with other editors which are one the market for years now. But this for sure will change.

## Language Support 🧩

advanced PHP currently supports the following features:

✅ compatible with HTML

✅ variable substitution

✅ variable substitution with curly brackets

✅ separation between function parameters, arguments, variables and this

✅ separation between different elements like declarations, methods, variable prefixes etc.

✅ supports Nova's rainbow brackets option

### advanced PHP
![advanced PHP]() 

### standard PHP-HTML
![standard PHP-HTML]() 

Same theme in both case. 

## Theming 🎨

(2020-11-20) The syntax works best with [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension). 💯

The syntax provides an easy way to improve the highlighting for theme developers.

```
/* Statics */
advphp-base.static.condition { 
    /* if, else, elseif, foreach, ... */
}
advphp-base.static.processor { 
    /* echo, return, print, ... */
}
advphp-base.static.declaration {
    /* new, public, private, ... */
}
advphp-base.static.import {
    /* include, require, ... */
}
advphp-base.static.constant {
    /* __DIR__, __METHOD__, ... */
}
advphp-base.static.wordOperator {
    /* AND, OR, XOR, ... */
}

/* Syntax */
advphp-base.operator {
    /* +, -, /, >, ... */
}
advphp-base.bracket {
    /* [], {}, (), "", ... */
}
advphp-base.delimiter {
    /* , */
}

/* Variables */
advphp-base.identifier.variable.prefix {
    /* $ */
}
advphp-base.identifier.variable.name {
    /* $variable */
}
advphp-base.identifier.variable.this {
    /* $this */
}

/* Functions */
advphp-base.identifier.function.keyword {
    /* function */
}
advphp-base.identifier.function.name {
    /* my_function() */
}
advphp-base.arguments {
    /* my_function($argument) {} */
}
advphp-base.identifier.argument.name {
    /* my_function($argument) {} */
}

/* Objects */
advphp-base.identifier.object.name {
    /* Object:: */
}

/* Strings */
advphp-base.string,
advphp-base.value.string,
advphp-base.string.doubleQuote {
    /* "string" */
}
```

## Contribution 🤝
This is my first extension for Nova or any other IDE. So, if you feel to improve things, then you are more than welcome. 😅