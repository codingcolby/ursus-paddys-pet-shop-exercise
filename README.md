# Paddy's Pet Shop

Here at Paddy's we sell fantastical an exotic creatures to our clients. We have had someone come in and do some design work and styling for us but still need the application to function properly. The application will allow our staff to add new creatures to our inventory and also checkout customers wishing to adopt our fantastical pets. There is already quite the inventory of fantastical creatures which we have provided.


## Introduction

There are quite a few things already created for you in this project. This project is leveraging [bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/) for the styling and when you open up the `index.html` in your browser you will see that there is styled HTML already available for you. The goal is to add functionality to this preexisting template.

All of the JavaScript to create the needed functionality for this exercise should be placed in the `client.js` file. The `style.css`, `jquery-3.4.1.min.js`, `bootstrap.min.js`, `bootstrap.min.css`, and `client.js` files have all already been sourced into the `index.html`. Take a moment to explore the HTML that is already in place before jumping into **Phase 1**. In the `client.js` file there is a global array called `petInventory` that has a list of creatures already available at the store.

You **should not** use the existing classes in the HTML to target with JavaScript. Create new classes to assign to elements with a `js-` prefix on each of the classes.

The requirements for this exercise are broken into different phases. After completing a phase make sure to take a good solid break this is not meant to be done quickly.

All form fields are wrapped with a `<form>` tag so they will cause the page to reload. Don't forget to prevent the default behavior of the form reloading the page.


### Phase 1: Rendering Current Inventory on the Page

**Goal:** Get the supplied pet inventory to display on the page when the page loads.

1. On initial page load call to a function that will render the pet inventory to the page
1. Each object in the `petInventory` array should be rendered as a **Pet Card** in the **Available Pets** section of the page
1. The HTML for a **Pet Card** is wrapped with `<!-- START: Repeatable Pet Card -->` and `<!-- END: Repeatable Pet Card -->` comments
1. The `name`, `type`, `price`, and `notes` properties for each object in the `petInventory` array should be displayed in the appropriate sections of the **Pet Card**


### Phase 2: Adding a New Pet to Inventory

**Goal:** After having filled out the information for the **Add a New Pet** form the new pet will be added to the page as a **Pet Card**



### Phase 3: Purchase a Pet

**Goal:** When you click the **Purchase** button on an individual **Pet Card** that specific pet is added to the **Selected Creatures** section of the **Checkout**


### Phase 4: Checkout with Purchased Pets

**Goal:** After all of the creatures wanted have been added to the **Checkout** and the customer's information has been entered into the **Customer Info** form after the **Checkout** button is clicked all of the **Checkout** information is cleared out and the purchased creatures are removed from inventory


### Phase 5: Show All Transactions


