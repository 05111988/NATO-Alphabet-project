# NATO-Alphabet-project
This Python project converts words into their corresponding NATO phonetic alphabet codes. It uses pandas to read a CSV file containing letter-to-code mappings and then prompts the user to enter a word. The program outputs each letter as its NATO phonetic equivalent, ensuring accurate communication for spelling over radio, phone, or noisy channels.
NATO Phonetic Alphabet Converter
A Python program that converts any word into its NATO phonetic alphabet representation. This is useful for clear communication in noisy environments or over radio/telephone.

📜 Features
Reads NATO phonetic codes from a CSV file.

Converts user input into a list of phonetic words.

Implements dictionary comprehension with pandas.

Handles invalid inputs gracefully.

🛠 Technologies Used
Python 3

Pandas for CSV reading and DataFrame handling

🚀 How It Works
The program loads the CSV file containing letter-to-phonetic mappings.

It prompts the user to enter a word.

Each letter is converted to its NATO phonetic equivalent.

The phonetic list is displayed.

💻 Example Usage

Edit
Enter a word: HELLO
['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']
File Structure
NATO Alphabet Project
│── nato_phonetic_alphabet.csv   # Data file containing letter-to-code mappings
│── NATO ALPHABET.ipynb          # Jupyter Notebook with code
📌 Requirements
Install dependencies before running:

pip install pandas
▶️ Running the Project
Run the Jupyter Notebook or Python script:

python nato_alphabet.py





