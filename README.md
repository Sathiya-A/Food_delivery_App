### `npm start` To start the app

This project is a food delivery simulator, that fetch the data of the menus (or restaurants) and displays it with the map function on the main page.

The add to cart, remove from cart and clear the cart functionalities (items and prices) are implemented using the hooks useContext and useReducer, as these functions are used in different components.

Inside the cart (which is a modal I created to keep the app in the same page, no using router), apart from the options of removing or adding more items of the selected meals, I added the option of ordering the meals.

The header cart button is animated using CSS keyframes, useEffect and JS methods setTimeout and clearTimeout.

The styles are implemented with CSS modules so the classes are unique and avoid name collisions.
