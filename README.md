# eBuy

An Android e-commerce application built with Java and Room database for browsing, purchasing, and managing products.

## Features

- User authentication (sign up / sign in)
- Product browsing with search and filter
- Shopping cart with checkout functionality
- Order history tracking
- Admin controls for product management (add, edit, delete products)
- Role-based access (regular user and admin)

## Technologies

- Java
- Android SDK (compileSdk 34, minSdk 26)
- Room Database (SQLite ORM)
- AndroidX (AppCompat, Material Design, ConstraintLayout, CardView)
- RecyclerView for list rendering

## Project Structure

```
app/src/main/java/com/jasdeepsingh/ebuy/
  activites/         - Activities (MainActivity, Landing_Page, Sign_In_Page, Sign_Up_Page, Admin_Controls, EditProductActivity)
  entities/          - Data models (User, Product, ShoppingCart)
  db/                - Database layer (AppDatabase, BuyDAO)
  RecyclerViewContents/ - Adapters (ProductAdapter, UserAdapter)
  Util.java          - Utility/helper methods
```

## How to Run

1. Open the project in Android Studio
2. Sync Gradle dependencies
3. Run on an emulator or physical device (Android 8.0+)
