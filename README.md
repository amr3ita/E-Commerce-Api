
# E-Commerce API

This is my first api project with .net and i hope i can do more best in the future and i will update this project if i get some ideas to update it

A .Net API project with .Net7, in this project i made controllers for:
- Brands
- Categories
- Products
- Orders
- Accounts
- Roles

I made reRepositories(Services) for every controller methods(end points) each Repository class has its own interface

## What Can I Do In This Project!!

- For `Brands`,`Categories`,`Products`,`Orders` I can make CRUD (Create, Read, Update, Delete) operations on each one.
- For `Accounts` I can Register,Login,assign user to Role.
- For `Roles` I can get all Roles, add new role, delete role.

## features

- When someone register the default role is user.
- When I make order the product quantity of product will be reduced, and if i delete order it reset(increase) the quantity again to the product.
- some features only admins can do:
    - add, update and delete Brand
    - add, update and delete category
    - add, update and delete product
    - add, delete Role

- Not anyone can update or delete order and order item only the owner of this order.

[Video](https://www.linkedin.com/posts/amr-walied-1856131b4_backend-backenddeveloper-dotnet-activity-7166107325840265217-1zaO?utm_source=share&utm_medium=member_desktop)
