# Cell Science Bootstrap

###To initialize dev environment and download Bootstrap:
run:
```bash
npm i
```

```bash
bower i
```

make edits to customboot.less variables

then run:
```bash
grunt dist-css
```
to create new .css file

###To use current theme:
Link to 
```html
<link rel="stylesheet" href="/styles/bootstrap.min.css">
```
```html

and include jquery and bootstrap scripts, either your own or the bower downloaded ones:
<script src="bower_components/jquery/dist/jquery.min.js"></script>
<script src="bower_components/bootstrap/dist/js/bootstrap.min.js"></script>
  ```

in your project


