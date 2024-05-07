# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmaceutical Company</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Pharmaceutical Company</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Products
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Medicines</a>
              <a class="dropdown-item" href="#">Vaccines</a>
              <a class="dropdown-item" href="#">Supplements</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Content Sections -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-6">
        <h2>Welcome to Our Pharmaceutical Company</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod velit sit amet justo sodales, ut interdum nunc posuere. Donec et leo a justo vulputate vehicula.</p>
      </div>
      <div class="col-md-6">
        <img src="pharma.png" alt="Pharmaceutical Company" height="300" width="'400">
      </div>
    </div>
    <div class="row mt-5">
      <div class="col-md-4">
        <h3>Our Products</h3>
        <p>Explore our range of high-quality pharmaceutical products.Our pharmacy offers a diverse selection of medicines to address various health concerns.</p>
        <a href="#" class="btn btn-primary">View Products</a>
      </div>
      <div class="col-md-4">
        <h3>Responsibility</h3>
        <p>Dispensing medications accurately and safely, including interpreting prescriptions and providing dosage instructions.
         </p>
        <a href="#" class="btn btn-primary">Read more</a>
      </div>
      <div class="col-md-4">
        <h3>Contact Us</h3>
        <p>Get in touch with us for any inquiries or feedback.</p>
        <a href="#" class="btn btn-primary">Contact Us</a>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-light mt-5 py-3">
    <div class="container text-center">
      <p>&copy; 2024 Pharmaceutical Company. BY VIJAY R(212223240178).</p>
    </div>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    .rounded-img {
      border-radius: 50%;
      overflow: hidden;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Pharmacy</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Product Content -->
  <div class="container mt-5">
    <h2 class="text-center mb-4">Our Products</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="dettol.png" class="card-img-top rounded-img" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Product 1</h5>
            <p class="card-text">Description of Product 1.</p>
            <a href="#" class="btn btn-primary btn-block">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="zeelab.png" class="card-img-top rounded-img" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Product 2</h5>
            <p class="card-text">Description of Product 2.</p>
            <a href="#" class="btn btn-primary btn-block">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="lotions.png" class="card-img-top rounded-img" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Product 3</h5>
            <p class="card-text">Description of Product 3.</p>
            <a href="#" class="btn btn-primary btn-block">Buy Now</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap JS dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Pharmacy</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- About Content -->
  <div class="container mt-5">
    <h2>About Us</h2>
    <p>Welcome to Our Pharmacy! We are dedicated to providing exceptional pharmacy services and healthcare solutions to our community.</p>
    <p>At Our Pharmacy, we prioritize the safety and well-being of our customers. Our team of experienced pharmacists and staff are here to support you with personalized care, expert advice, and compassionate service.</p>
    <p>We are proud to be an active member of our community, participating in health initiatives, educational programs, and outreach activities to promote public health and wellness.</p>
    <p>Thank you for choosing Our Pharmacy for your healthcare needs. We look forward to serving you!</p>
  </div>

  <!-- Bootstrap JS dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Pharmacy</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Contact Content -->
  <div class="container mt-5">
    <h2>Contact Us</h2>
    <p>If you have any inquiries or feedback, please feel free to contact us using the form below:</p>
    <p>vijay2108@gmail.com</p>      
    <form>
      <div class="form-group">
        <label for="inputName">Name</label>
        <input type="text" class="form-control" id="inputName" placeholder="Enter your name">
      </div>
      <div class="form-group">
        <label for="inputPhone">Phone Number</label>
        <input type="tel" class="form-control" id="inputPhone" placeholder="Enter your phone number">
      </div>
      <div class="form-group">
        <label for="inputEmail">Email address</label>
        <input type="email" class="form-control" id="inputEmail" aria-describedby="emailHelp" placeholder="Enter your email">
      </div>
      <div class="form-group">
        <label for="inputMessage">Message</label>
        <textarea class="form-control" id="inputMessage" rows="5" placeholder="Enter your message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>

  <!-- Bootstrap JS dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
## OUTPUT:
![pic1](https://github.com/vijayr21/Pharma/assets/149347607/18f5b32d-d44b-4bd4-951e-3d34e264503a)
![pic2](https://github.com/vijayr21/Pharma/assets/149347607/45d0b1e0-6812-443e-9cc1-01894657e5f2)
![pic3](https://github.com/vijayr21/Pharma/assets/149347607/ca1b103d-6ca2-4765-ab9b-6b174db9de97)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
