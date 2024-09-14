<template>
 <header>
        <h2>Toto je navod ako napisat front end</h2>
        <nav>
            <a href="index.html">Home</a> | 
            <a href="services.html">Services</a> | 
            <a href="contact.html">Contact</a> | 
            <a href="#">Privacy Policy</a>
          </nav>
    </header>
 

    
   
   </template>
   
   <script>
   export default {
     name: 'HelloWorld',
     props: {
       msg: String
     }
   }
   </script>
   
   <!-- Add "scoped" attribute to limit CSS to this component only -->
   <style scoped>
   h4 {
       color: darkred;
   }
   
   article {
       border: 2px solid darkviolet;
       border-radius: 15px;
       margin: 20px;
       padding: 10px;
   }
   
   .non-article-heading {
       color: blue;
   }
   
   .footer-image {
       width: 20%;
   }
   
   .article-image {
       width: 20ex;
       display: block;
       margin-left: auto;
       margin-right: auto;
       border-radius: 50px;
   }
   
   footer {
   text-align: center;
   background-color: aliceblue;
   padding: 10px;
   }
   
   header {
       padding: 10px;
       text-align: center;
       background-color: aliceblue;
   }
   
   body {
       margin: 0;
   }
   
   a {
       color: rgb(57, 57, 57);
   }
   nav {
       list-style-type: none;
       padding: 0;
       margin: 0;
       display: inline-block;
       margin-right: 15px;
       height: 2em;
   }
   
   
   nav a {
       font-size: 16px;
       text-decoration: none;
       transition: font-size 0.3s ease;
   }
   
   nav a:hover {
       font-size: 20px;
       color: darkmagenta;
   }
   
   
   .contact-form {
       background-color: #fff;
       padding: 20px;
       border-radius: 8px;
       box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
       width: 100%;
       max-width: 400px;
       margin-left: auto;
       margin-right: auto;
   }
   .contact-form h2 {
       margin-bottom: 20px;
       font-size: 24px;
       text-align: center;
   }
   .contact-form input[type="text"],
   .contact-form input[type="email"],
   .contact-form textarea {
       width: 100%;
       padding: 10px;
       margin-bottom: 15px;
       border: 1px solid #ccc;
       border-radius: 4px;
       box-sizing: border-box;
       font-size: 16px;
   }
   .contact-form textarea {
       height: 150px;
       resize: vertical;
   }
   .contact-form button {
       width: 100%;
       padding: 10px;
       background-color: #4CAF50;
       color: white;
       border: none;
       border-radius: 4px;
       font-size: 18px;
       cursor: pointer;
   }
   .contact-form button:hover {
       background-color: #45a049;
   }
   </style>
   