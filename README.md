# Abderrahmani Hamza - Personal Profile & Portfolio

Welcome to the source code for my personal profile and portfolio website! This project is a modern, responsive, single-page application built with React.js and Vite. It features a sleek, tech-focused "terminal" aesthetic tailored to highlight my passion for cybersecurity and computer science.

## 🚀 Features

- **Terminal/Tech Aesthetic**: A deep charcoal background with terminal green (`#39d353`) and monospaced font highlights.
- **Hero Section**: A welcoming introduction with terminal command buttons serving as calls to action.
- **Tech Stack & Skills Grid**: Displays my core programming languages (C, Python, PHP/Laravel) and environments (Linux CLI, Neovim).
- **Interactive Knowledge Base**: A structured, tabbed UI that categorizes my educational resources and notes across Cybersecurity, Operating Systems, C, and Python.
- **Terminal Contact Section**: A clean, macOS-inspired terminal window containing clickable links to my Email, LinkedIn, and GitHub.
- **Fully Responsive**: Optimized for seamless viewing on both desktop and mobile devices.

## 📁 Project Structure

This project uses Vite for fast development and bundling. The core application logic and UI are located in the `src/` directory.

```text
Profile/
├── index.html              # The main HTML template
├── package.json            # Project metadata and dependencies
├── vite.config.js          # Vite configuration
├── src/
│   ├── main.jsx            # Entry point for React
│   ├── App.jsx             # Main application layout component
│   ├── index.css           # Global CSS variables and styling
│   ├── components/         # React UI Components
│   │   ├── Hero.jsx        # Header/Intro component
│   │   ├── Skills.jsx      # Tech stack grid
│   │   ├── Resources.jsx   # Tabbed knowledge base
│   │   └── Contact.jsx     # Terminal-styled contact info
│   └── data/
│       └── resources.js    # JSON data for the Knowledge Base items and URLs
```

## 🛠️ Modifying Content

### Changing Resources Data
The learning materials in the Knowledge Base section are populated dynamically. To add, edit, or remove resources or URLs, simply modify the `src/data/resources.js` file.

### Changing Contact Links
To update your email or social media profiles, edit the `contacts` array found inside `src/components/Contact.jsx`.

## 💻 Installation & Usage

To run this project locally on your machine, you'll need [Node.js](https://nodejs.org/) installed.

1. **Navigate to the project directory** (if you aren't already there):
   ```bash
   cd path/to/Profile
   ```

2. **Install the dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **View the site**:
   Open your browser and navigate to the local URL provided by Vite (usually `http://localhost:5173/`).

## ⚙️ Built With

- **React.js**: For component-based UI development.
- **Vite**: For extremely fast local development and building.
- **Lucide-React**: For clean, modern SVG icons used in the links and contact section.
- **Vanilla CSS3**: Leveraging CSS variables and flexbox/grid for responsive layout styling.
