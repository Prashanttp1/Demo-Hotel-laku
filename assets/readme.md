For navbar: b5-navbar
b5-table
b5-form
b5-card
b5-btn (link)
b5-accordian
b5-carcusel
so on
.......................................
color:
text-color_name
e.g. text-primary

background color:
bg-colourName

e.g.
bg-sucess

Box Model
padding:
p-5             (padding: 48px)
pt-5             
ps-5(padding-left: 48px)
pe-5(padding_right: 48px)
pb-5(padding_bottom: 48px)


margin
m-5
mt-5
mb-5
ms-5
me-5

text-center

Width:
w-100
w-75
w-50
w-25


Shadow:
shadow
shadow

border
border border-5 border-danger

border radius 
rounded
rounded rounded-5

breakpoint:
extra small device:480px
sm        mobile 600px
md        tablet 760px
lg        laptop 992px
xl        Desktop 1200px
xxl       Large screen devices>=1400px

reponsive
row
column=12





<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Blue Horizon Hotel</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background: url('https://images.unsplash.com/photo-1576671081837-94c59c62b569') no-repeat center center/cover;
      height: 90vh;
      color: rgb(247, 10, 204);
      text-shadow: 1px 1px 4px #0d67e4;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }
  </style>
</head>
<body>
  <img src="..." class="img-fluid" alt="...">

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Blue Horizon Hotel</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navMenu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#rooms">Rooms</a></li>
        <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">About us</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section class="hero text-center">
  <h1 class="display-3">Welcome to Blue Horizon</h1>
  <p class="lead">Your perfect getaway starts here</p>
  <a href="#rooms" class="btn btn-primary btn-lg">Explore Rooms</a>
</section>

<!-- About -->
<section class="py-5 text-center bg-light">
  <div class="container">
    <h2>About Us</h2>
    <p class="lead">Blue Horizon Hotel is a luxury retreat nestled in the hills. Offering exceptional hospitality, world-class facilities, and breathtaking views, we ensure your stay is unforgettable.</p>
  </div>
</section>

<!-- Rooms -->
<section id="rooms" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Our Rooms</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card shadow">
          <img src="https://source.unsplash.com/300x200/?hotel,room" class="card-img-top" alt="Deluxe Room">
          <div class="card-body">
            <h5 class="card-title">Deluxe Room</h5>
            <p class="card-text">Spacious room with king bed, balcony, and city view.</p>
            <p><strong>$120/night</strong></p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow">
          <img src="https://source.unsplash.com/300x200/?luxury,room" class="card-img-top" alt="Executive Suite">
          <div class="card-body">
            <h5 class="card-title">Executive Suite</h5>
            <p class="card-text">Luxurious suite with separate living area and jacuzzi.</p>
            <p><strong>$200/night</strong></p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow">
          <img src="https://source.unsplash.com/300x200/?resort,bed" class="card-img-top" alt="Standard Room">
          <div class="card-body">
            <h5 class="card-title">Standard Room</h5>
            <p class="card-text">Comfortable room with essential amenities for a great stay.</p>
            <p><strong>$80/night</strong></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Services -->
<section id="services" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-4">Our Services</h2>
    <div class="row text-center">
      <div class="col-md-4">
        <h5>24/7 Room Service</h5>
        <p>We offer round-the-clock assistance for all your needs.</p>
      </div>
      <div class="col-md-4">
        <h5>Free Wi-Fi</h5>
        <p>Enjoy seamless internet access throughout your stay.</p>
      </div>
      <div class="col-md-4">
        <h5>Spa & Wellness</h5>
        <p>Relax and rejuvenate with our premium spa treatments.</p>
      </div>
    </div>
  </div>
</section>

<!-- Contact -->
<section id="contact" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Contact Us</h2>
    <div class="row">
      <div class="col-md-6">
        <h5>Location</h5>
        <p>Blue Horizon Hotel, Lakeside, Pokhara, Nepal</p>
        <p><strong>Phone:</strong> +977-9800000000</p>
        <p><strong>Email:</strong> info@bluehorizon.com</p>
      </div>
      <div class="col-md-6">
        <form>
          <div class="mb-3">
            <label class="form-label">Your Name</label>
            <input type="text" class="form-control" placeholder="Full Name">
          </div>
          <div class="mb-3">
            <label class="form-label">Email address</label>
            <input type="email" class="form-control" placeholder="name@example.com">
          </div>
          <div class="mb-3">
            <label class="form-label">Message</label>
            <textarea class="form-control" rows="3" placeholder="Write your message..."></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- About Us Content -->
<section class="py-5">
  <div class="container">
    <h2 class="mb-4 text-center">About Blue Horizon Hotel</h2>
    <p class="lead text-center mb-5">Founded in 2010, Blue Horizon Hotel has been a beacon of hospitality and comfort in the heart of Pokhara.</p>

    <div class="row">
      <div class="col-md-6">
        <h4>Our Story</h4>
        <p>
          Nestled in the tranquil landscapes of Lakeside, Pokhara, Blue Horizon Hotel began with a mission to offer travelers a serene, home-like stay combined with luxury amenities. Our dedication to service and our love for nature shine through in every guest experience we deliver.
        </p>
        <p>
          Over the years, we have expanded our services and upgraded our facilities to meet global standards, while maintaining the warmth of Nepali hospitality.
        </p>
      </div>
      <div class="col-md-6">
        <img src="https://images.unsplash.com/photo-1542314831-068cd1dbfeeb" class="img-fluid rounded shadow" alt="Hotel Exterior">
      </div>
    </div>

    <hr class="my-5">

    <div class="row">
      <div class="col-md-4 text-center">
        <h5>🌿 Eco-Friendly</h5>
        <p>We use sustainable practices like solar energy and plastic-free amenities.</p>
      </div>
      <div class="col-md-4 text-center">
        <h5>👨‍👩‍👧‍👦 Family-Friendly</h5>
        <p>Spacious family rooms, kids' play area, and a friendly staff await you.</p>
      </div>
      <div class="col-md-4 text-center">
        <h5>💼 Business Ready</h5>
        <p>Conference rooms, high-speed Wi-Fi, and 24/7 business support available.</p>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white text-center p-3">
  <p>&copy; 2025 Blue Horizon Hotel. All rights reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>

<!-- Footer -->
<footer class="bg-dark text-white text-center p-3">
  <p>&copy; 2025 Blue Horizon Hotel. All rights reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>