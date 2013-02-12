## `application/index.sass`

```sass
@import application/components/buttons
@import application/components/buttons
```
After `rake assets:precompile`, `public/assets/application.css` looks like:

```css
.btn{color:green}.btn{color:green}
```

## `admin/index.sass`

```sass
/**
 *= require admin/components/buttons
 *= require admin/components/buttons
 */
```

After `rake assets:precompile`, `public/assets/admin.css` looks like:

```css
.btn{color:blue}
```
