---
layout: "page"
title: "Go For It Go For It (Play The Game)"
permalink: /game
---
<html>
<head>

<script language="javascript">
</script>

<style>
.dropbtn {
    background-color: #4CAF50;
    color: white;
    padding: 16px;
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

.wrapper {
    text-align: center;
}
</style>
</head>

<body>
<div class="wrapper">
  <div class="dropdown">
    <button class="dropbtn">Choose Your Episode</button>
    <div class="dropdown-content">
      <a href="/s1e1">Season 1 Episode 1</a>
      <a href="/s1e2">Season 1 Episode 2</a>
      </div>
    </div>
</div>

<p id="demo"></p>

<script>
function season1() {
  document.getElementById("demo").innerHTML = "Hello World";
};



</script>
</body>
</html>
