# haan_app with html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Hunaifah - Web Development</title>
    <link rel="stylesheet" href="./styles/style.css" />
  </head>

  <body>
    <!-- Header -->
    <header>
      <div class="main-container">
        <div class="nav">
          <div class="logo">
            <a href="#hero"
              ><img
                src="images/logo.png"
                alt="logo_haan_studio"
                class="logo_haan_studio"
            /></a>
          </div>

          <nav>
            <ul>
              <li><a href="#services">Services</a></li>
              <li><a href="#portofolios">Portofolio</a></li>
              <li><a href="#skills">Skills</a></li>
              <li><a href="#contacts">Contact</a></li>
              <li>
                <a href="/resume.pdf" target="_blank">
                  <div class="btn">Resume</div>
                </a>
              </li>
            </ul>
          </nav>

          <div onclick="dropdown()" class="burger">
            <div class="line-1"></div>
            <div class="line-2"></div>
            <div class="line-3"></div>
          </div>

          <ul id="dropdown">
            <li onclick="dropdown_item()"><a href="#services">Services</a></li>
            <li onclick="dropdown_item()">
              <a href="#portofolios">Portofolio</a>
            </li>
            <li onclick="dropdown_item()"><a href="#skills">Skills</a></li>
            <li onclick="dropdown_item()"><a href="#contacts">Contact</a></li>
            <li onclick="dropdown_item()"><a href="/resume.pdf">Resume</a></li>
          </ul>
        </div>
      </div>
    </header>
    <!-- End of Header -->

    <section id="hero">
      <div class="hero-left">
        <h3 class="pre-tittle">Creative Web & Visual Designer</h3>
        <h1 class="hero-name">Hello, <br /><span>I'm Hunaifah</span></h1>
        <a href="#contact">
          <div class="button-contact-me">Contact Me</div>
        </a>
      </div>
      <div class="hero-right">
        <img src="./images/hero.svg" alt="a designer" />
      </div>
    </section>

    <!-- Services -->
    <section id="services">
      <div class="services-main-container">
        <h3 class="pre-tittle">services</h3>
        <h1 class="section-tittle services-tittle">Specialized In</h1>

        <div class="grid-3">
          <!-- Service 1 -->
          <div class="service">
            <div class="service-icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M24 5c-3.923 3.265-5.623 4.716-7.15 4.716-2.44 0-3.681-3.675-4.85-7.716-1.165 4.028-2.41 7.715-4.853 7.715-1.513 0-3.168-1.404-7.147-4.715 3.321 7.018 3 14.292 3 17h18c0-1.718-.478-9.65 3-17zm-16.853 6.715c2.295 0 3.787-1.64 4.853-3.761 1.064 2.122 2.556 3.762 4.85 3.762 1.121 0 2.188-.43 3.126-1.042-.432 1.907-.68 3.72-.82 5.326h-14.322c-.138-1.617-.38-3.423-.808-5.324.927.607 2 1.039 3.121 1.039zm-2.14 8.285c-.003-.593-.016-1.267-.047-2h14.065c-.032.745-.046 1.422-.047 2h-13.971z"
                />
              </svg>
            </div>
            <h4>UI/UX Design</h4>
            <p>
              Turn what you have in mind of a digital product into reality. For
              any platform you consider.
            </p>
          </div>

          <!-- Service 2 -->
          <div class="service">
            <div class="service-icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M11.333 8.701l-7.837 4.262s-1.339 5.254-3.497 8.604l2.419 2.433c3.314-2.133 8.604-3.511 8.604-3.511l4.263-7.837-3.952-3.951zm-1.664 10.091c-1.241.365-3.64 1.131-5.915 2.207l1.806-1.806c.348-.349.8-.569 1.288-.63.647-.081 1.113-.63 1.113-1.263 0-.703-.569-1.275-1.275-1.275-.637 0-1.183.471-1.263 1.113-.06.487-.281.94-.629 1.288l-1.779 1.779c1.072-2.274 1.825-4.652 2.184-5.891l5.778-3.143 1.838 1.837-3.146 5.784zm2.345-12.252s2.148-3.969 3.475-6.54l8.511 8.511c-2.582 1.321-6.556 3.459-6.556 3.459l-5.43-5.43z"
                />
              </svg>
            </div>
            <h4>Brand Design</h4>
            <p>
              Make your business famous with eye-catching visuals to provide a
              defined and personalized brand identity.
            </p>
          </div>
          <!-- Service 3 -->
          <div class="service">
            <div class="service-icon">
              <svg
                width="24"
                height="24"
                xmlns="http://www.w3.org/2000/svg"
                fill-rule="evenodd"
                clip-rule="evenodd"
              >
                <path
                  d="M12 0c6.623 0 12 5.377 12 12s-5.377 12-12 12-12-5.377-12-12 5.377-12 12-12zm-7.363 18.764c1.828 1.989 4.451 3.236 7.363 3.236h.004l-4.618-7.998-2.749 4.762zm16.023-1.764h-9.233l2.749 4.762c2.767-.615 5.104-2.378 6.484-4.762zm-18.201-8c-.298.947-.459 1.955-.459 3 0 1.823.489 3.533 1.343 5.005l2.889-5.003-.001-.002.003-.002 1.731-2.998h-5.506zm18.203-1.997l-4.617 7.997h5.496c.298-.947.459-1.955.459-3 0-1.82-.487-3.526-1.338-4.997zm-6.927 1.997h-3.461l-1.733 3.002 1.731 2.998h3.464l1.731-2.999-1.732-3.001zm2.887 1.001l2.747-4.758c-1.828-1.992-4.452-3.242-7.366-3.243l4.619 8.001zm-6.792-7.764c-2.769.613-5.109 2.377-6.49 4.763h9.24l-2.75-4.763z"
                />
              </svg>
            </div>
            <h4>Photography</h4>
            <p>
              Explain the form and function of your own product, make people
              interested in its characteristics!
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- End services -->

    <!-- Portofolio -->
    <section id="portofolios">
      <div class="portofolios-main-container">
        <h3 class="pre-tittle">MY WORKS</h3>
        <h1 class="section-tittle">Featured Portofolios</h1>
        <div class="grid-3">
          <!-- portofolio 1 -->
          <div class="portofolio">
            <div class="portofolio-icon">
              <img src="images/porto1.png" alt="image_portofolio" />
            </div>
            <div class="portofolio-body">
              <div class="portofolio-title">
                <h4>Study Program Website</h4>
                <a href=""
                  ><img
                    src="images/icon_share.png"
                    alt="icon_share"
                    class="icon_share"
                /></a>
              </div>
              <div class="portofolio-budge">
                <div class="budge">Figma</div>
                <div class="budge">Figjam</div>
              </div>
              <p>
                Turn what you have in mind of a digital product into reality.
                For any platform you consider.
              </p>
            </div>
          </div>
          <!-- portofolio 2 -->
          <div class="portofolio">
            <div class="portofolio-icon">
              <img src="images/porto2.png" alt="image_portofolio" />
            </div>
            <div class="portofolio-body">
              <div class="portofolio-title">
                <h4>Cafe Product Catalogue</h4>
                <a href=""
                  ><img
                    src="images/icon_share.png"
                    alt="icon_share"
                    class="icon_share"
                /></a>
              </div>
              <div class="portofolio-budge">
                <div class="budge">Photography</div>
                <div class="budge">Photoshop</div>
              </div>
              <p>
                Make your business famous with eye-catching visuals to provide a
                defined and personalized brand identity.
              </p>
            </div>
          </div>
          <!-- portofolio 3 -->
          <div class="portofolio">
            <div class="portofolio-icon">
              <img src="images/porto3.png" alt="image_portofolio" />
            </div>
            <div class="portofolio-body">
              <div class="portofolio-title">
                <h4>Logo Name</h4>
                <a href=""
                  ><img
                    src="images/icon_share.png"
                    alt="icon_share"
                    class="icon_share"
                /></a>
              </div>
              <div class="portofolio-budge">
                <div class="budge">Mock up</div>
                <div class="budge">Adobe Illustrator</div>
              </div>
              <p>
                Explain the form and function of your own product, make people
                interested in its characteristics!
              </p>
            </div>
          </div>
          <!-- portofolio 4 -->
          <div class="portofolio">
            <div class="portofolio-icon">
              <img src="images/porto4.png" alt="image_portofolio" />
            </div>
            <div class="portofolio-body">
              <div class="portofolio-title">
                <h4>Identity Crisis Website</h4>
                <a href=""
                  ><img
                    src="images/icon_share.png"
                    alt="icon_share"
                    class="icon_share"
                /></a>
              </div>
              <div class="portofolio-budge">
                <div class="budge">Figma</div>
                <div class="budge">Figjam</div>
              </div>
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Praesentium reprehenderit culpa odio officia velit corporis, sit
                rem quisquam obcaecati libero?
              </p>
            </div>
          </div>
          <!-- portofolio 5 -->
          <div class="portofolio">
            <div class="portofolio-icon">
              <img src="images/porto5.png" alt="image_portofolio" />
            </div>
            <div class="portofolio-body">
              <div class="portofolio-title">
                <h4>Product Carousel Posts</h4>
                <a href=""
                  ><img
                    src="images/icon_share.png"
                    alt="icon_share"
                    class="icon_share"
                /></a>
              </div>
              <div class="portofolio-budge">
                <div class="budge">Figma</div>
                <div class="budge">Adobe Illustrator</div>
              </div>
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Praesentium reprehenderit culpa odio officia velit corporis, sit
                rem quisquam obcaecati libero?
              </p>
            </div>
          </div>
          <!-- portofolio 6 -->
          <div class="portofolio">
            <div class="portofolio-icon">
              <img src="images/porto5.png" alt="image_portofolio" />
            </div>
            <div class="portofolio-body">
              <div class="portofolio-title">
                <h4>Storytelling Photography</h4>
                <a href=""
                  ><img
                    src="images/icon_share.png"
                    alt="icon_share"
                    class="icon_share"
                /></a>
              </div>
              <div class="portofolio-budge">
                <div class="budge">Photoshop</div>
                <div class="budge">Lightroom</div>
              </div>
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Praesentium reprehenderit culpa odio officia velit corporis, sit
                rem quisquam obcaecati libero?
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Portofolio -->

    <!-- Skills -->
    <section id="skills">
      <div class="skill">
        <h3 class="pre-tittle">LEARNING PATH</h3>
        <h1 class="section-tittle">Education, Experience & Skill</h1>

        <div class="skill-grid">
          <div class="skill-line">
            <div class="vertical-line vertical-line-1">
              <div class="ball-line"></div>
              <div class="vertical-line-body">
                <p class="vertical-line-title">Universitas ‘Aisyiyah Bandung</p>
                <p class="vertical-line-subtitle">
                  Bachelor's Degree - Visual Communication Design
                </p>
                <p class="vertical-line-title">2021 - Present</p>
              </div>
            </div>
            <div class="vertical-line vertical-line-2">
              <div class="ball-line"></div>
              <div class="vertical-line-body">
                <p class="vertical-line-title">
                  Member of HIMA DKV Unisa Bandung
                </p>
                <p class="vertical-line-subtitle">
                  Communications Media Division, Production Section
                </p>
                <p class="vertical-line-title">2023 - Present</p>
              </div>
            </div>
            <div class="vertical-line vertical-line-3">
              <div class="ball-line"></div>
              <div class="vertical-line-body">
                <p class="vertical-line-title">
                  Internship at Sahabat Bunda Company
                </p>
                <p class="vertical-line-subtitle">Graphic Designer</p>
                <p class="vertical-line-title">June - September 2023</p>
              </div>
            </div>
            <div class="vertical-line vertical-line-4">
              <div class="ball-line"></div>
              <div class="vertical-line-body">
                <p class="vertical-line-title">
                  Celerates Acceleration Program - Studi Independen MBKM
                </p>
                <p class="vertical-line-subtitle">
                  Web Development & UI UX Design
                </p>
                <p class="vertical-line-title">February - June 2024</p>
              </div>
            </div>
          </div>
          <div class="skill-list">
            <p class="skill-list-desc">
              For 3 years, I continued to learn in the field of design and
              experiment with technology, I’m still growing and exploring new
              things, and here you can see a summary of my skills.
            </p>
            <div>
              <ul>
                <li>Figma</li>
                <li>Figjam</li>
                <li>Adobe Illustrator</li>
                <li>Adobe Photoshop</li>
                <li>Lightroom</li>
                <li>Canva</li>
                <li>Capcut</li>
              </ul>
              <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Javascript</li>
                <li>ReactJS</li>
                <li>MySQL</li>
                <li>NodeJs</li>
                <li>ExpressJs</li>
              </ul>
              <ul>
                <li>Layouting</li>
                <li>Typography</li>
                <li>Color Theory</li>
                <li>Basic Editing Photo & Video</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End skills -->

    <!-- Contact -->
    <section id="contacts">
      <div class="contact">
        <div class="contact-grid">
          <div class="contact-message">
            <input type="text" placeholder="Name" class="form-input" />
            <input type="text" placeholder="Email" class="form-input" />
            <textarea
              type="text"
              placeholder="Message"
              class="form-input"
              rows="10"
            ></textarea>
            <button type="submit" class="btn-send">Send Message</button>
          </div>
          <div class="contact-static">
            <div class="contact-flex contact-address">
              <div class="contact-box">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M12 2c3.196 0 6 2.618 6 5.602 0 3.093-2.493 7.132-6 12.661-3.507-5.529-6-9.568-6-12.661 0-2.984 2.804-5.602 6-5.602m0-2c-4.198 0-8 3.403-8 7.602 0 4.198 3.469 9.21 8 16.398 4.531-7.188 8-12.2 8-16.398 0-4.199-3.801-7.602-8-7.602zm0 11c-1.657 0-3-1.343-3-3s1.343-3 3-3 3 1.343 3 3-1.343 3-3 3z"
                  />
                </svg>
              </div>
              <div>
                <p class="contact-static-title">Address</p>
                <p class="contact-static-subtitle">
                  Jl. Rajamantri No.35, Turangga, Lengkong, Kota Bandung
                </p>
              </div>
            </div>
            <div class="contact-flex contact-phone">
              <div class="contact-box">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M18.48 22.926l-1.193.658c-6.979 3.621-19.082-17.494-12.279-21.484l1.145-.637 3.714 6.467-1.139.632c-2.067 1.245 2.76 9.707 4.879 8.545l1.162-.642 3.711 6.461zm-9.808-22.926l-1.68.975 3.714 6.466 1.681-.975-3.715-6.466zm8.613 14.997l-1.68.975 3.714 6.467 1.681-.975-3.715-6.467z"
                  />
                </svg>
              </div>
              <div>
                <p class="contact-static-title">Phone</p>
                <p class="contact-static-subtitle">(+62) 812824012020</p>
              </div>
            </div>
            <div class="contact-flex contact-email">
              <div class="contact-box">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M0 3v18h24v-18h-24zm21.518 2l-9.518 7.713-9.518-7.713h19.036zm-19.518 14v-11.817l10 8.104 10-8.104v11.817h-20z"
                  />
                </svg>
              </div>
              <div>
                <p class="contact-static-title">Email</p>
                <p class="contact-static-subtitle">hunayfa743@gmail.com</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Contact -->

    <!-- Footer -->
    <footer>
      <div class="footer-icon">
        <a href="">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="18"
            height="18"
            viewBox="0 0 24 24"
          >
            <path
              d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"
            />
          </svg>
        </a>
        <a href="">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            viewBox="0 0 24 24"
          >
            <path
              d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5s-2.48-1.119-2.48-2.5c0-1.38 1.11-2.5 2.48-2.5s2.48 1.12 2.48 2.5zm.02 4.5h-5v16h5v-16zm7.982 0h-4.968v16h4.969v-8.399c0-4.67 6.029-5.052 6.029 0v8.399h4.988v-10.131c0-7.88-8.922-7.593-11.018-3.714v-2.155z"
            />
          </svg>
        </a>
        <a href="">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="20"
            height="20"
            viewBox="0 0 24 24"
          >
            <path
              d="M22 7h-7v-2h7v2zm1.726 10c-.442 1.297-2.029 3-5.101 3-3.074 0-5.564-1.729-5.564-5.675 0-3.91 2.325-5.92 5.466-5.92 3.082 0 4.964 1.782 5.375 4.426.078.506.109 1.188.095 2.14h-8.027c.13 3.211 3.483 3.312 4.588 2.029h3.168zm-7.686-4h4.965c-.105-1.547-1.136-2.219-2.477-2.219-1.466 0-2.277.768-2.488 2.219zm-9.574 6.988h-6.466v-14.967h6.953c5.476.081 5.58 5.444 2.72 6.906 3.461 1.26 3.577 8.061-3.207 8.061zm-3.466-8.988h3.584c2.508 0 2.906-3-.312-3h-3.272v3zm3.391 3h-3.391v3.016h3.341c3.055 0 2.868-3.016.05-3.016z"
            />
          </svg>
        </a>
      </div>
      <p>&copy; <span id="year"></span> - Made by Haan Studio</p>
    </footer>
    <!-- End Footer -->

    <script>
      date = new Date();
      year = date.getFullYear();
      document.getElementById("year").innerHTML = year;

      var dropdownBool = false;
      function dropdown() {
        dropdownBool = !dropdownBool;
        if (dropdownBool === false) {
          document.getElementById("dropdown").style.display = "none";
        } else {
          document.getElementById("dropdown").style.display = "flex";
        }
      }

      function dropdown_item() {
        dropdownBool = !dropdownBool;
        document.getElementById("dropdown").style.display = "none";
      }
    </script>
  </body>
</html>

