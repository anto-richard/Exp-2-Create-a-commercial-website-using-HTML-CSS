# Exp-2-Create-a-commercial-website-using-HTML-CSS...

## AIM:

To create a commercial website using HTML & CSS.

## ALGORITHM:

### STEP 1:

Create basic outline for website using html.

### STEP 2:

Create style part of the website using css.

### STEP 3:

Link the css file with html code using link tag.

### STEP 4:

Run the code and check the webpage in an web browser.

## PROGRAM:

```html

HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodka</title>
    <link rel="stylesheet" type="text/css" href="website.css">
</head>    
<body>
    <nav>
        <h2 class="logo">Food<span>ka</span></h2>
        <ul>
            <li><a href = "#">Home</a></li>
            <li><a href = "#">About</a></li>
            <li><a href = "#">catalog</a></li>
            
        </ul>
        <a href="#" class="btn">ORDER NOW</a>   
    </nav>
        <div class="content">
            <img src="hdburg.png" style="float: right;height: 300px;">
            <p><b>Quality food </b><br> <B>Delivered !</B></p>
        </div>
        <abt style="font-family:Arial, Helvetica, sans-serif;font-size: 22px;line-height: 29px;">A cooked beef patty sandwiched between two slices of bread—typically a circular bun—is known as a hamburger.<br>
             Along with other components like onions or herbs, the patty may also be seasoned with salt and pepper. <br>
             Cheese, lettuce, tomato, pickles, and sauces like ketchup and mustard are just a few more toppings that can be added to the sandwich.<br>
              A typical dish offered in fast food establishments, diners, and backyard barbecues around the globe is the hamburger.</abt>
            <br>
        <br>
        <br>
        <a href="#" class="btn">GET STARTED</a>  
           <br>
            <br>
            <br>
            <br>
       <img src="removebg.png" style="float: left;height: 300px;border: none;">
    <div class="content">
        <p style="white-space:pre-wrap;text-align: left;"><b> Traditional Vegetarian Food</b></p>
        
    </div>
       <abt style="font-family:Arial, Helvetica, sans-serif;font-size: 22px;line-height: 29px;">Traditional vegetarian cuisine has been a part of many civilizations and cuisines around the world for centuries. It is a style of cooking that emphasises on making a range of mouthwatering and nourishing dishes utilising plant-based materials such vegetables, fruits, grains, legumes, nuts, and seeds.

        Traditional vegetarian cuisine offers a number of advantages, including health advantages. The vitamins, minerals, and fibre found in fruits and vegetables are vital for maintaining overall health and wellbeing. Additionally, studies have shown that those who eat a plant-based diet had lower incidences of chronic illnesses like diabetes, heart disease, and several types of cancer.</abt>
<br>
<br>
<br> 



    <center>
    <a href="#" class="btn2">Order Veg Food</a></center>
   
    
    <div class="service">
        <div class="title">
         <center>   <h4>Our Happy Customers</h4></center>
         <img src="br3.png" style="float: left;">
        </div>
        <div class="box">
            <div class="card">
                
                <h5><b>Andrew Banks</b></h5>
                <div class="pra">
                   <p >"I dont always clop,but when I do,its because of food. Wow what great food has just
                    not let me leave the store until now for this very minute"
                   </p> 
                   <p style="text-align: center;">
                    
                </p>
                </div>
            </div>
            <div class="card">
                
                <h5>John Morrison</h5>
                <div class="pra">
                   <p >The food here is one of the human to eat but when I do,it's because of food.Wow what 
                    great food has just not let me to leave the store until now for this very minute.
                   </p> 
                   <p style="text-align: center;">
                     
                </p>
                </div>
            </div>
            
        </div>
    </div> 


</body>
</html>

```

```css

CSS:

body {
    background-image: url("https://img.freepik.com/free-photo/abstract-luxury-gold-studio-well-use-as-background-layout-presentation_1258-52914.jpg?size=626&ext=jpg&ga=GA1.2.1093554274.1680599274&semt=ais");
    background-repeat: no-repeat;
    background-size: cover;
    font-family: Arial, sans-serif;
    text-align: center;
}
span{
    color: gold;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: -2px;
    padding-left: 8%;
    padding-right: 8%;
}
.logo{
    color: black;
    font-size: 50px;
    letter-spacing: 1px;
    cursor: pointer;
}
nav ul li{
    list-style-type: none;
    display: inline-block;
    padding: 10px 25px;
}
nav ul li a{
    color:  black;
    text-decoration: none;
    font-weight: bold;
    text-transform: capitalize;
}
nav ul li a:hover{
    color: grey;
    transition: .4s;
}
.btn{
    background-color: orange;
    color: white;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 10px 25px;
    border-radius: 30px;
    transition: transform .4s;
}
.btn:hover{
    transform: scale(1.2);
}
.btn2{
    background-color: black;
    color: yellow;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 10px 25px;
    border-radius: 30px;
    transition: transform .4s;
}
.about{
    width: 100%;
    padding: 100px 0px;
    background-color: #191919;
}
.about img{
    height: 300px;
    float: left;
    
}
.about-text{
    width: 550px;

}
.main{
    width: 1130px;
    max-width: 95%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.about-text h5{
    color: black;
    letter-spacing: 2px;
    font-size:22px;
    margin-bottom: 25px;
    text-transform: capitalize;
}
.about-text p{
    color: black;
    letter-spacing: 1px;
    line-height: 29px;
    font-size: 18px;
    margin-bottom: 45px;
}

.menu{
    display: flex;
    justify-content: space-around;
    
}
a{
    color: black;
    font-size: 20px;
}
.content{
    color: black;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 50px;

}
.service{
    background: rgb(244, 243, 239);
    width: 100%;
    padding: 100px 10px;
}
.title h4{
    color: black;
    font-size: 50px;
    width: 1130px;
    
    text-align: center;
}
.box{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 400px;
    
    float: right;
    overflow: hidden;
background-color: goldenrod;

}
.card{
    height: 230px;
    width: 335px;
    padding: 20px 35px;
    background: whitesmoke;
    
    margin: 15px;
    position: relative;
    overflow: hidden;
    text-align: center;
}
h5{
    color: gold;
    font-size: 25px;
    margin-bottom: 15px;
}
.pra p{
    color: burlywood;
    font-size: 16px;
    line-height: 27px;
    margin-bottom: 25px;
 }
 .footer{
    width: 100%;
    background-color: black;
    background-size: cover;
 }
 
 ```

## OUTPUT:

![f1](https://github.com/anto-richard/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/93427534/1a7de7a5-309d-464d-b574-a257aeb16ea5)

![f2](https://github.com/anto-richard/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/93427534/625b0bae-0691-4bf8-b9a5-d0248df325a1)

![f3](https://github.com/anto-richard/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/93427534/f52eff22-23e0-4f49-b441-a14643e294d0)


## RESULT:

A commercial website using HTML & CSS has been created and output verified sucessfully.
