<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AM Studio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; }
        header { background-color: #222; color: white; padding: 30px; text-align: center; }
        nav { text-align: center; background: #333; padding: 10px; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        section { padding: 40px; text-align: center; }
        .services, .pricing { display: flex; justify-content: center; flex-wrap: wrap; gap: 20px; }
        .service-card, .price-card { border: 1px solid #ddd; border-radius: 10px; padding: 20px; width: 280px; background: white; box-shadow: 0 3px 7px rgba(0,0,0,0.1); }
        footer { text-align: center; padding: 20px; background-color: #eee; }
        button { background-color: #222; color: white; padding: 10px 20px; border: none; cursor: pointer; border-radius: 5px; }
        form { display: flex; flex-direction: column; max-width: 400px; margin: auto; gap: 10px; }
        input, textarea { padding: 10px; border: 1px solid #ccc; border-radius: 5px; width: 100%; }
        @media (max-width: 600px) {
            .services, .pricing { flex-direction: column; align-items: center; }
            .service-card, .price-card { width: 90%; }
        }
    </style>
</head>
<body>
    <header>
        <h1>AM Studio (AM)</h1>
        <p>Creative Editing Services by Ms. Mounika Arepalli</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="home">
        <h2>Welcome</h2>
        <p>Turn your memories into stunning visuals. We design custom posters, edit videos, and enhance photos professionally.</p>
        <button>Get Started</button>
    </section>
    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-card">
                <h3>Photo Editing</h3>
                <p>Retouching, background removal, color correction, and more.</p>
            </div>
            <div class="service-card">
                <h3>Video Editing</h3>
                <p>Reels, vlogs, wedding highlights, business promos.</p>
            </div>
            <div class="service-card">
                <h3>Invitation Design</h3>
                <p>Custom digital invitations for weddings, birthdays, events.</p>
            </div>
            <div class="service-card">
                <h3>Documentation & PPT Design</h3>
                <p>Project reports, business presentations, portfolios, and proposals.</p>
            </div>
        </div>
            <div class="service-card">
                <h3>Video Editing</h3>
                <p>Reels, vlogs, wedding highlights, business promos.</p>
            </div>
            <div class="service-card">
                <h3>Invitation Design</h3>
                <p>Custom digital invitations for weddings, birthdays, events.</p>
            </div>
        </div>
    </section>
    <section id="pricing">
        <h2>Pricing</h2>
        <div class="pricing">
            <div class="price-card">
                <h3>Basic Package</h3>
                <p>Photo edit / Simple poster</p>
                <p>Starting at ₹49</p>
            </div>
            <div class="price-card">
                <h3>Standard Package</h3>
                <p>Video editing / Invitation design</p>
                <p>Starting at ₹99</p>
            </div>
            <div class="price-card">
                <h3>Premium Package</h3>
                <p>Event highlights / Custom design bundle</p>
                <p>Starting at ₹149</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="4" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <p>Email: miss.funnygirl.009@gmail.com</p>
        <p>Contact Person: Ms. Mounika Arepalli</p>
    </section>
    <section id="order">
        <h2>Place Your Order</h2>
        <p>Need a custom design, documentation, or presentation? Submit your details below or contact via WhatsApp.</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="text" placeholder="Service Required (e.g., PPT, Editing)" required>
            <textarea rows="4" placeholder="Project Details" required></textarea>
            <button type="submit">Submit Request</button>
        </form>
        <p>Or contact directly on WhatsApp:</p>
        <p><a href="https://mail.me/miss.funnygirl.009@gmail.com" target="_blank">Chat on mail</a></p>
    </section>
    <footer>
        <p>&copy; 2025 AM Studio. All Rights Reserved.</p>
    </footer>
</body>
</html>
