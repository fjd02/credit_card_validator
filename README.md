# 🔐 Credit Card Validator
A simple Python program to validate credit card numbers using the Luhn algorithm.

The Luhn algorithm is as follows:

1. From the right to left, double the value of every second digit; if the product is greater than 9, sum the digits of the products.
2. Take the sum of all the digits.
3. If the sum of all the digits is a multiple of 10, then the number is valid; else it is not valid.

## 🚀 Features
- Validates credit card numbers using the Luhn checksum formula.
- Accepts card numbers with spaces or hyphens.
- Simple command-line interface.
- Written entirely in Python.

## 📂 Project Structure

```
📦 credit_card_validator
┣ 📄 main.py # Main script
┣ 📄 README.md # Project documentation
┗ 📄 LICENSE # License information
```

## 🛠 Installation and Usage
### 🔹 Requirements
- Python 3.x installed on your system.

### 🔹 Running the Script
Clone the repository (or download the script):

```bash
git clone https://github.com/fjd02/credit_card_validator.git
```

and run it:

```bash
python main.py
```

Then, enter the card number when prompted.

### 🔹 Example
#### Input:
```
Introduce the card number: 4556 7375 8689 9855
```

#### Output:
```
VALID!
```

## 🔧 Technologies Used
- 🐍 Python

## ✨ Contributions
Feel free to contribute! Fork the repository, create a new branch, and submit a pull request.

## 📝 License
This project is licensed under the **MIT License**. See the [`LICENSE`](LICENSE) file for details.

