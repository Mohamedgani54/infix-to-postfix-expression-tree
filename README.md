# Expression Tree Lab — DSA Working Model

Interactive infix-to-postfix conversion using recursive descent parsing, an expression tree, and postorder traversal. This is a different approach from Shunting Yard.

## Run
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. Enter `(A+B)*C-D/E` and click **Build tree**.
4. Click **Next node** to step through postorder traversal. Use **Previous** and **Reset traversal** to repeat.

No server or package installation is needed.

Example: `(A+B)*C-D/E` → `AB+C*DE/-`

Files: `index.html` (interface), `style.css` (design), `script.js` (parser/tree/traversal), `README.md` (instructions).

Complexity: O(n) time and O(n) space. Supports single-character alphanumeric operands, `+ - * / ^`, and parentheses.
