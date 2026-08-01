# e-plantShopping — Paradise Nursery

An elegant, feature-rich e-commerce web application built with React and Redux Toolkit for browsing and purchasing houseplants. This project was developed as the final capstone assignment for the IBM/Coursera Front-End Developer certification program.

---

## 🌿 Project Overview

Paradise Nursery brings the joy of greenery directly to your screen. Users can explore a curated landing page, browse a structured directory of diverse indoor plant categories, manage items inside a responsive shopping cart ecosystem, and view real-time price calculations synced globally via state management.

---

## 🚀 Key Features Built & Implemented

### 1. Landing Page (`App.jsx` & `App.css`)
*   **Immersive Visual Design:** Rich background imagery styling featuring automated sizing constraints.
*   **Welcome Module:** Explicit corporate branding statements outlining our environmental philosophy.
*   **Interactive Controls:** Smooth operational "Get Started" buttons handling active view state transitions directly.

### 2. Product Directory (`ProductList.jsx` & `ProductList.css`)
*   **Curated Grid Layout:** Showcases at least **6 unique houseplants grouped across 3 distinct natural categories**.
*   **Informational Detail Cards:** Each plant profile displays structural thumbnails, verified names, and formatted unit costs.
*   **State-Aware UI Buttons:** Action tags immediately alter layout properties to block multiple continuous clicks once added.
*   **Global Layout Navigation Elements:** Fixed navigation layer featuring operational links mapping back to historical view states.
*   **Reactive Header Counter Elements:** Badges that change color and increment automatically as items enter the workspace.

### 3. Shopping Cart Architecture (`CartSlice.jsx` & `CartItem.jsx`)
*   **Redux State Engine:** Complete pipeline handling additions, baseline decreases, and deletions without component coupling.
*   **Granular Financial Feedback Layers:** Computes both overall basket investments alongside local multi-item cost subsets.
*   **Actionable Adjusters:** Quick-tap controls modifying quantities with inline validation to prevent negative values.
*   **Dynamic Checkout Feedback Blocks:** Triggers non-blocking temporary notification flags previewing future system extensions.
*   **Back-Tracking Navigation Blocks:** Smart loops returning users to their exact scrolling coordinates when picking extra products.

---

## 🛠️ Tech Stack & Engineering Concepts Used

*   **View Layer:** React.js (Functional components, Hooks layout structures, State preservation hooks).
*   **Global State Container:** Redux Toolkit (`configureStore`, `createSlice` patterns).
*   **Styling Architecture:** Modern CSS Grid architecture, Flexbox layouts, Media Queries (`@media`) targeting mobile and desktop viewports.
*   **Asset Tooling:** Local project images, modern structural layout icons, custom icon frameworks.

---

## 📂 Submission Component Directory Mapping

For peer grading validation, here are the core application modules structured within the repository:

| Requirement / Component File | Scope & Technical Implementation Details |
| :--- | :--- |
| **`AboutUs.jsx`** | Contains company vision statements, operational parameters, and brand descriptions. |
| **`App.css`** | Manages typography resets, immersive landing wrapper backgrounds, and structural hero buttons. |
| **`App.jsx`** | Core application router rendering landing pages, conditional view states, and structural text layouts. |
| **`CartSlice.jsx`** | The Redux Toolkit data layer managing the cart array, quantity state updates, and tracking algorithms. |
| **`ProductList.jsx`** | Grid layouts showcasing categories, dynamic product mapping, and disabled status indicators. |
| **`CartItem.jsx`** | Sub-totals mapping component, functional action handlers, and back-tracking navigation buttons. |

---

## ⚙️ Local Development Setup Instructions

Follow these steps to run the project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/e-plantShopping.git](https://github.com/YOUR_GITHUB_USERNAME/e-plantShopping.git)
   cd e-plantShopping
Verify that all functionalities work correctly before final submission.
