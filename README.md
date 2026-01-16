# Node.js with TypeScript Template

This repository serves as a modern template for setting up a Node.js project with TypeScript. It uses modern tooling including tsx for fast development with hot reload.

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/nodejs-typescript-template.git
   ```

2. Navigate to the project directory:
  
   ```bash
   cd nodejs-typescript-template
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

### Development

To run the project in development mode with automatic code reloading, use:

   ```bash
   npm run dev
   ```

This command uses [tsx](https://github.com/privatenumber/tsx) in watch mode to automatically reload your application when files change. tsx is a modern, blazing-fast TypeScript execution engine built on esbuild.

### Build

To build the TypeScript source code, use:

   ```bash
   npm run build
   ```

This command compiles TypeScript files from the `src/` directory to the `dist/` directory.

### Production

To run the built application in production, use:

   ```bash
   npm run prod
   ```

This command executes the compiled `index.js` file from the `dist/` directory.

## Project Structure

- `src/`: Contains the source code of the application.
    
    - `index.ts`: Main entry point of the application.
    - `helloWorld.ts`: Example module demonstrating TypeScript functionality.
- `dist/`: Output directory where the compiled JavaScript files are stored.
    

## Configuration Files

- `tsconfig.json`: TypeScript compiler configuration using modern bundler module resolution.
- `package.json`: Project metadata and script definitions.
