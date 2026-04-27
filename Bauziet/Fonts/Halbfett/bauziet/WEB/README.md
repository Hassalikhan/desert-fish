# Installing Webfonts
Follow these simple Steps.

## 1.
Put `bauziet/` Folder into a Folder called `fonts/`.

## 2.
Put `bauziet.css` into your `css/` Folder.

## 3. (Optional)
You may adapt the `url('path')` in `bauziet.css` depends on your Website Filesystem.

## 4.
Import `bauziet.css` at the top of you main Stylesheet.

```
@import url('bauziet.css');
```

## 5.
You are now ready to use the following Rules in your CSS to specify each Font Style:
```
font-family: Bauziet-Regular;
font-family: Bauziet-Bold;
font-family: Bauziet-MediumItalic;
font-family: Bauziet-Semibold;
font-family: Bauziet-SemiboldItalic;
font-family: Bauziet-BoldItalic;
font-family: Bauziet-ExtraboldItalic;
font-family: Bauziet-Light;
font-family: Bauziet-Variable;
font-family: Bauziet-VariableItalic;
font-family: Bauziet-Extrabold;
font-family: Bauziet-Italic;
font-family: Bauziet-LightItalic;
font-family: Bauziet-Medium;

```
## 6. (Optional)
Use `font-variation-settings` rule to controll axes of variable fonts:
wght 800.0wght 400.0

Available axes:
'wght' (range from 200.0 to 800.0'wght' (range from 300.0 to 800.0

