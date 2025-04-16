# Calculator App

A simple calculator application built with TypeScript and HTML, designed for basic arithmetic operations. The app is served locally using `lite-server`.

## Features

- Perform basic arithmetic operations: Addition, Subtraction, Multiplication, and Division.
- Clear the display to reset calculations.
- Built with TypeScript for type safety and structured code.

## Project Structure

```
calculator-app/
├── src/
│   ├── calculator.ts        # TypeScript code for calculator logic
│   └── index.html           # HTML file for the calculator UI
├── dist/
│   ├── calculator.js        # Compiled JavaScript file
├── bs-config.json           # Configuration for lite-server
├── tsconfig.json            # TypeScript configuration file
├── package.json             # Project metadata and dependencies
```

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- A package manager like `npm`.

## Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd calculator-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Compile TypeScript to JavaScript:
   ```bash
   npx tsc
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Use the calculator buttons to perform arithmetic operations.
- The result of calculations will be displayed in the input field.

## Troubleshooting

- If the app doesn't start, ensure `lite-server` is installed correctly and the `calculator.js` file is generated in the `dist/` folder.
- Check the browser console (F12 > Console) for any errors.

## License

This project is licensed under the MIT License.
