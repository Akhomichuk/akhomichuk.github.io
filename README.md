* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}

/* Header Styles */
header {
    background: #333;
    color: white;
    padding: 1rem;
    position: fixed;
    width: 100%;
    top: 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

nav .logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 2rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a:hover {
    color: #ddd;
}

/* Hero Section */
.hero {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: linear-gradient(to right, #4facfe, #00f2fe);
    color: white;
    padding: 2rem;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.cta-button {
    padding: 0.8rem 1.5rem;
    background: #333;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.cta-button:hover {
    background: #555;
}

/* About Section */
.about {
    padding: 4rem 2rem;
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
}

.about h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

/* Contact Section */
.contact {
    padding: 4rem 2rem;
    background: #f4f4f4;
    text-align: center;
}

.contact h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.contact form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

.contact form label {
    margin: 0.5rem 0;
    text-align: left;
}

.contact form input,
.contact form textarea {
    padding: 0.5rem;
    margin-bottom: 1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact form button {
    padding: 0.8rem;
    background: #333;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact form button:hover {
    background: #555;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem;
}

/* Responsive Design */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
    }
...
