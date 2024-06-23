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
[mario.jpg](data:image/jpeg;base64,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)<br>

[pizza.jpg](data:image/jpeg;base64,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)
