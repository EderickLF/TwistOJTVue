<template lang='pug'>
section.section_1
  .bg
    .columns
      img.column(src="~assets/logo-cvx.png" style="width:70px; height:55px;")
      h1(class='navbar-item' style="color:white") ConvX
    nav.navbar
      div.navbar-brand
        a(class='navbar-item' href="#AboutUs" style="color:white") About Us
        a(class='navbar-item' href="#Contact" style="color:white") Contact Us
        a(class='navbar-item' href="#How" style="color:white") How It Works
            a(class='SignIn button' href="#SignIn" style="color:white; background-color: #3f51b5;") Sign In
    .title
      h1(class="title")   
</template>

<script>
export default {}
</script>


<style>

.navbar{
float:right;
padding:15px 150px 0 0;
background-color:transparent;

}


.SignIn{
  padding-left:10px;
  outline:none;
  border:none;
  left:15px;
 
}


.columns{
float:left;
padding-left:200px;
padding-top:28px;
background-color:transparent;
color:white;
}

.bg{
background-image:url("~assets/banner-1.jpeg");
background-size: cover;
height: 650px;
background-position: center;
}
</style>
