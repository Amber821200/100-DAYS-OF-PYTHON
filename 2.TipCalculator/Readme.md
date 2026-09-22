# 💰 Tip Calculator

A simple Python program that calculates how much each person should pay when splitting a bill, including a chosen tip percentage.

This is **Day 2** of my **100 Days of Python** journey, following **100 Days of Code: The Complete Python Pro Bootcamp** by **Dr. Angela Yu**.

---

## 🧠 What I Learned

This project helped me practice:

- Taking user input with `input()`
- Converting input using `int()` and `float()`
- Performing arithmetic calculations
- Working with percentages
- Dividing a bill between multiple people
- Using f-strings for formatted output
- Formatting decimal values with `.2f`

---

## ⚙️ How It Works

The program asks the user for:

1. The total bill amount
2. The desired tip percentage
3. The number of people splitting the bill

It then calculates the amount each person should pay.

### Formula

```text
Bill per person = (Bill ÷ Number of people) × (1 + Tip ÷ 100)
