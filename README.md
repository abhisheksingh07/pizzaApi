# ******************* pizzaApi ******************** #

## Api End Points ##


## Get index page API(GET)
http://localhost:3000/

## Register API(POST)
http://localhost:3000/register

## Login API(POST)
http://localhost:3000/login

## All Menu Items API(GET)
http://localhost:3000/product/menuitems

## Logout API(GET)
http://localhost:3000/logout

## Add new items in product collection API(POST){Only the registerd user with role value true able create new item}
http://localhost:3000/product/add-new-item

## Add item in cart API(POST)
http://localhost:3000/cart/additem-cart

## Get the all the items add in cart API(GET)
http://localhost:3000/cart/getitem-cart

## Delete the item from the cart(DELETE)
http://localhost:3000/cart/empty-cart

## Place the order of cart item(POST)
http://localhost:3000/cart/place-order

## Get the Data of all placed-order(GET){Only the registerd user with role value true able to see the outcome}
http://localhost:3000/orders/dashboard
