# Kyrsten Stewart Portfolio

This project is a personal portfolio website created using HTML5 and CSS3. This website is an online portfolio to showcase projects and allow visitors to view content.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


    ```bash
# Example command
git clone https://github.com/Kyrste9128/repository.git
    ```

## Usage

zHOME: Breif introduction to the owner of portfolio
PORJECT: Project includes names, descriptions, and project additions.
CONTACT: Visitors can view contact information.

Technologies used: 
HTML5
CSS3
Responsive Design


    ```html
<!-- Example HTML code -->
<section id="about">
  <h2>About Me</h2>
  <p>Welcome to my personal website.</p> </section>
## Contributing

Guidelines for how others can contribute to your project.

## License

2026 Kyrsten Stewart. All Rights Reserved.
# Kyrste9128.github.io

body {
   background-color: #f2f2f2;
   font-family: Arial, sans-serif;
   margin: 0;
   padding: 0;
}

header {
   text-align: center;
   padding: 20px;
}


nav ul {
   display: flex;
flex-direction: row;
   justify-content: center;
gap: 20px;
   list-style: none;
   padding: 0;
}

nav li {
   margin: 0 15px;
}

nav a {
   display: block;
   background-color: #333;
   color: white;
   padding: 12px 20px;
   text-decoration: none;
   border-radius: 4px;

   transition: background-color 0.3s;
}

nav a:hover {
   background-color: #555;
}

main {
display: flex;
flex-direction: column;
gap: 20px;
max-width: 960px;
   margin: auto;
}


section {
   background-color: white;
   padding: 20px;
   margin: 20px 0;

   box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);

   transition: transform 0.3s;
}

section:hover {
   transform: scale(1.02);
}

table {
   width: 100%;
   border-collapse: collapse;
}

caption {
   font-size: 1.2em;
   font-weight: bold;
   margin-bottom: 10px;
}

.highlightCol {
   background-color: #f9f9f9;
}

th,
td {
   border: 1px solid #ccc;
   padding: 12px;
   text-align: left;
}

thead {
   background-color: #444;
   color: white;
}

tfoot td {
   text-align: center;
   font-style: italic;
   border-top: 1px solid #ccc;
}

footer {
   text-align: center;
   padding: 20px;
}

#contact form {
   display: flex;
   flex-direction: column;
   gap: 10px;
   max-width: 500px;
}

#contact input,
#contact textarea {
   padding: 10px;
   border: 1px solid #ccc;
   border-radius: 4px;

   transition: border-color 0.3s ease;
}
#contact input:hover,
#contact textarea:hover {
   border-color: #777;
}

#contact input:focus,
#contact textarea:focus {
   border-color: #0066cc;
   outline: none;
}

#contact input[type="submit"] {
   background-color: #333;
   color: white;
   border: none;
   cursor: pointer;
}

#contact input[type="submit"]:hover {
   background-color: #555;
}

#contact input[type="submit"]:focus {
   background-color: #0066cc;
}

@media screen and (min-width: 320 px) {
body {
font size: 14px;
}

nav ul {
flex-direction: column;
align-itmes: center; 
}
}

@media screen and (min-width: 769px) {
body {
font-size: 16px;
}

nav ul {
flex-direction: row;
}
}

@media screen and (min-width: 1024px) {
body {
font-size: 18px;
}

main {
max-width: 1200px;
}
}
