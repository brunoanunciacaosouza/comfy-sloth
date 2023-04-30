# Comfy E-Store

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)

## 📃About The Project

An E-commerce website built using React with Stripe for payment gateway.
This web app includes multiple pages like Products Page with option to filter your product search, Cart Page to review your purchases and Checkout Page to complete the purchase with Stripe Payment.
Auth0 is used for User Authentication before Checking out.

![Desktop preview](./images/home.png)

## 📄Pages

- Home Page
- Products Page
- Single Product Page
- About Page
- Error Page
- Cart Page
- Checkout Page

![Desktop preview](./images/about.png)
![Desktop preview](./images/products.png)
![Desktop preview](./images/single-product.png)
![Desktop preview](./images/cart.png)

## 🛠️ Tools/Ferramentas

- styled components
- react hooks
- react router
- Authentication implemented using Auth0 React
- Payments using stripe
- Axios

## Run Locally

### 1. Clone this repository

```
$ git clone git@github.com:brunoanunciacaosouza/comfy-sloth.git
$ cd comfy-sloth-ecommerce-site-react
```

### 2. Create .env File

- create .env

```
    REACT_APP_AUTH_DOMAIN=<Your secret auth0 value>
    REACT_APP_CLIENT_ID=<Your secret auth0 value>
```

### 3. Run the app

```
$ npm install && npm start
```

The app will run in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
