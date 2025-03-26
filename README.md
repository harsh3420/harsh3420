- 👋 Hi, I’m @harsh3420
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
harsh3420/harsh3420 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Business Service Website</title>
  <!-- Basic CSS for white and blue theme -->
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff;
      color: #333;
    }
    header {
      background-color: #0073e6; /* Blue color similar to Amazon's accents */
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #005bb5;
    }
    nav a {
      color: #fff;
      padding: 15px 20px;
      text-decoration: none;
      text-transform: uppercase;
      font-weight: bold;
    }
    nav a:hover {
      background-color: #004494;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section-title {
      text-align: center;
      margin-bottom: 30px;
    }
    /* Footer */
    footer {
      background-color: #0073e6;
      color: #fff;
      text-align: center;
      padding: 10px;
    }
    /* Responsive layout */
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
      nav a {
        padding: 10px;
      }
    }
    /* Button Style */
    .btn {
      background-color: #0073e6;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      text-transform: uppercase;
    }
    .btn:hover {
      background-color: #005bb5;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>My Business Service</h1>
    <p>Your one-stop solution for all service needs</p>
  </header>

  <!-- Navigation Bar -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#prices">Prices</a>
    <a href="#payment">Payment</a>
    <a href="#contact">Contact</a>
    <a href="#instagram">Instagram</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h2 class="section-title">Home</h2>
    <p>Welcome to our business service website. Yahan aapko humare services, prices aur contact details milenge.</p>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2 class="section-title">About Us</h2>
    <p>Hum ek professional team hain jo aapko best business services provide karte hain. Humari dedication aur expertise se aapka business aur grow karega.</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2 class="section-title">Our Services</h2>
    <ul>
      <li>Service 1 - Detailed description of service 1</li>
      <li>Service 2 - Detailed description of service 2</li>
      <li>Service 3 - Detailed description of service 3</li>
      <!-- Add more services as needed -->
    </ul>
  </section>

  <!-- Prices Section -->
  <section id="prices">
    <h2 class="section-title">Prices</h2>
    <p>Yahan aapko humare services ke prices milenge. Har service ke liye alag pricing structure available hai.</p>
    <table border="1" width="100%" style="border-collapse: collapse; text-align: center;">
      <tr>
        <th>Service</th>
        <th>Price</th>
      </tr>
      <tr>
        <td>Service 1</td>
        <td>$100</td>
      </tr>
      <tr>
        <td>Service 2</td>
        <td>$200</td>
      </tr>
      <!-- Add more rows as required -->
    </table>
  </section>

  <!-- Payment Section -->
  <section id="payment">
    <h2 class="section-title">Payment</h2>
    <p>Payment ke liye secure gateway integrate kiya gaya hai. Aap credit/debit card ya online wallet se payment kar sakte hain.</p>
    <!-- Example button for payment action -->
    <button class="btn" onclick="paymentAction()">Pay Now</button>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2 class="section-title">Contact Us</h2>
    <p>Humse contact karne ke liye neeche diye gaye form ko use karein:</p>
    <form id="contactForm" onsubmit="submitForm(event)">
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name" required><br><br>
      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email" required><br><br>
      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="4" required></textarea><br><br>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </section>

  <!-- Instagram Section -->
  <section id="instagram">
    <h2 class="section-title">Instagram</h2>
    <p>Follow our Instagram page for latest updates:</p>
    <a href="https://www.instagram.com/yourpage" target="_blank" class="btn">Visit Instagram</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Business Service. All rights reserved.</p>
  </footer>

  <!-- Basic JavaScript for dynamic functionalities -->
  <script>
    function submitForm(event) {
      event.preventDefault();
      // Process form submission dynamically (AJAX, API call etc.)
      alert("Thank you for contacting us!");
      document.getElementById("contactForm").reset();
    }

    function paymentAction() {
      // Redirect to payment gateway or process payment dynamically
      alert("Redirecting to secure payment gateway...");
      // window.location.href = "payment_gateway_url";
    }
  </script>

</body>
</html>