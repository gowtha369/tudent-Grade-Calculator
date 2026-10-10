# 🎓 Student Grade Calculator

A simple Python program that calculates total marks, average marks, and percentage.

Each subject is marked out of **100**, and all subjects have equal weight.

## ✨ Features

- Choose the number of subjects.
- Enter marks for each subject.
- Calculate total marks.
- Calculate average marks and percentage.
- Reject marks outside the range of 0–100.
- Handle invalid number inputs.

## 🛠️ Built With

**Python 3** — no extra packages needed.

## 🚀 How to Run

1. Install Python 3.
2. Download this repository using **Code → Download ZIP**.
3. Extract the ZIP file.
4. Open a terminal in the folder containing `grade_calculator.py`.
5. Run:

```bash
python grade_calculator.py
```

On Windows, you can also use:

```bash
py grade_calculator.py
```

## 📋 Example

Enter the number of subjects and your marks:

```text
How many subjects? 3
Marks for subject 1: 70
Marks for subject 2: 80
Marks for subject 3: 90
```

The program displays:

```text
--- Your Results ---
Total: 240.00 / 300
Average: 80.00
Percentage: 80.00%
```

## 🧮 Calculations

| Result | Formula |
|---|---|
| Total | Sum of all marks |
| Average | Total ÷ number of subjects |
| Percentage | Total ÷ maximum possible marks × 100 |

Because every subject is out of 100, the average and percentage have the same numerical value.

## 📁 Project Files

| File | Purpose |
|---|---|
| `grade_calculator.py` | Calculator program |
| `README.md` | Project description and instructions |

## ⚠️ Current Limitations

- All subjects must be marked out of 100.
- All subjects have equal weight.
- Results are displayed in the terminal and are not saved.
- Does not assign letter grades or determine pass/fail.

## 🎯 Learning Goals

Practice Python user input, loops, lists, input validation, error handling, and basic calculations.

## 🔮 Future Improvements

- Save results to a file.
- Add subject names.
- Support different maximum marks.
- Support weighted subjects.
