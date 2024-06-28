# Writeup for Making restaurant website:
## 27/6/24
Final Code from My Side, After making changes using CSS ,Bootstrap and Tailwind.

### index.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge"
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Luxurious+Script&display=swap" rel="stylesheet">
    <title>The Enchanted Gastronome</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-image: url('images/home.jpg');
            background-repeat: no-repeat;
            background-attachment: fixed; 
            background-size: 100% 100%;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            color: #e3b9b3;
            background-color:#613a43;
            font-family: "Luxurious Script", cursive;
            font-weight: 400;
            font-style: normal;
            padding: 10px;
        }
        h2 {
            text-align: left;
            padding-top: 10px;
            margin-left: 20px;
            font-family: "Poppins", sans-serif;
            font-weight: 600;
            font-style: normal;
            padding-bottom: 30px;
            color: yellow;
        }
        .Margin {
            margin-left: 40px;
        }
        .card-body {
            background-color: #e5e5e5;
        }
       
    </style>
</head>
<body>
    <div>
        <div>
            <h1>The Enchanted Gastronome</h1>
        </div>
        <div>
            <nav class="navbar navbar-expand-lg" style="background-color: #97a989;">
                <div class="container-fluid">
                  <a class="btn btn-success" href="index.html" style="color: #ffffff;">Home</a>
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="btn-group">
                      <a class="btn btn-success" href="about.html" style="color: #ffffff;">About</a>
                      <a class="btn btn-success" href="contact.html" style="color: #ffffff;">Contact</a>
                      <a class="btn btn-success" href="book.html" style="color: #ffffff;">Book a seat</a>
                    </div>
                  </div>
                </div>
              </nav> 
        </div>
        <main>

            <header>
                <h2>Our Exquisite Culinary Creations:-</h4>
            </header>

            <div>
                <div class = "Margin">
                    <div class="d-flex flex-wrap">
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/eggnoodles.jpg" class="card-img-top" alt="mario">
                            <div class="card-body">
                                <h5 class="card-title">Egg Noodles</h5>
                                <p class="card-text">Egg noodles are a type of noodle distinguished by the inclusion of eggs along with the usual flour and water. They are a versatile ingredient in many cuisines around the world, known for their rich flavor and tender texture.</p>
                                <a href="book.html" class="btn btn-primary">500Rs</a>
                            </div>
                        </div>
                
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/pizzas.jpg" class="card-img-top" alt="mario">
                            <div class="card-body">
                                <h5 class="card-title">Chicago Pizza</h5>
                                <p class="card-text">
                                    A crispy, cracker-like crust with toppings spread to the edges, cut into squares, and often called "party-cut" or "tavern-cut."
                                </p>
                                <a href="book.html" class="btn btn-success">500Rs</a>
                            </div>
                        </div>
                    </div>
                    </div>
                </div>
            </div>
        </main>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
```
### about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Luxurious+Script&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-image: url(images/about.jpg);
            background-repeat: no-repeat;
            background-attachment: fixed; 
            background-size: 100% 100%;
            color: white;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            color: #e3b9b3;
            background-color:#613a43;
            font-family: "Luxurious Script", cursive;
            font-weight: 400;
            font-style: normal;
            padding: 10px;
        }
        .container{
            font-family: "Poppins", sans-serif;
            font-weight: 200;
        }
        
    </style>
</head>
<body>
    <div>
        <h1>The Enchanted Gastronome</h1>
    </div>
    <nav class="navbar navbar-expand-lg" style="background-color: #e6d3a7;">
        <div class="container-fluid">
            <a class="btn btn-info" href="about.html" style="color: #ffffff;">About</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="btn btn-success" href="index.html" style="color: #ffffff;">Home</a>
                    <a class="btn btn-info" aria-current="page" href="about.html" style="color: #ffffff;">About</a>
                    <a class="btn btn-success" href="contact.html" style="color: #ffffff;">Contact</a>
                    <a class="btn btn-success" href="book.html" style="color: #ffffff;">Book a seat</a>
                </div>
            </div>
        </div>
    </nav>

    <main class="container mt-4">
        <header>
            <h2>About Us</h2>
            <p>The Enchanted Gastronome is a whimsical dining experience where each dish tells a story inspired by folklore and fairy tales from around the world. The restaurant is designed to resemble a magical forest grove, with softly glowing lanterns, twisted tree branches as dividers between tables, and tables adorned with miniature gardens and mystical artifacts.</p>
        </header>

        <section>
            <h3>Ambiance</h3>
            <p>Soft, ethereal music fills the air, changing subtly with each course to reflect different mythical realms. Servers are dressed in elegant attire reminiscent of woodland creatures, adding to the magical atmosphere.</p>
        </section>
    </main>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>

```
### contact.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Luxurious+Script&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-image: url('images/bg.jpg');
            background-repeat: no-repeat;
            background-attachment: fixed; 
            background-size: 100% 100%;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            color: #e3b9b3;
            background-color:#613a43;
            font-family: "Luxurious Script", cursive;
            font-weight: 400;
            font-style: normal;
            padding: 10px;
        }

        .container{
            color: white;
            font-family: "Poppins", sans-serif;
            font-weight: 200;
        }

        
    </style>
</head>
<body>
    <div>
        <h1>The Enchanted Gastronome</h1>
    </div>
    <nav class="navbar navbar-expand-lg" style="background-color:#ae7c7c;">
        <div class="container-fluid">
            <a class="btn btn-success" href="contact.html" style="color: #ffffff;">Contact</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="btn btn-info" href="index.html" style="color: #ffffff;">Home</a>
                    <a class="btn btn-info" href="about.html" style="color: #ffffff;">About</a>
                    <a class="btn btn-success" aria-current="page" href="contact.html" style="color: #ffffff;">Contact</a>
                    <a class="btn btn-info" href="book.html" style="color: #ffffff;">Book a seat</a>
                </div>
            </div>
        </div>
    </nav>

    <main class="container mt-4">
        <header>
            <h2>Contact Us</h2>
            <p>Get in touch with us for reservations, inquiries, or feedback.</p>
        </header>

        <section>
            <h3>Address</h3>
            <p>123 Restaurant Street, Cityville, Country</p>
        </section>

        <section>
            <h3>Phone</h3>
            <p>+123 456 7890</p>
        </section>

        <section>
            <h3>Email</h3>
            <p>theenchantedgastronome@gmail.com</p>
        </section>
    </main>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>

```
### book.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book a Seat</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Luxurious+Script&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-image: url('images/book.jpg');
            background-repeat: no-repeat;
            background-attachment: fixed; 
            background-size: 100% 100%;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            color: #e3b9b3;
            background-color:#613a43;
            font-family: "Luxurious Script", cursive;
            font-weight: 400;
            font-style: normal;
            padding: 10px;
        }
        .container{
            font-family: "Poppins", sans-serif;
            font-weight: 200;
            color: whitesmoke;
        }
    </style>
</head>
<body>
    <div>
        <h1>The Enchanted Gastronome</h1>
    </div>
    <nav class="navbar navbar-expand-lg" style="background-color: #eca9a9;">
        <div class="container-fluid">
            <a class="btn btn-success" href="book.html" style="color: #ffffff;">Book a seat</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="btn btn-info" href="index.html" style="color: #ffffff;">Home</a>
                    <a class="btn btn-info" href="about.html" style="color: #ffffff;">About</a>
                    <a class="btn btn-info" href="contact.html" style="color: #ffffff;">Contact</a>
                    <a class="btn btn-success" aria-current="page" href="book.html" style="color: #ffffff;">Book a seat</a>
                </div>
            </div>
        </div>
    </nav>

    <main class="container mt-4">
        <header>
            <h2>Book a Seat</h2>
            <p>Make a reservation to dine at our restaurant.</p>
        </header>

        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" placeholder="Enter your name">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email address</label>
                <input type="email" class="form-control" id="email" placeholder="Enter your email">
            </div>
            <div class="mb-3">
                <label for="date" class="form-label">Date</label>
                <input type="date" class="form-control" id="date">
            </div>
            <div class="mb-3">
                <label for="time" class="form-label">Time</label>
                <input type="time" class="form-control" id="time">
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </main>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>

```
### images:<br>
[mario.jpg](https://upload.wikimedia.org/wikipedia/en/a/a9/MarioNSMBUDeluxe.png)<br>

[pizza.jpg](https://upload.wikimedia.org/wikipedia/commons/9/91/Pizza-3007395.jpg)

[pizzas.jpg] (https://images.unsplash.com)

[eggnoodles.jpg ] (https://images.unsplash.com)

[home.jpg] (https://images.unsplash.com)

[about.jpg] (https://images.unsplash.com)

[contact.jpg] (https://images.unsplash.com)


I think, that's good enough for the day.<br>
