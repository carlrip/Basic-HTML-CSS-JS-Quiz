# Intermediate CSS Quiz

The following questions should take you no longer than 1 hour to answer.  

1. Which direction do the following `div` elements flow? Horizontally or vertically?  

HTML:
```
<div class="layout">
  <div class="section">Section 1</div>
  <div class="section">Section 2</div>
  <div class="section">Section 3</div>
<div>
```
CSS:
```
.layout {
  display: flex;
}
.section {
  display: flex;
}
```

2. Continue the CSS implementation below of a bottom nav bar:

HTML:
```
<div class="bottom-nav">
  <button>Option 1</button>
  <button>Option 2</button>
  <button>Option 3</button>
</div>
```
CSS:
```
.bottom-nav {
  background: #2d3748;
  display: flex;
}
.bottom-nav button {
  padding: 10px 20px;
  color: #e0e4e9;
}
```

- The nav options need to be spaced evenly across the page. The nav bar should be anchored at the bottom of the page as well. You shouldn't need to change the HTML - you should only need to add additional properties to the `bottom-nav` CSS class.
- Make changes to the CSS so that the nav options have the same background colour as the nav bar and they have no border. 
- Make changes to the CSS so that the nav option text is white when hovered over and there is no blue outline when an option is clicked



3. Continue the CSS implementation below of a left nav bar:

HTML:
```
<div class="left-nav">
  <button>Option 1</button>
  <button>Option 2</button>
  <button>Option 3</button>
</div>
```
CSS:
```
.left-nav {
  background: #2d3748;
  padding: 40px 0px;
  width: 100px;
  display: flex;
}
.left-nav button {
  width: 100%;
  padding: 5px 0px;
  margin-bottom: 10px;
  color: #e0e4e9;
}
```

- The nav bar needs to be anchored to the left of the page and the nav options need to flow vertically down the nav bar. Each nav option needs to be centered horizontally within the nav bar. Make changes to the `left-nav` class to meet these requirements.
- Make changes to the CSS so that the nav options have the same background colour as the nav bar and they have no border. 
- Make changes to the CSS so that the nav option text is white when hovered over and there is no blue outline when an option is clicked

4. Continue the CSS implementation below of two images with text:

HTML:
```
<div class="rounded-picture">
  <img src="https://images.pexels.com/photos/220453/pexels-photo-220453.jpeg?auto=compress&cs=tinysrgb&h=350"  />
  <span>BH</span>
</div>
<div class="rounded-picture">
  <img src="https://images.pexels.com/photos/415829/pexels-photo-415829.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260"  />
  <span>JP</span>
</div>
```
CSS:
```
.rounded-picture {
}
.rounded-picture img {
  height: 50px;
  width: 50px;
  object-fit: cover;
}
```

- The text should be underneath the image and centered. The two images should flow horizontally across the page. Make changes to the `rounded-picture` class to meet these requirements.
- Make changes so that the images are rounded.

5. Continue the CSS implementation below of an `input` with a `button` inside:

HTML:
```
<div class="input-container">
  <input type="text" />
  <button>Go</button>
</div>
```

CSS:
```
.input-container {
  display: inline-block;
}
.input-container button {
  width: 30px;
  height: 22px;
  right: 0px;
}
```

- Make changes to the CSS so that the `button` appears inside the `input` at the right hand side.

6. Continue the CSS implementation below of a `button` with some popup content above it.

HTML:
```
<div class="page">
  <div class="button-popup button-popup-open">
    <button>Open</button>
    <div>Some useful content ...</div>
  </div>
</div>
```

CSS:
```
.page {
  padding: 100px 100px;
}
.button-popup {
}
.button-popup button {
  box-sizing: border-box;
  height: 30px;
  width: 50px;
}
.button-popup div {
  display: none;
  box-shadow: 0 0 6px 0 rgba(0,0,0,.12);
  box-sizing: border-box;
  width: 200px;
  height: 50px;
  padding: 10px 10px;
}
.button-popup.button-popup-open div {
  display: block;
}
```

- Make changes to the CSS so that the popup `div` appears above the `button` and centered.

7. Make the necessary change to the `margin` CSS property below so that the search box is centered horizontally.

HTML: 
```
<div class="top-nav">
  <input type="search" placeholder="Search ..." />
</div>
```

CSS:
```
.top-nav {
  display: flex;
}
.top-nav input {
  margin: 
}
```

8. Make the necessary changes to the following CSS so that the list contains a vertical scrollbar. The scrollbar should work on iOS touch as well.

HTML: 
```
<ul class="list">
  <li>Bob</li>
  <li>Sam</li>
  <li>Jane</li>
  <li>Sarah</li>
  <li>Anne</li>
  <li>Jeff</li>
</ul>
```

CSS:
```
.list {
  list-style: none;
  padding: 10px;
  height: 100px;
  width: 100px;
}
.list li {
  padding: 5px 0px;
}
```

9. Add a media query to the CSS below so that the image tiles are displayed underneath one another and centered when the page is up to 800px wide.

HTML:
```
<div class="tiles">
  <div class="tile">
    <img src="https://images.pexels.com/photos/220453/pexels-photo-220453.jpeg?auto=compress&cs=tinysrgb&h=350"  />
    <span>Barry Harries</span>
  </div>
  <div class="tile">
    <img src="https://images.pexels.com/photos/415829/pexels-photo-415829.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260"  />
    <span>Jenny Young</span>
  </div>
</div>
```

CSS:
```
.tiles {
  display: flex;
  justify-content: space-between;
}
.tile {
  margin: 15px 0px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.tile img {
  height: 300px;
  width: 300px;
  object-fit: cover;
}
```


   
🏆🏆🏆   

Send your answers to Carl to get your score and feedback. 



















