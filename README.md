# clean-card-web
A clean card with image, title and a subtitle (customize yourself) with HTMl and CSS only.

![alt](https://github.com/jaikeerthick/clean-card-web/blob/main/Screenshot%20(124).png)
### Html :

```html
<div class="main-card">
  <img src="anyimage.jpg" alt="profile img" style="width:200px">
  <div class="container">
    <h4><b>Jai Keerthick</b></h4>
    <p>Developer</p>
  </div>
</div>
```
### CSS :

```CSS
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
  width: 200px;
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

/* Add some padding inside the card container (optional) */
.container {
  padding: 2px 16px;
}
```

#### That's all.. Cheers! 

![alt](https://github.com/jaikeerthick/clean-card-web/blob/main/Screenshot%20(123).png)
