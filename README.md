
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" Club content="width=device-width, initial-scale=1.0">
  <title>Deccan Gymkhana Sports Club </title>
  <style>
   body {
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      background-color: #f4f7fb;
      color: #333;
      scroll-behavior: smooth;
    }

  header {
      background: linear-gradient(rgba(0,123,255,0.7), rgba(0,123,255,0.7)), 
                  url('https://images.unsplash.com/photo-1517649763962-0c623066013b?auto=format&fit=crop&w=1600&q=80') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }

  header h1 {
      font-size: 2.8em;
      margin-bottom: 10px;
    }

  header p {
      font-size: 1.2em;
      letter-spacing: 1px;
    }

   
  nav {
      background-color: #0056b3;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 12px;
      position: sticky;
      top: 0;
      z-index: 100;
    }

  nav a {
      color: white;
      text-decoration: none;
      margin: 10px 20px;
      font-weight: bold;
      position: relative;
      transition: 0.3s;
    }

  nav a::after {
      content: "";
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 0;
      height: 3px;
      background: #ffcc00;
      transition: width 0.3s;
    }

  nav a:hover::after {
      width: 100%;
    }

 
  section {
      background-color: white;
      margin: 30px auto;
      padding: 30px;
      border-radius: 10px;
      max-width: 900px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

  section h2 {
      text-align: center;
      color: #007bff;
      border-bottom: 3px solid #007bff;
      display: inline-block;
      padding-bottom: 5px;
      margin-bottom: 20px;
    }

   
  .activities {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

  .card {
      background: #f9f9f9;
      border-radius: 10px;
      padding: 20px;
      width: 250px;
      text-align: center;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

  .card:hover {
      transform: translateY(-5px);
    }

  .card h3 {
      color: #0056b3;
    }

    
  form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

  form input, form textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1em;
    }

  form button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.3s;
    }

  form button:hover {
      background-color: #0056b3;
    }

  
  footer {
      background: linear-gradient(90deg, #007bff, #0056b3);
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

 
  .activities {
        flex-direction: column;
        align-items: center;
      }
      header h1 {
        font-size: 2em;
      
      }
</style>     
      
      
      
      
      
    

  
</head>
<body>
  <header>
    <h1>Deccan Gymkhana Sports Club</h1>
    <p> Play , Train , Maintain Your Fitness , Have Fun</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#activities">Activities</a>
    <a href="#contact">Get in touch</a>
  </nav>
  <section id="about">
    <h2>About Us</h2>
    <p>
       Our club was founded in 2015 by a small group of sports enthusiasts and 
       represents fitness and teamwork. To encourage sportsmanship in the 
       neighborhood, we frequently hold training camps, competitions, and friendly games.
    </p>   
  </section>
  <section id="home">
    <h2>Welcome to Our Club</h2>
    <p>
       Greetings from Deccan Gymkhana Sports Club! Sports like football, cricket, 
       and badminton are great ways for people of all ages to stay active. Join the 
       community, excitement, and energy every weekend!

    </p>
  </section>
    <section id="activities">
    <h2>Our Activities</h2>
    <div class="activities">
      <div class="card">
        <h3>Football</h3>
        <p>Join us every Sunday for football matches at our ground. All players are welcome!</p>
      </div>
      <div class="card">
        <h3>Cricket</h3>
        <p>Every Saturday, all age groups participate in weekend cricket matches and practice.</p>
      </div>
      <div class="card">
        <h3>Badminton</h3>
        <p>Every Wednesday, there are indoor badminton nights, which are enjoyable and excellent for fitness!</p>
      </div>
    </div>
  </section>
    <section id="contact">
    <h2>Get in touch with us</h2>
    <p>Please use the form below if you would like to participate or if you have any questions. We will respond to you as soon as possible.</p>

<form onsubmit="return showMessage(event)">
      <input type="text" id="name" placeholder="Your Name" required>
      <input type="email" id="email" placeholder="Your Email" required>
      <textarea id="message" rows="4" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>

  <p id="thankyou" style="display:none; color:green; text-align:center; margin-top:10px;">
      ✅ I'm grateful. We will respond to you as soon as possible.
    </p>

  <p style="text-align:center; margin-top:15px;">
      📧 sunnypandey2029@gmail.com
      ☎️ +91 6307217313
      📍 Deccan Gymkhana Sports Academy in Pune
    </p>
  </section>

  <footer>
    <p>Deccan Gymkhana Sports Club | Designed by Sunny Pandey</p>
  </footer>  
</body>
</html>

