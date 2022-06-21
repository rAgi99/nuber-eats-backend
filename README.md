# Nuber Eats

The Backend of Nuber Eats Clone

## User Model:

- id
- createdAt
- updatedAt

- email
- password
- role(client|owner|delivery)

## User CRUD:

- Create Account
- Log In
- See Profile
- Edit Profile
- Verify Email

## Restaurant Model

- name
- category
- address
- coverImage

- Edit Restaurant
- Delete Restaurant

- See Categories
- See Restaurants by Category (pagination)
- See Restaurants (pagination)
- See Restaurant

* Create Dish
* Edit Dish
* Delete Dish

- Orders CRUD

- Orders Subscription:

  - Pending Orders (Owner) (T: createOrder)
  - Pending Pickup Order (Delivery)
  - Order Status (Customer, Delivery, Owner) (T: editOrder)

- Payments (CRON)
