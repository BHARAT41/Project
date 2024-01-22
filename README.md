<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact</title>
    <link rel="stylesheet" href="index.css" />
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet"/>
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet" />
  </head>
  <body>
    <section class="header">
      <a href="home.html" class="logo">
        <img width="40" height="38" src="https://img.icons8.com/3d-fluency/94/hamburger.png" alt=""/>
        FoodZone
      </a>
      <ul class="navbar-links">
          <li><a href="home.html" target="_self">Home</a></li>
          <li><a href="servies.html" target="_self">Service</a></li>
          <li><a href="About.html" target="_self">About</a></li>
          <li><a href="contact.html" target="_self">contact</a></li>
          <li><a href="team.html" target="_self">Team</a></li>
      </ul>
      <div class="header-icons">
          <i class='bx bx-search' id="search-icon"></i>
          <i class='bx bx-cart-alt' id="cart-icon"></i>
          <i class='bx bx-user' id="user-icon"></i>
      </div>
  </section>
    <div class="container">
      <table>
        <form action="">
    
        <tr>
          <td class="contactHead">
            <p>Contact As</p>
          </td>
        </tr>
        
          <tr>
            <td>
              <label for="Name" class="label">Enter Your Name</label><br>
              <input type="text" id="input" placeholder="Your Name" required/>
            </td>
          </tr>
          <tr>
            <td>
              <label for="Email" class="label">Enter Your Email</label><br>
              <input type="email" id="input" placeholder="Your Email" required/>
            </td>
          </tr>
    
          <tr>
            <td>
              <label for="number" class="label">Enter Your Contact</label><br>
              <input type="text" id="input" placeholder="Your Contact" pattern="[0-9]{10}" maxlength="10" required/>
            </td>
          </tr>
          
          <tr>
            <td>
                <label for="Address" class="label">Enter Your Address</label><br>
                <input type="text" id="input" placeholder="Your Address" required>
            </td>
          </tr>
          <tr>
            <td class="button">
               <input type="submit" name="submit" value="Submit" class="bt"><br>
            </td>
          </tr> 
        </form>
    </table>
    </div>
  

  <section class="footer" style="margin:250px 0 0 0; background-color: #ebeff2;">
    <div class="footer-box">
      <h2>FoodZone</h2>
      <div class="social">
        <a href="#"><i class="bx bxl-facebook"></i></a>
        <a href="#"><i class="bx bxl-instagram"></i></a>
        <a href="#"><i class="bx bxl-twitter"></i></a>
      </div>
    </div>

    <div class="footer-box">
      <h3>Support</h3>
      <ul>
        <li><a href="#">Help & Support</a></li>
        <li><a href="#">Return Policy</a></li>
        <li><a href="#">Terms of Use</a></li>
        <li><a href="#">FAQ</a></li>
      </ul>
    </div>
    <div class="footer-box">
      <h3>Our Branches</h3>
      <ul>
        <li><a href="#">Gujarat</a></li>
        <li><a href="#">Mumbai</a></li>
        <li><a href="#">Banglore</a></li>
        <li><a href="#">Delhi</a></li> 
      </ul>
    </div>
  </section>

    <div class="copyright">
      <p>&#169; FoodZone All Right Reserved</p>
    </div>




   
  </body>
</html>













@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500&family=Roboto:wght@100;300;400&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
  scroll-behavior: smooth;
  font-family: "Poppins", sans-serif;
}

:root {
  --main-color: #fda702;
  --second-color: #ebeff2;
  --text-color: #02171d;
  --bg-color: #fff;
  --box-shadow: 2px 2px 10px 4px rgb(154, 154, 164);
}

.btn{
  padding: 10px 22px;
  background: var(--main-color);
  color: var(--bg-color);
  font-weight: 500;
  text-transform: uppercase;
}

.btn:hover {
  background: var(--text-color);
  transition: 0.8s;
}

section {
  padding: 40px 100px;
}

.header {
  position: fixed;
  width: 100%;
  top: 0;
  right: 0;
  display: flex;
  z-index: 1000;
  justify-content: space-between;
  align-items: center;
  padding: 20px 100px;
  transition: 0.5s linear;
  background: var(--bg-color);
}

.logo {
  display: flex;
  align-items: center;
  font-size: 25px;
  font-weight: 600;
  column-gap: 10px;
  color: var(--text-color);
}

.navbar-links {
  display: flex;
  column-gap: 43px;
  position: absolute;
  left: 40%;
}

.navbar-links a {
  font-size: 16px;
  font-weight: 500;
  color: var(--text-color);
}

.navbar-links a:hover {
  color: var(--main-color);
}

.header-icons {
  font-size: 22px;
  cursor: pointer;
  position: absolute;
  right: 60px;
}


.home {
  width: 100%;
  min-height: 100vh;
  display: flex;
  justify-content: space-around;
  align-items: center;
  gap: 30px;
  background: var(--second-color);
}

.home-text h1 {
  font-size:55px;
  margin-bottom: 16px;
}

.heading {
  text-align: center;
}

.heading h1 {
  font-size: 25px;
  font-weight: 600;
  text-transform: capitalize;
  color: var(--text-color);
}

.heading span {
  padding: 10px 7px;
  background: var(--main-color);
  color: var(--bg-color);
  font-weight: 500;
  display: inline-block;
  text-transform: uppercase;
}

 
.service {
  background: var(--second-color);
  display: flex;
  gap: 100px;
  justify-content: center;
  align-items: center;
  margin: 100px 0 0 0 ;
}
.service-title {
  border-bottom: 5px solid black;
}
.service-container {
  display: flex;
  gap: 32px;
  margin-top:50px;
}

.service-container .box,.userbox {
  background-color: white;
  position: relative;
  padding: 10px;
  margin-top: 10px;
  box-shadow: var(--box-shadow);
  border-radius: 60px;
  height: 290px;
  width: 230px;
}

.service-container .box img {
  height: 150px;
  width: 150px;
  border-radius: 800px;
  position: absolute;
  left: 45px;
  bottom: 200px;
}

.service-container .box .content {
  padding-right: 6px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-top: 100px;
}
.service-container .box .content p {
  font-size: 13px;
  font-weight: 500;
  text-align: center;
}

/*-----------------------     Team   --------------------------*/
.team {
  margin: 100px 0 90px 0;
}
.team-container {
  display: grid;
  grid-template-columns:1fr 1fr 1fr;
  gap: 16px;
  margin: 36px 0 45px 0;
}

.team-container .box {
  padding: 10px;
  border: 1px solid var(--text-color);
  border-radius: 8px;
  text-align: center;
  box-shadow: var(--box-shadow);
  transition: all 0.5s;
}

.team-container .box img {
  width: 90px;
  height: 90px;
  object-fit: cover;
  border-radius: 50%;
}

.team-container .box p {
  font-size: 14px;
  font-style: italic;
  margin: 8px 8px;
}

.team-container .box h2 {
  font-size: 1.2rem;
  font-weight: 600;
}

.team-container .box:hover {
  background: var(--text-color);
  color: var(--main-color);
}

/*------------------    Footer  -------------------*/
.footer {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 16px;
  color: var(--text-color);
}

.footer-box h2 {
  font-size: 30px;
  font-weight: 600;
  margin-bottom: 10px;
}

.footer-box p {
  font-size: 100;
  margin-bottom: 10px;
}

.social {
  display: flex;
  align-items: center;
  column-gap: 8px;
}

.social a .bx {
  font-size: 24px;
  color: var(--text-color);
  padding: 10px;
  background: var(--second-color);
  border-radius: 8px;
}

.social a .bx:hover {
  background: var(--main-color);
  color: var(--bg-color);
  transition: all 0.6s;
}

.footer-box h3 {
  font-size: 600;
  margin-bottom: 10px;
}

.footer-box ul li a {
  color: var(--text-color);
}

.footer-box ul li a:hover {
  color: var(--main-color);
}

.copyright {
  padding: 20px;
  text-align: center;
  color: var(--text-color);
}

/*----------------------------    About     ------------------------ */

.about img {
  margin-left: 70px;
  border-radius: 900px;
}



.contact {
  margin: 300px 0 0 400px;
}



/* Form Contact as */


.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

table {
  padding: 15px;
  height: 400px;
  width: 350px;
  background-color: white;
  border-radius: 10px;
  margin-top:100px;
}

.contactHead {
  height: 30px;
  width: 100%;
  margin: 10px 0 20px 30px;
}

.contactHead p {
  color: rgb(36, 6, 207);
  text-align: center;
  letter-spacing: 2px;
  font-weight: 500;
  font-size: 19px;
  margin: 3px 0 14px 5px;
}

table tr td input[type="text"],
table tr td input[type="email"] {
  outline: none;
  margin: 7px 0 2px 0;
  background: none;
  color: rgba(0, 0, 0, 0.877);
  border: 1px solid rgb(231, 225, 225);
  border-radius: 6px;
  padding: 10px;
}
table tr td input[type="text"]:hover,
table tr td input[type="email"]:hover{
    border-color: #3d24bb;
    transition: 0.5s;
}

#input {
  width: 100%;
}

.light-text {
  color: rgb(80, 71, 71);
  font-weight: 400;
  margin-right: 6px;
  font-size: 14px;
}


.label {
  color: rgb(0, 0, 0);
  font-weight: 500;
  font-size: 13px;
  margin-top: 50px;
  font-family:'Poppins';
}

.bt {
  border: none;
  background: none;
  margin: 10px 7px 0 40px;
  background-color: rgb(89, 89, 233);
  padding: 7px;
  border-radius: 5px;
  color: white;
  letter-spacing: 1px;
  width: 200px;
}
.bt:hover {
  background-color: #2e1f6a;
  transition: 0.6s;
}
.footer {
  font-size: 13px;
  margin: 7px 0px 0 22px; 
  text-decoration: none; 
  text-align: center;
}

