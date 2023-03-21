The first function is addProductToCart(). This function takes in an argument of productId. Essentially, an unique identifier that helps us know which product we want to add to the cart.

Within the function, we start by finding the product with the matching productId by using the find() method on the products array. We store this product object in a variable called productToAdd.

Next, we check if the product is already in the cart by using the find() method on the cart array. If the product is already in the cart, we increase its quantity by 1. If it's not already in the cart, we add it to the cart array with a quantity of 1.

Finally, we update the visual representation of the cart by calling the renderCart() function, which will display the updated cart to the user.

-------------------------------------------------------------------------------------------

The increaseQuantity function takes in a parameter, productId which represents the unique identifier of a product. The function first finds the product in the cart array that has the same productId using the find() method. If the product is found, the function increases the quantity property of that product by 1. If the product is not found in the cart, the function returns without doing anything.


-----------------------------------------------------
removeProductFromCart function

⭐ user must be able to  remove product completely from cart
⭐ if product exists in the cart remove entire product
- if there no product in the cart, alert() error msg
    "you must first add a product!"
- confirm if user wants to remove from cart?
- 
--------------------------------------





-------------------------------------------------------------------------------------------




-------------------------------------------------------------------------------------------