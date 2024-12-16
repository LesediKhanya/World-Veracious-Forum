# World-Veracious-Forum
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>World Veracious Forum</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="635BAB34-0C66-42AD-B7D4-0AA5A48CDEA7.png" alt="World Veracious Forum Logo">
        </div>
        <h1>World Veracious Forum</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#world">World</a></li>
                <li><a href="#politics">Politics</a></li>
                <li><a href="#technology">Technology</a></li>
                <li><a href="#sports">Sports</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Latest News</h2>
            <article>
                <h3>Article Title 1</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam interdum purus non eros ullamcorper ultricies.</p>
            </article>
            <article>
                <h3>Article Title 2</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam interdum purus non eros ullamcorper ultricies.</p>
            </article>
            <!-- Add more articles as needed -->
        </section>
    </main>
    <footer>
        <p>&copy; 2024 World Veracious Forum</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #FFFFFF; /* White */
    color: #000000; /* Black */
}

header {
    background-color: #000000; /* Black */
    color: #FFFFFF; /* White */
    padding: 1rem 0;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo img {
    height: 50px;
    width: auto;
    margin-left: 1rem;
}

header h1 {
    flex-grow: 1;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    gap: 1rem;
    margin-right: 1rem;
}

header nav ul li {
    display: inline;
}

header nav ul li a {
    color: #FFFFFF; /* White */
    text-decoration: none;
}

header nav ul li a:hover {
    text-decoration: underline; /* Optional: underline on hover */
}

main {
    padding: 2rem;
}

main section {
    margin-bottom: 2rem;
}

main section h2 {
    border-bottom: 2px solid #000000; /* Black */
    padding-bottom: 0.5rem;
}

main article {
    background-color: #FFFFFF; /* White */
    padding: 1rem;
    margin-bottom: 1rem;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

main article h3, main article p {
    color: #000000; /* Black */
}

footer {
    background-color: #000000; /* Black */
    color: #FFFFFF; /* White */
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
