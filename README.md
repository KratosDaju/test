🧮 Retro Button Calculator  
*Clean, simple, and ready for daily math*

[Calculator preview](https://github.com/AadarshaKarki/test/blob/main/Calculator%20preview.png)  


✨ What's inside?

A fully functional, beautifully dark calculator built with **vanilla HTML, CSS, and JS**.  
No external libraries – just a solid grid of buttons, a crisp display, and full keyboard support.

It handles:
- ➕ Addition  
- ➖ Subtraction  
- ✖️ Multiplication  
- ➗ Division  
- 🧮 Percentage (`%`)  
- ⚖️ Sign toggle (`±`)  
- 🔄 Clear (`C`)  
- ⌨️ Keyboard input (numbers, operators, Enter, Backspace, etc.)

🧪 Live demo mindset

Open `index.html` in any modern browser – no build step, no server, no nonsense.  
It even works great on mobile phones (responsive layout).

 🎮 How to use

**Mouse / touch:**  
Just click the buttons. The big `=` gives the result. `C` wipes everything.

**Keyboard (much faster):**  
- Numbers: `0`–`9`  
- Operators: `+`, `-`, `*`, `/`  
- Decimal point: `.`  
- Equals: `Enter` or `=`  
- Clear: `C` / `c` / `Delete` / `Escape`  
- Backspace: deletes last digit  
- Percentage: `%`  
- Sign flip: `±` (or `_` key as a fallback)

> ⚠️ Division by zero shows an alert and resets – because even calculators have boundaries.

 🛠️ Under the hood

The code is one tidy HTML file with embedded style and script.  
- `style` gives a modern glass‑morphism look with smooth button presses.  
- `script` manages state (`currentInput`, `previousInput`, `operation`) and avoids floating‑point surprises (results are rounded to 8 decimals).  
- The display limits length and falls back to exponential notation when numbers get too long.

🧪 Want to tweak?

Go ahead – it's yours.  
- Change colors in the `.calc` / `.op` / `.eq` classes.  
- Add a square root button by extending the operators.  
- Swap the monospace font for something wilder.  

📦 Installation

bash
git clone https://github.com/yourusername/retro-calculator.git
cd retro-calculator
# then open index.html in your browser
