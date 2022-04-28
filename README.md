## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/steveswo/steveswo.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/steveswo/steveswo.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <meta name="description" content="Blyroad Dental Practise">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>

  <style>
  body {
font-family: "Lato", sans-serif;
}

.sidebar {
height: 100%;
width: 0;
position: fixed;
z-index: 1;
top: 0;
left: 0;
background-color: #111;
overflow-x: hidden;
transition: 0.5s;
padding-top: 60px;
}

.sidebar a {
padding: 8px 8px 8px 32px;
text-decoration: none;
font-size: 25px;
color: #818181;
display: block;
transition: 0.3s;
}

.sidebar a:hover {
color: #f1f1f1;
}

.sidebar .closebtn {
position: absolute;
top: 0;
right: 25px;
font-size: 36px;
margin-left: 50px;
}

.openbtn {
font-size: 20px;
cursor: pointer;
background-color: #111;
color: white;
padding: 10px 15px;
border: none;
}

.openbtn:hover {
background-color: #444;
}

#main {
transition: margin-left .5s;
padding: 16px;
}

/* On smaller screens, where height is less than 450px, change the style of the sidenav (less padding and a smaller font size) */
@media screen and (max-height: 450px) {
.sidebar {padding-top: 15px;}
.sidebar a {font-size: 18px;}
}

  /* Form Services Dropdown */
  .dropbtn {
    background-color: #04AA6D;
    color: white;
    padding: 6px;
    font-size: 16px;
    border: none;
  }

  .dropdown {
    position: relative;
    display: inline-block;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
  }

  .dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
  }

  .dropdown-content a:hover {background-color: #ddd;}

  .dropdown:hover .dropdown-content {display: block;}

  .dropdown:hover .dropbtn {background-color: #3e8e41;}

  .book {background-color: #009900; color: white; padding: 10px; border-radius: 10px; font-weight: bold;} /* Green */
  .book:hover {background-color: #46a049;}


  a { text-decoration: none; }
  </style>

  <script>

  </script>
</head>

<body>
  <div id="mySidebar" class="sidebar">
    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">×</a>
    <a href="#">Home</a>
    <a href="#">Services</a>
    <a href="#">Location</a>
    <a href="#">Contact us</a>
  </div>

  <div id="main">
    <button class="openbtn" onclick="openNav()">☰ </button>
  </div>

  <a href="https://tinyurl.com/65nchdk8"> <img src="Smarteeth Location.png" alt="location" style="float: left; height: 400px; width: 100%;"> </a>
  <!-- <map name="workmap">
      <area shape= "default" href="map.htm" onclick="myFunction()">
    </map> -->

  <p> We're located at: </p>
  <a href="https://tinyurl.com/65nchdk8"> 232 Blythe Road <br>
    Brook Green, <br>
    London <br>
    W14 0HJ </a>
  <br> <br>

  <p style=> Book your appointment with us <button class="book"> BOOK APPOINTMENT </button> <p>
  </p>

  <p> Or contact us directly: </p>
  <a href="tel:+020 7602 5089">  <img src="Phone.png" style="height: 50px; float: left;"> </a>
  <p> &nbsp Office: <a href="tel:+020 7602 5089"> 020 7602 5089 </a> </p> <br>

  <a href="https://wa.me/1234"> <img src="Whatsapp.jpg" style="height: 40px; float: left; margin: 5px"> </a>
  <p> &nbsp Whatsapp: <a href="https://wa.me/1234"> 0744192384 </a> </p>

  <a href="mailto: theteam@smartteeth.com"> <img src="Gmail.png" style="height: 30px; float: left;"> </a>
  <p> &nbsp &nbsp &nbspEmail: <a href="mailto: theteam@smartteeth.com"> theteam@smartteeth.com </a> </p> <br>

  <form class="" action="index.html" method="post" style= "border: green solid 2px; width: 40%; border-radius: 15px; padding: 10px;">
    <label for="name"> </label>
    <input type="text" name="name" value="Name"> <br> <br>
    <label for="name"> </label>
    <input type="text" name="name" value="Contact number"> <br> <br>
    <label for="name"> </label>
    <input type="text" name="name" value="Email"> <br> <br>

    <div class="dropdown">
      <button class="dropbtn"> Services &#9660; </button>
      <div class="dropdown-content">
        <a href="#"> Whitening </a>
        <a href="#"> Crowning </a>
        <a href="#"> Implant </a>
      </div>
    </div> <br> <br>

    <textarea rows="5" cols="18"> Additional comments </textarea> <br> <br>
    <input type="submit" />
  </form>

  <script>
    function openNav() {
      document.getElementById("mySidebar").style.width = "250px";
      document.getElementById("main").style.marginLeft = "250px";
    }

    function closeNav() {
      document.getElementById("mySidebar").style.width = "0";
      document.getElementById("main").style.marginLeft= "0";
    }
  </script>

</body>

</html>
