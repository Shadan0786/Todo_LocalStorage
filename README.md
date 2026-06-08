# Todo LocalStorage

A simple and elegant todo application that uses browser LocalStorage to persist your tasks.

## Features

- ✅ Create, read, update, and delete todos
- 💾 Auto-saves todos to browser LocalStorage
- 🎨 Clean and responsive user interface
- ⚡ Fast and lightweight
- 📱 Works on all devices

## Technologies Used

- **JavaScript** (86.7%) - Core application logic
- **CSS** (8%) - Styling and layout
- **HTML** (5.3%) - Markup structure

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Shadan0786/Todo_LocalStorage.git
```

2. Navigate to the project directory:
```bash
cd Todo_LocalStorage
```

3. Open `index.html` in your web browser

## Usage

1. **Add a Todo**: Type your task in the input field and press Enter or click the add button
2. **Mark as Complete**: Click on a todo to mark it as complete
3. **Delete a Todo**: Click the delete button next to a todo to remove it
4. **Data Persistence**: Your todos are automatically saved to LocalStorage and will persist even after closing the browser

## How It Works

The application uses the browser's LocalStorage API to save todos locally. When you add, complete, or delete a todo:
- The data is immediately saved to LocalStorage
- On page reload, the application retrieves the saved todos
- No backend server is required

## Project Structure

```
Todo_LocalStorage/
├── index.html          # Main HTML file
├── style.css           # Styling
├── script.js           # Application logic
└── README.md           # This file
```

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License.

## Author

[Shadan0786](https://github.com/Shadan0786)

---

Happy task managing! 🚀
