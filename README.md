# TMNotaryandSigningSolutions
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TM Notary & Signing Solutions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #002f6c;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
        }
        .logo {
            position: absolute;
            top: 10px;
            left: 20px;
            width: 100px;
        }
        .profile-pic {
            display: block;
            margin: 20px auto;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #004aad;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
            text-align: center;
        }
        .services, .contact, .booking, .testimonials {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #002f6c;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        input, select, button {
            margin: 10px;
            padding: 10px;
            width: 80%;
            max-width: 400px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="TM Notary Logo" class="logo">
        <h1>TM Notary & Signing Solutions</h1>
        <p>Reliable | Professional | Efficient</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#booking">Book an Appointment</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <img src="profile.jpg" alt="Professional Profile" class="profile-pic">
            <p>At TM Notary & Signing Solutions, we provide professional notary and loan signing services with accuracy and efficiency. Whether you need general notarization, loan signings, or remote online notarization, we are here to assist.</p>
        </section>
        <section id="services" class="services">
            <h2>Our Services & Pricing</h2>
            <ul>
                <li>Standard Loan Signing: $125 - $200 per appointment</li>
                <li>Reverse Mortgages: $175 - $250 per appointment</li>
                <li>Loan Modifications: $75 - $100 per appointment</li>
                <li>Standard Notarization: $5 - $25 per signature</li>
                <li>Remote Online Notarization (RON): $25 per notarization</li>
                <li>Mobile Notary Services: $35 - $75 travel fee</li>
            </ul>
        </section>
        <section id="booking" class="booking">
            <h2>Book an Appointment</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Your Phone Number" required>
                <select name="service" required>
                    <option value="">Select a Service</option>
                    <option value="loan-signing">Loan Signing</option>
                    <option value="reverse-mortgage">Reverse Mortgage</option>
                    <option value="loan-modification">Loan Modification</option>
                    <option value="notarization">General Notarization</option>
                    <option value="remote-notary">Remote Online Notarization</option>
                </select>
                <select name="location" required>
                    <option value="">Select a Location</option>
                    <option value="wilmington">Wilmington, DE</option>
                    <option value="newark">Newark, DE</option>
                    <option value="dover">Dover, DE</option>
                    <option value="other">Other (Specify in Notes)</option>
                </select>
                <input type="text" name="referral" placeholder="Referral Code or Name">
                <input type="date" name="date" required>
                <button type="submit">Book Now</button>
            </form>
        </section>
        <section id="testimonials" class="testimonials">
            <h2>Client Testimonials</h2>
            <p>See what our satisfied clients have to say:</p>
            <div id="reviews">
                <p>"Excellent service, very professional and reliable!" - Jane D.</p>
                <p>"Highly recommend TM Notary for any notary needs!" - Mark S.</p>
            </div>
        </section>
        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <p>Email: tmnotarysolutions@example.com</p>
            <p>Phone: (123) 456-7890</p>
            <p>Service Area: Wilmington, DE & Surrounding Areas</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 TM Notary & Signing Solutions. All Rights Reserved.</p>
    </footer>
</body>
</html>