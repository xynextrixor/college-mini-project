# Deepak Unit Converter

## Project overview
A unit converter for kilometers, miles, kilograms, pounds, and Celsius/Fahrenheit.

## Run in VS Code
1. Open `deepak/unit-converter.html`.
2. Right-click and select **Open with Live Server**.
3. Enter a number, select a conversion, and choose **Convert**.

To copy: create `deepak/unit-converter.html`, paste the full code, save, and run.

## How it works
- The number input supplies the value.
- The dropdown supplies the conversion type.
- JavaScript reads both values.
- A conversion object contains formulas and output units.
- `.toFixed(2)` formats the result to two decimal places.
- Invalid empty input displays an instruction instead of converting.

## Conversion formulas
- Kilometers to miles: `km * 0.621371`
- Miles to kilometers: `miles * 1.60934`
- Kilograms to pounds: `kg * 2.20462`
- Celsius to Fahrenheit: `(C * 9 / 5) + 32`

## Viva questions

**Q1. What is a unit converter?**
It is a program that changes a quantity from one measurement unit to another.

**Q2. Why is `Number()` used?**
It converts the input string into a number.

**Q3. Why validate empty input?**
Empty or invalid input should not be processed as a valid calculation.

**Q4. What is `.toFixed(2)`?**
It converts a number to a fixed decimal format.

**Q5. Can the project add more units?**
Yes. Add a dropdown option and a formula to the conversion object.
