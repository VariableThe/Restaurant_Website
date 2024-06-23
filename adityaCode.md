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
