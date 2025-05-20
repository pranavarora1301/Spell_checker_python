**Spell Checker App**

A simple Python command-line application that detects and corrects spelling mistakes using the `pyspellchecker` library. Enter any text and get instant corrections, word by word.

---

**Features**

- Detects and corrects spelling errors in real-time
- Preserves correct words
- Interactive loop until user exits
- Uses `pyspellchecker` for high-accuracy word correction

---

**Requirements**

- Python 3.x
- `pyspellchecker` library

Install the required package using pip:

```bash
pip install pyspellchecker
```

**How to Run**

Clone the repository and run the script:
```
git clone https://github.com/yourusername/spell-checker-app.git
cd spell-checker-app
python app.py
```

**Sample Usage**
```
--- Spell Checker ---
Enter text to check (or type 'exit' to quit): This is a spleling test
Correcting 'spleling' to 'spelling'
Corrected text: This is a spelling test
```

**Code Structure**

- SpellCheckerApp class handles correction logic and user interaction
- correct_text(text):
 - Splits input into words
 - Applies correction to each word using self.spell.correction()
- run():
 - Continuously prompts the user for input and displays corrected output

**Limitations**

- Only single-word corrections are applied (not context-aware)
- Works best for English language and dictionary-supported words

**Future Improvements**

- Add support for batch file input
- Include GUI (using tkinter or PyQt)
- Highlight changes instead of replacing directly
- Support multiple languages

**Contributing**

Feel free to fork the repository and submit a pull request. Feedback and improvements are always welcome.
