<!DOCTYPE html>
<html FLEXILINK="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Business Website</title>
    <style>
        /* CSS code for styling your website */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .hero {
            height: 80vh;
            background-image: url("hero.jpg");
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .hero h1 {
            color: white;
            font-size: 5rem;
            text-shadow: 2px 2px 4px black;
        }

        .hero button {
            padding: 15px 25px;
            border: none;
            border-radius: 5px;
            background-color: white;
            color: black;
            font-size: 1.5rem;
            cursor: pointer;
        }

        .about {
            padding: 50px 0;
            background-color: lightgray;
        }

        .about h2 {
            text-align: center;
            font-size: 3rem;
            margin-bottom: 25px;
        }

        .about p {
            font-size: 1.2rem;
            line-height: 1.5;
        }

        .services {
            padding: 50px 0;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 25px;
        }

        .service {
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 25px;
        }

        .service h3 {
            font-size: 2rem;
            margin-bottom: 15px;
        }

        .service p {
            font-size: 1.2rem;
            line-height: 1.5;
        }

        .contact {
            padding: 50px 0;
            background-color: lightblue;
        }

        .contact h2 {
            text-align: center;
            font-size: 3rem;
            margin-bottom: 25px;
        }

        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .contact input, .contact textarea {
            width: 80%;
            padding: 15px;
            border: none;
            border-radius: 5px;
            margin-bottom: 15px;
        }

        .contact button {
            width: 40%;
            padding: 15px;
            border: none;
            border-radius: 5px;
            background-color: white;
            color: black;
            font-size: 1.5rem;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Hero section -->
        <div class="hero">
            <div class="hero-content">
                <h1>My Business Website</h1>
                <button>Get in touch</button>
            </div>
        </div>
        <!-- About section -->
        <div class="about">
            <h2>About Us</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis leo quis nisi consequat ullamcorper. Morbi vitae semper nisl, quis tincidunt nunc. Fusce id lacus quis velit tincidunt luctus. Cras quis augue id nisl aliquam fringilla. Phasellus euismod, leo quis lacinia feugiat, lorem magna malesuada nisi, sit amet sagittis eros justo sed leo.</p>
        </div>
        <!-- Services section -->
        <div class="services">
            <div class="service">
                <h3>Service 1</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis leo quis nisi consequat ullamcorper. Morbi vitae semper nisl, quis tincidunt nunc.</p>
            </div>
            <div class="service">
                <h3>Service 2</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis leo quis nisi consequat ullamcorper. Morbi vitae semper nisl, quis tincidunt nunc.</p>
            </div>
            <div class="service">
                <h3>Service 3</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis leo quis nisi consequat ullamcorper. Morbi vitae semper nisl, quis tincidunt nunc.</p>
            </div>
        </div>
        <!-- Contact section -->
        <div class="contact">
            <h2>Contact Us</h2>
            <form>
                <input type="text" name="name" placeholder="Name">
                <input type="email" name="email" placeholder="Email">
                <textarea name="message" placeholder="Message"></textarea>
                <button>Send</button>
            </form>
        </div>
    </div>
    <script>
        // JavaScript code for adding interactivity to your website
    </script>
</body>
</html>


