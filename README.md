<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
      crossorigin="anonymous"
    />

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">

    <!-- --- font --- -->

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,400;0,700;0,800;1,100;1,200&family=Poppins:ital,wght@0,100;0,300;0,400;0,700;1,700&display=swap"
      rel="stylesheet"
    />

    <!-- CSS VANILA -->

    <link rel="stylesheet" href="style.css" />

    <title>Mukhamad Muhdzor Al Maksum</title>
  </head>

  <body id="atas">
    <nav
      class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top shadow-lg py-4"
    >
    <div class="container d-flex justify-content-center">
        <div class="date"></div>
        <a class="navbar-brand mx-auto mt-2" href="#atas">Mukhamad Muhdzor Al Maksum</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
      <div class="time"></div>
    </nav>

    <!-- Hero -->

    <section class="jumbotron text-center">
      <img
        class="img-thumbnail img-fluid"
        src="gambar/profil.jpg"
        alt=""
      /><br />
      <b class="fs-2">Mukhamad Muhdzor Al Maksum</b>
      <p class="lead">Junior Programmer | Undergraduate</p>
    </section>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <path
        fill="aqua"
        fill-opacity="1"
        d="M0,32L102.9,192L205.7,96L308.6,192L411.4,160L514.3,128L617.1,128L720,160L822.9,256L925.7,128L1028.6,64L1131.4,192L1234.3,64L1337.1,256L1440,64L1440,0L1337.1,0L1234.3,0L1131.4,0L1028.6,0L925.7,0L822.9,0L720,0L617.1,0L514.3,0L411.4,0L308.6,0L205.7,0L102.9,0L0,0Z"
      ></path>
    </svg>

    <!-- About -->
    <section class="about">
      <div class="container">
        <div class="row text-center">
          <h3>About Me</h3>
        </div>

        <div class="row text-center" id="about_body">
          <div class="col-sm-6">
            <h5>Pendidikan</h5>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit.
              Praesentium modi voluptas recusandae placeat sed consectetur. Cum,
              illum incidunt optio corporis inventore sapiente nulla voluptas
              facere eaque ad amet necessitatibus nam velit deleniti a maiores
              asperiores aut doloribus et blanditiis obcaecati perferendis
              laborum dolore. Aliquam voluptates debitis dicta nobis rerum
              dignissimos.
            </p>
          </div>

          <div class="col-sm-6">
            <h5>Skill</h5>
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae,
              porro quidem temporibus animi accusamus dolore debitis distinctio
              fuga mollitia repudiandae itaque eaque saepe recusandae, incidunt
              asperiores. Voluptates beatae cumque pariatur dolorum corporis
              sunt eos fugit dignissimos unde porro sit iste sequi, magnam esse
              debitis laboriosam quas neque perferendis atque dicta!
            </p>
          </div>
        </div>
      </div>
    </section>

    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <path
        fill="#fff"
        fill-opacity="1"
        d="M0,32L102.9,192L205.7,96L308.6,192L411.4,160L514.3,128L617.1,128L720,160L822.9,256L925.7,128L1028.6,64L1131.4,192L1234.3,64L1337.1,256L1440,64L1440,0L1337.1,0L1234.3,0L1131.4,0L1028.6,0L925.7,0L822.9,0L720,0L617.1,0L514.3,0L411.4,0L308.6,0L205.7,0L102.9,0L0,0Z"
      ></path>
    </svg>

    <!-- Galeri -->

    <section class="gallery">
      <div class="container mb-5">
        <div class="row text-center mb-4">
          <b class="fs-2">My Project</b>
        </div>

        <div class="row text-center" id="gallery_body">
          <div class="col-sm-4">
            <img
              id="projek1"
              src="gambar/landing.png"
              class="card-img-top img-fluid"
              alt="Tabung Creative Digital"
            />
          </div>

          <div class="col-sm-4 d-flex justify-content-center">
            <img
              id="projek2"
              src="gambar/mobile.png"
              class="card-img-top img-fluid"
              alt="Tabung Creative Digital"
            />
          </div>

          <div class="col-sm-4 d-flex justify-content-center">
            <img
              id="projek3"
              src="gambar/laduni.png"
              class="card-img-top img-fluid"
              alt="Tabung Creative Digital"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Kami -->

    <section class="kontak">
      <div class="container">
        <div class="row">
          <form class="col-sm-6 mx-auto mb-5">
            <div class="mb-3">
              <label for="name" class="form-label">Name</label>
              <input
                type="text"
                class="form-control"
                id="name"
                placeholder="Enter Your Name"
              />
            </div>

            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input
                type="email"
                class="form-control"
                id="email"
                aria-describedby="emailHelp"
                placeholder="Enter Your E-mail"
              />
            </div>

            <div class="mb-3">
              <label for="massage" class="form-label">Massage</label>
              <textarea
                type="text"
                class="form-control"
                id="massage"
                placeholder="Your Massage"
              /></textarea>
            </div>

            <button type="submit" class="btn btn-primary">Submit</button>
          </form>
        </div>
      </div>
    </section>

    <section>
      <footer>
        
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
            <path
              fill="#fff"
              fill-opacity="1"
              d="M0,32L102.9,192L205.7,96L308.6,192L411.4,160L514.3,128L617.1,128L720,160L822.9,256L925.7,128L1028.6,64L1131.4,192L1234.3,64L1337.1,256L1440,64L1440,0L1337.1,0L1234.3,0L1131.4,0L1028.6,0L925.7,0L822.9,0L720,0L617.1,0L514.3,0L411.4,0L308.6,0L205.7,0L102.9,0L0,0Z"
            ></path>
          </svg>

          <div class="container">
            <div class="col-sm-12 d-flex justify-content-center fs-5">
               
              <ul class="list-unstyled mt-5">
                <li><b>Media Social</b></li><br>
                <li><a href="https://www.instagram.com/al_maksum17/" target="_blank"><i class="bi bi-instagram"> al_maksum17</i></a></li>
                <li><a href="https://web.facebook.com/id17zero/" target="_blank"><i class="bi bi-facebook"> Mukhamad Muhdzor Al Maksum</i></a></li>
                <li><a href="https://github.com/almaksum" target="_blank"><i class="bi bi-github"> almaksum</i></a></li>
              </ul>
            </div>
          </div>
        
        <div class="text-center">
          &copy; Power By <i class="bi bi-heart-fill" id="heart"></i> Mukhamad Muhdzor Al Maksum
        </div>
      </footer>
    </section>

    <script src="script.js"></script>

  </body>
</html>
repository mencoba github
