
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <!-- For IE -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <!-- For Resposive Device -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Taba3ni</title>

    <!-- Favicon -->
    <link rel="icon" type="image/png" sizes="56x56" href="images/icon.png">


    <!-- Main style sheet -->
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <!-- responsive style sheet -->
    <link rel="stylesheet" type="text/css" href="css/responsive.css">


    <!-- Fix Internet Explorer ______________________________________-->

    <!--[if lt IE 9]>
			<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
			<script src="vendor/html5shiv.js"></script>
			<script src="vendor/respond.js"></script>
		<![endif]-->

</head>

<body>
    <div class="main-page-wrapper home-page-one">

        <!-- ===================================================
				Loading Transition
			==================================================== -->
        <div id="loader-wrapper">
            <div id="loader"></div>
        </div>



        <div class="html-top-content">
            <!-- 
				=============================================
					Theme Header
				============================================== 
				-->
            <header class="theme-main-header">
                <div class="container">
                    <div class="menu-wrapper clearfix">
                        <div class="logo float-left"><a href="index.html"><img src="images/3.png" alt="Logo" width="150" height="60" ></a></div>
                       

                    </div>
                    <!-- /.menu-wrapper -->
                </div>
                <style>
                /* The snackbar - position it at the bottom and in the middle of the screen */
                #snackbar {
                visibility: hidden; /* Hidden by default. Visible on click */
                min-width: 250px; /* Set a default minimum width */
                margin-left: -125px; /* Divide value of min-width by 2 */
                background-image: linear-gradient(180deg, #2af598 0%, #009efd 100%);
                color: #fff; /* White text color */
                text-align: center; /* Centered text */
                border-radius: 2px; /* Rounded borders */
                padding: 16px; /* Padding */
                position: fixed; /* Sit on top of the screen */
                z-index: 1; /* Add a z-index if needed */
                left: 50%; /* Center the snackbar */
                bottom: 30px; /* 30px from the bottom */
                }

                /* Show the snackbar when clicking on a button (class added with JavaScript) */
                #snackbar.show {
                visibility: visible; /* Show the snackbar */
                /* Add animation: Take 0.5 seconds to fade in and out the snackbar. 
                However, delay the fade out process for 2.5 seconds */
                -webkit-animation: fadein 0.5s, fadeout 0.5s 2.5s;
                animation: fadein 0.5s, fadeout 0.5s 2.5s;
                }

                /* Animations to fade the snackbar in and out */
                @-webkit-keyframes fadein {
                from {bottom: 0; opacity: 0;} 
                to {bottom: 30px; opacity: 1;}
                }

                @keyframes fadein {
                from {bottom: 0; opacity: 0;}
                to {bottom: 30px; opacity: 1;}
                }

                @-webkit-keyframes fadeout {
                from {bottom: 30px; opacity: 1;} 
                to {bottom: 0; opacity: 0;}
                }

                @keyframes fadeout {
                from {bottom: 30px; opacity: 1;}
                to {bottom: 0; opacity: 0;}
                }
                </style>
                <script>
                function myFunction() {
                // Get the snackbar DIV
                var x = document.getElementById("snackbar");

                // Add the "show" class to DIV
                x.className = "show";

                // After 3 seconds, remove the show class from DIV
                setTimeout(function(){ x.className = x.className.replace("show", ""); }, 3000);
                }
                </script>
            </header>
            <!-- /.theme-main-header -->


            <!-- 
				=====================================================
					Theme Main SLider
				=====================================================
				-->
            <div id="theme-main-banner" class="banner-one">
                <div data-src="images/home/slide-1.jpg">
                    <div class="camera_caption">
                        <div class="main-container">
                            <div class="container">
                                 <h2 class="wow fadeInUp animated">Taba3ni</h2>
                                <h5 class="wow fadeInUp animated">#Nebniw_Tunis_Zina</h5>
                               <br>
                                <p class="wow fadeInUp animated">Application mobile avec un chatbot intégré<br> pour gérer la mobilité des citoyens au grand tunis</p>
                               <div align="left">
                                <a  class="tran3s wow fadeInRight animated button-two" data-wow-delay="0.499s" onclick="myFunction()"><img   src="images/icon/2.png" alt="">GooglePlay</a>
                                <div class="image-wrapper wow fadeInUp animated" data-wow-delay="0.75s">
                                	<table>
                                		<tr><td><img src="images/transppng" alt=""   width="200" height="10"></td><td><img src="images/img-1.png" alt=""   width="330" height="600"></td></tr>
                                	</table>
                                    
                                </div>
                                
                            </div></div>
                            <!-- /.container -->
                            
                        </div>
                        <!-- /.main-container -->
                        
                    </div>
                    <!-- /.camera_caption -->
                    
                </div>
                
            </div>
            <!-- /#theme-main-banner -->
            <div id="snackbar">Coming soon..</div>


            <!--
				=====================================================
					What We Do
				=====================================================
				-->
            <div class="what-we-do bg">
                <div class="container">
                    <div class="theme-title-one text-center">
                      
                        <h3>
Caractéristiques étonnantes pour vous convaincre</h3>
                    </div>
                    <!-- /.theme-title-one -->





            <div class="boost-your-phone">
        
                <!-- /

                    
                -->
               
                       <div class="container">
                    <div class="row">
                        <div class="col-lg-6 col-xs-12 float-right  wow fadeInRight">
                            <div class="text">
                                <div class="theme-title-two">
                                    <h4>Les fonctionnalités principales</h4>
                                    <br>
                                    <ul>
                                    <li><i class="flaticon-tick"></i> Affiche tout les itinéraire possible pour allez a une ville</li>
                                    <li><i class="flaticon-tick"></i> Estimer le temp d'arrivé du bus, metro ou TGM</li>
                                    <li><i class="flaticon-tick"></i> Localisé tout les moyens publiques prés de vous tel que Pharmacie, Hopitaux, Postes ...</li>
                                </ul>
                                </div>
                                <!-- /.theme-title-two -->
                                
                            </div>
                        </div>
                    </div>
                    <div class="boster-image-wrapper  wow fadeInLeft">
                    <table>
                        <tr>  <td><img src="images/transp.png" width="20" height="100" alt=""></td>
                    </tr>
                    <tr>   <td><img src="images/Taba3ni3.png" alt=""></td>
                    </tr>
                </table>
                        
                     
                    </div>
                    <!-- /.boster-image-wrapper -->
                </div> <br><br><br>

                        <div class="container">
                    <div class="row">
                        <div class="col-lg-6 col-xs-12 float-right  wow fadeInLeft">
                     
                        
                       
                         <table>
                        <tr>  <td><img src="images/transp.png" width="10" height="70" alt=""></td>
                    </tr>
                    <tr>   <td><                        <img src="images/3d.png" alt="">
</td>
                    </tr>
                </table>



                        </div>
                    </div>
                    <div class="boster-image-wrapper  wow fadeInRight">

                          <div class="text">
                                <div class="theme-title-two">
                                    <h4>Chatbot intelligent pour vous aidez</h4>
                                    <br>
                                    <ul>
                                    <li><i class="flaticon-tick"></i> Chatbot intelligent multilangue arabe , français , anglais</li>
                                    <li><i class="flaticon-tick"></i> doté d'une intelligence artificielle avec NLP et machine learning</li>
                                    <li><i class="flaticon-tick"></i> Réponses instantané</li>
                                </ul>
                                </div>
                                <!-- /.theme-title-two -->
                                
                            </div>                 





                    </div>
                    <!-- /.boster-image-wrapper -->
                </div><br><br><br>    <div class="container">
                    <div class="row">
                        <div class="col-lg-6 col-xs-12 float-right  wow fadeInRight">
                            <div class="text">
                                <div class="theme-title-two">
                                    <h4>Map en temp réel</h4>
                                    <br>
                                    <ul>
                                    <li><i class="flaticon-tick"></i> Map du grand tunis détaillé</li>
                                    <li><i class="flaticon-tick"></i> Une carte intelligente comprend tout ce que vous ecrivez  </li>
                                    <li><i class="flaticon-tick"></i> Vous n'aurez pas besoin d'utilisez la clavier, vous pouvez parlez</li>
                                </ul>
                                </div>
                                <!-- /.theme-title-two -->
                                
                            </div>
                        </div>
                    </div>
                    <div class="boster-image-wrapper  wow fadeInLeft">
                    <table>
                        <tr>  <td><img src="images/transp.png" width="10" height="100" alt=""></td>
                    </tr>
                    <tr>   <td><img src="images/mapss.png" alt=""></td>
                    </tr>
                </table>
                        
                     
                    </div>
                    <!-- /.boster-image-wrapper -->
                </div> 
            </div>
            <!-- /.boost-your-phone -->







                    <!-- /.row -->
                </div>
                <!-- /.container -->
            </div>
            <!-- /.what-we-do -->



            <!--
				=====================================================
					Boost Your Phone
				=====================================================
			



            <!--
				=====================================================
					Advance Feature
				=====================================================
				-->
         
            <!-- /.advance-feature -->




            <div class="two-section-wrapper">
                <!--
					=====================================================
						Testimonial Slider
					=====================================================
					-->
                <div class="testimonial-section">
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-8 col-xs-12 float-right wow fadeInUp">
                                <div class="theme-title-one">
                                    <h6>TÉMOIGNAGES</h6>
                                    <h2>Vérifiez ce que les gens <br>
À propos de nous!</h2>
                                </div>
                                <!-- /.theme-title-one -->
                            </div>
                            <!-- /.col- -->
                        </div>
                        <!-- /.row -->
                    </div>
                    <!-- /.container -->
                    <div class="main-bg-wrapper">
                        <div class="overlay">
                            <div id="watch-video">
                                <h6>Watch</h6>
                                <h4>Intro Video</h4>
                                <a href="https://www.youtube.com/watch?v=lRhPkabLheY" target="_blank"><i class="fa fa-play" aria-hidden="true"><span></span></i></a>
                            </div>
                            <div class="main-slider-wrapper">
                                <div class="testimonial-slider">
                                    <div class="item">
                                        <i class="flaticon-straight-quotes"></i>
                                        <p>“nchaaalllahh wlhh a7sen hajaa This is made my day</p>
                                        <div class="clearfix">
                                            
                                            <div class="name float-left">
                                                <h6>Khaoula nailli</h6>
                                                <span>etudiante a FST</span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="item">
                                        <i class="flaticon-straight-quotes"></i>
                                        <p>“Hethy bthaabt application li lezma ftunis ❤ Bravo </p>
                                        <div class="clearfix">
                                            
                                            <div class="name float-left">
                                                <h6>Asma</h6>
                                                <span>etudiante a FST</span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="item">
                                        <i class="flaticon-straight-quotes"></i>
                                        <p>“Bonne continuation</p>
                                        <div class="clearfix">
                                            
                                            <div class="name float-left">
                                                <h6>Helmi chamsi</h6>
                                                <span>etudiant a l'esprit</span>
                                            </div>
                                        </div>
                                    </div>
                                      <div class="item">
                                        <i class="flaticon-straight-quotes"></i>
                                        <p>“c'est une bonne idée bravo et bonne continuation </p>
                                        <div class="clearfix">
                                            
                                            <div class="name float-left">
                                                <h6>Alya</h6>
                                                <span>etudiante a l'ISG</span>
                                            </div>
                                        </div>
                                    </div>
                                      <div class="item">
                                        <i class="flaticon-straight-quotes"></i>
                                        <p>“Keep going</p>
                                        <div class="clearfix">
                                            
                                            <div class="name float-left">
                                                <h6>Khalil</h6>
                                                <span>etudiant a l'ISG</span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <!-- /.testimonial-slider -->
                            </div>
                            <!-- /.main-slider-wrapper -->
                        </div>
                    </div>
                    <!-- /.main-bg-wrapper -->
                </div>
                <!-- /.testimonial-section -->

                <!-- 
					=============================================
						Pricing Plan Style One
					============================================== 
					-->
                <div class="pricing-plan-section">
                    <div class="container">
           
                            
                             <div class="row">
                                <div class="tab-content">
                                    <div class="table-content">
                                    	 <div class="app-screenshot">
              
                <div class="screenshot-container">
                    
                    <div class="slider-row">
                        <div class="screenshoot-slider">
                                        <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                            	<div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Stations</h6>
                                              <br>
                                                <strong>&nbsp;&nbsp;4215</strong>
                                               </div>
                                          
                                            </div>
                                        </div>

                                           <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pharmacies</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;508</strong>
                                           </div>
                                            </div>
                                        </div>
                                           <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;les lignes Bus</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;183</strong>
                                           </div>
                                            </div>
                                        </div>

                                          <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;kiosque</h6>
                                              <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;72</strong>
                                           </div>
                                            </div>
                                        </div>
                                         <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                            	<div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;parking</h6>
                                                <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;33</strong>




                                            </div>
                                              
                                            </div>
                                        </div>
                                          <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                            	<div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sonede</h6>
                                             <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;14</strong>
                                            </div>
                                           
                                            </div>
                                        </div>
                                          <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                            	<div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;steg</h6>
                                             <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;22</strong>
                                            </div>
                                               
                                            </div>
                                        </div>
                                         <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                            	<div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;hopitaux</h6>
                                             <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;24</strong>
                                           </div>
                                            </div>
                                        </div>
                                         
                                          <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                            	<div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Municipalité</h6>
                                            <br> 
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;46</strong>
                                           </div>
                                            </div>
                                        </div>
                                         <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                            	<div class="text-left">
                                                <h6>&nbsp;&nbsp;Poste tunisienne</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;81</strong>
                                           </div>
                                            </div>
                                        </div>
                                      
                                           <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Musées</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;16</strong>
                                           </div>
                                            </div>
                                        </div>
                                         <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Aziza</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;62</strong>
                                           </div>
                                            </div>
                                        </div>
                                          <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MG</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;23</strong>
                                           </div>
                                            </div>
                                        </div>
                                          <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Monoprix</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;40</strong>
                                           </div>
                                            </div>
                                        </div>
                                          <div id="monthly" class="tab-pane price-table in active">
                                            <div class="col-inner">
                                                <div class="text-left">
                                                <h6>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Carrefour</h6>
                                           <br>
                                                <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;38</strong>
                                           </div>
                                            </div>
                                        </div>
                                      


                                        <!-- /#yearly -->
                                    </div>
                                    <!-- /.table-content -->
                                </div>
                                <!-- /.tab-content -->
                            </div>
                        </div>
                    </div>
                </div>
                        </div>
                        <!-- /.row -->
                    </div>
                    <!-- /.container -->
                </div>
                <!-- /.pricing-plan-section -->
            </div>
            <!-- /.two-section-wrapper -->



            <!--
				=====================================================
					App ScreenShot
				=====================================================
				-->
            <div class="app-screenshot">
                <h2>Capture d'écran de l'application</h2>
                <div class="screenshot-container">
                    <div class="phone-mockup"><img src="images/home/mobile-mockup.png" alt="" class=""></div>
                    <div class="slider-row">
                        <div class="screenshoot-slider">
                        
                         
                           
                            <div class="item"><img src="images/img8.png" alt=""></div>
                            <div class="item"><img src="images/img9.png" alt=""></div>
                            <div class="item"><img src="images/img10.png" alt=""></div> 
                            <div class="item"><img src="images/img17.png" alt=""></div>
                          
                                <div class="item"><img src="images/im11.png" alt=""></div>
                            <div class="item"><img src="images/im222.png" alt=""></div>
                             <div class="item"><img src="images/img15.png" alt=""></div>  
                            <div class="item"><img src="images/img21.png" alt=""></div>

                            
                               <div class="item"><img src="images/img4.png" alt=""></div>
                            
                            <div class="item"><img src="images/img6.png" alt=""></div>  
                            <div class="item"><img src="images/img18.png" alt=""></div>
                             <div class="item"><img src="images/img13.png" alt=""></div>   
                            <div class="item"><img src="images/img14.png" alt=""></div>

                            <div class="item"><img src="images/img19.png" alt=""></div>
                             <div class="item"><img src="images/img11.png" alt=""></div>
                            <div class="item"><img src="images/201.png" alt=""></div>
                          <div class="item"><img src="images/img12.png" alt=""></div>

                             
                         
                           

                        </div>
                        <!-- /.screenshoot-slider -->
                    </div>
                    <!-- /.row -->
                </div>
              
                <!-- /.screenshot-container -->
            </div>
            <!-- /.app-screenshot -->


            <!--
				=====================================================
					Conatct Us
				=====================================================
				-->
     

            <!--
				=====================================================
					Google-map
				=====================================================
				-->
       
        </div>
        <!-- /.html-top-content -->



        <!--
			=====================================================
				Footer 
			=====================================================
			-->
        <footer>
            <div class="container">
                <div class="footer-data-wrapper">
                    <form action="#" class="subscribe-form">
                        <h2>Abonnez-vous à notre newsletter !!
</h2>
                        <div class="input-wrapper">
                            <div class="row">
                                <div class="col-md-5 col-md-6 col-xs-12">
                                    <input type="text" placeholder="Nom*">
                                </div>
                                <div class="col-md-5 col-md-6 col-xs-12">
                                    <input type="email" placeholder="Adresse email">
                                </div>
                                <div class="col-md-2 col-xs-12">
                                    <div class="theme-button">
                                        <span></span>
                                        <input type="submit" value="S'INSCRIRE">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </form>
                    <div class="bottom-footer">
                        <div class="row">
                            <div class="col-lg-6 col-md-7 col-xs-12 text-right pull-right">
                                
                                <ul class="social-icon">
                                    <li><a href="https://web.facebook.com/Taba3ni-360643314794068/" class="tran3s"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                                    <li><a href="#" class="tran3s"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                                    
                                    <li><a href="#" class="tran3s"><i class="fa fa-pinterest" aria-hidden="true"></i></a></li>
                                </ul>
                            </div>
                            <div class="col-lg-6 col-md-5 col-xs-12 footer-logo">
                                <div class="logo"><a href="index.html"><img src="images/3.png" alt="Logo" width="150" height="60" ></a></div>
                               
                            </div>
                        </div>
                        <!-- /.row -->
                    </div>
                    <!-- /.bottom-footer -->
                </div>
            </div>
            <!-- /.container -->
        </footer>



        <!-- Scroll Top Button -->
        <button class="scroll-top tran3s color-one-bg">
				<i class="fa fa-long-arrow-up" aria-hidden="true"></i>
			</button>




        <!-- Js File_________________________________ -->

        <!-- j Query -->
        <script type="text/javascript" src="vendor/jquery.2.2.3.min.js"></script>

        <!-- Bootstrap JS -->
        <script type="text/javascript" src="vendor/bootstrap/bootstrap.min.js"></script>

        <!-- Vendor js _________ -->
        <!-- Camera Slider -->
        <script type='text/javascript' src='vendor/Camera-master/scripts/jquery.mobile.customized.min.js'></script>
        <script type='text/javascript' src='vendor/Camera-master/scripts/jquery.easing.1.3.js'></script>
        <script type='text/javascript' src='vendor/Camera-master/scripts/camera.min.js'></script>
        <!-- WOW js -->
        <script type="text/javascript" src="vendor/WOW-master/dist/wow.min.js"></script>
        <!-- Tilt js -->
        <script type="text/javascript" src="vendor/tilt.js/src/tilt.jquery.js"></script>
        <!-- Fancybox -->
        <script type="text/javascript" src="vendor/fancybox/dist/jquery.fancybox.min.js"></script>
        <!-- Validation -->
        <script type="text/javascript" src="vendor/contact-form/validate.js"></script>
        <script type="text/javascript" src="vendor/contact-form/jquery.form.js"></script>

        <!-- owl.carousel -->
        <script type="text/javascript" src="vendor/owl-carousel/owl.carousel.min.js"></script>

        <!-- Theme js -->
        <script type="text/javascript" src="js/theme.js"></script>

    </div>
    <!-- /.main-page-wrapper -->
</body>

</html>
