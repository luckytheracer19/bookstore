# bookstore

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The English Book Shop | Since 1952</title>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        :root { --primary-blue: #0047AB; --text-dark: #333; --bg-light: #f9f9f9; }
        body { font-family: 'Poppins', sans-serif; margin: 0; background: var(--bg-light); color: var(--text-dark); 
        /* Header */
        header { background: var(--primary-blue); color: white; padding: 1.5rem; text-align: center; }
        header h1 { font-family: 'Playfair Display', serif; margin: 0; font-size: 2.5rem; }
        header p { margin: 5px 0 0; letter-spacing: 2px; text-transform: uppercase; font-size: 0.9rem; }
        /* Hero Section */
        .hero { height: 400px; background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://unsplash.com'); background-size: cover; background-position: center; display: flex; align-items: center; justify-content: center; color: white; text-align: center; }
        .hero-text h2 { font-size: 3rem; margin-bottom: 10px; }
              /* Gallery Sections */
        section { padding: 50px 10%; }
        h3 { font-family: 'Playfair Display', serif; font-size: 2rem; border-bottom: 2px solid var(--primary-blue); display: inline-block; margin-bottom: 30px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .card { background: white; padding: 15px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); transition: transform 0.3s; text-align: center; }
        .card:hover { transform: translateY(-10px); }
        .card img { width: 100%; height: 200px; object-fit: cover; border-radius: 4px; }
        .card h4 { margin: 15px 0 5px; }
        /* Footer */
        footer { background: #222; color: #888; text-align: center; padding: 2rem; font-size: 0.8rem; }
    </style>
</head>
<body>
    <header>
        <h1>The English Book Shop</h1>
        <p>Chandigarh's Literary Landmark Since 1952</p>
    </header>
    <div class="hero">
        <div class="hero-text">
            <h2>Escape into a World of Words</h2>
            <p>Explore our curated collections of global literature and premium stationery.</p>
        </div>
    </div>
    <section id="books">
        <h3>Featured Books</h3>
        <div class="grid">
            <div class="card">
                <img src="https://unsplash.com" alt="Novel">
                <h4>Modern Classics</h4>
                <p>Curated fiction from top authors.</p>
            </div>
            <div class="card">
                <img src="https://unsplash.com" alt="Childrens Book">
                <h4>Young Readers</h4>
                <p>Magic for every age group.</p>
            </div>
            <div class="card">
                <img src="https://unsplash.com" alt="Poetry">
                <h4>Poetry & Anthologies</h4>
                <p>Verses that stir the soul.</p>
            </div>
        </div>
    </section>
    <section id="stationery" style="background: #eceff1;">
        <h3>Premium Stationery</h3>
        <div class="grid">
            <div class="card">
                <img src="https://unsplash.com" alt="Journal">
                <h4>Leather Journals</h4>
                <p>For your thoughts and sketches.</p>
            </div>
            <div class="card">
                <img src="https://unsplash.com" alt="Pens">
                <h4>Fine Writing</h4>
                <p>Luxury pens and calligraphy tools.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>SCO 31, Sector 17-E, Chandigarh | Open Daily: 10:30 AM - 8:30 PM</p>
        <p>&copy; 2026 The English Book Shop. All Rights Reserved.</p>
    </footer>
</body>
</html>
