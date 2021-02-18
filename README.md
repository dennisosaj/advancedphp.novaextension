![advanced PHP Logo](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/thumb.png?raw=true) 

# advanced PHP 🔥

advanced PHP provides syntax highlighting for special PHP writing. It is also fully compatible with HTML, you don't need to switch between syntaxes.

*Note:* you need a compatible Theme, like [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension), for proper highlighting.

## Why, though? 🤔

Nova is a pretty editor with rich features, but it seems in lacking for language support. Because I'm a long time Sublime Text 3 user I wanted to get some fresh air and started looking into Nova. Unfortunately all my projects looked horrible with the standard PHP-HTML syntax, so I started building this extension. 

Nova is still fresh and can't compete in terms of extensions with other editors which are on the market for years now. But this for sure will change.

## Language Support 🧩

advanced PHP currently supports the following features:

✅ compatible with HTML

✅ variable substitution

✅ variable substitution with curly brackets

✅ SQL recognition within strings

✅ CURL-, WP-Constants 

✅ separation between function parameters, arguments, variables and this

✅ separation between different elements like declarations, methods, variable prefixes etc.

✅ supports Nova's rainbow brackets option

✅ supports Nova's hierarchical subtree 

✅ supports Nova's function folding

✅ offers completions and suggestions

### advanced PHP:

With [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension):

![advanced PHP](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/advphp.png?raw=true) 

### standard PHP-HTML:

With standard "Palette" theme:

![standard PHP-HTML](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/php-html.png?raw=true) 

## Theming 🎨

### 👉 supported Themes

[![Varia Theme](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/Themes/varia.png?raw=true)](https://github.com/dennisosaj/variatheme.novaextension)
[![Nord for Nova](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/Themes/nord.png?raw=true)](https://github.com/GwynethLlewelyn/Nord.novaextension)
[![Monokai Pro](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/Themes/monokai-pro.png?raw=true)](https://github.com/keisto/Monokai-Pro.novaextension)
[![Tomorrow Night Eighties](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/Themes/tomorrow-night-eighties.png?raw=true)](https://github.com/blakewatson/nova-tomorrow-night-eighties)

- [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension)
- [Nord for Nova](https://github.com/GwynethLlewelyn/Nord.novaextension)
- [Monokai Pro](https://github.com/keisto/Monokai-Pro.novaextension)
- [Tomorrow Night Eighties](https://github.com/blakewatson/nova-tomorrow-night-eighties)

### 👉 Development

The syntax provides an easy way to style the syntax for theme developers. As a theme developer please let me know if your theme supports "advanced PHP". ✌️

#### Statics
```
advphp.static.condition { 
    if, else, elseif, foreach, ...
}
advphp.static.processor { 
    echo, return, print, ...
}
advphp.static.declaration {
    new, public, private, ...
}
advphp.static.import {
    include, require, ...
}
advphp.static.constant {
    __DIR__, __METHOD__, ...
}
advphp.static.wordOperator {
    AND, OR, XOR, ...
}
```

#### Wordpress Keywords
```
advphp.wp.keywords {
    ABSPATH, WP_ADMIN, ...
}
```

#### CURL Keywords
```
advphp.curl.keywords {
    CURLOPT_HEADER, CURLOPT_PROXY, ...
}
```

#### SQL Keywords
```
advphp.sql.keywords {
    SELECT, FROM, WHERE, ...
}
```

#### Syntax
```
advphp.operator {
    +, -, /, >, ...
}
advphp.bracket {
    [], {}, (), "", ...
}
advphp.delimiter {
    ,
}
```

#### Variables
```
advphp.identifier.variable.prefix {
    $
}
advphp.identifier.variable.name {
    $variable
}
advphp.identifier.variable.this {
    $this
}
```

#### Functions
```
advphp.identifier.function.keyword {
    function
}
advphp.identifier.function.name {
    my_function()
}
advphp.identifier.parameter.prefix {
    my_function($parameter) {}
}
advphp.identifier.parameter.name {
    my_function($parameter) {}
}
```

#### Objects
```
advphp.identifier.object.name {
    Object::
}
```

#### Strings 
```
advphp.string,
advphp.value.string,
advphp.string.doubleQuote,
advphp.string.singleQuote, {
    "string", 'string'
}

advphp.string.backTic {
    `string`
}
```

## Contribution 🤝
This is my first extension for Nova or any other IDE. So, if you feel to improve things, then you are more than welcome. 😅