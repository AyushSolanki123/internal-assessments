# Internal Assessments

1.  GraphQL CRUD application using Ngrx and should have auth functionality
    >
        - added auth using jwt
        - created REST apis for authentication and GraphQL apis for CRUD

---

2.  E-Commerce Amplify CRUD application with Ngrx and Auth using Cognito and One-to-Many Relationship in GraphQL
    -   `Modules added`
        >
            1. Auth Module
                - Login user
                - Register User
                - Confirm User
            2. Home Module
                - List Items
                - Search Items using @searchable directive
                - Filter Items
            3. Item Details Module
                - Display Item Information
                - Add Item to Cart
            4. Cart Module
                - Display Cart Items
                - Increase or Decrease Quantity of Items
                - Remove Items from Cart
                - Checkout Cart
            5. User Profile
                - Display User Details
                - Edit User Details
    -   `Miscellaneous`
        >
            1. Created Custom Query in Graphql to list all the cart Items by cart using **@index** directive
            2. Loading Screen until Api call finishes
            3. Toast for Success and Failure
            4. Dynamic Navbar for Auth Module and other modules.

---

3.  Final Assessment - Flight Booking CRUD Application with Ngrx and auth using Cognito
    -   `Modules added`
        >
              1. Auth Module
                  - Login User
                  - Register User
                  - Confirm User
              2. Home Module
                  - GuideLines for Booking Ticket
              3. Book Tickets Module
                  - List All Available Flight
                  - Add Booking
              4. View Details Module
                  - List all Bookings
                  - Update booking
                  - Delete Booking
    -   `Miscellaneous`
        >
              1. Created Custom query in graphql to list all bookings by user
              2. Loading Screen until Api call finishes
              3. Dynamic Navbar for Auth Module and other modules.
              4. Added a shared Module to make loading component available in all modules
              5. Added Auth Guard to handle unauthorized access
              6. Added a page not found Screen
