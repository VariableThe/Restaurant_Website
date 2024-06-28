# Writeup for Making restaurant website:
## 23/6/24
Well, let us begin<br>
Ok, after initialising tailwind and bootcamp, I've started working on making the barebones of the website<br>
So far I've made a few things, namely, index, contact, about and book a seat html files.<br>
I'll paste the code here:<br>

### index.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Enchanted Gastronome</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-color: #1f1f1f;
            color: #ffffff;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            background-color: #cb0a0d;
            font-family: 'Georgia', serif;
            padding: 10px;
        }
        h2 {
            text-align: left;
            padding-top: 10px;
            margin-left: 20px;
            padding-bottom: 30px;
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
            <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
                <div class="container-fluid">
                  <a class="navbar-brand" href="index.html" style="color: #ffffff;">Home</a>
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                      <a class="nav-link" href="about.html" style="color: #ffffff;">About</a>
                      <a class="nav-link" href="contact.html" style="color: #ffffff;">Contact</a>
                      <a class="nav-link" href="book.html" style="color: #ffffff;">Book a seat</a>
                    </div>
                  </div>
                </div>
              </nav> 
        </div>
        <main>

            <header>
                <h2>Popular dishes:-</h4>
            </header>

            <div>
                <div class = "Margin">
                    <div class="d-flex flex-wrap">
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/mario.jpg" class="card-img-top" alt="mario">
                            <div class="card-body">
                                <h5 class="card-title">Mario</h5>
                                <p class="card-text">A very tasty little Italian plumber</p>
                                <a href="#" class="btn btn-primary">500 Rs</a>
                            </div>
                        </div>
                
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/pizza.jpg" class="card-img-top" alt="mario">
                            <div class="card-body">
                                <h5 class="card-title">Mario</h5>
                                <p class="card-text">A very tasty pizza</p>
                                <a href="#" class="btn btn-primary">500 Rs</a>
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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-color: #1f1f1f;
            color: #ffffff;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            background-color: #cb0a0d;
            font-family: 'Georgia', serif;
            padding: 10px;
        }
        
    </style>
</head>
<body>
    <div>
        <h1>The Enchanted Gastronome</h1>
    </div>
    <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
        <div class="container-fluid">
            <a class="navbar-brand" href="about.html" style="color: #ffffff;">About</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link" href="index.html" style="color: #ffffff;">Home</a>
                    <a class="nav-link active" aria-current="page" href="about.html" style="color: #ffffff;">About</a>
                    <a class="nav-link" href="contact.html" style="color: #ffffff;">Contact</a>
                    <a class="nav-link" href="book.html" style="color: #ffffff;">Book a seat</a>
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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-color: #1f1f1f;
            color: #ffffff;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            background-color: #cb0a0d;
            font-family: 'Georgia', serif;
            padding: 10px;
        }
        
    </style>
</head>
<body>
    <div>
        <h1>The Enchanted Gastronome</h1>
    </div>
    <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
        <div class="container-fluid">
            <a class="navbar-brand" href="contact.html" style="color: #ffffff;">Contact</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link" href="index.html" style="color: #ffffff;">Home</a>
                    <a class="nav-link" href="about.html" style="color: #ffffff;">About</a>
                    <a class="nav-link active" aria-current="page" href="contact.html" style="color: #ffffff;">Contact</a>
                    <a class="nav-link" href="book.html" style="color: #ffffff;">Book a seat</a>
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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body {
            background-color: #1f1f1f;
            color: #ffffff;
        }
        h1 {
            font-weight: bold;
            text-align: center;
            background-color: #cb0a0d;
            font-family: 'Georgia', serif;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div>
        <h1>The Enchanted Gastronome</h1>
    </div>
    <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
        <div class="container-fluid">
            <a class="navbar-brand" href="book.html" style="color: #ffffff;">Book a seat</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link" href="index.html" style="color: #ffffff;">Home</a>
                    <a class="nav-link" href="about.html" style="color: #ffffff;">About</a>
                    <a class="nav-link" href="contact.html" style="color: #ffffff;">Contact</a>
                    <a class="nav-link active" aria-current="page" href="book.html" style="color: #ffffff;">Book a seat</a>
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

I think, that's good enough for the day.<br>


## 28/6/24

Okay, so after getting the code back from Piyush, I've started working on it and done a few changes, namely made the text enclosed in classes in order to draw a box around them to provide readability while keeping the background images intact.<br>
I'va also added more items and colour schemed their price tags based ont them being veg, vegan or non-veg, so as to add more realsim.<br>
The code is now as follows:

### index.html:
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
            background-position: center;
            background-size: cover;
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
            margin-bottom: -10px;
        }
        h2 {
           text-align: left;
           margin-top: 10px;
           padding-top: 10px;
           padding-left: 20px;
           font-family: "Poppins", sans-serif;
           font-weight: 600;
           font-style: normal;
           padding-bottom: 30px;
           color: yellow;
           background-image: linear-gradient(to right, rgba(0, 0, 0, 0.8), rgba(218, 27, 96, 0.0));
           background-clip: padding-box;
           -webkit-background-clip: padding-box;
           border-radius: 10px;
           padding: 10px 20px;
}

        .Margin {
            margin-left: 40px;
        }
        .card-body {
            background-color: #e5e5e5;
        }
        .navbar {
            margin-top: 0;
        }
       
    </style>
</head>
<body>
    <div>
        <div>
            <h1>The Enchanted Gastronome</h1>
        </div>
        <div>
            <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
                <div class="container-fluid">
                  <a class="navbar-brand d-flex align-items-center" href="index.html" style="color: #ffffff;  font-size: 2em;">Home</a>
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                      <a class="nav-link" href="about.html" style="color: #ffffff;">About</a>
                      <a class="nav-link" href="contact.html" style="color: #ffffff;">Contact</a>
                      <a class="nav-link" href="book.html" style="color: #ffffff;">Book a seat</a>
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
                            <img src="images/pizza.jpg" class="card-img-top" alt="mario">
                            <div class="card-body">
                                <h5 class="card-title">Chicago Pizza</h5>
                                <p class="card-text">
                                    A crispy, cracker-like crust with toppings spread to the edges, cut into squares, and often called "party-cut" or "tavern-cut."
                                </p>
                                <a href="book.html" class="btn btn-primary">500Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/burger.jpg" class="card-img-top" alt="Burger">
                            <div class="card-body">
                                <h5 class="card-title">Cheeseburger</h5>
                                <p class="card-text">A classic American favorite, cheeseburgers consist of a beef patty topped with cheese, lettuce, tomato, onion, pickles, and condiments in a bun.</p>
                                <a href="book.html" class="btn btn-danger">250Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/tacos.jpg" class="card-img-top" alt="Tacos">
                            <div class="card-body">
                                <h5 class="card-title">Tacos</h5>
                                <p class="card-text">Tacos are traditional Mexican dishes consisting of a tortilla filled with various ingredients such as meats, vegetables, cheese, and salsa.</p>
                                <a href="book.html" class="btn btn-danger">180Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/pasta.jpg" class="card-img-top" alt="Pasta">
                            <div class="card-body">
                                <h5 class="card-title">Spaghetti Carbonara</h5>
                                <p class="card-text">A classic Italian pasta dish made with eggs, cheese (typically Pecorino Romano), pancetta, and black pepper.</p>
                                <a href="book.html" class="btn btn-danger">280Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/steak.jpg" class="card-img-top" alt="Steak">
                            <div class="card-body">
                                <h5 class="card-title">Ribeye Steak</h5>
                                <p class="card-text">A tender and flavorful cut of beef, ribeye steak is known for its marbling and juicy texture when grilled or pan-seared.</p>
                                <a href="book.html" class="btn btn-danger">700Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/ramen.jpg" class="card-img-top" alt="Ramen">
                            <div class="card-body">
                                <h5 class="card-title">Ramen</h5>
                                <p class="card-text">A Japanese noodle soup dish consisting of Chinese-style wheat noodles served in a meat or fish-based broth, often flavored with soy sauce or miso.</p>
                                <a href="book.html" class="btn btn-danger">320Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/salad.jpg" class="card-img-top" alt="Salad">
                            <div class="card-body">
                                <h5 class="card-title">Caesar Salad</h5>
                                <p class="card-text">A classic salad made with romaine lettuce, croutons, Parmesan cheese, and a dressing typically consisting of olive oil, lemon juice, egg, Worcestershire sauce, garlic, Dijon mustard, anchovies, and black pepper.</p>
                                <a href="book.html" class="btn btn-primary">200Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/sandwich.jpg" class="card-img-top" alt="Sandwich">
                            <div class="card-body">
                                <h5 class="card-title">Club Sandwich</h5>
                                <p class="card-text">A triple-decker sandwich typically made with sliced turkey or chicken, bacon, lettuce, tomato, and mayonnaise.</p>
                                <a href="book.html" class="btn btn-danger">180Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/chocolatecake.jpg" class="card-img-top" alt="Chocolate Cake">
                            <div class="card-body">
                                <h5 class="card-title">Chocolate Cake</h5>
                                <p class="card-text">A rich, moist cake made with cocoa and topped with chocolate frosting or ganache.</p>
                                <a href="book.html" class="btn btn-success">300Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/sushi.jpg" class="card-img-top" alt="Sushi">
                            <div class="card-body">
                                <h5 class="card-title">Sushi</h5>
                                <p class="card-text">Sushi is a Japanese dish consisting of vinegared rice combined with various ingredients such as seafood, vegetables, and occasionally tropical fruits.</p>
                                <a href="book.html" class="btn btn-danger">300Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/icecream.jpg" class="card-img-top" alt="Ice Cream">
                            <div class="card-body">
                                <h5 class="card-title">Vanilla Ice Cream</h5>
                                <p class="card-text">A classic frozen dessert made with cream, sugar, and vanilla flavoring.</p>
                                <a href="book.html" class="btn btn-success">150Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/biryani.jpg" class="card-img-top" alt="Biryani">
                            <div class="card-body">
                                <h5 class="card-title">Chicken Biryani</h5>
                                <p class="card-text">A flavorful rice dish made with basmati rice, chicken, and a blend of aromatic spices.</p>
                                <a href="book.html" class="btn btn-danger">400Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/dosa.jpg" class="card-img-top" alt="Dosa">
                            <div class="card-body">
                                <h5 class="card-title">Masala Dosa</h5>
                                <p class="card-text">A popular South Indian dish consisting of a thin, crispy crepe made from fermented rice and lentil batter, filled with spiced mashed potatoes.</p>
                                <a href="book.html" class="btn btn-success">250Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/soup.jpg" class="card-img-top" alt="Soup">
                            <div class="card-body">
                                <h5 class="card-title">Tomato Soup</h5>
                                <p class="card-text">A comforting soup made with tomatoes, broth, and various herbs and spices.</p>
                                <a href="book.html" class="btn btn-success">180Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/tiramisu.jpg" class="card-img-top" alt="Tiramisu">
                            <div class="card-body">
                                <h5 class="card-title">Tiramisu</h5>
                                <p class="card-text">An Italian dessert made of layers of coffee-soaked ladyfingers, mascarpone cheese, and cocoa powder.</p>
                                <a href="book.html" class="btn btn-primary">350Rs</a>
                            </div>
                        </div>
                        <div class="card mx-3 mb-3" style="width: 18rem;">
                            <img src="images/salmon.jpg" class="card-img-top" alt="Salmon">
                            <div class="card-body">
                                <h5 class="card-title">Grilled Salmon</h5>
                                <p class="card-text">Fresh salmon fillet grilled to perfection, served with a side of vegetables or salad.</p>
                                <a href="book.html" class="btn btn-danger">600Rs</a>
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
### about.html:
```
<!DOCTYPE html>
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
                background-image: url('images/about.jpg');
                background-repeat: no-repeat;
                background-attachment: fixed; 
                background-position: center;
                background-size: cover;
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
                margin-bottom: -10px;
            }
            h2 {
               text-align: left;
               margin-top: 10px;
               padding-top: 10px;
               padding-left: 20px;
               font-family: "Poppins", sans-serif;
               font-weight: 600;
               font-style: normal;
               padding-bottom: 30px;
               color: yellow;
               background-image: linear-gradient(to right, rgba(0, 0, 0, 0.8), rgba(218, 27, 96, 0.0));
               background-clip: padding-box;
               -webkit-background-clip: padding-box;
               border-radius: 10px;
               padding: 10px 20px;
    }
    
            .Margin {
                margin-left: 40px;
            }
            .card-body {
                background-color: #e5e5e5;
            }
            .navbar {
                margin-top: 0;
            }
            .Boxed{
                background-image: linear-gradient(to right, rgba(255, 255, 255, 0.7), rgb(255, 255, 255, 0.7));
                border-radius: 10px;
                padding: 10px 20px;
                font-size: 1.5em;
            }
            h3 {
               text-align: left;
               margin-top: 10px;
               padding-top: 10px;
               padding-left: 20px;
               font-family: "Poppins", sans-serif;
               font-weight: 600;
               font-style: normal;
               padding-bottom: 30px;
               color: rgb(255, 255, 255);
               background-image: linear-gradient(to right, rgba(0, 0, 0, 0.8), rgba(255, 255, 255, 0));
               background-clip: padding-box;
               -webkit-background-clip: padding-box;
               border-radius: 10px;
               padding: 10px 20px;
            }
           
        </style>
    </head>
    <body>
        <div>
            <div>
                <h1>The Enchanted Gastronome</h1>
            </div>
            <div>
                <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
                    <div class="container-fluid">
                      <a class="navbar-brand d-flex align-items-center" href="about.html" style="color: #ffffff;  font-size: 2em;">About</a>
                      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                        <div class="navbar-nav">
                          <a class="nav-link" href="index.html" style="color: #ffffff;">Home</a>
                          <a class="nav-link" href="contact.html" style="color: #ffffff;">Contact</a>
                          <a class="nav-link" href="book.html" style="color: #ffffff;">Book a seat</a>
                        </div>
                      </div>
                    </div>
                  </nav> 
            </div>

    <main class="container mt-4">
        <header>
            <h2>About Us</h2>
            <p class = "Boxed">The Enchanted Gastronome is a whimsical dining experience where each dish tells a story inspired by folklore and fairy tales from around the world. The restaurant is designed to resemble a magical forest grove, with softly glowing lanterns, twisted tree branches as dividers between tables, and tables adorned with miniature gardens and mystical artifacts.</p>
        </header>

        <section>
            <h3>Ambiance</h3>
            <p class = "Boxed">Soft, ethereal music fills the air, changing subtly with each course to reflect different mythical realms. Servers are dressed in elegant attire reminiscent of woodland creatures, adding to the magical atmosphere.</p>
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
                background-image: url('images/about.jpg');
                background-repeat: no-repeat;
                background-attachment: fixed; 
                background-position: center;
                background-size: cover;
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
                margin-bottom: -10px;
            }
            h2 {
               text-align: left;
               margin-top: 10px;
               padding-top: 10px;
               padding-left: 20px;
               font-family: "Poppins", sans-serif;
               font-weight: 600;
               font-style: normal;
               padding-bottom: 30px;
               color: yellow;
               background-image: linear-gradient(to right, rgba(0, 0, 0, 0.8), rgba(218, 27, 96, 0.0));
               background-clip: padding-box;
               -webkit-background-clip: padding-box;
               border-radius: 10px;
               padding: 10px 20px;
    }
    
            .Margin {
                margin-left: 40px;
            }
            .card-body {
                background-color: #e5e5e5;
            }
            .navbar {
                margin-top: 0;
            }
            .Boxed{
                background-image: linear-gradient(to right, rgba(255, 255, 255, 0.7), rgb(255, 255, 255, 0.7));
                border-radius: 10px;
                padding: 10px 20px;
                font-size: 1.2em;
            }
            h3 {
               text-align: left;
               margin-top: 10px;
               padding-top: 10px;
               padding-left: 20px;
               font-family: "Poppins", sans-serif;
               font-weight: 600;
               font-style: normal;
               padding-bottom: 30px;
               color: rgb(255, 255, 255);
               background-image: linear-gradient(to right, rgba(0, 0, 0, 0.8), rgba(255, 255, 255, 0));
               background-clip: padding-box;
               -webkit-background-clip: padding-box;
               border-radius: 10px;
               padding: 10px 20px;
            }
           
        </style>
    </head>
    <body>
        <div>
            <div>
                <h1>The Enchanted Gastronome</h1>
            </div>
            <div>
                <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
                    <div class="container-fluid">
                      <a class="navbar-brand d-flex align-items-center" href="contact.html" style="color: #ffffff;  font-size: 2em;">Contact</a>
                      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                        <div class="navbar-nav">
                          <a class="nav-link" href="index.html" style="color: #ffffff;">Home</a>
                          <a class="nav-link" href="about.html" style="color: #ffffff;">About</a>
                          <a class="nav-link" href="book.html" style="color: #ffffff;">Book a seat</a>
                        </div>
                      </div>
                    </div>
                  </nav> 
            </div>

    <main class="container mt-4">
        <header>
            <h2>Contact Us</h2>
            <p class = "Boxed">Get in touch with us for reservations, inquiries, or feedback.</p>
        </header>

        <section>
            <h3>Address</h3>
            <p class = "Boxed">123 Restaurant Street, Cityville, Country</p>
        </section>

        <section>
            <h3>Phone</h3>
            <p class = "Boxed">+123 456 7890</p>
        </section>

        <section>
            <h3>Email</h3>
            <p class = "Boxed">theenchantedgastronome@gmail.com</p>
        </section>
    </main>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
```
### book.html:
```
<!DOCTYPE html>
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
                background-image: url('images/about.jpg');
                background-repeat: no-repeat;
                background-attachment: fixed; 
                background-position: center;
                background-size: cover;
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
                margin-bottom: -10px;
            }
            h2 {
               text-align: left;
               margin-top: 10px;
               padding-top: 10px;
               padding-left: 20px;
               font-family: "Poppins", sans-serif;
               font-weight: 600;
               font-style: normal;
               padding-bottom: 30px;
               color: yellow;
               background-image: linear-gradient(to right, rgba(0, 0, 0, 0.8), rgba(218, 27, 96, 0.0));
               background-clip: padding-box;
               -webkit-background-clip: padding-box;
               border-radius: 10px;
               padding: 10px 20px;
    }
    
            .Margin {
                margin-left: 40px;
            }
            .card-body {
                background-color: #e5e5e5;
            }
            .navbar {
                margin-top: 0;
            }
            .Boxed{
                background-image: linear-gradient(to right, rgba(255, 255, 255, 0.7), rgb(255, 255, 255, 0.7));
                border-radius: 10px;
                padding: 10px 20px;
                font-size: 1.5em;
            }
            h3 {
               text-align: left;
               margin-top: 10px;
               padding-top: 10px;
               padding-left: 20px;
               font-family: "Poppins", sans-serif;
               font-weight: 600;
               font-style: normal;
               padding-bottom: 30px;
               color: rgb(255, 255, 255);
               background-image: linear-gradient(to right, rgba(0, 0, 0, 0.8), rgba(255, 255, 255, 0));
               background-clip: padding-box;
               -webkit-background-clip: padding-box;
               border-radius: 10px;
               padding: 10px 20px;
            }
           
        </style>
    </head>
    <body>
        <div>
            <div>
                <h1>The Enchanted Gastronome</h1>
            </div>
            <div>
                <nav class="navbar navbar-expand-lg" style="background-color: #6f2cf5;">
                    <div class="container-fluid">
                      <a class="navbar-brand d-flex align-items-center" href="book.html" style="color: #ffffff;  font-size: 2em;">Book a seat</a>
                      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                        <div class="navbar-nav">
                          <a class="nav-link" href="index.html" style="color: #ffffff;">Home</a>
                          <a class="nav-link" href="about.html" style="color: #ffffff;">About</a>
                          <a class="nav-link" href="contact.html" style="color: #ffffff;">Contact</a>
                        </div>
                      </div>
                    </div>
                  </nav> 
            </div>

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
So, this is it for now, I can't think of any mopre obvious improvements, we were suggested to add animations to the website, but when I tried looking it up, I was unable to find a good lead. I doubt we have enough time to implement it anyway. So now the first task on the agenda remains to put the site up on github pages, I'll write back after doing that.<br>



