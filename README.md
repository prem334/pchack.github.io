<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUCIFER</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<script src="https://kit.fontawesome.com/f9d8b0bda2.js" crossorigin="anonymous"></script>
</head>
<body> 
    <section class="header">
         <nav>
             <a href="LUCI HTML.html"><img src="image/lucisec (1).png"> </a>
             <div class="nav-links" id="navLinks">
                <i class="fa-solid fa-circle-xmark" onclick="hideMenu()"></i>
                 <ul>
                     <li><a class="active" href="#">HOME</a></li>
                     <li><a href="#">ABOUT</a></li>
                     <li><a href="#">Course</a></li>
                     <li><a href="#">BLOG</a></li>
                 </ul>
             </div>
             <i class="fa-solid fa-bars" onclick="showMenu()"></i>
         </nav>

         <div class="text-box">
            <h1>Welcome To Luci's World</h1>
            <p>Hacking is now easiest thing in the world.You just need to run <br>kali linux and you are good to go.</p>
            <a href="" class="hero-btn">Visit Us To Know More</a>
         </div>

    </section>

    <!----- course ------>

   <section class="course">
    <h1>Courses We Needed</h1>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>

     <div class="row">
        <div class="course-col">
            <h3>Intermediate</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero placeat nulla nam repellendus modi odio, dolor omnis perspiciatis numquam debitis officiis neque enim quos! Dignissimos perferendis obcaecati nulla molestiae cum?</p>
        </div>
        <div class="course-col">
            <h3>Degree</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero placeat nulla nam repellendus modi odio, dolor omnis perspiciatis numquam debitis officiis neque enim quos! Dignissimos perferendis obcaecati nulla molestiae cum?</p>
        </div>
        <div class="course-col">
            <h3>Post Graduation</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero placeat nulla nam repellendus modi odio, dolor omnis perspiciatis numquam debitis officiis neque enim quos! Dignissimos perferendis obcaecati nulla molestiae cum?</p>
        </div>
     </div>

   </section>

   <!------- office ------>

   <section class="office">
    <h1>Our Global Office</h1>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>

    <div class="row">
        <div class="office-col">
            <img src="image/633x580_ncp.jpg">
            <div class="layer">
                <h3>MUMBAI</h3>
            </div>
        </div>
    </div>
   </section>

   <!-------- Facilities --------->

   <section class="facilities">
       <h1>Our Facilities</h1>
       <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>

       <div class="row">
          <div class="facilities-col">
            <img src="image/download (3).jfif">
            <h3>Best Computer Lab</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
          </div>
          <div class="facilities-col">
            <img src="image/library.png">
            <h3>world Office Library</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
          </div>
          <div class="facilities-col">
            <img src="image/playground.png">
            <h3>Largest Play Ground</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.Pellentesque aliquet turpis nulla.</p>
          </div>
       </div>

   </section>

   <!--------- testimonials ------------>

   <section class="testimonials">
    <h1>What Our Employees Says</h1> 
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    
    <div class="row">
        <div class="testimonial-col">
            <img src="image/download (2).jfif">
            <div>
                <p>"Thank you for putting in the extra effort during this busy time. The client truly appreciates it and your positive attitude has helped us all stay motivated."</p>
                <h3>anonymous</h3>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp-half-stroke"></i>
            </div>
        </div>
        <div class="testimonial-col">
            <img src="image/hacking-hackerman-hackers-anonymous-wallpaper-preview.jpg">
            <div>
                <p>"Ava, your work looks great! It is clear that you care about your work, and I appreciate that you asked the client about their design preferences before creating their website."</p>
                <h3>anonymous</h3>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp"></i>
                <i class="fa-solid fa-star-sharp"></i>
            </div>
        </div>
    </div>

   </section>

   <!----- Call To Action --------->

   <section class="cta">
    <h1>Enroll For Our Various Online Jobs<br>Anywhere From The Office</h1>
    <a href="" class="hero-btn">CONTACT US</a>
   </section>

   <!----- Footer --------->

   <section class="footer">
    <h4>About Us</h4>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure recusandae, laboriosam tempore, explicabo nesciunt at optio,<br> et ut odit architecto ullam iste maxime? Animi delectus voluptatem quam, non molestias magnam.</p>
    <div class="icons">
        <i class="fa-brands fa-facebook-square"></i>
        <i class="fa-brands fa-twitter-square"></i>
        <i class="fa-brands fa-instagram-square"></i>
        <i class="fa-brands fa-linkedin"></i>
    </div>
    <p>Website Created By Mr.Nomul</p>
   </section>






<!------JavaScript for Toggle Menu------->
<script>
    
    var navLinks = document.getElementById("navLinks");

    function showMenu(){
        navLinks.style.right = "0";
    }
    function hideMenu(){
        navLinks.style.right = "-200px";
    }

</script>
 
</body>
</html>















































