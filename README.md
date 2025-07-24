<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preethi's Fashion</title>
    <style>
        body {font-family: Arial, sans-serif; margin:0; padding:0; background:#fefefe;}
        header {background: linear-gradient(45deg, #ff4081, #ffca28); color:#fff; padding:20px; text-align:center;}
        nav {display:flex; justify-content:center; background:#333; flex-wrap:wrap; position:sticky; top:0; z-index:1000;}
        nav a {color:white; padding:14px 20px; text-decoration:none; transition: background 0.3s ease;}
        nav a:hover {background:#ff4081;}
        section {padding:40px; text-align:center;}
        h1,h2 {color:#ff4081;}
        .gallery {display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:20px;}
        .gallery img {width:100%; border-radius:10px; box-shadow:0 4px 8px rgba(0,0,0,0.2);}
        footer {background:#333; color:white; text-align:center; padding:20px; margin-top:40px;}
        .btn {background:#ff4081; color:white; padding:10px 20px; text-decoration:none; border-radius:5px; transition: background 0.3s ease;}
        .btn:hover {background:#e91e63;}
        @media(max-width:768px){nav {flex-direction:column; align-items:center;} nav a {width:100%; text-align:center; border-top:1px solid #444;}}
    </style>
</head>
<body>
    <header>
        <h1>Preethi's Fashion</h1>
        <p>Trendy • Stylish • Affordable</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#collections">Collections</a>
        <a href="#new">New Arrivals</a>
        <a href="#offers">Offers</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to Preethi's Fashion</h2>
        <p>Your one-stop destination for the latest fashion trends.</p>
        <a href="#collections" class="btn">Explore Collections</a>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Preethi's Fashion is a school project showcasing creativity and design in the fashion world. 
        We bring style and comfort together in one place.</p>
    </section>

    <section id="collections">
        <h2>Our Collections</h2>
        <p>Explore our curated fashion collections for every season.</p>
        <div class="gallery">
            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzAwIiBoZWlnaHQ9IjQwMCIgdmlld0JveD0iMCAwIDMwMCA0MDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjMwMCIgaGVpZ2h0PSI0MDAiIGZpbGw9IiNmZjQwODEiLz48dGV4dCB4PSI1MCIgeT0iMjAwIiBmb250LXNpemU9IjI0IiBmaWxsPSIjZmZmIj5EcmVzcyAxPC90ZXh0Pjwvc3ZnPg==" alt="Dress 1">
            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzAwIiBoZWlnaHQ9IjQwMCIgdmlld0JveD0iMCAwIDMwMCA0MDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjMwMCIgaGVpZ2h0PSI0MDAiIGZpbGw9IiNmZmNhMjgiLz48dGV4dCB4PSI1MCIgeT0iMjAwIiBmb250LXNpemU9IjI0IiBmaWxsPSIjZmZmIj5EcmVzcyAyPC90ZXh0Pjwvc3ZnPg==" alt="Dress 2">
            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzAwIiBoZWlnaHQ9IjQwMCIgdmlld0JveD0iMCAwIDMwMCA0MDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjMwMCIgaGVpZ2h0PSI0MDAiIGZpbGw9IiMwMGJjZDQiLz48dGV4dCB4PSI1MCIgeT0iMjAwIiBmb250LXNpemU9IjI0IiBmaWxsPSIjZmZmIj5EcmVzcyAzPC90ZXh0Pjwvc3ZnPg==" alt="Dress 3">
        </div>
    </section>

    <section id="new">
        <h2>New Arrivals</h2>
        <p>Fresh designs for your perfect look!</p>
    </section>

    <section id="offers">
        <h2>Special Offers</h2>
        <p>Get up to 50% off on selected items. Limited period only!</p>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery">
            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzAwIiBoZWlnaHQ9IjQwMCIgdmlld0JveD0iMCAwIDMwMCA0MDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjMwMCIgaGVpZ2h0PSI0MDAiIGZpbGw9IiM0Y2FmNTAiLz48dGV4dCB4PSI1MCIgeT0iMjAwIiBmb250LXNpemU9IjI0IiBmaWxsPSIjZmZmIj5Mb29rIDE8L3RleHQ+PC9zdmc+" alt="Look 1">
            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzAwIiBoZWlnaHQ9IjQwMCIgdmlld0JveD0iMCAwIDMwMCA0MDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjMwMCIgaGVpZ2h0PSI0MDAiIGZpbGw9IiM5YzI3YjAiLz48dGV4dCB4PSI1MCIgeT0iMjAwIiBmb250LXNpemU9IjI0IiBmaWxsPSIjZmZmIj5Mb29rIDI8L3RleHQ+PC9zdmc+" alt="Look 2">
            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzAwIiBoZWlnaHQ9IjQwMCIgdmlld0JveD0iMCAwIDMwMCA0MDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjMwMCIgaGVpZ2h0PSI0MDAiIGZpbGw9IiNmNDQzMzYiLz48dGV4dCB4PSI1MCIgeT0iMjAwIiBmb250LXNpemU9IjI0IiBmaWxsPSIjZmZmIj5Mb29rIDM8L3RleHQ+PC9zdmc+" alt="Look 3">
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: preethisfashion@example.com</p>
        <p>Phone: +91 9876543210</p>
    </section>

    <footer>
        <p>&copy; 2025 Preethi's Fashion | Designed for School Project</p>
    </footer>
</body>
</html>