<!DOCTYPE html>
<html>
<head>
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix clone page</title>
    <link rel="stylesheet" href="style.css"/>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
     integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm"
      crossorigin="anonymous"/>
    
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Borel&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
       rel="stylesheet"/>

</head>
<body>
    <header>
         <nav class="navbar">
            <div class="navbar_netflix">
                <img src="img/logo.png" alt="The Netflix logo" class="netflix_logo"/>
            </div>
            <div class="navbar_nav_items">
              <div class="nav_item">
                <div class="dropdown_container">
                  <i class="fa-solid fa-globe"></i>
                  <select name="language" id="languageSelect" class="language_drop_down">
                    <option value="english" selected>English</option>
                    <option value="hindi">Hindi</option>
                  </select>
                </div>
                </div>
                <div class="nav_item">
                    <button class="signin_button">Sign In</button>
                </div>
            </div> 
          </div>
         </nav>
    </header> 
    
    <main>
      <section class="hero">
        <div class="hero_bg_image_container">
          <img src="img/background.jpg" alt="BG hero image" class="hero_bg_image">
        </div>
        <div class="hero_bg_overlay"></div>
        <div class="hero_card">
          <h1 class="hero_title">Unlimited Movies, TV <br/> Shows and More.</h1>
          <p class="hero_subtitle">Watch anywhere and Cancel anytime.</p>
          <p class="hero_description">Ready to watch? Enter your email to create or restart your membership.</p>
        
          <div class="email_form_container">
            <div class="form_container">
              <input type="email" class="email_input" placeholder=" " />
              <label class="email_label">Email Address</label>
            </div>
            <button class="primary_button">Get Started <i class="fa-light fa-chevron-right"></i></button>
          </div>
        </div> 
      </section>
      <section class="features_container">

      <!--Feature 1-->
        <div class="feature">
          <div class="feature_details">
            
              <h3 class="feature_title">Enjoy on your TV.</h3>
              <h5 class="feature_sub_title">Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Bluu-ray players and more.</h5>
            </div>
            <div class="feature_image_container">
              <img src="img\tv.png" alt="feature image" class="feature_image"/>
              <div class="feature_background_video_container">
                <video autoplay="" loop="" muted="" class="feature_background_video">
                  <source src="img\video-tv-in-0819.m4v" type="video/mp4"/>             
                </video>"
              
            </div>
          </div>
        </div>
      
      <!--Feature 2-->
        <div class="feature">
          <div class="feature_details">
            
              <h3 class="feature_title">Download your shows to watch offline.</h3>
              <h5 class="feature_sub_title">Save your favourites easily and always have something to watch.</h5>
            </div>
            <div class="feature_image_container">
              <img src="img\mobile-0819.jpg" alt="feature image" class="feature_image"/>
              
            <div class="feature_2_poster_container">
              <div class="poster_container">
               <img src="img\boxshot.png" alt="poster" class="poster" />
              </div>
              <div class="poster_details">
                <h4>Stranger Things</h4>
                <h6>Downloading...</h6>
              </div>
              <div class="download_gif_container">
                <img src="img\download-icon.gif" alt="downloading gif" class="gif" />
              </div>
            </div>
          </div>
        </div>
      
      <!--Feature 3-->
      <div class="feature">
        <div class="feature_details">
          
            <h3 class="feature_title">Watch everywhere.</h3>
            <h5 class="feature_sub_title">Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</h5>
          </div>
          <div class="feature_image_container">
            <img src="img\tv.png" alt="feature image" class="feature_image"/>
            <div class="feature_background_video_container">
              <video autoplay="" loop="" muted="" class="feature_background_video">
                <source src="img\video-tv-in-0819.m4v" type="video/mp4"/>             
              </video>"
            
          </div>
        </div>
      </div>
    
    <!--Feature 4-->
    <div class="feature">
      <div class="feature_details">
        
          <h3 class="feature_title">Create profiles for children.</h3>
          <h5 class="feature_sub_title">Send children on adventures with their favourite characters in a space made just for them-free with your membership.</h5>
        </div>
        <div class="feature_image_container">
          <img src="img\tv.png" alt="feature image" class="feature_image"/>
          <div class="feature_background_video_container">
            <video autoplay="" loop="" muted="" class="feature_background_video">
              <source src="img\video-tv-in-0819.m4v" type="video/mp4"/>             
            </video>"
          
        </div>
      </div>
    </div>
  
      </section>
    </main>

  
</body>
</html> 
