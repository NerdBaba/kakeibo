# Kakeibo - Mindful Spending Tracker 🏡➕️簿

A simple, visually appealing frontend prototype for a personal finance application inspired by the Japanese Kakeibo method. This application aims to help users track their spending mindfully.

*(Note: This is currently a frontend-only demonstration with static data and UI interactions. No data is saved persistently.)*

<!-- Add a screenshot or GIF of the app in action here -->
<!-- ![Kakeibo App Screenshot](link/to/your/screenshot.png) -->

## ✨ Features

*   **Splash Screen:** Elegant loading animation featuring the Kanji for Kakeibo (家計簿).
*   **Dashboard:**
    *   Overview of today's and this month's spending.
    *   Monthly budget visualization with a "bamboo growth" progress bar.
    *   List of recent expense entries.
    *   Quick action buttons to add expenses or set budgets.
*   **Add Expense:**
    *   Intuitive form to input amount, category, date, payment method, and optional notes.
    *   Visual category selection with icons.
    *   Loading state indicator on the save button.
*   **Expense History:**
    *   List of past expenses with details (category, date, amount, payment method).
    *   Search bar (UI only).
    *   Placeholder filter/sort buttons.
    *   Edit/Delete options per entry (UI only).
*   **Budget Management:**
    *   Overall monthly budget progress.
    *   Breakdown of budgets by category with individual progress bars.
    *   Visual warning animation (`pulse`) for categories nearing their budget limit.
*   **Payment Methods:**
    *   View and manage different payment types (Cash, Card, UPI).
    *   Modals to add new Credit/Debit Cards and UPI providers (UI only).
*   **Settings:**
    *   Placeholders for managing categories, currency selection, security (passcode/biometrics toggles), data export/deletion, and a mindful reflection prompt.
*   **Japanese Aesthetic:**
    *   Uses Noto Sans & Noto Sans JP fonts.
    *   "Washi paper" background texture.
    *   Subtle animations inspired by ink strokes, bamboo growth, and ripples.
*   **Responsive Design:** Built with Tailwind CSS for adaptability to mobile screen sizes (primarily designed for `max-w-md`).
*   **Enhanced UI Elements:** Sticky header, profile dropdown menu, notification icon (with badge simulation), modal dialogs.

## 🛠️ Technology Stack

*   **HTML5:** Semantic markup for structure.
*   **CSS3:**
    *   **Tailwind CSS:** Utility-first CSS framework for rapid styling.
    *   **Custom CSS:** For animations (Keyframes: `brushStroke`, `fadeIn`, `inkSpread`, `slideUp`, `strokeDraw`, `pulse`, `spin`), specific component styles (`washi-bg`, `bamboo-growth`, `ripple`, `card`, `modal`, etc.), and font imports.
*   **JavaScript (Vanilla):**
    *   DOM manipulation for page navigation, modal control, splash screen timing.
    *   Event handling for buttons, profile menu, category selection.
    *   Simulating loading states and notifications.
    *   Applying animations dynamically.
*   **Google Fonts:** Noto Sans & Noto Sans JP.

## 🚀 Getting Started

As this is a frontend-only prototype contained within a single HTML file:

1.  **Clone or Download:** Get the `kakeibo` directory containing the `index.html` file.
    ```bash
    git clone <repository-url>
    cd <repository-directory>/kakeibo
    ```
    OR
    Download the `index.html` file directly.

2.  **Open in Browser:** Simply double-click the `index.html` file, or right-click and choose "Open With" your preferred web browser (like Chrome, Firefox, Safari, Edge).

That's it! You can now interact with the user interface.

## 💡 Potential Future Enhancements

*   **Data Persistence:** Implement Local Storage or connect to a backend API (like Firebase, Supabase, or a custom REST API) to save and retrieve user data.
*   **User Authentication:** Add sign-up/login functionality.
*   **Functional Actions:** Implement actual edit, delete, search, and filter logic for expenses and budgets.
*   **Data Visualization:** Add charts (e.g., using Chart.js) to visualize spending patterns and budget adherence.
*   **Reporting:** Generate monthly/yearly spending reports.
*   **Real Notifications:** Implement a proper notification system.
*   **PWA Features:** Add a service worker and manifest file for offline capabilities and installability.
*   **Category Management:** Allow users to add, edit, and delete spending categories.
