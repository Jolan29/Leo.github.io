# Leo.github.io
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Leo Cortez - Graphic Designer</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">Leo Cortez</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#portfolio">Portfolio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="hero" class="jumbotron text-center">
    <h1 class="display-4">Leo Cortez</h1>
    <p class="lead">Graphic Designer</p>
    <a href="#portfolio" class="btn btn-primary btn-lg">View Portfolio</a>
  </section>

  <!-- About Section -->
  <section id="about" class="container">
    <h2>About Me</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed scelerisque luctus urna, eu tristique
      tortor iaculis ut. Sed sodales lacus vel vestibulum cursus. Mauris pharetra dolor ac tempor cursus.
      Nullam eu ipsum purus.</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="container">
    <h2>Portfolio</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="project1.jpg" class="card-img-top" alt="Project 1">
          <div class="card-body">
            <h5 class="card-title">Project 1</h5>
            <p class="card-text">Description of Project 1</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="project2.jpg" class="card-img-top" alt="Project 2">
          <div class="card-body">
            <h5 class="card-title">Project 2</h5>
            <p class="card-text">Description of Project 2</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="project3.jpg" class="card-img-top" alt="Project 3">
<div class="card-body">
            <h5 class="card-title">Project 3</h5>
            <p class="card-text">Description of Project 3</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="container">
    <h2>Contact Me</h2>
    <form>
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" class="form-control" id="name" required>
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" class="form-control" id="email" required>
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <textarea class="form-control" id="message" rows="5" required></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="container-fluid text-center bg-dark text-white">
    <p>&copy; 2023 Leo Cortez. All rights reserved.</p>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
</body>

</html>
/* style.css */

/* Hero Section */
#hero {
  background-color: #f4f4f4;
  padding: 100px 0;
}

/* About Section */
#about {
  padding: 50px 0;
}

/* Portfolio Section */
#portfolio {
  padding: 50px 0;
}

.card {
  margin-bottom: 20px;
}

/* Contact Section */
#contact {
  padding: 50px 0;
}

/* Footer */
footer {
  padding: 20px 0;
}
