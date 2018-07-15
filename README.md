# Shop-App
OVERVIEW
A small e-commerce single page app with CRUD operations.  There is a frontend and backend, but no database so data is not persistent.

MAIN FEATURES
Utilizes localstorage and routing for the login.  Once logged in the user is redirected to the shop, and cannot access the shop unless logged in.  If the user manually clears local storage in the browser, the next action will redirect them to the login screen.  CRUD operations include adding to the cart and clearing all items in it.  404 handling is included if the user enters anything unknown in url.  Cart is cleared on logout.  There is no database, but the cart is stored in state.

TECHNOLOGIES
REST API on the backend using Express, React and React Router on the frontend.  Axios is used on the frontend for CRUD requests to the API.
