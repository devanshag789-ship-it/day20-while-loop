# #DAY 20 — WHILE LOOP IN PYTHON

---

## 1. Introduction to While Loop

A **while loop** is used when we want to repeat a block of code **as long as a condition remains True**.

The loop keeps running until the condition becomes **False**.

Real-world idea:

- Keep asking for password until correct
- Count numbers until a limit is reached
- Run a program until the user exits

---

## 2. Basic Syntax

```python
while condition:
	code
```

- The condition is checked first.
- If it is **True**, the loop runs.
- If it becomes **False**, the loop stops.

---

## 3. Simple Example

```python
i=1

while i<=5:
	print(i)
	i+=1
```

Output:

```python
1
2
3
4
5
```

Explanation:

- The loop runs while `i <= 5`.
- After each run, `i` increases by 1.

---

## 4. Example — Counting Down

```python
count=5

while count>0:
	print(count)
	count-=1
```

Output:

```python
5
4
3
2
1
```

---

# Why `while` ?

## 5. Password Manager

```python
password=""

while password!="python":
	password=input("Enter password: ")

print("Access granted")
```

The loop keeps asking until the correct password is entered.

---

## 6. Infinite Loop

If the condition never becomes False, the loop runs forever.

```python
count=1
while True:
	print("Running...",count)
	count+=1
```

To stop it manually, press **Ctrl + C**.

---

## 7. Important Points

- Used when the number of repetitions is **not fixed**.
- The condition must eventually become False.
- Always update the variable inside the loop.

---

# 📝 SUMMARY — WHILE LOOP

- Runs while condition is True
- Stops when condition becomes False
- Useful when repetition count is unknown

---

## One-Line Concept

> A `while` loop repeatedly executes a block of code as long as a specified condition remains True.
> 

# 🧠 Practice Exercise

## 📝Quick Quiz

Modify the above **“Password Manager”** to make it behave more like a real system.

If the user enters the wrong password, the program should display:

```python
Wrong Password!!!!
Try Again....
```

The program should keep asking for the password until the correct password is entered.
