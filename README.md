# TZIV - Turing-Machine - Morse Code Translation with Turing Machine

## Task Overview
Given a Morse code transmission as input, where dot and dash have their standard meanings, and the symbol "/" denotes a short pause (between letters), and two symbols denote a long pause (between words). Design a Turing machine to translate the input text into the Latin alphabet (words separated by an underscore). For the translated text, after the separator '$', also print the character (dot or dash) that occurred more times in the input and the count of its occurrences "extra" compared to the other character (in unary representation). If the counts of both characters are equal, print both characters.

## Example Inputs

- Valid Examples:
    - `.../-./../-./.-//-/.-//--/./-./..$`
    - `-/../--/.$`

- Invalid Examples:
    - `...---/.$`
    - `...//-./$`
    - `...///.-$`

## Turing Machine Design

- Implement a Turing machine that performs Morse code translation.
- Use the Latin alphabet for the output.
- Print the extra occurrences information after the separator '$'.
