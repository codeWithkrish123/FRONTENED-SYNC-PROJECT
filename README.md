# FRONTENED-SYNC-PROJECT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FRONTENED-SYNC-PROJECT</title>
    

    <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

    
       :root{
        --primary-color:#6366f1;
        --accent-color:#3f83f8;
        --text-color:#333333;
        --link-color:#2563eb;
        --background-color:#ffffff;
        --light-gray:#f0f0f0;
        --gray:#808080;
        --dark-gray:#555;


       }

*{
    margin:0px;
    padding:0px;
    box-sizing: border-box;
    font-family:'inter',sans-serif;
    text-decoration: none;
}
   body{
    height:100vh;
    padding:0.1rem;
    background-color: var(--background-color);
    text-align:center;
    color: var(--background-color);

   }
    .header-content{
        display:flex;
        justify-content: space-between;
        max-width: 1280px;
        margin:0 auto;
        align-items:center;
        padding:1rem;
      
       
    }
    .logo{
        display:flex;
        align-items: center;
        font-size:2rem;
        color: var(--text-color);
        font-weight:bold;
        gap:0.625rem;
    }
    .logo img{
       height:5.875rem;
       width:1.938rem;
    }
    .logo-text{
      font-size: 1.5rem;
    }
    
    .nav_container{
       
      display:none;
      gap:1rem;

    }

   @media only screen and (min-width: 768px) {
  .nav_container {
    display:flex;
  }
}
     
        
     
  .nav-link{
    color:#718096;
    font-weight: bold;
    transition:color 0.1s;
    
  
  }
  .nav-link:hover{
      color:var(--link-color);
  }
  .contact_container{
    display:none;
      border:none;
      border-radius: 0.37rem;
      padding:10px;
      color:var(--background-color);
      background-color:var(--primary-color);
      font-size: 1rem;
      font-weight:bold;
      transform:all 0.1s;
      }

       @media only screen and (min-width: 768px) {
     .contact_container {
      display:block;
    }
  }


  .contact_container:hover{
       background-color: #5254f8;
  }

  .button_container{
      display:none;
      border:none;
      border-radius: 0.375rem;
      background-color: var(--background-color);
       padding:10px;
  }
  .button_icon{
     height:1.5rem;
    width:1.5rem;
  }
     
   @media only screen and (max-width: 768px) {
     .button_container {
      display:block;
    }
  }




  /* main section */

  .header{
    margin:o auto;
  }

  .content-boxes{
    height:80vh;
    padding:0.1rem;
    background-color: var(--background-color); 
     
  }
  .main-section{
     max-width: 1240px;
    display:flex;
    flex-direction: column;
    align-items:center;
    margin:0 auto;
  }
   
  .left-box{
     width:50%;
     height:50%;
      animation: slideFromLeft 1s ease-out forwards;
      padding:2px;
   
  }

 @keyframes slideFromLeft {
            0% {
                opacity: 0;
                 transform: translateX(-100%);
            }
            100% {
                transform: translateX(0%);
                opacity: 1;
            }

        }
  
  .section-label{
    font-size: 0.9rem; 
    color:var(--primary-color);
    font-weight: 600; 
    padding:1.1rem;    
    
  }
  .head-section{
      color:var(--text-color);
      font-size: 2.25rem;
       padding:1.1rem;
       margin:1px;
  }
 .section-label2{
    font-size: 0.99rem;
    color:var(--gray);
   padding:1.1rem;
   
 }
 .button-group{
  display:flex;
  justify-content: center;
  gap:1.5rem;
    margin:2rem;
 }
   .button-box1,.button-box2{
      border:none;
      border-radius: 0.37rem;
      padding:10px;
      color:var(--background-color);
      background-color:var(--primary-color);
      font-size: 1rem;
      font-weight:bold;
      transform:all 0.1s;
   }
   .button-box2{
    background-color:var(--dark-gray);
   }
    .button-box1:hover{
         background-color:#5254f8;
     }
      
       .button-box2:hover{
          background-color: #333333;
       }
       .right-box{
         display:flex;
         justify-content: center;
         align-items: center;
         margin:20px;
       }
       .logo_big-image{
          height:400px;
          width:450px;
          border-radius: 1.225rem;
          overflow: hidden;
          box-shadow: 0px 0px 1px 1px black;
       }
      @media only screen and (min-width: 768px) {
     .main-section {
       flex-direction:row;
  }
    .left-box{
      text-align:left;
    }
    .head-section{
         padding:0px;
         font-size:3.6rem;
    }
    .button-group{
   justify-content:left;
   margin-left: 10px;
}
.section-label{
    font-size: 0.8rem;
    /* padding-left: 2px; */
   
    margin-left:1rem;
}
.logo_big-image{
  height:65vh;
}
.section-label2{
  color:#808080;
  width:75%vh;
  font-size: 0.9rem;
}

      }

      /* for midd company section */
      .company-container{
          display:flex;
          justify-content: center;
          align-items:center;
          animation: slideFromLeft 1s ease-out forwards;
          /* height:70vh; */
      }

        @keyframes slideFromLeft {

     0% {
                opacity: 0;
                 transform: translateX(-100%);
            }
            100% {
                transform: translateX(0%);
                opacity: 1;
            }

    
  }


  

.high-pay-company{
     display:grid;
      grid-template-columns: repeat(4,1fr);
     gap:3rem;
     padding:1rem;
     color:var(--text-color);
     border-radius: 10px;
     background-color: var(--light-gray);
     margin-bottom:25px;
     /* height:65vh; */
     border:1px solid black;
}

@media only screen and (max-width: 640px){
      .high-pay-company{
         grid-template-columns: repeat(auto-fit, minmax(15px, 1fr));
           overflow: hidden;
              }
        .content-boxes{
          height:50vh;
        }
         
}
  .company-head{
     color: var(--text-color);
     margin:20px;
     animation: slideFromLeft 1s ease-out forwards;         
     font-weight: bold;
  }

  @keyframes slideFromLeft {

     0% {
                opacity: 0;
                 transform: translateX(-100%);
            }
            100% {
                transform: translateX(0%);
                opacity: 1;
            }

    
  }

 .para1{
    text-align:center;
    font-size: small;
    margin:0 auto;

 }
 .compony-logo{
    font-size: 1rem;
    font-weight: 500;
    color: var(--light-gray);
    display:flex;
    gap:0.5rem;
 }


 /* card-section */
   

 .feature-container{
    background-color: var(--light-gray);
    padding:2rem auto;
    text-align: center;
     height:105vh;
   
 }
 .feature-content{
  max-width:800px;
  margin:0 auto;
  padding:0 2rem;
  margin-bottom:50px;
 }
 .main-tittle{
    font-size:2.2rem;
    color: var(--text-color);
 }
 .main-descrfiption{
    color: rgb(58, 56, 56);
    font-size:0.9rem;
 }
 .main-info{
  display:flex;
  flex-direction:column;
  gap:1rem;
  justify-content: center;
  align-items:center;
 }

 .feature-grid{
   display:grid;
   gap:1rem;
   grid-template-columns: repeat(2,1fr);
   margin-top: 1rem;
  
 }
 .img-inside-container{
    height:1.5rem;
    width:1.5rem;
 }
 .icon-container{
    height:3rem;
    width:3rem;
    background-color: var(--background-color);
    border-radius: 50%;
    display:flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 20px;
 }
 .feature-card{
   display:flex;
   flex-direction: column;
   justify-content: center;
   align-items: center;
   padding:1rem;
   border-radius: 1rem;
  transition: all 0.3s ease;
 }

 @media only screen and (max-width: 640px){
      .feature-grid{
         grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
           overflow: hidden;
              }
        .content-boxes{
          height:50vh;
        }
         
}

 
 .feature-card:hover{
  transform: translateY(-10px);

 }
.feature-title{
  color: white;
  font-size:larger;
  margin-bottom: 15px;
}

.feature-description{
   color:white;
   font-size: 0.9rem;
   font-weight: bolder;
}

.feature-card:nth-child(1){
   background-color: #4a90e2;
}
.feature-card:nth-child(2){
   background-color: #ff6289;
}

.feature-card:nth-child(3){
   background-color: #fcbf58;
}

.feature-card:nth-child(4){
   background-color: #44bfc3;
}

.feature-card:nth-child(5){
   background-color: #77b85d;
}

.feature-card:nth-child(6){
   background-color: #7d78b1;
}
.img1-inside-container{
   height:3rem;
   width:3rem;
   border-radius: 50%;
   border: 2px solid green;
   /* padding: 0;
   zoom: 20px; */
   /* margin-bottom:-20px; */
}


    /* testimonial-styling */

    

    .testimonial-heading{
       color:var(--text-color);
       font-weight:bolder ;
       margin-bottom: 20px;
    
    }

    .testimonial-grid{
       max-width:850px;
       display:grid;
       grid-template-columns: 1fr 1fr 1fr;
       gap:3rem;
       margin:2px auto;
       margin-left: 100px;
       /* padding:30px; */
    }

    @media only screen and (max-width: 640px){
      .testimonial-grid{
         grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
           overflow: hidden;
              }
        .content-boxes{
          height:50vh;
        }
        
         
}
  


         



.testimonial-content{
    margin-bottom:40px;
    height:250px;
}



    .testimonial-box1{
       display:flex;
       flex-direction: column;
       justify-content: center;
       align-items: center;
       border:0.5px solid rgb(227, 221, 221);
       padding:10px;
       border-radius: 10px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    transition:transform 0.3s ease, box-shadow 0.3s ease;
    }
      .testimonial-box1:hover{
          transform:scale(1.05);
          border:1px solid blue;

      }


    .testimonial-para{
       color: var(--text-color);
       min-width: 400px;
       margin-bottom: 20px;
       font-size: 0.8rem;
       font-weight: 400;
       

    }
    .testimonial-image{
        margin-bottom: 15px;
    }

    .testimonial-image1{
          height:80px;
          width:80px;
    }
    .sarah-head{
       color: var(--primary-color);
    }
    .sarah-para{
      color: var(--text-color);
      font-size: 0.9rem;
      font-weight: 450px;
    }


    /* Newslleter-section */

     .Newsletter-container{
        background-color: var(--background-color);
        max-width: 1000px;
        height:50vh;
        padding: 2rem;
         margin:0 auto;
     }
     .newsletter-content{
         display:flex;
         flex-direction:row;
         background-color: var(--light-gray);
         height:100%;
         border-radius: 8px;

     }
     .newsletter-left-content{
          width:50%;
          height:100%;
     }
      .Newseller-img-logo{
        width:500px;
        height:300px;
         object-fit: cover;
         object-position: center;

      }
      .newsletter-right-content{
           display:flex;
           flex-direction:column;
           gap:1rem;
           padding:6rem;
           justify-content: center;
           align-items: flex-start;
      }
     .Newsleter-head{
        font-size:1.9rem;
        font-weight: bolder;
        margin-left:-25px;
        color: var(--link-color);
        margin-bottom: 5px;

     }
     .Newsletter-para{
       color:#777;
       font-size: 0.9rem;
       margin-left:-151px;
       font-weight:medium;
       
     }
    
    .form-newselter{
       padding:0 3rem;
       display:flex;
       /* flex-direction: column; */
       margin-bottom: 1rem;
       gap:0.6rem;
       margin-left:-10px;
       max-width: 500px;
       margin-bottom:-8px;

    }
    .email{
      margin-left:-64px;
      background-color: var(--background-color);
      /* width:100%; */
      color:#333;
      outline: none;
      border:1px solid #ccc;
      border-radius: 4px;
      padding:0.5rem 0.75rem;
      
    }
    .send-container{
        background-color:var(--primary-color);
        color:var(--background-color);
        border:none;
        border-radius: 0.25rem;
        padding:0.5rem 1rem;
    }
   

    .send-container:hover{
      background-color: var(--link-color);
    }

     .newsletter-para-anchor-para{
      padding:0 3rem;
       min-width:459px;
       margin-left:-90px;
       color:var(--text-color);
       font-size: 0.8rem;
    }
    .Newsletter-aanchor{
        color:var(--link-color);
    }
    .Newsletter-aanchor:hover{
        text-decoration:underline;
    }
    .newsletter-anchor1{
         color:var(--link-color);
        
    }
    .newsletter-anchor1{
          text-decoration:underline;
    }
     @media only screen and (max-width: 640px) {
  .Newsletter-container{
      flex-direction:column;
      
  }
  .newsletter-right-content{
      margin:0 auto;
  }
     }

     /* footer-section */

     .footer-content{
       max-width: 1280px;
         border:none;
         margin:0 auto;
         display:flex;
         justify-content:space-around;
        
         
     }
     .social-media{
       display:flex;
       justify-content:center;
       align-items: center;
       gap:1rem;
       margin-right:125px;
     }
     
      .social-media{
         display:flex;
         justify-content:center ;
         align-items: center;
         margin-left:12px;
         /* margin:50px; */
         
      }

      .stud-sync-left{
         display:flex;
          flex-direction:column;
           gap:1.5rem;
           padding:40px;
         height:350px;
        width:400px;
        border:none;
       margin:50px;            
      }
      .para-seamless{
        color: var(--text-color);
      }
      .logo-text-footer{
          color: var(--text-color);
          font-weight: bolder;
         
      }
      .right-grid-footer{
        display:grid;
        grid-template-columns: repeat(4,1fr);
        gap:5rem;
        border:none;
        height:350px;
        width:700px;
        margin:40px; 
        padding-right:-50px;
        padding-left:50px;
        padding:38px;
      }
      .product-head{
         color:var(--text-color);
         font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
      }
      .product-container{
        margin-bottom:10px;
      }
      .product-container h3{
        margin-bottom:20px;
      }
      .product-container li{
         list-style-type: none;
        margin-bottom:20px;
      }
      .overview{
           color:var(--gray);
           font-size:0.9rem;
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
          
      }
      .product-footer-container{
      display:flex;
      flex-direction:column;


      }
      .stud-sync-footer{
          margin-left: 35px;
      }
        
      .product-head h3{
             margin-bottom: 20px;
      }
    .low-footer-content{
       color:var(--text-color);
        border:none;
    }
    .para1-footer-content{
         font-size:0.9rem;
    }
    .logo-footer{
      display:flex;
        align-items: center;
        font-size:1.5rem;
        color: var(--text-color);
        font-weight:bold;
        gap:0.625rem;
    }
    .img-logo{
        height:1.65em;
        width:1.65rem;
    }
    .seam-footer-container{
        font-size: 0.9rem;
        color: var(--gray);
    }

    

  
     

 
   </style>


    

</head>




<body>
        <div class="header">
            <header class ="header-content">
                <a href="#logo"class="logo">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/StudySyn.svg" alt="">
                    <span class="logo-text">StudySync</span>
                </a>

                 <nav class ="nav_container">
                    <a href="#Home"class="nav-link">Home</a>
                     <a href="#features"class="nav-link">features</a>
                      <a href="/for selling.html"class="nav-link">Pricing</a>
                       <a href="/css blog project/index.html"class="nav-link">Blog</a>
                        <a href="#About"class="nav-link">About</a>
                 </nav>

                 <a href="/form.html"class="contact_container">
                        Contact Us
                 </a>

                 <button type ="button"class="button_container">

                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/Hamburger.svg" alt=""class="button_icon">
                 </button>

            </header>
        </div>

           <!-- main body section: -->
             
           <!-- for outside a div to inside all code for hero section -->
          <div class="content-boxes">
                     
                 <section class="main-section">

                     <!-- for left box text section -->
                  <div class="left-box">
                     <p class="section-label">
                      very proud to introduce
                    </p>
                    <h1 class="head-section">
                      Seamless Learning for Brighter Futures
                    </h1>
                    <p class ="section-label2">
                      Our innovative platform offers an effortless and seamless approach to learning , 
                      emprowing student of all ages to achieve brighter future.join us a 
                      transformative journey to simplify education and unlock your full potential
                    </p>
                  
                    <div class="button-group">
                       <a href="#start"  class="button-box1">Start now</a>
                       <a href="#tour"class="button-box2">Tour now</a>
                    </div>
                   

                  </div>
                 <!-- for right box only image section -->
                  <div class="right-box">
                        
                    <img src="https://github.com/loveBabbar/CodehelpYTWebDev/blob/main/html_CSS_JS/lecture33/images/usgs-hoS3dzgpHzw-unsplash.jpg?raw=true" alt="logo_big-image"class="logo_big-image">

                  </div>
             </section>     
                   </div>
                 
                
                   <!-- for mid main section -->
                    <h2 class = "company-head">Trusted by the best</h2>
               <div class="company-container">
                             
                <div class="high-pay-company">    
               
                  <div class="google">
                   
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/Google.svg" alt="" class="company-logo">
                     <span class ="para1">Google</span>
                     <!-- </span> -->
                  </div>

                   <div class="Mocrosoft">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/Microsoft.svg" alt="" class="compny-logo">
                     <span class ="para1">Microsoft</span>

                  </div>

                   <div class="Linked-in">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/linkedin.svg" alt=""class="company-logo">
                     <span class ="para1">Linked|n</span>

                  </div>

                   <div class="VectorEdu">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/VectorEdu.svg" alt="" class="Vector-logo"height="15px"width="15px" >
                     <span class ="para1">VectorEdu</span>

                  </div>
                </div>
               </div>
               
               <!-- card section -->

              <div class="feature-container">
                <div class="feature-content">
                          
                  <div class="main-info">
                            <h2 class="main-tittle">Our competitive advantage</h2>
                            <p class="main-descrfiption">This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of real written text but is random or otherwise generated</p>
                  </div>

                   <div class="feature-grid">
            <!-- Card 1: Personalized Learning -->
            <div class="feature-card">
                <div class="icon-container">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/PersonalizedLearn.svg" alt="Personalized Learning" class="img-inside-container">
                </div>
                <div class="feature-info">
                    <div class="feature-title">Personalized Learning</div> 
                    <div class="feature-description">Offer tailored learning experiences through AI and machine learning to cater to individual student needs and learning styles.</div>
                </div> 
            </div>

            <!-- Card 2: Affordability -->
            <div class="feature-card">
                <div class="icon-container">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/Affordability.svg" alt="Affordability" class="img-inside-container">
                </div>
                <div class="feature-info">
                    <div class="feature-title">Affordability</div> 
                    <div class="feature-description">Provide high-quality education at an affordable price point, making it accessible to a broader audience</div>
                </div> 
            </div>

            <!-- Card 3: Industry Expert Sessions -->
            <div class="feature-card">
                <div class="icon-container">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/IndustryPatner.svg" alt="Industry Experts" class="img-inside-container">
                </div>
                <div class="feature-info">
                    <div class="feature-title">Industry Partnerships</div> 
                    <div class="feature-description">Collaborate with well-known companies and institutions to offer accredited courses and certifications, adding credibility to your offerings</div>
                </div> 
            </div>

            <!-- Card 4: Interactive Learning -->
            <div class="feature-card">
                <div class="icon-container">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/Analytics.svg" alt="Interactive Learning" class="img-inside-container">
                </div>
                <div class="feature-info">
                    <div class="feature-title">Analytics and Insights
</div> 
                    <div class="feature-description">Offer detailed progress tracking and analytics to help students and teachers monitor performance and make data-driven decisions.</div>
                </div> 
            </div>

            <!-- Card 5: Certification -->
            <div class="feature-card">
                <div class="icon-container">
                    <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/InnovativeTech.svg" alt="Certification" class="img-inside-container">
                </div>
                <div class="feature-info">
                    <div class="feature-title">Innovative Technology</div> 
                    <div class="feature-description">Utilize cutting-edge technology, such as augmented reality or virtual reality, to create immersive learning experiences</div>
                </div> 
            </div>
                              
            <!-- Card 6: 24/7 Support -->
            <div class="feature-card">
                <div class="icon-container">
                    <img src="https://cdn-icons-png.flaticon.com/128/733/733585.png" alt="24/7 Support" class="img1-inside-container">
                </div>
                <div class="feature-info">
                    <div class="feature-title">Responsive Support</div> 
                    <div class="feature-description">Provide exceptional customer support and assistance to students and educators.</div>
                </div> 
            </div>
        </div>
              </div>

              

                     

              <!-- Testimonial-section -->

              <div class="testimonial-container">

                        <div class="testimonial-content">
                               <h2 class ="testimonial-heading">What Others Say About Us</h2>

                                      
                               <!--Testimonial-container  -->

                                 <div class="testimonial-grid">

                                  <!-- box1 -->
                                     <div class="testimonial-box1">
                                                   
                                      <div class="testimonial-para">
                                        <p>StudySync revolutionized my classroom! Engaging content and teacher resources make learning enjouyable.ighly recomended for education</p>
                                      </div>

                                      <div class="testimonial-image">
                                          <img src="https://github.com/loveBabbar/CodehelpYTWebDev/blob/main/html_CSS_JS/lecture33/images/avatar1.png?raw=true" alt="" class ="testimonial-image1">
                                      </div>

                                      <div class="testimonial-headandppara">
                                        <h3 class="sarah-head">Sarah Johnson</h3>
                                        <p class="sarah-para">8th Grade English Teacher</p>
                                      </div>

                                     </div>

                                     <!-- box1 end -->



                                     <!-- box-2 -->

                                        <div class="testimonial-box1">
                                                   
                                      <div class="testimonial-para">
                                        <p>"StudySync transformed our family's learning journey. Safe, interactive, and progress tracking features are invaluable for parents.</p>
                                      </div>

                                      <div class="testimonial-image">
                                          <img src="https://github.com/loveBabbar/CodehelpYTWebDev/blob/main/html_CSS_JS/lecture33/images/avatar2.png?raw=true" alt="taklu-mamu" class ="testimonial-image1">
                                      </div>

                                      <div class="testimonial-headandppara">
                                        <h3 class="sarah-head">Mark Davis</h3>
                                        <p class="sarah-para"> Parent</p>
                                      </div>

                                     </div>

                                     <!-- box2 end -->

                                     <!--  box3 -->

                                        <div class="testimonial-box1">
                                                   
                                      <div class="testimonial-para">
                                        <p>"StudySync, a true game-changerl Flexible content, tailored assessments, and excellent support, Integra to our school district's success"</p>
                                      </div>

                                      <div class="testimonial-image">
                                          <img src="https://github.com/loveBabbar/CodehelpYTWebDev/blob/main/html_CSS_JS/lecture33/images/avatar3.png?raw=true" alt="" class ="testimonial-image1">
                                      </div>

                                      <div class="testimonial-headandppara">
                                        <h3 class="sarah-head">Dr. James Carter </h3>
                                        <p class="sarah-para">School Administrator</p>
                                      </div>

                                     </div>

                                     <!-- box3 end -->
                                     </div>

                        </div>
                 
              <!-- </div>           -->


              <!-- Newsletter-container -->
              
              <div class="Newsletter-container">

                   <div class="newsletter-content">
                         <div class="newsletter-left-content">
                                  
                          <img src="https://github.com/loveBabbar/CodehelpYTWebDev/blob/main/html_CSS_JS/lecture33/images/img.png?raw=true" alt="" class="Newseller-img-logo" height="450px"width="450px">

                         </div>

                         <div class="newsletter-right-content">
                              <div class="newsletter-headandpara">
                                <h2 class="Newsleter-head">Get the latest update</h2>
                                  <p class="Newsletter-para">Sign up for our newsleter</p>
                              </div>

                              <form  class="form-newselter">
                                     <input type="text"class="email"name="email"placeholder="Email">
                                       <button class="send-container">Send</button>
                              </form>

                              <div class="newsletter-para-anchor-para">
                                  By signing up to our newsletter you agree to our
                                   <a href="#" class="Newsletter-aanchor">Term of Services</a>
                                   and
                                   <a href="#"class="newsletter-anchor1">Privacy policy</a>
                                   
                              </div>
                         </div>
                   </div>

              </div>

              <!--  FOOTER-SECTION -->

              <div class="footer-container">
                     <div class="footer-content">

                        
                                <div class="stud-sync-left">

                                        <div class="stud-sync-footer">  
                                   <a href="#logo"class="logo-footer">  
                             <img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/StudySyn.svg" alt="" class="img-logo">
                              <span class="logo-text-footer">StudySync</span>
                            </a>
                            </div>

                                <div class="para-seamless">
                                  <p class="seam-footer-container"> Seamless Learning for brighter Future</p>
                                </div>

                               <ul class="social-media">
                                <li><img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/instagram.svg" alt=""></li>
                                <li><img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/twitter.svg" alt=""></li>
                                <li><img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/linkedin-copy.svg" alt=""></li>
                                <li><img src="https://raw.githubusercontent.com/loveBabbar/CodehelpYTWebDev/5f10c3122a1081eed273bdf54a733d5302540105/html_CSS_JS/lecture33/images/github.svg" alt=""></li>
                               </ul>

                                </div>

                        
                                <div class="right-grid-footer">
                                  <div class="product-footer-container">
                                    <ul class="product-container">
                                           <h3 class="product-head">products</h3>
                                               <li class="overview">Overview</li>
                                               <li class="overview">Solutions</li>
                                               <li class="overview">Pricing</li>
                                               <li class="overview">Customers</li>
                                    </ul>
                                  </div>

                                  <div class="product-container">
                                    <ul class="product-container">
                                           <h3 class="product-head">Company</h3>
                                               <li class="overview">About</li>
                                               <li class="overview">investor Relations</li>
                                               <li class="overview">Jobs</li>
                                               <li class="overview">press</li>
                                               <li class="overview">Blog</li>
                                    </ul>
                                  </div>


                                  <div class="product-container">
                                    <ul class="product-container">
                                           <h3 class="product-head">Support</h3>
                                               <li class="overview">Contact</li>
                                               <li class="overview">Documentation</li>
                                               <li class="overview">Chat</li>
                                               <li class="overview">FAQ</li>
                                    </ul>
                                  </div>


                                  <div class="product-container">
                                    <ul class="product-container">
                                           <h3 class="product-head">Legal</h3>
                                               <li class="overview">Term of Services</li>
                                               <li class="overview">Privacy policy</li>
                                               <li class="overview">Cookie setting</li>
                                              
                                    </ul>
                                  </div>

                              




                                </div>
                                 </div>
                                           <div class="low-footer-content">
                                        
                                              <p class="para1-footer-content">&copy;2021- present studSync.All rights reserved</p>
                                            

                                           </div>
                                    
                                      
                                </div>



                        
                    
                     



      
</body>
</html>
