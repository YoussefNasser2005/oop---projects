📘 clsUtil Class (English)

The clsUtil class is a small C++ utility library that provides helper functions to simplify common programming tasks.
Instead of rewriting the same logic (random generators, swapping, encryption, array operations), you can use this ready-made toolbox.

✨ Key Features
🎲 Random Generators

RandomNumber(from, to) ➝ Returns a random number within range.

GetRandomCharacter(CharType) ➝ Returns a random character (small, capital, digit, or mixed).

GenerateWord(CharType, Length) ➝ Generates a random word of given length.

GenerateKey(CharType) ➝ Generates a random key (e.g., ABCD-EFGH-IJKL-MNOP).

GenerateKeys(Number, CharType) ➝ Generates multiple keys.

📑 Array Operations

ReadArray() ➝ Reads elements from user input.

PrintArray() ➝ Prints array elements.

ShuffleArray() ➝ Shuffles array elements.

FillArrayWithRandomNumbers() ➝ Fills array with random numbers.

FillArrayWithRandomWords() ➝ Fills array with random words.

FillArrayWithKeys() ➝ Fills array with random keys.

🔄 Swap Functions

Supports swapping between:

Integers int

Floats float

Strings string

Dates clsDate

🔐 Encryption & Decryption

EncryptText(Text, Key) ➝ Encrypts text by shifting characters.

DecryptText(Text, Key) ➝ Decrypts text using the same key.
