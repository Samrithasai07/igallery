# Ex.08 Design of Interactive Image Gallery
## Date:03.12.2024

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: rgb(255, 255, 255);


}
div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 90%;
  height: 500px;
}

div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .responsive {
    width: 150%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h1 style="text-align: center; background-color:rgb(228, 131, 178);">Responsive Image Gallery</h1>
<center>
  <h2 >SAMRITHA (24013637)</h2>
</center>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="Dumplings.jpg">
      <img src="Dumplings.jpg" alt="dumplings" height="100px"  >
    </a>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="beach.jpg">
      <img src="beach.jpg" alt="bach" height="100px">
    </a>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="falls.jpg">
      <img src="falls.jpg" alt="falls" height="100px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="me.jpg">
      <img src="me.jpg" alt="Samritha" height="100px" >
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="cat.jpg">
      <img src="cat.jpg" alt="cat" height="100px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="cycle.jpg">
      <img src="cycle.jpg" alt="cycle" height="100px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="v.jpg">
      <img src="v.jpg" alt="V" height="100px">
    </a>

  </div>
</div>



<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="dog.jpg">
      <img src="dog.jpg" alt="dog" height="250px">
    </a>

  </div>
</div>



</body>
</html>
```

## OUTPUT:
![Screenshot 2024-12-25 111724](https://github.com/user-attachments/assets/c3a2050b-4d98-4cb0-be84-dce7731c0ebc)
![Screenshot 2024-12-25 111737](https://github.com/user-attachments/assets/0f7f8826-26bd-43d8-ad96-8f2e2aa2140b)



## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
