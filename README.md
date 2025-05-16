# Password Generator

A React-based password generator application that allows users to create secure passwords with customizable options. Built with React, Vite, and styled with Tailwind CSS, this application provides a modern and user-friendly interface for generating strong passwords.

## ✨ Features

- Generate random passwords with one click
- Customize password length (6-100 characters)
- Toggle numbers inclusion for stronger passwords
- Toggle special characters inclusion for enhanced security
- Copy generated password to clipboard instantly
- Modern and responsive UI with Tailwind CSS
- Real-time password strength visualization

## 🛠️ Tech Stack

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- [ESLint](https://eslint.org/) - For code linting and maintaining code quality

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository
```bash
git clone https://github.com/vikasyadav01234/passwordgen.git
cd passwordgen
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

The development server will start at `http://localhost:5173`

## 📁 Project Structure

```
├── src/
│   ├── App.jsx         # Main password generator component
│   ├── main.jsx        # Application entry point
│   ├── App.css         # Component-specific styles
│   ├── index.css       # Global styles including Tailwind
│   └── assets/         # Static assets
│       └── react.svg   # React logo
├── public/
│   └── vite.svg       # Vite logo
└── config files
    ├── eslint.config.js    # ESLint configuration
    ├── postcss.config.js   # PostCSS configuration
    ├── tailwind.config.js  # Tailwind CSS configuration
    └── vite.config.js      # Vite configuration
```

## 🔧 Configuration

This project uses several configuration files:

- `vite.config.js` - Vite bundler configuration
- `tailwind.config.js` - Tailwind CSS customization
- `postcss.config.js` - PostCSS plugins configuration
- `eslint.config.js` - ESLint rules and settings

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
