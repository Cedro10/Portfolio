/* style.css */

/* Global styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

h1, h2, h3 {
    color: #333;
}

a {
    color: #0066cc;
}

/* Section styles */
.section {
    padding: 60px 0;
}

.accueil {
    background-color: #0066cc;
    color: white;
    text-align: center;
}

.acceuil h1 {
    font-size: 3rem;
}

.acceuil p {
    font-size: 1.5rem;
}

.container {
    width: 80%;
    margin: 0 auto;
}

.apropos, .services, .contact {
    background-color: #ffffff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 30px;
    padding: 30px;
    border-radius: 8px;
}

.apropos ul, .services ul {
    list-style-type: none;
    padding: 0;
}

.apropos li, .services li {
    margin: 10px 0;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
} 
/* Formulaire de contact */
form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

form label {
    font-weight: bold;
}

form input, form textarea {
    padding: 10px;
    font-size: 1rem;
    border: 1px solid #ddd;
    border-radius: 4px;
}

form textarea {
    resize: vertical;
    min-height: 150px;
}

form button {
    padding: 10px 20px;
    background-color: #0066cc;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1rem;
}

form button:hover {
    background-color: #005bb5;
}
.accueil {
    background: url('images/banner.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}
