# bakery
<!DOCTYPE html>

<html>
<head>
    <style>
        body{
   font-size:20px;
            color: rgb(255, 255, 255);
            background-size: cover;
        }
         .box{ width: 900px;
       float:right;
       border:1px solid none;}
       .box ul li{
           width: 120px;
           float:left;
           margin: 10px auto;
           text-align: center;
       }
 .mainmenu
.mainmenu a
.mainmenu a:hover
.mainmenu img{
position: fixed;
z-index: -1;
top:0px; left:0px; width:100%; height: 100vh;
opacity: 0.9;
/*object-fit:cover;*/
transition: all ease 0.5s;
}
   .wd{
           width: 300px;
           height: 539px;
           background-color: black;
           opacity: 0.8;
           padding: 55px;
       }
       .wd h1{
           text-align: center;
           text-transform: uppercase;
           font-weight: 300px;
       }
       .wd h4{
           text-align: justify;
           color:darkgray;
           font-weight: 100px;
       }
       .wd h2{
           text-align: center;
           text-transform: uppercase;
           font-weight: normal;
           margin: 40px auto;
       }
       .opt form , input[type="button"]{
           background-color: black;
           color:white;
         /* padding:10px;*/
           margin:-14px auto;
           padding-left: 50px;
           padding-right: 50px;
           text-align: center;
           font-size: 16px;
       }
     form, input[type="button"] {
       animation: glowing 300ms infinite;
       font-weight: 500%;
      }
      @keyframes glowing {
 0% {
   background-color: red;
 }
 50% {
   background-color: orange;
 }
 100% {
   background-color: maroon;
 }
}
   </style>
</head>
<body>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script>
$(function(){
var image = $(".mainmenu").find('img').attr('src');
$(".mainmenu a").mouseover(function(){
var newimg = $(this).attr('data-image');
$(this).parent().find('img').attr("src", newimg);
});
});
</script>
   <div class="box">
<div class="mainmenu">
<img src="https://th.bing.com/th/id/R.01fcba7dbc7f641e4ca4f65fb69245fd?rik=ReBuBi03CprQjA&riu=http%3a%2f%2flanuevabakery.com%2fassets%2fimages%2fCakes%2fcakes2_big.jpg&ehk=C2kKAtNJCQSU7MtODu2s3Co5vibJbXiCyPHcftntsIs%3d&risl=&pid=ImgRaw&r=0">
<a data-image = "food.png" href=""> Home</a>
<a data-image = "menucard.jpg" href=""> Menu</a>
<a href=""> FAQ</a>
<a href=""> Contact</a>
</div>
   </div>
   <div class="wd">
<h1> WELCOME TO JANTY BAKERY</h1>
<h4> <i>Order delicious cakes online, 100% quality, safety and taste assured.</i></h4>
<h2> Call 0746721832 for reservations</h2>
<div class="opt">
<form action="" method="post">
<input type="button" value="ORDER NOW">
</form>
</div>
</div>
</body>
</html>
