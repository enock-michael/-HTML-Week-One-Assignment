<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description"
        content="Demonstration of semantic HTML5 page with headings from H1 to H6 in hierarchical order, accessible and SEO-friendly.">
    <meta name="keywords"
        content="HTML5, headings, accessibility, SEO, semantic,websites,">
    <meta name="author" content="plp">
    <title>HTML5 Headings Hierarchy-(plp)</title>
</head>

<body>

    <header>
        <h1>H1: Welcome to Our Website</h1>
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="#section1">Introduction</a></li>
                <li><a href="#section2">Features</a></li>
                <li><a href="#section3">About</a></li>
                <li><a href="#section4">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Section 1 -->
        <section id="section1">
            <h2>H2: Introduction</h2>
            <h3>H3: Purpose</h3>
            <h4>H4: Scope</h4>
            <h5>H5: Audience</h5>
            <h6>H6: Notes</h6>
            <p>This section explains the purpose of this HTML5 page
                demonstrating headings hierarchy.</p>
        </section>

        <!-- Section 2 -->
        <section id="section2">
            <h2>H2: Features</h2>
            <h3>H3: Semantic Structure</h3>
            <h4>H4: Accessibility</h4>
            <h5>H5: SEO Optimization</h5>
            <h6>H6: Future Enhancements</h6>
            <p>This section describes the main features of this example page.
            </p>
        </section>

        <!-- Section 3 -->
        <section id="section3">
            <h2>H2: About</h2>
            <h3>H3: Author</h3>
            <h4>H4: Background</h4>
            <h5>H5: Experience</h5>
            <h6>H6: Contact Info</h6>
            <p>Information about the author and the purpose of this educational
                page.</p>
        </section>

        <!-- Section 4 -->
        <section id="section4">
            <h2>H2: Contact</h2>
            <h3>H3: Get in Touch</h3>
            <h4>H4: Email</h4>
            <h5>H5: Phone</h5>
            <h6>H6: Social Media</h6>
            <form aria-label="Contact Form">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"
                    aria-required="true"><br><br>

                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"
                    aria-required="true"><br><br>

                <label for="message">Message:</label><br>
                <textarea id="message" name="message"
                    aria-required="true"></textarea><br><br>

                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 plp. All rights reserved.</p>
    </footer>

</body>

</html>
