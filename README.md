# msonry

An alternative to generate responsive masonry grid layout.

##### Usage :

* include in your HTML
```
<script src="https://raw.githubusercontent.com/ngemilchiki/msonry/master/msonry.min.js"></script>
```
* example
```
<div id=msonry>

  <li>
    <img src="">
    <div></div>
  </li>
  
  <li>
    <img src="">
    <div></div>
  </li>

  ...
  
</div>
```
* the `div` tag inside `li` is customizable. e.g. as an overlay of an image
```
<style>
#msonry li div {
  background: black;
  color: white;
  opacity: 0;
}
#msonry li div:hover {
  opacity: 1;
}
</style>

<div id=msonry>

  <li>
    <img src="">
    <div>
      <h2>title of image</h2>
      <p>description of image</p>
    </div>
  </li>
  
  ...

</div>
