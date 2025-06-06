# Task Manager App

A simple and elegant task management application built with React, TypeScript, and Tailwind CSS.

## Features

- ✨ View a list of tasks
- ➕ Add new tasks
- ✅ Mark tasks as completed
- 🗑️ Delete tasks
- 💅 Modern and responsive UI
- 🎨 Clean and intuitive design

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite (Build tool)

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 14.0 or higher)
- npm (usually comes with Node.js)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/eyob2m/taskapp.git
cd taskapp
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit:
```
http://localhost:5173
```

## Project Structure

```
taskapp/
├── src/
│   ├── components/
│   │   └── Todo.tsx       # Main Todo component
│   ├── types/
│   │   └── Task.ts        # Task interface definition
│   ├── App.tsx           # Root component
│   └── index.css         # Global styles and Tailwind imports
├── tailwind.config.js    # Tailwind CSS configuration
└── package.json         # Project dependencies and scripts
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with React and TypeScript
- Styled with Tailwind CSS
- Bootstrapped with Vite
