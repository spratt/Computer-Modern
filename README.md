Computer-Modern
===============

Makes it simple to use a web-optimized version of the Computer Modern
font in web pages.  Simply include the following style code on your
web page:

```css
<style>
  @font-face {
    font-family: "Computer Modern";
    src: url('http://spratt.github.io/Computer-Modern/cmunss.otf');
  }
  @font-face {
    font-family: "Computer Modern";
    src: url('http://spratt.github.io/Computer-Modern/cmunsx.otf');
    font-weight: bold;
  }
  @font-face {
    font-family: "Computer Modern";
    src: url('http://spratt.github.io/Computer-Modern/cmunsi.otf');
    font-style: italic, oblique;
  }
  @font-face {
    font-family: "Computer Modern";
    src: url('http://spratt.github.io/Computer-Modern/cmunbxo.otf');
    font-weight: bold;
    font-style: italic, oblique;
  }

  body {
    font-family: "Computer Modern", serif;
  }
</style>
```
