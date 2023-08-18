## Pure javascript AJAX append plugin

Load the script in your project like this `<script src="infinity.js"></script>`.

You can initialize the plugin with the following lines:

```html
<script>
  var el = document.querySelector('.ajax-append');
  if (el) {
    new infinity(el, {
      navSelector: '.pagination .pager',
      nextSelector: '.pagination a.next',
      loadingSelector: '.loading',
      pageFragment: '.ajax-append',
      scrollBuffer: 200,
      scrollOnLoad: true,
      scrollOnLoadDistance: 200,
      scrollOnLoadSpeed: 500,
      onInit: function () {},
      beforeContentLoaded: function (link) {},
      afterContentLoaded: function (html) {}
    });
  }
</script>
```
