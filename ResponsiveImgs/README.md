# Responsive Images

Since the static images with fixed heights and lengths will be cut off or displayed out-of-scale compared surronding text, the responsive images address the scaling issue.

The key code is:

```html
<img src=".../someImg.png"  class="img img-responsive"/>
<!-- As per v4 specified -->
<img src="..." class="img img-fluid" alt="Responsive image">
```

## Styling Imgs With Bootstrap

1. Rounded Images

    ```html
    <img src="..." class="rounded" alt="...">
    ```

2. Circle
   ```html
   <img src="..." alt="..." class="rounded-circle">
   ```


3. Thumbnail
   
    ```html
    <img src="..." alt="..." class="img-thumbnail">
    ```

More details can be found in documentations, [Images](https://getbootstrap.com/docs/4.3/content/images/), [Borders](https://getbootstrap.com/docs/4.3/utilities/borders/).

## Embeded Content in a Webpage