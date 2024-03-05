Knights - Men's Apparel Fashion Store

Knights is a Django-based web application for a men's apparel fashion store. It allows users to browse through various categories of clothing, view product details, add items to their cart, and manage their favorites. The application also provides user authentication functionality for registration and login.

Features
User Authentication: Users can register, log in, and log out securely.
Product Management: Admins can add, edit, and delete products and categories via the Django admin interface.
Product Browsing: Users can browse through different categories of men's apparel.
Product Details: Detailed information about each product is available, including images, descriptions, prices, and quantities.
Cart Functionality: Users can add products to their cart and manage the quantity of items.
Favorites: Users can mark products as favorites for easy access later.
Responsive Design: The application is designed to be responsive, ensuring a seamless experience across devices.
Installation

Clone the repository:
git clone <repository_url>

Navigate to the project directory:
cd knights

Install dependencies:
pip install -r requirements.txt

Run migrations:
python manage.py migrate

Create a superuser (for admin access):
python manage.py createsuperuser

Start the development server:
python manage.py runserver

Access the application in your web browser at http://127.0.0.1:8000/.

Usage

-As an admin, log in to the admin interface at /admin to manage products and categories.

-As a regular user, navigate through the website to browse products, add items to the cart, and manage favorites.

-Register for an account if you're a new user or log in with existing credentials.


Contributing

-Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
