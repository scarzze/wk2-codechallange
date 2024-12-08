# wk2-codechallange
Shopping List Application

This is a simple, interactive shopping list web application where users can:

    Add items to their shopping list.
    Indicate the price of each item.
    Mark items as purchased using checkboxes.
    Clear the entire list when needed.

The app provides an efficient way to manage shopping lists dynamically within a web browser.
Features

    Add Items:
        Users can input an item name and its price.
        Items are displayed dynamically in the list.

    Mark as Purchased:
        Each item includes a checkbox that allows users to mark it as purchased.
        Purchased items are visually updated with a strikethrough style.

    Clear List:
        A "Clear Items" button lets users remove all items from the list at once.

    Non-Persistent Data:
        The shopping list resets upon refreshing the browser, ensuring no data persistence for a lightweight experience.

Technologies Used

    HTML: Provides the structure of the application.
    CSS: Handles the styling for the application, creating a visually appealing interface.
    JavaScript: Implements dynamic functionality for adding, marking, and clearing items from the shopping list.

How to Use

    Clone or download this repository.
    Open the project directory and launch the index.html file in a browser.
    Interact with the app:
        Add items by typing in the input fields and clicking the "Add to Cart" button.
        Use the checkboxes to mark items as purchased.
        Click "Clear Items" to reset the list.

Code Structure

    HTML (index.html):
        Includes the structure of the application, with input fields, a list container, and action buttons.
    CSS (index.css):
        Provides styling for the layout, buttons, and list items.
    JavaScript (index.js):
        Implements core functionality:
            Handles form submissions.
            Updates the DOM dynamically to display items.
            Manages the purchased state using checkboxes.
            Clears the list on demand.

Setup

    Ensure a modern web browser is installed (e.g., Chrome, Firefox).
    Clone the repository:

    git clone <repository_url>

    Open the index.html file in a browser to start using the application.

Future Improvements

    Add local storage to make the shopping list persistent across browser sessions.
    Include an editing feature for item names and prices.
    Enhance the UI/UX with animations and better visual feedback.

Contributing

Feel free to fork this repository and submit pull requests with improvements or bug fixes. Contributions are welcome!
