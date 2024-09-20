!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meal kit Service</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Convenience Food Option</h1>
        <p>Find ingredients or order meals online in a few clicks.</p>
    </header>

    <main>
        <section class="order-form">
            <h2>Enter Your Dish</h2>
            <form>
                <!-- Dish input -->
                <label for="dish">Dish Name:</label>
                <input type="text" id="dish" name="dish" placeholder="Enter your dish..." required>

                <!-- Choose product type -->
                <label for="product-type">Choose Product Type:</label>
                <select id="product-type" name="product-type">
                    <option value="raw">Raw Ingredients</option>
                    <option value="pre-prepared">Pre-Prepared Ingredients</option>
                    <option value="cooked">Cooked Meals</option>
                </select>

                <!-- Quantity input -->
                <label for="quantity">How many servings?</label>
                <input type="number" id="quantity" name="quantity" min="1" max="10" value="1">

                <!-- Budget input -->
                <label for="budget">Enter Your Budget (in $):</label>
                <input type="number" id="budget" name="budget" placeholder="e.g. 50" required>

                <!-- Submit button -->
                <button type="submit">Find Ingredients/Order Now</button>
            </form>
        </section>

        <section class="instructions">
            <h2>Instructions</h2>
            <p>Get detailed instructions or watch videos for your dish preparation.</p>
            <button>Text Instructions</button>
            <button>Video Instructions</button>
        </section>
    </main>

    <footer>
        <p>© 2024 Convenience Food Ordering Platform. All rights reserved.</p>
    </footer>
</body>
</html>