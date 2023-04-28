---
layout: blog
type: blog
title: "E1: UI Basics Technical Essay"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Assignment 3 Checkpoint
  - Blog
---

1.Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype
In screencast. Link here: https://drive.google.com/file/d/1c9tcFr6CwuTGvwUEx8LTyKcfhB9c189m/view?usp=share_link 

2.Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.
There is a separate page that the user can view and edit. Users select a quantity of a product on the store page then click the add to cart button. Users can update the quantity of their cart with an update cart button. 

3.Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.
How sessions will be used to manage the shopping cart, my partner did the routing for this, from what I am understanding, the item is added to the session with a variable products_key that is first an empty array for each product type (earrings, rings, bracelets,necklaces). But as the user adds products, it will start adding the items and amount wanted into the array.  

4.How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
Avoid access when the user tries to make a purchase, the server will check for a cookie, if the user does not have a cookie it will make them login first. If they do not have an account, then they have to register. Security concerns: cookies being vulnerable and easy to access and change, thus could access someone else’s account or purchases. 

5.Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)
After logging-in, the products page says welcome (username), the invoice page also says thank you (username).

6.If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
I am working with a partner. My partner, as mentioned before, did a lot of work already with the routing. I will be working on the admin-back end side and IRS and anything else that comes up. 

7.How are you approaching Assignment 3 differently than Assignment 2?
I am approaching Assignment 2 differently by looking up and doing more to understand how cookies and sessions work because the concept is completely new, which is different from Assignment 2 where I only need to figure out the problems and come up with ways to implement them into code.


