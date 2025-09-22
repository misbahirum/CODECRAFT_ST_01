# Calculator Test Cases

This document contains detailed test cases for a calculator application that supports addition, subtraction, multiplication, and division operations.

---

## Test Case 1
- **Test Case ID**: TC001
- **Test Description**: Verify addition of two positive integers.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `5`
  2. Press `+`
  3. Enter `7`
  4. Press `=`
- **Expected Results**: Displayed result should be `12`.

---

## Test Case 2
- **Test Case ID**: TC002
- **Test Description**: Verify subtraction resulting in a negative number.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `5`
  2. Press `-`
  3. Enter `10`
  4. Press `=`
- **Expected Results**: Displayed result should be `-5`.

---

## Test Case 3
- **Test Case ID**: TC003
- **Test Description**: Verify multiplication with decimal numbers.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `2.5`
  2. Press `*`
  3. Enter `4`
  4. Press `=`
- **Expected Results**: Displayed result should be `10`.

---

## Test Case 4
- **Test Case ID**: TC004
- **Test Description**: Verify division resulting in a whole number.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `20`
  2. Press `/`
  3. Enter `4`
  4. Press `=`
- **Expected Results**: Displayed result should be `5`.

---

## Test Case 5
- **Test Case ID**: TC005
- **Test Description**: Verify division resulting in a decimal value.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `7`
  2. Press `/`
  3. Enter `2`
  4. Press `=`
- **Expected Results**: Displayed result should be `3.5`.

---

## Test Case 6
- **Test Case ID**: TC006
- **Test Description**: Verify division by zero (invalid input).
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `9`
  2. Press `/`
  3. Enter `0`
  4. Press `=`
- **Expected Results**: Calculator should display an error message like *"Cannot divide by zero"*.

---

## Test Case 7
- **Test Case ID**: TC007
- **Test Description**: Verify handling of non-numeric input (invalid input).
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `A`
  2. Press `+`
  3. Enter `5`
  4. Press `=`
- **Expected Results**: Calculator should display an error message or reject the input.

---

## Test Case 8
- **Test Case ID**: TC008
- **Test Description**: Verify multiple operations following BODMAS rules.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `5`
  2. Press `+`
  3. Enter `3`
  4. Press `*`
  5. Enter `2`
  6. Press `=`
- **Expected Results**: Calculator should follow BODMAS, so result should be `11` (since `3*2=6`, then `5+6=11`).

---

## Test Case 9
- **Test Case ID**: TC009
- **Test Description**: Verify calculation with negative numbers.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `-4`
  2. Press `*`
  3. Enter `6`
  4. Press `=`
- **Expected Results**: Displayed result should be `-24`.

---

## Test Case 10
- **Test Case ID**: TC010
- **Test Description**: Verify handling of large numbers.
- **Preconditions**: Calculator is open and functional.
- **Test Steps**:
  1. Enter `999999`
  2. Press `+`
  3. Enter `1`
  4. Press `=`
- **Expected Results**: Displayed result should be `1000000`.

---
