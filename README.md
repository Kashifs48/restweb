# Ex.07 Restaurant Website
## Date:16/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Late Night Cafeteria</title>
</head>
<body>

    <div style="font-size: 40px; color: #74a8d1; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; text-align: center; background-color: rgb(255, 255, 255); padding: 20px;">
        <h1>LN SNACKERS</h1>
        <img src="LN logo.png" alt="LN" style="width: 300px; height: auto; margin-top: 1px;">
    </div>

    <nav style="background-color: #203a4c; padding: 10px; text-align: center; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
        <ul style= "list-style-type: none; padding: 0; margin: 0;">
            <li style="display: inline; margin-right: 20px;"><a href="#home" style="text-decoration: none; color: white;">Home</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#about" style="text-decoration: none; color: white;">About</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#menu" style="text-decoration: none; color: white;">Menu</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#members" style="text-decoration: none; color: white;">Administration</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#query" style="text-decoration: none; color: white;">Query</a></li>
            <li style="display: inline; margin-right: 20px;"><a href="#contact" style="text-decoration: none; color: white;">Contact</a></li>
        </ul>
    </nav>

    <section id="home" style="padding: 20px; text-align: center; background-color: rgb(161, 145, 214); font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
        <h2>Introducing the all new LN SNACKERS</h2>
        <p>Welcome to LN Snackers, where snacking meets innovation and flavor.</p>
        <p>We use only the finest ingredients, carefully sourced to ensure every snack is as wholesome as it is delicious. </p>
        <p>From classic favorites to bold, adventurous blends, our snacks are crafted to excite your taste buds. </p>
        <p>At LN Snackers, we believe that every bite should be a delightful journey</p>
        <p>"Bringing people together, one plate at a time." </p>
    </section>

    <section id="about" style="padding: 20px; text-align: center; background-color: #bfd6f0; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
        <h2>About Us</h2>
        <p>At LN Snackers, we’re all about bringing joy to every bite! </p>
        <p>We specialize in crafting delicious, high-quality snacks that satisfy cravings and fuel your day.</p>
        <p>Whether you’re on the go, hosting friends, or just indulging in a little treat for yourself, LN Snackers is here to make every moment more flavorful. </p>
        <p>With a passion for taste and a commitment to excellence, we’re your go-to for snacks that hit the spot.</p>
    </section>

    <section id="menu" style="padding: 20px; text-align: center; background-color: #71a6e3; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
        <h2>Signature Dishes</h2>
        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
            <div style="text-align: left;">
                <img src="Chicken-Biryani.jpg" style="width: 150px; height: 150px;">
                <p>Dum Biriyani - Rs 200</p>
            </div>
            <div style="text-align: left;">
                <img src="Tandoori-Chicken-Square-image.jpg" style="width: 150px; height: 150px;">
                <p>Tandoori Chicken - Rs 250</p>
            </div>
            <div style="text-align: left;">
                <img src="infused.jpg" style="width: 150px; height: 150px;">
                <p>Infused Chicken - Rs 275</p>
            </div>
            <div style="text-align: left;">
                <img src="mohabbat-ka-sharbat-recipe.jpg" style="width: 150px; height: 150px;">
                <p>Mohabbat Ka Sharbat - Rs 100</p>
            </div>
            <div style="text-align: left;">
                <img src="tiramisu.jpg" alt="Savory tart with a filling of cream, eggs, and bacon or lardons." style="width: 150px; height: 150px;">
                <p>Tiramisu - Rs 125</p>
            </div>
            <div style="text-align: left;">
                <img src="Waffle.jpg" alt="Mussels cooked in white wine, shallots, and parsley." style="width: 150px; height: 150px;">
                <p>Waffle - Rs 150</p>
            </div>
        </div>
    </section>

    <section id="members" style="padding: 20px; text-align: center; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
        <h2>Honourable Committee</h2>
        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
            <div style="text-align: center;">
                <img src="ceo.png" style="width: 150px; height: 150px;">
                <p>Syed Kashif - Founder</p>
            </div>
            <div style="text-align: center;">
                <img src="mukesh.jpg" style="width: 150px; height: 150px;">
                <p>Mukesh - Investor</p>
            </div>
            <div style="text-align: center;">
                <img src="sanjeev kapoor.jpg" style="width: 150px; height: 150px;">
                <p>Sanjeev Kapoor - Our Chief Chef</p>
            </div>
            <div style="text-align: center;">
                <img src="chefdamu.png" style="width: 150px; height: 150px;">
                <p>Damu - Our Executive Chef</p>
            </div>
            <div style="text-align: center;">
                <img src="ramshriram.webp" style="width: 150px; height: 150px;">
                <p>Ram Shriram - Overseas Partner</p>
            </div>
        </div>
    </section>

    <section id="query" style="padding: 20px; text-align: center; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; background-color: #4a3d26; color: white;">
        <h2>Any Query</h2>
        <p>Inform us your feedback and queries here</p>
        <form action="#" style="text-align: center;">
            <input type="name" placeholder="Your Name" style="padding: 5px; margin: 5px;"><br>
            <textarea placeholder="Your Query" rows="4" style="padding: 5px; margin: 5px;"></textarea><br>
            <button type="submit" style="padding: 10px 20px; background-color: #b88d49; color: white; border: none; cursor: pointer;">Submit</button>
        </form>
    </section>

    <section id="contact" style="padding: 20px; text-align: center; background-color: #192c42; color: white; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
        <h2>Contact Us</h2>
        <p>Have questions or Want to book a table? </p>
        <p>Our email - lnsnackers56@gmail.com</p>
        <p>Our telephone - +91 74632 54091</p>
    </section>

    <div style="font-size: 15xpx; text-align: bottom; background-color: rgb(183, 209, 229); padding: 20px; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
        <p>Designed and Developed by Syed Kashif S</p>
    </div>

</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (18).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
