<!--# Thomas-J.-Watson-Jr.
A simple responsive HTML &amp; CSS website dedicated to the founder of IBM,. Built for practice in basic web development and design -->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Thomas J. Watson Sr. Fan Club</title>
<style>
    /* General Page Styling */
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        background: linear-gradient(to right, #e0f2ff, #f5f5f5);
        color: #333;
        line-height: 1.6;
        animation: fadeIn 0.8s ease-in;
    }

    /* Header */
    header {
        background: linear-gradient(90deg, #003366, #0055a4);
        color: white;
        padding: 25px;
        text-align: center;
        box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    header h1 {
        margin: 0;
        font-size: 2.3rem;
    }
    header p {
        margin-top: 8px;
        font-size: 1.1rem;
        font-style: italic;
    }

    /* Navigation */
    nav {
        background-color: #0055a4;
        padding: 12px 0;
        text-align: center;
    }
    nav a {
        color: white;
        margin: 0 18px;
        text-decoration: none;
        font-weight: bold;
        transition: all 0.3s ease;
        padding: 6px 10px;
        border-radius: 5px;
    }
    nav a:hover {
        background-color: #ffcc00;
        color: #003366;
        box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    /* Main Content */
    main {
        max-width: 900px;
        margin: 25px auto;
        padding: 20px;
        background: white;
        border-radius: 12px;
        box-shadow: 0 6px 20px rgba(0,0,0,0.1);
        animation: slideUp 0.8s ease-out;
    }
    section {
        margin-bottom: 30px;
    }
    h2 {
        color: #003366;
        border-left: 5px solid #0055a4;
        padding-left: 10px;
        margin-bottom: 12px;
        transition: color 0.3s;
    }
    h2:hover {
        color: #ff6600;
    }
    ul {
        padding-left: 20px;
    }

    /* Images */
    img {
        max-width: 100%;
        border-radius: 8px;
        margin-top: 10px;
        box-shadow: 0 2px 8px rgba(0,0,0,0.15);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    img:hover {
        transform: scale(1.03);
        box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    /* Footer */
    footer {
        background-color: #003366;
        color: white;
        text-align: center;
        padding: 12px;
        margin-top: 30px;
        font-size: 0.9rem;
    }

    /* Animations */
    @keyframes fadeIn {
        from {opacity: 0;}
        to {opacity: 1;}
    }
    @keyframes slideUp {
        from {transform: translateY(20px); opacity: 0;}
        to {transform: translateY(0); opacity: 1;}
    }
</style>
</head>
<body>

<header>
    <h1>Thomas J. Watson Sr. Fan Club</h1>
    <p>Celebrating the legacy of the visionary founder of IBM</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#legacy">Legacy</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav>

<main>
    <section id="about">
        <h2>About Thomas J. Watson Sr.</h2>
        <p>
            Thomas John Watson Sr. (February 17, 1874 – June 19, 1956) was an American businessman who served as the chairman and CEO of IBM from 1914 to 1956. 
            Under his leadership, IBM grew from a small manufacturing company into a global leader in computing and data processing. 
            Known for introducing the corporate motto <strong>"THINK"</strong>, Watson shaped IBM’s culture and business philosophy for decades.
        </p>
    </section>

    <section id="legacy">
        <h2>Legacy</h2>
        <ul>
            <li>Transformed IBM into a worldwide technology leader.</li>
            <li>Introduced the iconic corporate motto "THINK".</li>
            <li>Established IBM’s reputation for innovation and quality.</li>
        </ul>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <img src="https://encrypted-tbn3.gstatic.com/licensed-image?q=tbn:ANd9GcSZujVjzHY1kLB-QCeFPc20USq5JTDmt9ZZ08SO6li5Pgr-S1o9xAAo32OZMNd_KNsJCIYXGS8JJwFVqrXNWresftArzul44tSFyYMk709ig4E_QQTXVVQZzK2SEmuGootFEdtUAvz_xlf4" alt="Thomas J. Watson Sr.">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDy_BvAfrkaTsORXBPAG3eBLkFMylunzAtVQ&s" alt="Thomas J. Watson Sr.">
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:rishi@gmail.com">trident@gmail.com</a></p>
    </section>
</main>

<footer>
    <p>&copy; 2025 Thomas J. Watson Sr. Fan Club | All rights reserved</p>
</footer>

</body>
</html>
