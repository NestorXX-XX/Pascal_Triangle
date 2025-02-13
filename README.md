# Pascal's Triangle and Combinatorial Tools

This project is a simple interactive web page designed for **Mr. Rosen's Discrete Math class**. It provides tools to explore combinatorial concepts, including:

- **Pascal's Triangle:** Displays Pascal's Triangle row by row with a smooth fade-in effect.
- **Combinatorial Calculator:** Computes binomial coefficients \(\binom{n}{k}\) given user inputs.
- **Binomial Expansion (with Simplification):** Expands and simplifies a binomial expression \((A+B)^n\) when possible, combining exponents for expressions like \(x^2\) and \(1/x\).

## Features

- **Pascal's Triangle:**  
  Enter the desired number of rows and see each row appear sequentially with a fade-in animation.

- **Combinatorial Calculator:**  
  Input values for \(n\) and \(k\) to calculate and display the binomial coefficient \( \binom{n}{k} \).

- **Binomial Expansion (Simplified):**  
  Enter an exponent and two terms (for example, `"x^2"` and `"1/x"`). If the terms match a single variable pattern, the tool simplifies the expansion by combining exponents. The result is rendered in a neat LaTeX format using MathJax.

## How to Use

1. **Download or Clone the Repository:**  
   Get the project files onto your computer.

2. **Open the HTML File:**  
   Open `index.html` in any modern web browser (with JavaScript enabled).

3. **Interact with the Tools:**  
   - **Pascal's Triangle:** Enter the number of rows and click "Show Triangle".
   - **Combinatorial Calculator:** Enter values for \(n\) and \(k\) and click "Calc nCk".
   - **Binomial Expansion:** Enter the exponent and terms \(A\) and \(B\) then click "Expand (A+B)^n" to view the rendered expansion.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.) with JavaScript enabled.
- An internet connection (to load MathJax from CDN) or host MathJax locally.

## Credits

This project was developed for **Mr. Rosen's Discrete Math class** as an educational tool to explore combinatorial concepts and binomial expansions.

## License

This project is open source and free to use for educational purposes. Feel free to modify and adapt the code for your own learning or teaching needs.
