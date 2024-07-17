# landing
/* General styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* Header styles */
header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

.logo {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    font-size: 1.5em;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav li {
    margin-left: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

/* Hero section styles */
.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 100px 0;
    max-width: 1200px;
    margin: 0 auto;
}

.hero-text {
    text-align: left;
    width: 50%;
}

h1 {
    font-size: 3em;
    margin-bottom: 20px;
}

p {
    line-height: 1.6;
    margin-bottom: 30px;
}

.btn {
    background-color: #007bff;
    color: #fff;
    padding: 15px 30px;
    border: none;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #0056b3;
}

.hero-image {
    width: 50%;
}

.hero-image img {
    width: 100%;
    height: auto;
}

/* Features section styles */
.features {
    padding: 80px 0;
    text-align: center;
}

.feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    padding: 0 50px;
}

.feature {
    background-color: #fff;
    border-radius: 10px;
    padding: 30px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.feature img {
    width: 50px;
    height: 50px;
    margin-bottom: 20px;
}

.feature h3 {
    margin-bottom: 10px;
}

/* Call to action (CTA) section styles */
.cta {
    background-color: #007bff;
    color: #fff;
    padding: 80px 0;
    text-align: center;
}

.cta-content {
    max-width: 800px;
    margin: 0 auto;
}

.cta h3 {
    margin-bottom: 20px;
}

/* Footer styles */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}
