# Vite + React + TanStack Boilerplate

This boilerplate provides a modern setup for building React applications using the following technologies:

- **Vite**: Lightning-fast build tool and development server.
- **React**: Popular JavaScript library for building user interfaces.
- **TanStack Router**: Flexible and type-safe routing for React.
- **TanStack Query**: Powerful data-fetching and caching for React.
- **TanStack Store**: Simplified global state management.
- **shadcn/ui**: UI components built with Radix and Tailwind CSS.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **TypeScript**: Typed JavaScript for scalable and maintainable code.

## Features

- 🚀 **Fast Development**: Powered by Vite's blazing fast build and HMR.
- 📦 **Modular Architecture**: Clean separation of concerns with state, routing, and UI components.
- 🔥 **State Management**: Manage global and server state with TanStack Query and TanStack Store.
- 🎨 **Beautiful UI**: Preconfigured shadcn/ui components styled with Tailwind CSS.
- 📘 **Type Safety**: End-to-end type safety with TypeScript.
- 🛠️ **Easily Customizable**: Ready for extensions and configuration tweaks.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [bun](https://bun.sh/) (preferred) or npm/yarn/bun

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/sebdrapier/VRTS-boilerplate.git
   cd VRTS-boilerplate
   ```

2. Install dependencies:

   ```bash
   bun install
   ```

3. Start the development server:

   ```bash
   bun run dev
   ```

   The application will be running at `http://localhost:5173`.

### Building for Production

To build the application for production:

```bash
bun run build
```

The built files will be in the `dist` directory.

### Linting and Formatting

This boilerplate includes configurations for ESLint and Prettier. Run the following commands to lint and format your code:

- Lint:

  ```bash
  bun run lint
  ```

## Project Structure

```plaintext
├── public          # Static assets
├── src
│   ├── components  # Reusable components
│   ├── hooks       # Custom hooks
│   ├── pages       # Page components
│   ├── routes      # Application routes (TanStack Router)
│   ├── state       # Global state (TanStack Store)
│   ├── styles      # Global styles (Tailwind CSS)
│   ├── utils       # Utility functions
│   ├── App.tsx     # Application entry point
│   └── main.tsx    # Vite entry point
└── vite.config.ts  # Vite configuration
```

## Tailwind CSS Configuration

Tailwind CSS is preconfigured with shadcn/ui. You can customize the `tailwind.config.js` file to suit your project's needs.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue if you encounter any problems.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
