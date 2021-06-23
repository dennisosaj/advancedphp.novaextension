![advanced PHP Logo](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/thumb.png?raw=true) 

# advanced PHP 🔥

advanced PHP provides syntax highlighting for special PHP writing. It is also fully compatible with HTML, you don't need to switch between syntaxes.

*Note:* you need a compatible Theme, like [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension), for proper highlighting.

## Why, though? 🤔

Nova is a pretty editor with rich features, ~~but it seems in lacking for language support~~ *. Because I'm a long time Sublime Text 3 user I wanted to get some fresh air and started looking into Nova. Unfortunately all my projects looked horrible with the standard PHP-HTML syntax, so I started building this extension. 

Nova is still fresh and can't compete in terms of extensions with other editors which are on the market for years now. But this for sure will change.

(*) **Update:** Nova released a lot of major updates since I developed this extension. I published it first when Nova 3 came out. Since Nova 7 they implemented most of the features I've developed in this extension, but my extension still fits my needs better.

To see how far they came I tried to get the same look with my [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension) for **Nova's PHP** and my **advanced PHP** highlighting. They're still some major differences. I focused more of the importance if strings and what kind of information they can hold. Also I tried to do a more logical separation of static keywords like: imports, processors, declarations, types and constants. I think when those features will be implement by Nova's standard PHP Syntax, my extension will be obsolete, but until then I will use it and try to improve it 😅

### advanced PHP:

With [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension):

![advanced PHP](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/advphp.png?raw=true) 

### standard PHP-HTML:

With [Varia Theme](https://github.com/dennisosaj/variatheme.novaextension):

![standard PHP-HTML](https://github.com/dennisosaj/advancedphp.novaextension/blob/main/Images/php-html.png?raw=true) 

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
- [Stuntrocket](https://github.com/stuntrocket/novatheme)

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
advphp.semicolon {
    ;
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

#### Namespace
```
advphp.definition.namespace {
    Name\Space
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