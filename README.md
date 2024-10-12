# cyolangphue.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Care Technological Solutions</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            color: #ffffff; /* White text for contrast */
            background-color: rgba(60, 30, 106, 0.9); /* Semi-transparent violet background */
            background-image: url('20241008_195945.png'); /* Replace with your background image file name */
            background-size: cover; /* Cover the entire background */
            background-position: center; /* Center the image */
            background-repeat: no-repeat; /* Do not repeat the image */
            text-align: center; /* Center all text */
        }
        header {
            padding: 20px;
            background-color: rgba(75, 0, 130, 0.9); /* Semi-transparent dark violet */
            color: white;
            border-bottom: 2px solid white; /* White bottom border for separation */
            position: relative; /* Position relative for background image */
            overflow: hidden; /* Hide overflow */
        }
        header::before {
            content: '';
            background-image: url('20241008_201130.png'); /* Replace with your logo image file name */
            background-size: 150%; /* Zoom in the background image */
            background-position: center; /* Center the image */
            background-repeat: no-repeat; /* Do not repeat the image */
            opacity: 0.3; /* Set opacity to show the purple background */
            position: absolute; /* Position the pseudo-element */
            top: 0; /* Align to the top */
            left: 0; /* Align to the left */
            right: 0; /* Align to the right */
            bottom: 0; /* Align to the bottom */
            z-index: 0; /* Send to back */
        }
        .tagline {
            font-size: 1.2em;
            margin: 10px 0;
            z-index: 1; /* Bring the tagline above the background */
            position: relative; /* Position relative to header */
            font-family: 'Orbitron', sans-serif; /* Use Orbitron font for tagline */
        }
        section {
            margin: 20px;
            padding: 20px;
            border-radius: 5px;
            background-color: rgba(255, 255, 255, 0.1); /* Slightly transparent background for sections */
        }
        h2 {
            font-family: 'Orbitron', sans-serif; /* Use Orbitron font for headings */
            color: #ffcc00; /* Gold color for headings */
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5); /* Text shadow for section headings */
        }
        p {
            font-family: 'Open Sans', sans-serif; /* Keep paragraphs in Open Sans */
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5); /* Text shadow for paragraphs */
        }
        .services, .team {
            display: flex;
            flex-direction: column;
            gap: 15px;
            align-items: center; /* Center the contents of services and team sections */
        }
        footer {
            padding: 20px;
            background-color: rgba(75, 0, 130, 0.9); /* Same as header */
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        a {
            color: #ffffff; /* Keep email link white for contrast */
            text-decoration: none; /* Remove underline from email link */
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5); /* Text shadow for email link */
        }
    </style>
</head>
<body>

<header>
    <img src="20241008_201130.png" alt="I Care Technological Solutions Logo" style="max-width: 200px; z-index: 1; position: relative;">
    <div class="tagline">Miracles happen when someone cares.</div>
</header>

<section>
    <h2>About Us</h2>
    <p><strong>Mission:</strong> To provide innovative IT solutions grounded in integrity and faith, empowering businesses to thrive while honoring God through our work.</p>
    <p><strong>Vision:</strong> To be a trusted IT service provider, known for our commitment to excellence, guided by Christian principles, and dedicated to serving our clients and community.</p>
    <p><strong>Core Values:</strong> Faith, Integrity, Service, Excellence, and Community. We strive to live out our faith in every aspect of our business, ensuring that we serve our clients with honesty and compassion.</p>
</section>

<section>
    <h2>Available Services</h2>
    <div class="services">
        <p><strong>IT Consulting:</strong> Our experts guide you through the evolving technological landscape, providing strategic advice tailored to your business needs.</p>
        <p><strong>Cloud Services:</strong> We offer secure, scalable cloud solutions to enhance efficiency and flexibility, empowering your business to adapt to the future.</p>
        <p><strong>Network Security:</strong> Protect your digital assets with our advanced security solutions, safeguarding your network from threats in an ever-changing environment.</p>
        <p><strong>Software Development:</strong> Our custom software solutions are designed to meet your specific needs, ensuring that your business runs smoothly and efficiently.</p>
        <p><strong>Managed IT Services:</strong> We take care of your IT infrastructure so you can focus on what matters most—growing your business, with the assurance of 24/7 support.</p>
    </div>
</section>

<section>
    <h2>Key Features</h2>
    <p>24/7 Support</p>
    <p>Tailored Solutions</p>
</section>

<section>
    <h2>History of the Company</h2>
    <p>Founded by a group of ex-college blockmates in 2024 after years of pursuing their individual desires, our company has grown from a small startup to a trusted IT partner for businesses of all sizes.</p>
</section>

<section>
    <h2>Meet Our Team</h2>
    <div class="team">
        <p><strong style="color: #ffcc00;">Jaziz Corsino:</strong> Founder & CEO</p>
        <p><strong style="color: #ffcc00;">Greeneia Bansil:</strong> Head of IT</p>
        <p><strong style="color: #ffcc00;">Enriko Remigio:</strong> Head of Network Security</p>
        <p><strong style="color: #ffcc00;">Sammy Rutledge:</strong> Head of Software Development</p>
        <p><strong style="color: #ffcc00;">Vinzen Navarro:</strong> Head of Cloud Services</p>
        <p><strong style="color: #ffcc00;">Thomas Semillano:</strong> Head of IT Consulting</p>
    </div>
</section>

<footer>
    <div>&copy; 2024 I Care Technological Solutions. All Rights Reserved.</div>
    <div>Address: 2614 Rizal Avenue, Olongapo City</div>
    <div>Email: <a href="mailto:corsinojazizomrick@gmail.com">corsinojazizomrick@gmail.com</a></div>
    <div>Contact Number: 09611002129</div>
</footer>

</body>
</html>
