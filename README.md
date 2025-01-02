<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Bookstore</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <div class="logo">
            <h1>Online Bookstore</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#books">Books</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#cart" id="cart-link">Cart (0)</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to the Online Bookstore</h2>
        <p>Browse through our collection of books from various genres. Find your next great read!</p>
    </section>

    <section id="books">
        <h2>Our Books</h2>
        <div class="book-container">
            <!-- Example Book Item 1 -->
            <div class="book-item">
                <img src="book1.jpg" alt="Book 1">
                <h3>Book Title 1</h3>
                <p>Author: Author Name</p>
                <p class="price">$20.00</p>
                <button class="add-to-cart" data-id="1" data-name="Book Title 1" data-price="20.00">Add to Cart</button>
            </div>

            <!-- Example Book Item 2 -->
            <div class="book-item">
                <img src="book2.jpg" alt="Book 2">
                <h3>Book Title 2</h3>
                <p>Author: Author Name</p>
                <p class="price">$25.00</p>
                <button class="add-to-cart" data-id="2" data-name="Book Title 2" data-price="25.00">Add to Cart</button>
            </div>

            <!-- Add more book items as necessary -->
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are an online bookstore offering a wide range of books, from bestsellers to niche genres. Our mission is to deliver quality literature to readers worldwide.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@onlinebookstore.com</p>
        <p>Phone: +123 456 7890</p>
    </section>

    <footer>
        <p>&copy; 2025 Online Bookstore. All rights reserved.</p>
    </footer>

    <!-- Shopping Cart Modal -->
    <div id="cart-modal" class="modal">
        <div class="modal-content">
            <span class="close-btn" id="close-btn">&times;</span>
            <h2>Your Cart</h2>
            <ul id="cart-items">
                <!-- Cart items will appear here -->
            </ul>
            <p id="total-price">Total: $0.00</p>
            <button id="checkout-btn">Checkout</button>
        </div>
    </div>
</body>
</html>
