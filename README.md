# Dissociart.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DissociArt</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <div class="logo">DissociArt</div>
        <nav class="nav">
            <ul>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#commissions">Commissions</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#find-us">Find Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero" class="hero">
        <h1>Welcome to DissociArt</h1>
        <p>Where street art meets raw emotion.</p>
        <a href="#gallery" class="cta-button">Explore Gallery</a>
    </section>

    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <p>Check out my latest works:</p>
        <div class="art-grid">
            <div class="art-piece">Artwork 1</div>
            <div class="art-piece">Artwork 2</div>
            <div class="art-piece">Artwork 3</div>
        </div>
    </section>

    <section id="commissions" class="commissions">
        <h2>Commissions</h2>
        <p>Want a custom piece? Fill out the form below:</p>
        <form action="submit.html" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="description" placeholder="Describe your idea..." required></textarea>
            <button type="submit">Request Commission</button>
        </form>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>Have questions or want to collaborate? Reach out to us!</p>
        <a href="https://wa.me/61408591219" target="_blank" class="whatsapp-button">
            Message DISSOCIART on WhatsApp
        </a>
    </section>

    <section id="find-us" class="find-us">
        <h2>Find Us on Google</h2>
        <p>Check out DissociArt's profile and reviews on Google:</p>
        <a href="https://g.co/kgs/XqPqKrf" target="_blank" class="google-button">
            View on Google
        </a>
    </section>

    <footer class="footer">
        <p>&copy; 2025 DissociArt. All rights reserved.</p>
    </footer>
</body>
</html>
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

/* Header */
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #333;
    color: #fff;
    padding: 1rem 2rem;
}
.header .logo {
    font-size: 1.5rem;
    font-weight: bold;
    text-transform: uppercase;
}
.nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
}
.nav ul li a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s;
}
.nav ul li a:hover {
    color: #f39c12;
}

/* Hero Section */
.hero {
    background: linear-gradient(to bottom, #222, #555);
    color: #fff;
    text-align: center;
    padding: 5rem 2rem;
}
.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}
.hero .cta-button {
    padding: 0.5rem 1rem;
    background: #f39c12;
    color: #fff;
    border: none;
    text-decoration: none;
    cursor: pointer;
    font-size: 1rem;
}
.hero .cta-button:hover {
    background: #e67e22;
}

/* Gallery */
.gallery {
    padding: 2rem;
    background: #eee;
    text-align: center;
}
.gallery h2 {
    margin-bottom: 1rem;
}
.art-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
}
.art-piece {
    background: #333;
    color: #fff;
    padding: 1rem;
    border-radius: 8px;
    text-align: center;
}

/* Contact Section */
.whatsapp-button {
    display: inline-block;
    padding: 0.8rem 1.2rem;
    background-color: #25D366; /* WhatsApp green */
    color: #fff;
    font-size: 1rem;
    font-weight: bold;
    text-decoration: none;
    border-radius: 5px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
    transition: background-color 0.3s ease;
}
.whatsapp-button:hover {
    background-color: #1ebe57; /* Darker WhatsApp green */
}

/* Find Us Section */
.google-button {
    display: inline-block;
    padding: 0.8rem 1.2rem;
    background-color: #4285F4; /* Google Blue */
    color: #fff;
    font-size: 1rem;
    font-weight: bold;
    text-decoration: none;
    border-radius: 5px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
    transition: background-color 0.3s ease;
}
.google-button:hover {
    background-color: #357AE8; /* Darker Google Blue */
}

/* Footer */
.footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

