# ⚖️ BMI Calculator – Python Project

### InfozaTech Python Programming Internship | Task 3

## 📌 About the Project

The **BMI Calculator** is a Python-based application developed as part of my Python Programming Internship at **InfozaTech**.

This project calculates a person's Body Mass Index (BMI) based on their weight and height. It also classifies the calculated BMI into different categories, such as Underweight, Normal Weight, Overweight, and Obese.

The application uses Python fundamentals, conditional statements, exception handling, and mathematical operations to provide accurate calculations and a user-friendly command-line experience.

## 🚀 Features

- **BMI Calculation:** Calculates BMI using weight and height.
- **Category Classification:** Identifies the BMI category based on the calculated result.
- **User Input:** Accepts weight in kilograms and height in centimetres.
- **Unit Conversion:** Automatically converts height from centimetres to metres.
- **Input Validation:** Prevents zero and negative weight or height values.
- **Error Handling:** Handles invalid numerical inputs using exception handling.
- **Formatted Output:** Displays BMI results rounded to two decimal places.

## 🧮 BMI Formula

BMI is calculated using the following mathematical formula:

```text
BMI = Weight (kg) / Height (m)²
```

**Example:**

- Weight: 65 kg
- Height: 170 cm (1.70 m)

```text
BMI = 65 / (1.70 × 1.70)
BMI = 22.49
```

## 📊 BMI Categories

| BMI Range | Category |
|---|---|
| Below 18.5 | Underweight |
| 18.5 – 24.9 | Normal Weight |
| 25.0 – 29.9 | Overweight |
| 30.0 and above | Obese |

*Note: These are standard adult BMI categories. BMI interpretation for teenagers requires age- and sex-specific growth charts.*

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Concepts Used:**
  - Variables and Data Types
  - User Input and Output
  - Type Conversion
  - Arithmetic Operations
  - Conditional Statements (if, elif, else)
  - Exception Handling (try, except)
  - Input Validation
  - Mathematical Calculations

## 💻 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/maverick092/infozatech-bmi-calculator.git
```

### Step 2: Navigate to the Project Folder

```bash
cd infozatech-bmi-calculator
```

### Step 3: Run the Python File

```bash
python bmi_calculator.py
```

## 📂 Project Structure

```text
infozatech-bmi-calculator/
│
├── bmi_calculator.py
└── README.md
```

## 🖥️ Sample Output

```text
================================
       BMI CALCULATOR
================================

Enter your weight (in kg): 65
Enter your height (in cm): 170

Your BMI is: 22.49
BMI Category: Normal Weight

================================
```

## 🧪 Testing

The application was designed to handle different input scenarios:

| Test Case | Input | Expected Behaviour |
|---|---|---|
| Normal BMI | 65 kg, 170 cm | Normal Weight |
| Underweight | 45 kg, 170 cm | Underweight |
| Overweight | 85 kg, 170 cm | Overweight |
| Obese | 100 kg, 170 cm | Obese |
| Invalid Input | abc, 170 cm | Displays error message |
| Zero Height | 65 kg, 0 cm | Displays validation error |

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Applying Python fundamentals to develop a real-world application.
- Performing mathematical calculations using Python.
- Implementing conditional logic for decision-making.
- Handling invalid inputs using exception handling.
- Improving code readability and program reliability.
- Understanding how to build interactive command-line applications.

## 👨‍💻 Internship Details

| Detail | Information |
|---|---|
| Organization | InfozaTech |
| Internship Domain | Python Programming |
| Task Number | Task 3 |
| Project Name | BMI Calculator |
| Language | Python |

## 🙌 Acknowledgement

I would like to thank **InfozaTech** for providing me with this internship opportunity and allowing me to improve my Python programming skills through practical project development.

This project is another milestone in my journey of learning Python, strengthening my programming fundamentals, and developing practical applications.

---

⭐ If you find this project useful, feel free to explore the repository!

**Developed with Python 🐍**
