# Ex.07 Restaurant Website

# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
website.html(Home page)
```
<HTML>
    <HEAD>
        <TITLE>🍧🍨🧁🥞🧋ELON'S RESTAURANT🍧🍨🧁🥞🧋</TITLE>
        <LINK REL="ICON" HREF="c:\Users\admin\Downloads\download.jpg">
        <STYLE>
            BODY{
                background-repeat: no-repeat;
                background-position: center;
                background-size: cover;
            
                
            }
            font{
                font-family: Georgia, 'Times New Roman', Times, serif;
            }
            div{
                display: inline-block;
                height: 600;
                width: 1500;    
                background-repeat: no-repeat;
            
                
            }
            FONT{
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            }
        </STYLE>
    </HEAD>
    <BODY background="c:\Users\admin\Downloads\forter-webinar.jpg.imgix.banner.jpg">
        <HR SIZE="7" COLOR="BLACK">
        <header style="background-image: url('c:/Users/admin/Downloads/FOOD.jpeg'); background-position: center; color: rgb(255, 255, 255);">
        <PRE>                                                                                      <img SRC="c:\Users\admin\Downloads\ELON2.jpg" BORDER="5" style="color: aqua; vertical-align:middle;" width="80" height="80"><FONT SIZE="6">ELON'S RESTAURANT</FONT></PRE>
        <HR SIZE="7" COLOR="BLACK">
        </header>
        <header>
            <pre style="background-color: aqua;">                                                                           <A HREF="WEBSITE.HTML" style="font-size: 24px;">HOME</A>       <A href="WEB1.HTML" style="font-size: 24px;">MENU</A>       <A href="WEB2.HTML" style="font-size: 24px;">ABOUT</A>      <A href="WEB3.HTML" style="font-size: 24px;">CONTACT</A>                </pre>
        </header>
        <pre>
                <div style="background-image: url('c:/Users/admin/Downloads/123.jpg');" ><FONT SIZE="9">                           SPECIAL DIWALI OFFER</FONT>           <BR><FONT SIZE="7" style="color: rgb(2, 238, 255);"><BR><BR><BR>                        NOW AT <STRIKE>30% OFF</STRIKE>  50% OFF</FONT><BR> <BR><BR><BR> <BR><BR><BR> <BR><BR><BR> <BR><BR><BR> <BR><BR><BR> <FONT SIZE="5" style="color: rgb(255, 255, 255);"> Vegan/Vegetarian Nuggets: Made from plant-based proteins such as soy, pea protein, or wheat gluten.
  Gluten-Free Nuggets: Use gluten-free breading for those with gluten sensitivities or celiac disease.
  Spicy Nuggets: Incorporate hot spices or sauces into the breading for a spicier flavor.</FONT></div>
        </pre>
        <footer>
            <h3 style="background-color: rgb(0, 247, 255); color: rgb(0, 0, 0); font: bold;"><MARQUEE>&copy; 2024 ELON'S RESTAURNT. All Rights Reserved. DONE BY JAIHARISH.R</MARQUEE></h3>
        </footer>
    
    </BODY>

</HTML>
```
web1.html(menu page)
```
<HTML>
    <HEAD>
        <TITLE>🍧🍨🧁🥞🧋ELON'S RESTAURANT🍧🍨🧁🥞🧋</TITLE>
        <LINK REL="ICON" HREF="c:\Users\admin\Downloads\download.jpg">
        <STYLE>
            BODY{
                background-repeat: no-repeat;
                background-position: center;
                background-size: cover;
                
            }
            font{
                font-family: Georgia, 'Times New Roman', Times, serif;
            }
            .container {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            width: 90%;
            max-width: 1200px;
            }

           .item {
            text-align: center;
            }
           .item img {
            width: 300;
            height: 350;
            margin: 30PX;
            }       
        </STYLE>
    </HEAD>
    <BODY background="c:\Users\admin\Downloads\forter-webinar.jpg.imgix.banner.jpg">
        <HR SIZE="7" COLOR="BLACK">
        <header style="background-image: url('c:/Users/admin/Downloads/FOOD.jpeg'); background-position: center; color: rgb(255, 255, 255);">
        <PRE>                                                                                      <img SRC="c:\Users\admin\Downloads\ELON2.jpg" BORDER="5" style="color: aqua;vertical-align:middle;" width="80" height="80"><FONT SIZE="6">ELON'S RESTAURANT</FONT></PRE>
        <HR SIZE="7" COLOR="BLACK">
        </header>
        <header>
            <pre style="background-color: aqua;">                                                                           <A HREF="WEBSITE.HTML" style="font-size: 24px;">HOME</A>       <A href="WEB1.HTML" style="font-size: 24px;">MENU</A>       <A href="WEB2.HTML" style="font-size: 24px;">ABOUT</A>      <A href="WEB3.HTML" style="font-size: 24px;">CONTACT</A>                </pre>
        </header>
        <center><h1 style="color: orangered;">Our Delicious Menu</h1></center>
        <div class="container">
            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\20240910-110122.webp">
                <H3>BURGER</H3>
                <H4>RS:300</H4>
            </DIV>
            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\FRENCH  FRIES.jpeg" >
                <h3>FRENCH FRIES</h3>
                <H4>RS:100</H4>
            </DIV>
            
            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\NUGGETS.jpg" >
                <H3>CHICKEN NUGGETS</H3>
                <H4>RS:200</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\pizza.jpg" >
                <H3>PIZZA</H3>
                <H4>RS:250</H4>
            </DIV>
            
            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\kfc-original-chicken-recipe.webp" >
                <H3>CHICKEN</H3>
                <H4>RS:250</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\ice cream cake.jpeg" >
                <H3>ICE CREAM CAKE</H3>
                <H4>RS:150</H4>   
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\Rabri-Falooda-scaled.jpg" >
                <H3>FALOODA</H3>
                <H4>RS:200</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\WAFFLES.jpg" >
                <H3>WAFFLES</H3>
                <H4>RS:180</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot (141).png" >
                <H3>MILK SHAKE</H3>
                <H4>RS:150</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\ccfe5b91423353.5e317bac1f049.png" >
                <H3>ICE CREAM</H3>
                <H4>RS:100</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\chicken tikka.jpg" >
                <H3>CHICKEN TIKKA</H3>
                <H4>RS:200</H4>
            </DIV>
            
            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\chicken-tikka-paratha-rolls-featured.jpg" >
                <H3>CHICKEN ROLL</H3>
                <H4>RS:70</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\NOODLES.jpg" >
                <H3>NOODLES</H3>
                <H4>RS:160</H4>
            </DIV>
            
            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\Chicken-Biryani-Recipe.jpg" >
                <H3>CHICKEN BIRYANI</H3>
                <H4>RS:350</H4>
            </DIV>

            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\Butter-Chicken-Garlic-Naan-Pizza.jpg" >
                <H3>BUTTER NAAN</H3>
                <H4>RS:600</H4>
            </DIV>
            
            <DIV CLASS="item">
                <img src="c:\Users\admin\Downloads\bombay-sandwich.jpg" >
                <H3>SANDWICH</H3>
                <H4>RS:140</H4>
            </DIV>
            
        </div>
    <footer>
        <h3 style="background-color: rgb(0, 247, 255); color: rgb(0, 0, 0); font: bold;"><MARQUEE>&copy; 2024 ELON'S RESTAURNT. All Rights Reserved. DONE BY JAIHARISH.R</MARQUEE></h3>
    </footer>
        </BODY>
</HTML>
```
web2.html(Administration page)
```
<HTML>
    <HEAD>
        <TITLE>🍧🍨🧁🥞🧋ELON'S RESTAURANT🍧🍨🧁🥞🧋</TITLE>
        <LINK REL="ICON" HREF="c:\Users\admin\Downloads\download.jpg">
        <STYLE>
            BODY{
                background-repeat: no-repeat;
                background-position: center;
                background-size: cover;
                
            }
            font{
                font-family: Georgia, 'Times New Roman', Times, serif;
            }
            .container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            width: 90%;
            max-width: 1200px;
            }

           .item {
            text-align: center;
            
            
            }
           .item img {
            width: 400;
            height: 450;
            margin: 40PX;
            }   
        </STYLE>
    </HEAD>
    <BODY background="c:\Users\admin\Downloads\forter-webinar.jpg.imgix.banner.jpg">
        <HR SIZE="7" COLOR="BLACK">
        <header style="background-image: url('c:/Users/admin/Downloads/FOOD.jpeg'); background-position: center; color: rgb(255, 255, 255);">
        <PRE>                                                                                      <img SRC="c:\Users\admin\Downloads\ELON2.jpg" BORDER="5" style="color: aqua;vertical-align:middle;" width="80" height="80"><FONT SIZE="6">ELON'S RESTAURANT</FONT></PRE>
        <HR SIZE="7" COLOR="BLACK">
        </header>
        <header>
            <pre style="background-color: aqua;">                                                                           <A HREF="WEBSITE.HTML" style="font-size: 24px;">HOME</A>       <A href="WEB1.HTML" style="font-size: 24px;">MENU</A>       <A href="WEB2.HTML" style="font-size: 24px;">ABOUT</A>      <A href="WEB3.HTML" style="font-size: 24px;">CONTACT</A>                </pre>
            <PRE>                                            <FONT SIZE="11"></FONT>                                                  </PRE>            
        </header>
        <pre ><font style="font-family: Georgia, 'Times New Roman', Times, serif; color: orangered; " size="6">                                                                         ----team members----</font><br>
        <font style="font-family: Georgia, 'Times New Roman', Times, serif; color: rgb(0, 0, 0); " size="7">                                        Our Master Chefs</font></pre>
           <br>
    <div class="container">
        <DIV CLASS="item">
            <img src="c:\Users\admin\Downloads\cc1.jpg" >
            <H3>Damodharan</H3>
        </DIV>

        <DIV CLASS="item">
            <img src="c:\Users\admin\Downloads\c15.jpg" >
            <H3>Sanjeev Kapoor</H3>
        </DIV>
        
        <DIV CLASS="item">
            <img src="c:\Users\admin\Downloads\c333.jpg" >
            <H3>Jeremiah Langhorne</H3>
        </DIV>

        <DIV CLASS="item">
            <img src="c:\Users\admin\Downloads\c14.jpg" >
            <H3>Vikram Khatri</H3>
        </DIV>

        <DIV CLASS="item">
            <img src="c:\Users\admin\Downloads\c13.jpg" >
            <H3>Atul Kochhar</H3>
        </DIV>

        <DIV CLASS="item">
            <img src="c:\Users\admin\Downloads\c11.jpg" >
            <H3>Vineet Bhatia</H3>
        </DIV>
    </div>    
        <footer>
            <h3 style="background-color: rgb(0, 247, 255); color: rgb(0, 0, 0); font: bold;"><MARQUEE>&copy; 2024 ELON'S RESTAURNT. All Rights Reserved. DONE BY JAIHARISH.R</MARQUEE></h3>
        </footer>
    </BODY>
</HTML>
```
web3.html(Contact us page)
```
<HTML>
    <HEAD>
        <TITLE>🍧🍨🧁🥞🧋ELON'S RESTAURANT🍧🍨🧁🥞🧋</TITLE>
        <LINK REL="ICON" HREF="c:\Users\admin\Downloads\download.jpg">
        <STYLE>
            BODY{
                background-repeat: no-repeat;
                background-position: center;
                background-size: cover;
                
            }
            font{
                font-family: Georgia, 'Times New Roman', Times, serif;
            }
        </STYLE>
    </HEAD>
    <BODY background="c:\Users\admin\Downloads\forter-webinar.jpg.imgix.banner.jpg">
        <HR SIZE="7" COLOR="BLACK">
        <header style="background-image: url('c:/Users/admin/Downloads/FOOD.jpeg'); background-position: center; color: rgb(255, 255, 255);">
        <PRE>                                                                                      <img SRC="c:\Users\admin\Downloads\ELON2.jpg" BORDER="5" style="color: aqua;vertical-align:middle;" width="80" height="80"><FONT SIZE="6">ELON'S RESTAURANT</FONT></PRE>
        <HR SIZE="7" COLOR="BLACK">
        </header>
        <header>
            <pre style="background-color: aqua;">                                                                           <A HREF="WEBSITE.HTML" style="font-size: 24px;">HOME</A>       <A href="WEB1.HTML" style="font-size: 24px;">MENU</A>       <A href="WEB2.HTML" style="font-size: 24px;">ABOUT</A>      <A href="WEB3.HTML" style="font-size: 24px;">CONTACT</A>                </pre>
        </header>
        <br>
        <div style="text-align: center; padding: 30px; color: rgb(0, 0, 0);">
            <h2 style="font-size: 32px; margin-bottom: 20px;">Get in Touch</h2>
            <p style="font-size: 18px; margin-bottom: 15px; line-height: 1.6;">
                Have a question about our menu, hours, or services? Looking to make a reservation or share feedback? 
                We're here to help! Fill out the form below, and we’ll get back to you as soon as possible.
            </p>
            <p style="font-size: 18px; margin-bottom: 15px; line-height: 1.6;">
                Prefer to talk to someone directly? Give us a call at 91+ 8248598754 OR send a mail to jaiharish.r.sec@gmail.com
            </p>
            <p style="font-size: 18px; line-height: 1.6;">
                Or, visit us at our location:
                <strong style="display: block; margin-top: 10px;">saveetha nagar, Food City, trichy-14</strong>
                <div>
                    <div style="text-align: center; margin: 30px auto; width: 50%; padding: 20px; ">
                        <h2 style="margin-bottom: 20px;">Leave Us a Review</h2>
                        <form>
                            <label for="name" style="display: block; margin-bottom: 8px; font-weight: bold;">Your Name</label>
                            <input type="text" id="name" name="name" placeholder="Enter your name" required style="width: 100%; padding: 10px; margin-bottom: 15px; ">
                
                            <label for="email" style="display: block; margin-bottom: 8px; font-weight: bold;">Your Email</label>
                            <input type="email" id="email" name="email" placeholder="Enter your email" required style="width: 100%; padding: 10px; margin-bottom: 15px; ">
                
                            <label for="review" style="display: block; margin-bottom: 8px; font-weight: bold;">Your Review</label>
                            <textarea id="review" name="review" placeholder="Write your review here" required style="width: 100%; padding: 10px; margin-bottom: 15px;"></textarea>
                
                            <button type="submit" style="padding: 10px 20px; background-color: aqua; color: white; border: none; border-radius: 4px; cursor: pointer; font-size: 16px;">Submit Review</button>
                        </form>
                    </div>
        </div>
        
        <footer>
            <h3 style="background-color: rgb(0, 247, 255); color: rgb(0, 0, 0); font: bold;"><MARQUEE>&copy; 2024 ELON'S RESTAURNT. All Rights Reserved. DONE BY JAIHARISH.R</MARQUEE></h3>
        </footer>
    </BODY>
</HTML>
```

# OUTPUT:
Home page
![Screenshot (219)](https://github.com/user-attachments/assets/fc7443cc-73ce-4cf7-82af-4a67d0bbb5fe)
Menu page
![screencapture-file-C-Users-admin-Desktop-HTML-STARTING-POINT-WEB1-HTML-2024-12-11-13_14_21](https://github.com/user-attachments/assets/e7e97381-3a0b-4bfd-9dcb-1f050902d1fc)
Administration page
![screencapture-file-C-Users-admin-Desktop-HTML-STARTING-POINT-WEB2-HTML-2024-12-11-13_18_42](https://github.com/user-attachments/assets/4df4e150-0d4e-47ec-a383-6b5b0bad8927)
Contact us page
![screencapture-file-C-Users-admin-Desktop-HTML-STARTING-POINT-WEB3-HTML-2024-12-11-14_14_20](https://github.com/user-attachments/assets/77e737b4-5301-4ee7-898b-5695ae325116)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
