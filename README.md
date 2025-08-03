
# Twitter Clone

A simple frontend clone of Twitter built using HTML, Tailwind CSS, and npm tooling.

## 🧩 Features

- Responsive layout mimicking Twitter's interface
- Styled using Tailwind CSS
- Modular project structure with input/output CSS
- Easy to extend or integrate into a full-stack app

## 📁 Project Structure

```
twitter-clone/
├── index.html              # Main HTML file
├── package.json            # npm config and scripts
├── package-lock.json       # npm dependency lock file
├── tailwind.config.js      # Tailwind configuration
└── css/
    ├── input.css           # Tailwind directives
    └── output.css          # Compiled Tailwind CSS
```

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed on your system

### Installation

1. Clone the repository or download the ZIP
2. Navigate to the project directory
3. Install dependencies:

```bash
npm install
```

4. Build the CSS using Tailwind:

```bash
npx tailwindcss -i ./css/input.css -o ./css/output.css --watch
```

5. Open `index.html` in your browser

## 📦 Technologies Used

- HTML5
- Tailwind CSS
- npm (for Tailwind tooling)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
