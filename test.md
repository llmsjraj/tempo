## Task: Build a simple e-commerce product listing page with a shopping cart and a Node.js backend API

## Requirements:
### FrontEnd

- Create a Next.js application with React components that displays a list of products.
- Each product should have an image, title, price, and an "Add to Cart" button.
- Implement a shopping cart component that displays the items added to the cart, their quantities, and the total price.
- Allow users to change the quantity of items in the cart and remove items from the cart.
- Use a responsive design that works well on both desktop and mobile devices.
- Follow good CSS architecture principles by structuring and organizing your styles. Consider using a CSS-in-JS library like styled-components or Emotion, or a CSS methodology like BEM or SMACSS.
- Write maintainable and well-structured code by following best practices for React and Next.js.

### Backend:
- Create a simple Node.js backend using a framework like Express.js, Koa, or Fastify.
- Implement a RESTful API with the following endpoints:
- GET /api/products: Retrieve the list of products.
- POST /api/cart: Add a product to the cart.
- PUT /api/cart/:id: Update the quantity of a product in the cart.
- DELETE /api/cart/:id: Remove a product from the cart.
- Implement proper error handling and validation for the API endpoints.
- Write tests for the API endpoints using a testing library like Jest, Mocha, or Supertest.

### Data:

You can use the following sample data for the products or create your own:

```
[  {    "id": 1,    "title": "Product 1",    "price": 19.99,    "image": "https://via.placeholder.com/150"  },  {    "id": 2,    "title": "Product 2",    "price": 29.99,    "image": "https://via.placeholder.com/150"  },  {    "id": 3,    "title": "Product 3",    "price": 39.99,    "image": "https://via.placeholder.com/150"  }]
```

### Extras:
- Implement authentication and user sessions to enable users to log in and have their own cart state.
- Use a database to store product and cart data. You may choose any database technology (e.g., MongoDB, PostgreSQL, or SQLite) based on your preference.
