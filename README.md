### Reactive Devices Project Overview 📱🛒

#### Project Description
[Reactive Devices](https://ukrainiane-panda.github.io/ReactiveDevices/) aims to create a responsive product catalog for mobile phones and accessories. The project utilizes a Figma design and external APIs for fetching product data. It features product listings, detailed pages, a shopping cart, favorites functionality, and search capabilities.

#### Project Structure
- **pages**: Individual page components (Home, Phones, Tablets, Accessories, ProductDetails, Cart, Favorites, Search, NotFound).
- **components**: Reusable components (Header, Footer, ProductsSlider, ProductCard, ProductsList, Loader, Pagination, Breadcrumbs, Search, NoSearchResults).
- **helpers**: Utility functions for managing the cart and other functionalities.

#### Styling
- SCSS files for styling, following BEM (Block Element Modifier) naming conventions.

#### Navigation
- Header links to different pages (Home, Phones, Tablets, Accessories, Favorites, Cart).
- NavLink highlights the current page.
- Breadcrumbs and "Back to top" button for easy navigation.

#### Home Page
- Hot prices, brand new products, and a slider with picture navigation.
- Links to specific product categories.

#### Phones, Tablets, Accessories Pages
- Separate pages with product listings, sorting, and pagination.
- Sort by newest, alphabetically, or by price.
- Pagination for easy navigation.
- Loader for a better user experience.

#### Product Details Page
- Detailed product page with images and suggested products.
- Choose different product images and view related products.
- Back button and breadcrumbs for navigation.

#### Cart Page
- Add, view, and manage cart items.
- Remove items, change quantities, and view the total amount.
- Cart data stored in localStorage for persistence.

#### Favorites Page
- Displays favorite products with add/remove functionality.
- Favorites count shown in the header.

#### Search
- Search bar for filtering products.
- Integrated with pagination and sorting.
- Debounce mechanism for smooth input handling.
- Search parameters stored in the URL.

#### Miscellaneous
- NotFoundPage for undefined routes.
- Error handling for situations where a specific phone is not found.

#### Future Features (marked with *)
- "Back to top" button on the home page.
- Automatic saving of the Cart to localStorage.
- Display total quantity near the Cart icon in the header.
