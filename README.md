# applicationgallery.github.io
Every gesture is an application
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Helvetica Neue', sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
    background-color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 3rem;
    position: sticky;
    top: 0;
    background-color: #fff;
    z-index: 100;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

header .logo {
    font-size: 1.8rem;
    font-weight: bold;
    letter-spacing: 1px;
}

header nav ul {
    display: flex;
    list-style: none;
    gap: 2rem;
}

header nav a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s ease;
}

header nav a:hover {
    color: #ff4c4c;
}

.hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    height: 80vh;
    background: url('assets/images/hero.jpg') center/cover no-repeat;
    color: #fff;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.btn {
    padding: 0.8rem 2rem;
    background-color: #ff4c4c;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    border-radius: 4px;
    transition: background 0.3s ease;
}

.btn:hover {
    background-color: #e03b3b;
}

.gallery, .artists, .contact {
    padding: 5rem 3rem;
    text-align: center;
}

.art-grid, .artist-grid {
    display: grid;
    gap: 2rem;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    margin-top: 2rem;
}

.art-item img, .artist-card img {
    width: 100%;
    border-radius: 8px;
    transition: transform 0.3s ease;
}

.art-item img:hover, .artist-card img:hover {
    transform: scale(1.05);
}

.artist-card h3 {
    margin-top: 0.8rem;
    font-weight: 600;
}

.contact form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    max-width: 500px;
    margin: 0 auto;
}

.contact input, .contact textarea, .contact button {
    padding: 0.8rem;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.contact button {
    background-color: #ff4c4c;
    color: #fff;
    border: none;
    cursor: pointer;
    transition: background 0.3s ease;
}

.contact button:hover {
    background-color: #e03b3b;
}

footer {
    padding: 2rem 3rem;
    text-align: center;
    background-color: #f5f5f5;
    margin-top: 5rem;
}
