# html-css-website
# Features
- Multi-page website (Home, Event-detail, Participants, Contact)
- Responsive design
- Navigation between pages
- Styled using CSS
Multiple-page responsive website built with HTML and CSS

[index.html](https://github.com/user-attachments/files/26641357/index.html)
[event-detail.html](https://github.com/user-attachments/files/26641358/event-detail.html)
[participants.html](https://github.com/user-attachments/files/26641361/participants.html)
[contact.html](https://github.com/user-attachments/files/26641367/contact.html)
[style.css](https://github.com/user-attachments/files/26641374/style.css)


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: palevioletred;
    color:#FFFFFF;
    line-height: 1.6;
  }
  
  a {
    text-decoration: none;
    color: #FF3C38;
  }
  
  a:hover {
    text-decoration: underline;
    text-decoration-color: #d42e2b;
  }

  ul {
    list-style: none;
  }
  
  header {
    background-color: rgb(22, 21, 21);
    padding: 20px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  
  .logo {
    height: 120px;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    align-content: center;
  }
  
  nav ul li a {
    color: #FFFFFF;
    font-weight: bold;
    font-family: 'Montserrat', sans-serif;
    padding: 8px 12px;
    transition: background 0.3s;
  }
  
  .hero {
    position: relative;
    height: 100vh;
    overflow: hidden;
  }
  
  .background-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -1;
  }
  
  .hero-content {
    position: relative;
    z-index: 1;
    text-align: center;
    top: 50%;
    transform: translateY(-50%);
    color: #fff;
    padding: 0 20px;
  }
  
  .hero-content h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 3.5rem;
    margin-bottom: 15px;
  }
  
  .hero-content p {
    font-size: 1.3rem;
    margin-bottom: 25px;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
  }
  
  .cta-button {
    padding: 12px 25px;
    background-color: #FF3C38;
    color: #fff;
    font-weight: bold;
    border-radius: 8px;
    font-size: 1rem;
    transition: background-color 0.3s;
    cursor: pointer;
    border: none;
  }
  
  .cta-button:hover {
    background-color: #d42e2b;
  }
  
  .gallery {
    padding: 60px 20px;
    text-align: center;
  }
  
  .gallery h2 {
    font-family: 'Montserrat', sans-serif;
    font-size: 2rem;
    margin-bottom: 30px;
    color: #FF3C38;
  }
  
  .image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    max-width: 1000px;
    margin: 0 auto;
  }
  
  .image-grid img {
    width: 100%;
    border-radius: 10px;
    transition: transform 0.3s ease;
  }
  
  .image-grid img:hover {
    transform: scale(1.05);
  }
  
  .contact-section {
    padding: 60px 20px;
    max-width: 800px;
    margin: 0 auto;
  }
  
  .contact-section h2 {
    font-family: 'Montserrat', sans-serif;
    font-size: 2rem;
    margin-bottom: 20px;
    color: #FF3C38;
  }
  
  .contact-form {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  
  .contact-form label {
    font-weight: bold;
    font-size: 1rem;
  }
  
  .contact-form input,
  .contact-form select,
  .contact-form textarea {
    padding: 10px;
    border-radius: 6px;
    border: none;
    font-size: 1rem;
    background-color: #030303;
    color: #fff;
  }
  
  .contact-form input::placeholder,
  .contact-form textarea::placeholder {
    color: #aaa;
  }

  .socials {
    background-color: #111;
    text-align: center;
    padding: 30px 20px;
    color: #fff;
  }
  
  .socials h3 {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    margin-bottom: 15px;
    color: #FF3C38;
  }
  
  .social-icons {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
  }
  
  .social-icons img {
    width: 35px;
    height: 35px;
    transition: transform 0.3s ease;
  }
  
  .social-icons img:hover {
    transform: scale(1.2);
  }

  footer {
    background-color: #000;
    color: #fff;
    text-align: center;
    padding: 20px;
    font-size: 0.9rem;
  }
  
  .footer-links {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin-bottom: 10px;
  }
  
  .footer-links a {
    color: #fff;
  }

  .event-container {
    max-width: 1200px;
    margin: 50px auto;
    padding: 0 20px;
    text-align: center;
  }
  
  .event-card {
    background: #2A2A2A;
    padding: 30px;
    border-radius: 10px;
    margin-bottom: 40px;
    text-align: center;
  }
  
  .event-card h1 {
    font-size: 2rem;
    color: #FF3C38;
    margin-bottom: 10px;
  }
  
  .event-card h2 {
    font-size: 1.5rem;
    margin-bottom: 15px;
  }
  
  .event-card p {
    margin-bottom: 10px;
    font-size: 1.1rem;
  }
  
  .event-actions {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin: 20px 0;
    flex-wrap: wrap;
  }
  
  .event-actions a,
  .toggle-label {
    background-color: #FF3C38;
    color: #fff;
    padding: 10px 15px;
    border-radius: 6px;
    font-weight: bold;
    transition: background-color 0.3s;
    display: inline-block;
    cursor: pointer;
  }
  
  .event-actions a:hover,
  .toggle-label:hover {
    background-color: #d42e2b;
  }
  
  .event-address {
    margin-top: 20px;
    font-size: 0.9rem;
    color: #ccc;
  }
  
  .event-banner {
    text-align: center;
    margin: 20px auto 40px;
    max-width: 800px;
    padding: 0 20px;
  }
  
  .event-banner img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .activities-section h2,
  .activities-title {
    font-size: 2rem;
    color: #FF3C38;
    margin: 20px 0;
  }

  .toggle-checkbox {
    display: none;
  }
  
  .toggle-checkbox:checked + .toggle-label + .hidden-info {
    display: block;
    margin-top: 10px;
    padding: 15px;
    background-color: #141414;
    border-radius: 8px;
    color: #fff;
  }
  
  .hidden-info {
    display: none;
  }

  @media (max-width: 768px) {
    nav ul {
      flex-direction: column;
      gap: 10px;
    }
  
    .logo {
      margin-bottom: 10px;
    }
  
    .hero-content h1 {
      font-size: 2.5rem;
    }
  
    .gallery h2,
    .contact-section h2,
    .activities-section h2 {
      font-size: 1.5rem;
    }
  
    .image-grid {
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    }
  }

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact & Registration - Laced Up Legends</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="images/Logo.png" alt="LUL Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="event-detail.html">Event Details</a></li>
                <li><a href="participants.html">Participants</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="contact-section">
            <h2>Get in Touch</h2>
            <p>Have questions about the event, venting opportunities, or general inquiries? Reach out to us using the form below or contact us directly via email.</p>
            <form action="#" method="post" class="contact-form">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required>

                <label for="type">Registering as:</label>
                <select name="type" id="type" required>
                    <option value="">-- Select --</option>
                    <option value="vendor">Vendor</option>
                    <option value="attendee">Attendee</option>
                    <option value="media">Media</option>
                </select>

                <label for="message">Message / Inquiry:</label>
                <textarea id="message" name="message" rows="5" placeholder="Your message..."></textarea>

                <button type="submit" class="cta-button">Submit Registration</button>
            </form>
        </section>
    </main>

    <section class="socials">
        <h3>Follow Us On</h3>
        <div class="social-icons">
          <a href="#"><img src="images/insta.jpeg" alt="Instagram" /></a>
          <a href="#"><img src="images/twitter.png" alt="Twitter" /></a>
          <a href="#"><img src="images/facebook.png" alt="Facebook" /></a>
          <a href="#"><img src="images/tiktok_PNG3.png" alt="TikTok" /></a>
        </div>
      </section>
    
      <footer>
        <p>&copy; 2025 Laced Up Legends. All rights reserved.</p>
      </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Participants- Laced Up Legends</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="images/Logo.png" alt="LUL Logo" class="logo">
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="event-detail.html">Event Details</a></li>
            <li><a href="participants.html">Participants</a></li>
            <li><a href="contact.html">Contact</a></li>
          </ul>
        </nav>
      </header>
    
      <main class="event-container">
        <h2>Organizers</h2>
        <p><strong>Event Name:</strong> Laced Up Legends: Detroit</p>
        <p><strong>Hosted by:</strong> Paul Wall</p>
    
        <h2>About the Organizers</h2>
        <ul>
          <li>A nonprofit dedicated to promoting sneaker culture in the community.</li>
          <li>With a passion for bringing people together, the team ensures unforgettable experiences for all attendees.</li>
          <li><strong>Key Contacts:</strong> Jane Doe – Event Director (jane@gmail.com), John Smith – Logistics Manager</li>
        </ul>
    
        <h2>Performers</h2>
        <ul>
          <li><strong>Headlining Act:</strong> DJ Maphorisa spinning deep house and Amapiano</li>
        </ul>
    
        <h2>Vendors</h2>
        <ul>
          <li>DJ Luna</li>
          <li>Jane Doe</li>
          <li>John Smith</li>
        </ul>
      </main>
    
      <footer>
        <div class="footer-links">
          <a href="index.html">Home</a>
          <a href="event-detail.html">Events</a>
          <a href="participants.html">Participants</a>
          <a href="contact.html">Contact</a>
        </div>
        <div class="copyright">
          &copy; 2025 Laced Up Legends. All rights reserved.
        </div>
      </footer>
    </body>
</body>
</html>
<!DOCTYPE html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Details - Laced Up Legends</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
    
    <header>
        <img src="images/Logo.png" alt="LUL Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="event-detail.html">Event Details</a></li>
                <li><a href="participants.html">Participants</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <div class="event-container">
          <h2>Upcoming Events</h2>
    
          <div class="event-banner">
            <img src="images/sneakercon-denver-apirl-26-2025.jpg" alt="Sneaker Con Denver April 26th 2025">
          </div>
    
          <div class="event-card">
            <h1>Laced Up Legends: Denver</h1>
            <h2>April 26th, 2025</h2>
            <p>Colorado Convention Center, 700 14th St, Denver, CO 80202</p>
            <div class="event-actions">
              <a href="#">Become a vendor</a>
              <a href="#">More info</a>
              <a href="#">Buy Tickets</a>
            </div>
          </div>
    
          <div class="event-banner">
            <img src="images/Screenshot 2025-04-21 185503.png" alt="Sneaker Con Detroit June 14th 2025">
          </div>
    
          <div class="event-card">
            <h1>Laced Up Legends: Detroit</h1>
            <h2>June 14th, 2025</h2>
            <p>Huntington Place Convention Center, 1 Washington Blvd, Detroit, MI 48226</p>
            <div class="event-actions">
              <a href="#">Become a vendor</a>
              <a href="#">More info</a>
              <a href="#">Buy Tickets</a>
            </div>
          </div>
        </div>
      </main>
    
      <footer>
        <div class="footer-links">
          <a href="index.html">Home</a>
          <a href="event-detail.html">Events</a>
          <a href="participants.html">Participants</a>
          <a href="contact.html">Contact</a>
        </div>
        <div class="copyright">
          &copy; 2025 Laced Up Legends. All rights reserved.
        </div>
      </footer>
    </body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laced Up Legends - Crown Your Kicks. Rule the Drop</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <img src="images/Logo.png" alt="LUL Logo" class="logo">
        <nav>
            <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="event-detail.html">Event Details</a></li>
            <li><a href="participants.html">Participants</a></li>
            <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <video autoplay muted loop class="background-video">
                <source src="images/video.m4v" type="video/mp4">
                Your browser does not support the video tag.
              </video>
              <div class="hero-content">
            <h1>Welcome to Laced Up Legends</h1>
            <p>The ultimate arena for sneaker royalty to buy, sell, and trade the most coveted kicks in the game.</p>
            <a href="event-detail.html" class="cta-button">Explore Event Details</a>
            </div>
        </section>

        <section class="gallery">
            <h2>Event Highlights</h2>
            <div class="image-grid">
              <img src="images/Screenshot 2025-04-21 185503.png" alt="Sneaker Event 1">
              <img src="images/sneakercon-denver-apirl-26-2025.jpg" alt="Sneaker Event 2">
              
        </div>  
        </section>
    </main>

    <section class="socials">
        <h3>Follow Us On</h3>
        <div class="social-icons">
          <a href="#" target="_blank"><img src="images/insta.jpeg" alt="Instagram" /></a>
          <a href="#" target="_blank"><img src="images/twitter.png" alt="Twitter" /></a>
          <a href="#" target="_blank"><img src="images/facebook.png" alt="Facebook" /></a>
          <a href="#" target="_blank"><img src="images/tiktok_PNG3.png" alt="TikTok" /></a>
        </div>
      </section>

    <footer>
        <p>&copy; 2025 Laced Up Legends. All rights reserved.</p>
    </footer>
</body>
</html>
