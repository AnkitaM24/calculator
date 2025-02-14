Objective: Build a drag-and-drop calculator builder where users can customize their own calculator layout by adding, removing, and rearranging components like number buttons, operations, and the result display.
Features
Drag & Drop Components: Users can dynamically add and remove buttons (numbers, operations) and arrange them on the calculator.
Predefined Components: Provide basic components like number buttons (0-9), operations (+, -, *, /), and a result display.
Custom Layout: Users can customize the layout by rearranging the components as per their preference.
Calculation Logic: The calculator functions correctly based on user inputs (number buttons and operation buttons).
State Management with Zustand: Uses Zustand for managing dynamic state and components in the calculator.
Tailwind CSS Styling: The UI is responsive and styled using Tailwind CSS for simplicity and cleanliness.
Bonus Features 
Dark Mode Toggle: Users can switch between light and dark modes for better accessibility.
Persistence with Local Storage: The custom layout is saved in local storage, ensuring the calculator layout persists even after the page is reloaded.
Undo/Redo Functionality: Users can undo or redo actions like adding/removing components or rearranging buttons.
Technologies Used
React: JavaScript library for building user interfaces.
Zustand: Lightweight state management for React.
Tailwind CSS: Utility-first CSS framework for creating responsive, clean designs.
JavaScript (ES6): Modern JavaScript syntax for clean and efficient code.

git clone https://github.com/your-username/calculator-builder.git
cd calculator-builder
npm install

How to Use
Add Components:

Drag and drop buttons from the component list (number buttons, operation buttons) to the calculator area.
Remove Components:

Click on any component inside the calculator area to remove it.
Rearrange Layout:

Drag the components (buttons, result display) to rearrange the layout of the calculator.
Perform Calculations:

Click the number buttons and operation buttons to perform arithmetic calculations. The result will be displayed dynamically as you click.
