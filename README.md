<link href="https://fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet" type="text/css">
    <link href="https://fonts.googleapis.com/css?family=Lato:400,700,400italic,700italic" rel="stylesheet" type="text/css">
<link href="style.css" rel="stylesheet" type="text/css">

</head>
<body id="page-top" class="index">
    <!-- Navigation -->
    <nav class="navbar navbar-default navbar-fixed-top">
        <div class="container">
            <!-- Brand and toggle get grouped for better mobile display -->
            <div class="navbar-header page-scroll">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#page-top"> <\NY> </a>
            </div>

            <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav navbar-right">
                    <li class="hidden">
                        <a href="#page-top"></a>
                    </li>
                   <li class="page-scroll">
                        <a href="#about">About</a>
                    </li>
                  
                    <li class="page-scroll">
                        <a href="#portfolio">Portfolio</a>
                    </li>
                    
                    <li class="page-scroll">
                        <a href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
            <!-- /.navbar-collapse -->
        </div>
        <!-- /.container-fluid -->
    </nav>

    <!-- Header -->
    <header>
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="intro-text">
                        <span class="name">Nyombi Ronald</span>
                        <hr class="star-light">
                      <span class="skills">Fullstack Web Developer</span>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Portfolio Grid Section -->
    <section id="portfolio">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2>Portfolio</h2>
                    <hr class="star-primary">
                </div>
            </div>
            <div class="row">
              <!-- Portifolio section -->
                <div class="col-sm-4 portfolio-item">
                  <!--portifolio 1-->
                    <a href="#portfolioModal1" class="portfolio-link" >
                        <div class="caption">
                            <div class="caption-content">
                                <i class="fa fa-code fa-3x"></i>
                            </div>
                        </div>
                        <img src="https://www.smashingmagazine.com/images/portfolio-design/nine.gif" class="img-responsive" alt="#">
                    </a>
                </div>
              <!--Portifolio section -->
                <div class="col-sm-4 portfolio-item">
                  <!-- Portifolio 2 -->
                    <a href="#portfolioModal2" class="portfolio-link" data-toggle="modal">
                        <div class="caption">
                            <div class="caption-content">
                                <i class="fa fa-code fa-3x"></i>
                            </div>
                        </div>
                        <img src="http://www.printmag.com/wp-content/uploads/Angstead-Portfolio-Site.png" class="img-responsive" alt="#">
                    </a>
                </div>
                <div class="col-sm-4 portfolio-item">
                  <!--Portifolio 4 -->
                    <a href="#portfolioModal3" class="portfolio-link" data-toggle="modal">
                        <div class="caption">
                            <div class="caption-content">
                                <i class="fa fa-code fa-3x"></i>
                            </div>
                        </div>
                        <img src="https://d3ui957tjb5bqd.cloudfront.net/uploads/2015/07/50PortfolioSites4.jpg" class="img-responsive" alt="#">
                    </a>
                </div>
                
            
            </div>
        </div>
    </section>
  <!--End of portifolio section -->

    <!-- About Section -->
    <section class="success" id="about">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2>About</h2>
                    <hr class="star-light">
                </div>
            </div>
            <div class="row">
                <div class="col-lg-4 col-lg-offset-2">
                    <p>I am an experienced web developer with a passion for learning and writing clean code. I take pride in the work that I deliver and always strive to adhere to best practices.
                      I am happiest building software that delivers value quickly, using modern techniques and principles, responding to change I enjoy working closely with stakeholders to get fast feedback.
                     </p>
                </div>
                <div class="col-lg-4">
                    <p>From all the skills I have learnt I would have to say the area I enjoy the most is php. Keeping ahead with the constantly evolving plugins, libraries and frameworks make it an exciting challenge. The most recent skill I have been learning has been test driven development and I hope to develop these skills further in my new position.</p>
                      
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2>Contact Me</h2>
                    <hr class="star-primary">
                </div>
            </div>
            <div class="row">
                <div class="col-lg-8 col-lg-offset-2">
                    <!-- To configure the contact form email address, go to mail/contact_me.php and update the email address in the PHP file on line 19. -->
                    <!-- The form should work on most web servers, but if the form is not working you may need to configure your web server differently. -->
                    <form name="sentMessage" id="contactForm" novalidate>
                        <div class="row control-group">
                            <div class="form-group col-xs-12 floating-label-form-group controls">
                                <label>Name</label>
                                <input type="text" class="form-control" placeholder="Name" id="name" required data-validation-required-message="Please enter your name.">
                                <p class="help-block text-danger"></p>
                            </div>
                        </div>
                        <div class="row control-group">
                            <div class="form-group col-xs-12 floating-label-form-group controls">
                                <label>Email Address</label>
                                <input type="email" class="form-control" placeholder="Email Address" id="email" required data-validation-required-message="Please enter your email address.">
                                <p class="help-block text-danger"></p>
                            </div>
                        </div>
                        <div class="row control-group">
                            <div class="form-group col-xs-12 floating-label-form-group controls">
                                <label>Phone Number</label>
                                <input type="tel" class="form-control" placeholder="Phone Number" id="phone" required data-validation-required-message="Please enter your phone number.">
                                <p class="help-block text-danger"></p>
                            </div>
                        </div>
                        <div class="row control-group">
                            <div class="form-group col-xs-12 floating-label-form-group controls">
                                <label>Message</label>
                                <textarea rows="5" class="form-control" placeholder="Message" id="message" required data-validation-required-message="Please enter a message."></textarea>
                                <p class="help-block text-danger"></p>
                            </div>
                        </div>
                        <br>
                        <div id="success"></div>
                        <div class="row">
                            <div class="form-group col-xs-12">
                                <button type="submit" class="btn btn-success btn-lg">Send</button>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center">
        <div class="footer-above">
            <div class="container">
                <div class="row">
                    <div class="footer-col col-md-4">
                        <h3>My Location</h3>
                        <p>7853 Namuwongo Road<br>Kampala Uganda</p>
                    </div>
                    <div class="footer-col col-md-4">
                        <h3>Connect with Me</h3>
                        <ul class="list-inline">
                            <li>
                                <a href="https://fb.com/little.phild" class="btn-social btn-outline" target="__blank"><i class="fa fa-fw fa-facebook"></i></a>
                            </li>
                            <li>
                                <a href="https://github.com/littlephild" class="btn-social btn-outline" target="__blank"><i class="fa fa-fw fa-github"></i></a>
                            </li>
                            <li>
                                <a href="https://twitter.com/nyombironald" class="btn-social btn-outline" target="__blank"><i class="fa fa-fw fa-twitter"></i></a>
                            </li>
                            <li>
                                <a href="https://www.linkedin.com/in/nyombi-ronald-64097b27" class="btn-social btn-outline"  target="__blank"><i class="fa fa-fw fa-linkedin"></i></a>
                            </li>
                        </ul>
                    </div>
                    <div class="footer-col col-md-4">
                        <h3>My Favorite Quote</h3>
                        <p>Any code of your own that you haven't looked at for six or more months might as well have been written by someone else.</a>.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-below">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                      Copyright &copy; <a href="https://github.com/littlephild" target="__blank">Little Phild</a> 2016
                    </div>
                </div>
            </div>
        </div>
    </footer>
