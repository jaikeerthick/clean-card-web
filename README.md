# clean-card-web
A clean card with image, title and a subtitle (customize yourself) with HTMl and CSS only.

### Html :

```html
<div class="main-card">
  <img src="https://avatars0.githubusercontent.com/u/56932879?s=460&u=0f61be55979423089b5410d2fbf2d93b6c27deee&v=4" alt="profile img" style="width:100%">
  <div class="container">
    <h4><b>Jai Keerthick</b></h4>
    <p>Developer</p>
  </div>
</div>
```
### CSS :

```css
.main-card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  border-radius: 5px; /* 5px rounded corners */
}

/* Add rounded corners to the top left and the top right corner of the image */
img {
  border-radius: 5px 5px 0 0;
}

/* On hovering, add a deeper shadow effect */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

/* Add some padding inside the card container (optional) */
.container {
  padding: 2px 16px;
}
```
