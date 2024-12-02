# Temperature Converter

A simple web-based application that allows users to convert temperatures between Celsius and Fahrenheit. The app includes an intuitive UI for inputting the temperature, selecting the unit of input, and displaying the converted temperature.

---

## Features

- **Temperature Input**: Users can input a temperature value, with built-in validation to ensure only numbers are accepted.
- **Unit Selection**: A dropdown menu or radio buttons to choose whether the input temperature is in Celsius or Fahrenheit.
- **Conversion Button**: A button to trigger the temperature conversion logic.
- **Result Display**: The converted temperature, along with the correct unit, is displayed dynamically.
- **Extras**:
  - Clear button to reset all inputs and outputs.
  - Stylish UI with responsive design.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript

---

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sujalyadav/temperature-converter.git
   ```

2. Navigate to the project directory:
   ```bash
   cd temperature-converter
   ```

3. Open the `index.html` file in your browser:
   - Double-click the file, or
   - Use a local server like Live Server (VS Code extension).

---

## File Structure

```plaintext
temperature-converter/
├── index.html          # Main HTML file
├── style.css           # Stylesheet for the UI
├── script.js           # JavaScript file for conversion logic
├── README.md           # Project documentation
```

---

## How to Use

1. **Input the Temperature**:
   - Enter a numeric value in the input field.
   - Example: `100`.

2. **Select the Input Unit**:
   - Choose whether the input temperature is in **Celsius** or **Fahrenheit** using the dropdown or radio buttons.

3. **Convert**:
   - Click the "Convert" button to display the converted temperature.

4. **Clear (Optional)**:
   - Click the "Clear" button to reset all fields.

---

## Example Conversion

### Input
- Temperature: `100`
- Unit: `Celsius`

### Output
- Converted Temperature: `212°F`

---

## Validation

- Ensures that the input field contains a valid numeric value.
- Displays an error message if invalid data (e.g., letters or symbols) is entered.

---

## Future Enhancements

- Add Kelvin as a conversion option.
- Allow users to copy the result with a single click.
- Include a history section to track previous conversions.

---

## License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## Author

**Sujal Yadav**  
Feel free to reach out at:  
- GitHub: [@sujalyadav](https://github.com/sujalyadav)  
- Email: ysujal208@gmail.com 

---
