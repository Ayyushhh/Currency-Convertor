# Currency Converter

![Currency Converter Screenshot](./currencyConvertor/src/assets/ss.png)

This project is a simple currency converter application built using React and Tailwind CSS. It allows users to convert amounts between different currencies using real-time exchange rates.

## Features

- Convert amounts between various currencies.
- Swap between "From" and "To" currencies.
- Responsive design with a visually appealing background.

## Technologies Used

- **React**: For building the user interface.
- **Tailwind CSS**: For styling the application.
- **JavaScript**: For logic and functionality.
- **Currency API**: For fetching real-time currency exchange rates.

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the application**:
   ```bash
   npm start
   ```

## Usage

- Enter the amount you want to convert in the "From" field.
- Select the currencies you want to convert from and to.
- Click "Convert" to see the converted amount.
- Use the "Swap" button to switch the "From" and "To" currencies.

## Components

- **App.jsx**: Main component that handles the conversion logic and UI.
- **InputBox**: A reusable component for input fields and currency selection.
- **useCurrencyInfo**: Custom hook to fetch and manage currency data.

## Configuration

- **tailwind.config.js**: Tailwind CSS configuration file.
- **postcss.config.js**: PostCSS configuration file for processing CSS.

## License

This project is licensed under the MIT License.