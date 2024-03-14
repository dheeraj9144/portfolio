<?php header('Content-type: text/css'); ?>

/*  import google fonts */
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Ubuntu:wght@400;500;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');

@font-face {
    font-style: normal;
  }
body{
    background-color: #000;
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
   
}
* p{
font-size: 15px;
}
html{
    scroll-behavior: smooth;
}

  
  /* Chat icon */
  .chat-icon {
    display: none; /* Hide the icon by default */
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: transparent;
    color: #fff;
    border-radius: 50%;
    width: 60px;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 24px;
    
    transition: background-color 0.3s;
    z-index: 999; /* Ensure the icon is above other elements */
  }


/* Media query for mobile view */
@media (max-width: 768px) {
  .chat-icon {
    display: flex; /* Show the icon only in mobile view */
  }
}

.chat-icon img {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  /* Add the animation */
  animation: bounce 1s infinite alternate;
}

@keyframes bounce {
  0% {
    transform: translateY(0);
  }
 
  100% {
    transform: translateY(-10px);
  }
}

/* custom scroll bar */
::-webkit-scrollbar {
    width: 10px;
}
::-webkit-scrollbar-track {
    background: #f1f1f1;
}
::-webkit-scrollbar-thumb {
    background: #888;
}

::-webkit-scrollbar-thumb:hover {
    background: #555;
}

/* all similar content styling codes */
section{
    padding: 75px 0;
}
.max-width{
    max-width: 1300px;
    padding: 0 80px;
    margin: auto;
}
.about, .services, .skills, .teams, .contact, footer{
    font-family: "Nunito", sans-serif;
  font-weight: 400;
}
.about .about-content,
.services .serv-content,
.skills .skills-content,
.contact .contact-content{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}
section .title{
    position: relative;
    text-align: center;
    font-size: 55px;
    font-weight: 400;
    margin-bottom: 60px;
    padding-bottom: 20px;
    font-family: "Nunito", sans-serif;
  font-weight: 400;
  color: #fff;
}
section .title::before{
    content: "";
    position: absolute;
    bottom: 0px;
    left: 50%;
    width: 180px;
    height: 3px;
    background: #ffffff;
    transform: translateX(-50%);
}
section .title::after{
    position: absolute;
    bottom: -8px;
    left: 50%;
    font-size: 20px;
    color: crimson;
    padding: 0 3px;
    background: #000000;
    transform: translateX(-50%);
}

/* navbar styling */
.navbar{
    
    margin: 15px;
    border-radius: 10px;
    position: fixed;
    width: calc(100% - 30px);
    z-index: 999;
    padding: 10px 0;
    font-family: "Nunito", sans-serif;
  font-weight: 400;
    transition: all 0.3s ease;
}
.navbar.sticky{
    padding: 12px 0;
    padding-bottom: 12px;
    margin: 15px;
    border-radius: 10px;
    color: #000;
    background: #ffffff;
    box-shadow: rgba(17, 17, 26, 0.1) 0px 4px 16px, rgba(17, 17, 26, 0.05) 0px 8px 32px;
}
.navbar.sticky .menu li a{
    color: #000;
}
.navbar.sticky .logo a{
    color: #000;
}
.navbar .max-width{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.navbar .logo a{
    color: #000000;
    font-size: 35px;
    font-weight: 600;
}
.navbar .logo a span{
    color: #0B60B0;
    transition: all 0.3s ease;
}
.navbar.sticky .logo a span{
    color: #000000;
    background-color: #fff;
}
.navbar .menu li{
    list-style: none;
    display: inline-block;
}
.navbar .menu li a{
    display: block;
    color: #000;
    font-size: 18px;
    font-weight: 500;
    margin-left: 25px;
    transition: color 0.3s ease;
}
.navbar .menu li a:hover{
    color: crimson;
}
.navbar.sticky .menu li a:hover{
    color: crimson;
}

/* menu btn styling */
.menu-btn{
    color: #000000;
    font-size: 23px;
    cursor: pointer;
    display: none;
}
.navbar.sticky .menu-btn{
    color: #000;
}
.scroll-up-btn{
    position: fixed;
    height: 45px;
    width: 42px;
    background: #0B60B0;
    right: 30px;
    bottom: 10px;
    text-align: center;
    line-height: 45px;
    color: #fff;
    z-index: 9999;
    font-size: 30px;
    border-radius: 6px;
    border-bottom-width: 2px;
    cursor: pointer;
    opacity: 0;
    pointer-events: none;
    transition: all 0.3s ease;
}
.scroll-up-btn.show{
    bottom: 30px;
    opacity: 1;
    pointer-events: auto;
}
.scroll-up-btn:hover{
    filter: brightness(90%);
}


/* home section styling */
.home{
    display: flex;
    background: url("images/hero_banner.png") no-repeat center;
    height: 100vh;
    color: #fff;
    min-height: 500px;
    background-size: cover;
    background-attachment: fixed;
    font-family: "Nunito", sans-serif;
  font-weight: 400;
}
.home .max-width{
  width: 100%;
}
.home .max-width .row{
  margin-right: 0;
}
.home .home-content .text-1{
    color: #000;
    font-size: 27px;
}
.home .home-content .text-2{
    color: #000;
    font-size: 75px;
    font-weight: 600;
    margin-left: -3px;
}
.home .home-content .text-3{
    color: #000;
    font-size: 40px;
    margin: 5px 0;
}
.home .home-content .text-3 span{
    color: #0B60B0;
    font-weight: 500;
}
.home .hire-me a{
    display: inline-block;
    padding: 10px 25px;
    margin-top: 20px;
    font-size: 16px;
    text-align: center;
    text-decoration: none;
    color: #000000;
    background-color: #fff;
    border: 2px solid #000000;
    border-radius: 4px;
    box-shadow: 3px 3px 0px #333333;
    transition: all 0.3s ease;
    cursor: pointer;
}
.home .hire-me a:hover{
    background-color: #000000;
    color: #ffffff;
    border: 2px solid #ffffff;
    box-shadow: 3px 3px 0px #ffffff;
}
.home .hire-me a:active {
    background-color: #fff;
    box-shadow: none;
    transform: translateY(4px);
  }

.social-links{
    padding-top: 20px;
     
   }
.social-links a{
       display: inline-block;
       padding-top: 10px;
       height: 40px;
       width: 40px;
       padding: 8px;
       background-color:#ffffff;
       margin:0 10px 10px 0;
       text-align: center;
       border: solid 2px #000000;
       border-radius:6px;
       color:#000;
       transition: all 0.5s ease;
       
   }
.social-links a:hover{
       background-color:transparent;
       border:solid 2px  #000000;
       color: #000000;
       
   }



   .footer-col .social-links{
    padding-top: 20px;
     
   }

   .footer-col .social-links a{
       display: inline-block;
       padding-top: 10px;
       height: 40px;
       width: 40px;
       padding: 8px;
       background-color:#ffffff;
       margin:0 10px 10px 0;
       text-align: center;
       border: solid 2px #ffffff;
       border-radius:6px;
       color:#000;
       transition: all 0.5s ease;
       
   }

.footer-col .social-links a:hover{
       background-color:transparent;
       border:solid 2px  #fff;
       color: #fff;
       
   }
   @media (max-width: 947px) {
    .home .hire-me a{
        display: inline-block;
        padding: 8px;
    }
      
    
   } 
  
/* Media query for desktop screens */
@media (max-width: 768px) {
    .home {
        height: 70vh; 
        /* background-size: 100% auto;  */
        background-attachment:fixed;
    }
}

/* about section styling */
.about .title::after{
    content: "who I am";
    color: crimson;
}
.about .about-content .left{
    width: 45%;
}
.about .about-content .left img{
    height: 500px;
    width: 400px;
    object-fit: cover;
    border-radius: 0px;
    
}
.about .about-content .right{
    width: 55%;
}
.about .about-content .right .text{
    color: #fff;
    font-size: 25px;
    font-weight: 600;
    margin-bottom: 10px;
}
.about .about-content .right .text span{
    color: #1e90e1;
}
.about .about-content .right p{
  color: #fff;
    text-align: justify;
}
.about .about-content .right a{
    display: inline-block;
    background: #fff;
    color: #000000;
    font-size: 20px;
    font-weight: 500;
    padding: 6px 18px;
    margin-top: 20px;
    border-radius: 6px;
    border: 2px solid #fff;
    transition: all 0.3s ease;
}
.about .about-content .right a:hover{
    color: #0B60B0;
    background: none;
}
.download-button {
    margin-top: 20px;
    position: relative;
    width: 160px;
    height: 40px;
    cursor: pointer;
    display: flex;
    align-items: center;
    border: 1px solid #fff;
    background-color: #fff;
    overflow: hidden;
  }
  
  .download-button, .button__icon, .button__text {
    transition: all 0.3s;
  }
  
  .download-button .button__text {
    transform: translateX(22px);
    color: #000000;
    font-weight: 600;
  }
  
  .download-button .button__icon {
    position: absolute;
    transform: translateX(119px);
    height: 100%;
    width: 39px;
    background-color: #e7e7e7;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .download-button .svg {
    width: 20px;
    fill: #000000;
  }
  
  .download-button:hover {
    background: #fff;
  }
  
  .download-button:hover .button__text {
    color: transparent;
  }
  
  .download-button:hover .button__icon {
    width: 160px;
    transform: translateX(0);
  }
  
  .download-button:active .button__icon {
    background-color: #e7e7e7;
  }
  
  .download-button:active {
    border: 1px solid #e7e7e7;
  }



/* services section styling */
.services, .teams{
    color:#fff;
    background: #111;
}
.services .title::before,
.teams .title::before{
    background: #fff;
}
.services .title::after,
.teams .title::after{
    background: #111;
    content: "what I provide";
}
.services .serv-content .card {
    width: calc(50% - 20px);
    background: #ffffff;
    text-align: left;
    border: 1px solid #fff;
    border-radius: 0;
    padding: 50px 25px;
    margin-top: 30px;
    cursor: pointer;
    transition: all 0.3s ease;
}

.services .serv-content .card:hover {
    background: #000000;
}

.services .serv-content .card .box {
    transition: all 0.3s ease;
}

.services .serv-content .card:hover .box {
    transform: scale(1.05);
}

.services .serv-content .card .text {
    color: #000;
    font-size: 25px;
    font-weight: 500;
    margin: 10px 0 7px 0;
    transition: color 0.3s ease;
}

.services .serv-content .card:hover .text {
    color: #ffffff;
}

.services .serv-content .card p {
    color: #000;
    transition: color 0.3s ease;
}

.services .serv-content .card:hover p {
    color: #ffffff;
}


/* skills section styling */

.skills .title::after{
    content: "what I know";
    color: crimson;
}
.skills .skills-content .column{
    width: calc(50% - 30px);
}
.skills .skills-content .left .text{
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 10px;
    color: #ffffff;
}
.skills .skills-content .left p{
    text-align: justify;
    color: #fff;
}
.skills .skills-content .left a{
    display: inline-block;
    background: #0B60B0;
    color: #fff;
    font-size: 18px;
    font-weight: 500;
    padding: 8px 16px;
    margin-top: 20px;
    border-radius: 6px;
    border: 2px solid #0B60B0;
    transition: all 0.3s ease;
}
.skills .skills-content .left a:hover{
    color: #0B60B0;
    background: none;
}
.skills .skills-content .right .bars{
    margin-bottom: 15px;
    color: #FFF;
}
.skills .skills-content .right .info{
    display: flex;
    margin-bottom: 5px;
    align-items: center;
    justify-content: space-between;
}
.skills .skills-content .right span{
    color: #fff;
    font-weight: 500;
    font-size: 18px;
}
.skills .skills-content .right .line{
    height: 5px;
    width: 100%;
    background: lightgrey;
    position: relative;
}
.skills .skills-content .right .line::before{
    content: "";
    position: absolute;
    height: 100%;
    left: 0;
    top: 0;
    background: #1076c0;
}
.skills-content .right .react::before{
    width: 70%;
}
.skills-content .right .node::before{
    width: 70%;
}
.skills-content .right .html::before{
    width: 90%;
}
.skills-content .right .css::before{
    width: 80%;
}
.skills-content .right .js::before{
    width: 70%;
}
.skills-content .right .php::before{
    width: 60%;
}
.skills-content .right .mysql::before{
    width: 60%;
}


/*   Recent Works    */
.recent_works{
    background-color: #111;
}
.projects {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 0 80px;
    font-family: "Nunito", sans-serif;
    width: 100%;
}

.recent_works .title::after {
    content: "what I have done";
    margin-top: 10px;
    background-color: #111;
}

.projects .project-column {
    flex: 0 0 45%;
    margin: 10px;
    margin-top: 30px;
    background-color: #111;
    padding: 10px;
    border-radius: 10px;
}
.projects .project-column .image{
    padding: 0;
    border-radius: 10px;
}
img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

.projects .project-column h2 {
    font-size: 24px;
    margin-top: 10px;
    margin-bottom: 6px;
    color: #fff;
    font-weight: 400;
}

.projects .project-column p {
    color: #fff;
}

.projects .project-column a {
    display: block;
    margin-top: 10px;
    color: #007bff;
    text-decoration: none;
}

@media screen and (max-width: 767px) {
    .recent_works .projects .project-column {
        flex: 0 0 100%; /* 100% width on smaller screens */
    }
    

    .projects {
        padding: 0 10px;
    }
}
@media screen and (min-width: 768px) and (max-width: 991px) {
    .projects {
        padding: 0 30px;
    }
}

/*      Articles       */
.articles .title::after {
    content: "what I have written";
    margin-top: 10px;
    background-color: #000000;
}
.blog {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 0 80px;
    font-family: "Nunito", sans-serif;
    width: 100%;
}

.blog .blog-column {
    flex: 0 0 45%;
    margin: 10px;
    margin-top: 30px;
    background-color: #ffffff;
    padding: 15px;
    border: 1px solid #fff;
}
.blog .blog-column:hover {
    color: #fff;
    background-color: #000000;
    transition: all 0.3s ease;
    border: 1px solid #fff;
}

.blog .blog-column h2 {
    font-size: 24px;
    margin-top: 10px;
    margin-bottom: 6px;
    color: #000000;
    font-weight: 400;
}
.blog .blog-column h4{
    color: crimson;
    font-weight: 400;
    font-size: 14px;
    margin-bottom: -6px;
}

.blog .blog-column:hover h2{
    color: #fff;
}

.blog .blog-column p {
    color: #000000;
}
.blog .blog-column:hover p{
    color: #fff;
}

.blog .blog-column a {
    display: block;
    margin-top: 10px;
    color: #007bff;
    font-size: 13px;
    text-decoration: none;
}

.articles .view-more {
    margin-top: 30px;
    text-align: center;
}

.articles .view-more a {
    font-family: "Nunito", sans-serif;
    display: inline-block;
    background-color: #fff;
    text-align: center;
    color: #000;
    padding: 12px 40px;
    border: 1px solid #000;
    border-radius: 50px;
}
.articles .view-more a:hover{
    color: #fff;
    background-color: #000000;
    border: 1px solid #ffffff;
    transition: all 0.4s ease;
}

@media screen and (max-width: 767px) {
    .articles .blog .blog-column {
        flex: 0 0 100%; /* 100% width on smaller screens */
    }
    

    .blog {
        padding: 0 10px;
    }
}
@media screen and (min-width: 768px) and (max-width: 991px) {
    .blog {
        padding: 0 30px;
    }
}


/* teams section styling */

/* .teams .carousel .card{
    background: #222;
    border-radius: 6px;
   
    text-align: center;
    overflow: hidden;
    transition: all 0.3s ease;
}

.teams .carousel .card .box{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
}
.teams .carousel .card:hover .box{
    transform: scale(1);
}
.teams .carousel .card .text{
    font-size: 25px;
    font-weight: 500;
    margin: 10px 0 7px 0;
    
}
.teams .carousel .card p{
    margin-bottom: 10px;
}
.teams .carousel .card img{
    height: 200px;
    width: 100%;
    object-fit: cover;
    border-radius: 5px;
    
    transition: all 0.3s ease;
}
.teams .carousel .card:hover img{
    border-color: #fff;
}
.owl-dots{
    text-align: center;
    margin-top: 20px;
}
.owl-dot{
    height: 13px;
    width: 13px;
    margin: 0 5px;
    outline: none!important;
    border-radius: 50%;
    border: 2px solid #fff!important;
    transition: all 0.3s ease;
}
.owl-dot.active{
    width: 35px;
    border-radius: 14px;
}
.owl-dot.active,
.owl-dot:hover{
    background: #fff!important;
}

/*        Technology Columns    
.technology {
    display: flex;
    align-items: flex-start;
}
.technology p{
    font-size: 10px;
    line-height: 2px;
    margin-top: 11px;
}

.tech-col-w, .tech-col-e, .tech-col-c, .tech-col-1, .tech-col-2, .tech-col-3, .tech-col-4 {
    flex: 1;
    padding-left: 5px;
    padding-right: 5px;
    margin-top: 5px;
    margin-left: 5px;
    text-align: center;
    justify-content: center;
    border: 1px solid #e7e7e7;
    border-radius: 20px;
}
.tech-col-w{
    background-color: #0675C4;
}
.tech-col-e{
    background-color: #92003B;
}
.tech-col-1{
    background-color: #DD4B25;
}
.tech-col-2{
    background-color: #254BDD;
}
.tech-col-3{
    background-color: #E8D44D;
}
.tech-col-4{
    background-color: #7377AD;
}

.live-preview{
    background-color: #fff;
    margin-bottom: 15px;
    border-radius: 5px;
    padding: 8px 60px;
    border: 1px solid #000;
}
.live-preview:hover{
    background-color: transparent;
    border: 1px solid #ffffff;
    transition: all 0.3s ease;
}
.live-preview a{
    color: #000000;
}
.live-preview:hover a{
    color: #fff;
} */

/* contact section styling */


/* Define the row */
.row {
    display: flex;
    flex-wrap: wrap; /* Enable wrapping of columns */
}

/* Define the left column with a default width of 60% */
.column-60 {
    flex: 0 0 calc(70%); /* Initial width of 60%, does not grow or shrink */
    display: flex;
    flex-direction: column;
    justify-content: center; /* Vertically center-align content */
    text-align: left;
}

/* Define the right column with a default width of 40% */
.column-40 {
    flex: 0 0 calc(30%); /* Initial width of 40%, does not grow or shrink */
    
    
        
}

/* Media query for screens narrower than 768px */
@media (max-width: 768px) {
    .column-60, .column-40 {
        flex: 0 0 100%; /* Both columns take full width on smaller screens */
        padding: 25px;
    }
    .row {
        padding: 20px;
        padding-bottom: 40px;
    }
}

/* Media query for tablet screens (e.g., iPad Air) */
@media (min-width: 769px) and (max-width: 1024px) {
    .row {
        padding: 40px 20px; /* Adjust padding for tablet screens */
    }
}

/* Media query for desktop screens */
@media (min-width: 1025px) {
    .row {
        padding: 40px 180px 80px; /* Apply padding to the row for desktop screens */
    }
}

.contact{
    background-color: #111;
}
.contact .title::after{
    content: "Get in Touch";
    background-color: #111;
}
.contact .contact-content .column{
    width: calc(50% - 30px);
}
.column-60 .text{
    color: #ffffff;
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 10px;
}
.column-60 p{
    color: #ffffff;
    padding-right: 0px;
    text-align: justify;
}
.column-60 .left .icons{
    margin: 10px 0;
}
.column-60 .i-row{
    display: flex;
    height: 65px;
    align-items: center;
}
.column-60 .i-row .info{
    margin-left: 30px;
    color: #ffffff;
}
.column-60 .i-row i{
    font-size: 25px;
    color: #ffffff;
}
.column-60 .info .head{
    font-weight: 500;
}
.column-60 .info .sub-title{
    color: #efefef;
}
.column-40 form .fields{
    display:block;
}
.column-40 form .field,
.column-40 form .fields .field{
    height: 45px;
    width: auto;
    margin-bottom: 25px;
    margin-left: 10px;
    margin-right: 10px;
}
.column-40 form .textarea{
    height: 80px;
    width: auto;
}
.column-40 form .name{
    margin-right: 10px;
}
.column-40 form .field input,
.column-40 form .textarea textarea{
    height: 100%;
    width: 100%;
    border: 1px solid lightgrey;
    border-radius: 6px;
    outline: none;
    padding: 0 15px;
    font-size: 17px;
    font-family: "Nunito", sans-serif;
  font-weight: 400;
    transition: all 0.3s ease;
}
.column-40 form .field input:focus,
.column-40 form .textarea textarea:focus{
    border-color: #b3b3b3;
}
.column-40 form .textarea textarea{
  padding-top: 10px;
  resize: none;
}
.column-40 form .button-area{
  display: flex;
  align-items: center;
}
.column-40 form .button-area button{
    display: inline-block;
    padding: 8px 15px;
    margin-left: 10px;
    font-size: 16px;
    text-align: center;
    text-decoration: none;
    color: #fff;
    background-color: #0B60B0;
    border: 2px solid #000;
    border-radius: 4px;
    box-shadow: 3px 3px 0px #000;
    transition: all 0.3s ease;
    cursor: pointer;
}
.column-40 form .button-area button:hover{
        background-color: #fff;
        color: #000;
        border: 2px solid #000;
        box-shadow: 3px 3px 0px #000;
}
.column-40 form .button-area button:active {
    background-color: #fff;
    box-shadow: none;
    transform: translateY(4px);
  }

.form-head h2{
    padding-top: 30px;
    font-family: "Nunito", sans-serif;
  font-weight: 400;
  text-align: center;
  padding-bottom: 5px;
  background-color: #0B60B0;
  color: #fff;
  margin-bottom: 20px;
}

  .iphone-12-container {
    width: 290px;
    height: 520px; 
    border-radius: 40px; 
    box-shadow: rgba(255, 255, 255, 0.174) 0px 15px 25px, rgba(255, 255, 255, 0.174) 0px 5px 10px;
    margin: 0px auto;
    overflow: hidden; 
    position: relative; 
    border: 6px solid #000000;
    box-sizing: border-box;
    background-color: #fff;
}

.notch {
    width: 140px;
    height: 25px; 
    background-color: #000;
    position: absolute;
    top: 0px;
    left: 50%;
    border-end-end-radius: 10px;
    border-bottom-left-radius: 10px;
    transform: translateX(-50%); 
}

.speaker {
    width: 40px; 
    height: 5px; 
    background-color: #313131;
    position: absolute;
    top: 8px;
    border-radius: 5px;
    left: 50%;
    transform: translateX(-50%);
}
.cam {
    width: 13px; 
    height: 13px; 
    background-color: #313131;
    position: absolute;
    top: 4px; 
    border-radius: 50px;
    left: 65%;
    transform: translateX(-35%); 
}

/* Style the screen area */
.iphone-12-container::before {
    content: "";
    display: block;
    width: 100%;
    height: 100%;
    border-radius: 25px 25px 0 0; 
    position: absolute;
    top: 0px;
    left: 0;
    right: 0;
    margin: auto;
    box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.2);
    z-index: -1;
}


/* Section: Footer */
.sec-margin{
    height: 2px; 
    background-color: #333;
}
footer{
    line-height: 1.5;
    font-family: "Nunito", sans-serif;
  font-weight: 400;
}
*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}
.container-footer{
    max-width: 85%;
    margin:auto;
   
}
.row-footer{
    display: flex;
    flex-wrap: wrap;
}
ul{
    list-style: none;
}
.footer{
    background-color: #000000;
    padding: 40px 0 40px 0;
}
.footer-col{
   width: 25%;
   padding: 0 15px;
}
.footer-col img{
  
  height: auto;
  width: 60%;
  padding: 4px ;
  border-radius: 3px;
}
.footer-col h4{
    font-size: 25px;
    color: #fff;
    text-transform: capitalize;
    margin-bottom: 18px;
    font-weight: 300;
    position: relative;
}

.footer-col ul li:not(:last-child){
    margin-bottom: 5px;
}
.footer-col ul li{
  list-style-type: none;
  color: white;
  
}
.footer-col ul li a{
    font-size: 14px;
    text-transform: capitalize;
    color: whitesmoke;
    text-decoration: none;
    font-weight: 400;
    
    transition: all 0.3s ease;
}
.footer-col ul li a:hover{
    color: #ffffff;
    padding-left: 6px;
}
/* .footer-col .social-links{
 padding-top: 20px;
  
}
.footer-col .social-links a{
    display: inline-block;
    padding-top: 10px;
    height: 40px;
    width: 40px;
    background-color:#f35a23;
    margin:0 2px 10px 0;
    text-align: center;
    
  
    border-radius: 100%;
    color: whitesmoke;
    transition: all 0.5s ease;
}
.footer-col .social-links a:hover{
   
     transform:scale(1.1);
   
     transition: ease-in all 0.2s;
     
} */
.footer-copyright h5{
    margin-bottom: 0px;
    font-size: 12px;
    text-align: center;
    color:whitesmoke;
    font-weight: 500;
  }
  .footer-copyright{
    background-color: #000000;
    padding: 10px;
  }
/* Footer */
@media(max-width: 767px){
    .footer{
        background-color: #111;
    }
    .footer-col{
      width: 50%;
      margin-bottom: 30px;
  }
  
  }
  @media(max-width: 574px){
    .footer{
        background-color: #111;
    }
    .footer-col{
      width: 100%;
  }
  }




  /*             Blog Posts     */
#blog-posts{
    margin-top: 50px;
  }
#blog-posts.max-width h1{
    color: #fff;
  }

/* responsive media query start */
@media (max-width: 1104px) {
    .about .about-content .left img{
        height: 400px;
        width: 350px;
    }
}

@media (max-width: 991px) {
    .max-width{
        padding: 0 50px;
    }
}
@media (max-width: 947px){
    
    .menu-btn{
        display: block;
        z-index: 999;
    }
    .menu-btn i.active:before{
        content: "\f00d";
    }
    .navbar .menu{
        position: fixed;
        height: 100vh;
        width: 60%;
        left: -100%;
        top: 0;
        background: #ffffff;
        text-align: left;
        padding-left: 20px;
        padding-top: 80px;
        transition: all 0.5s ease;
    }
    .navbar .menu.active{
        left: 0;
    }
    .navbar .menu li{
        display: block;
    }
    .navbar .menu li a{
        display: inline-block;
        margin: 20px 0;
        font-size: 25px;
    }
    .home .home-content .text-2{
        font-size: 70px;
    }
    .home .home-content .text-3{
        font-size: 35px;
    }
    .home .home-content a{
        font-size: 20px;
        padding: 10px 30px;
    }
    .max-width{
        max-width: 930px;
    }
    .about .about-content .column{
        width: 100%;
    }
    .about .about-content .left{
        display: flex;
        justify-content: center;
        margin: 0 auto 60px;
    }
    .about .about-content .right{
        flex: 100%;
    }
    .services .serv-content .card{
        width: calc(50% - 10px);
        margin-bottom: 20px;
    }
    .skills .skills-content .column,
    .contact .contact-content .column{
        width: 100%;
        margin-bottom: 35px;
    }
}

@media (max-width: 690px) {
    .max-width{
        padding: 0 23px;
    }
    .home .home-content .text-2{
        font-size: 60px;
    }
    .home .home-content .text-3{
        font-size: 32px;
    }
    .home .home-content a{
        font-size: 16px;
    }
    .services .serv-content .card{
        width: 100%;
    }
}

@media (max-width: 500px) {
    .home .home-content .text-2{
        font-size: 50px;
    }
    .home .home-content .text-3{
        font-size: 27px;
    }
    .about .about-content .right .text,
    .skills .skills-content .left .text{
        font-size: 19px;
    }
    .contact .right form .fields{
        flex-direction: column;
    }
    .contact .right form .name,
    .contact .right form .email{
        margin: 0;
    }
    .right form .error-box{
       width: 150px;
    }
    .scroll-up-btn{
        right: 15px;
        bottom: 15px;
        height: 38px;
        width: 35px;
        font-size: 23px;
        line-height: 38px;
    }
}
