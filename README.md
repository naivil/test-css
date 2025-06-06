
📄 FreshCart Website Documentation
Overview
FreshCart is an online grocery store front-end webpage that showcases:

Header navigation

Promotional hero section

Service highlights

Best-selling products

Footer with informational links and social media icons

🧱 Project Structure
📁 Folders Used
./CSS/style.css – External stylesheet for custom styling

./images/ – Contains all images used (logo, products, hero image, icons, etc.)

📌 HTML Structure
1. <head>
Includes meta tags, title, and external stylesheets:

Bootstrap Icons

Font Awesome icons

Custom stylesheet (style.css)

2. <body>
🔹 Header Section
Purpose: Top navigation for site-wide links.

html
Copy
Edit
<header>
  <div class="container">
    ...
    <a href="#"><img src="./images/organic-store-logo5.svg" alt="logo_img"></a>
    ...
    <nav class="navbar-1">...Groceries | Juice</nav>
    <nav class="navbar-2">...About | Contact | Cart</nav>
  </div>
</header>
Divided into two navbars:

navbar-1: Main categories

navbar-2: Links + cart + search input

Uses Bootstrap and Flexbox utility classes for layout.

🔹 Hero Section
Purpose: Promotional banner with branding and "Shop Now" CTA.

html
Copy
Edit
<section class="hero">
  <img src="./images/g3.avif"> <!-- Hero image -->
  <div class="hero-content">
    <img src="./images/logo-leaf-new.png">
    <h5>Free Shipping...</h5>
    <p>...</p>
    <a href=""><i class="bi bi-cart-fill"></i> Shop Now</a>
  </div>
</section>
Two-column layout

Left: product image

Right: promotional message

🔹 Services Section
Purpose: Highlights store services (e.g., free shipping, certified organic).

html
Copy
Edit
<section class="services">
  <div class="service-item">
    <i class="fa-solid fa-truck"></i> <!-- Icon -->
    <h4>Free Shipping</h4>
    <p>Above $5 Only</p>
  </div>
  ...
</section>
Four service boxes laid out using Flexbox grid

Each has an icon + headline + subtitle

🔹 Products Section
Purpose: Displays best-selling items in grid layout.

html
Copy
Edit
<section class="products">
  <div class="products-item">
    <img src="./images/bhujiya_sev_1.webp">
    <h5>Snacks</h5>
    <span>Haldiram-Bhujia Sev</span>
    <p>$35.00</p>
  </div>
  ...
</section>
Arranged in 2 rows of 4 columns (col-3)

Includes:

Image

Category

Product name

Star rating (placeholder)

Price (with discount where applicable)

🔹 Footer Section
Purpose: Provides navigation, customer support, program info, and social media links.

html
Copy
Edit
<footer>
  <div class="footer-first">
    <div class="Categories">...</div>
    <div class="know us">...</div>
    ...
    <div class="footer-icons">
      <i class="fa-brands fa-github"></i>
      <i class="fa-brands fa-x-twitter"></i>
      ...
    </div>
  </div>
</footer>
Divided into:

Product categories

Company info

Consumer support

Career opportunities

Program info

Social media icons

✅ Technologies Used
Feature	Description
HTML5	Page structure
CSS3	Custom styles (in external file)
Bootstrap Icons	Cart and badge icons
Font Awesome	Icons for services and social media
Responsive Design	Meta viewport tag for mobile compatibility

🔍 Suggestions for Improvement
Add semantic tags for better accessibility (e.g., <nav>, <article>, <aside>)

Add alt text to all images (some are missing)

Use actual star ratings with JavaScript or CSS (currently only icons)

Integrate functionality: cart system, search results, and responsive breakpoints

Improve SEO with relevant meta tags and structured data# test-css
