# Automated-Unit-Testing-in-Data-Engineering

This repository contains the submission for Lab 6 of the Data Engineering course, focusing on writing and automating unit tests for Python-based ETL functions. The goal was to build reliable and testable data engineering components that conform to production-grade quality assurance standards.

---

### 🧩 Business Problem

In modern data pipelines, code reliability and repeatability are crucial. ETL processes often break due to bad inputs or schema drift, making it essential to introduce testing frameworks that validate code under different scenarios. This lab explored how to use unit testing frameworks in Python to ensure that the components of a data pipeline behave as expected under various input conditions.

---

### 🎯 Project Objectives

- Write Python functions to clean and transform data
- Build test cases for edge conditions, valid inputs, and failure scenarios
- Validate each function using a structured testing framework
- Use `pytest` to organize, run, and document test outcomes

---

### 🛠️ Solution Approach

1. **Function Development**
   - Developed utility functions for:
     - Normalizing numerical columns
     - Replacing missing values with defaults
     - Validating schema conformance

2. **Test Suite Implementation**
   - Wrote unit tests using `pytest`
   - Created separate test modules to verify:
     - Data shape
     - Column type validations
     - Edge case behavior (e.g., empty inputs)

3. **Execution and Validation**
   - Used assertions to compare actual vs. expected outcomes
   - Employed `pytest` for command-line execution and result reporting

---

### 💡 Business Value

This lab demonstrates how automated testing enhances:

- **Code Reliability:** Ensures that updates or refactoring don’t silently break logic
- **Data Integrity:** Validates that transformations maintain schema and intent
- **Maintainability:** Reduces technical debt by enforcing well-tested, modular code

---

### 🚧 Challenges Encountered

- Testing functions that modify DataFrames in-place
- Dealing with Pandas warning messages in test assertions
- Structuring readable and reusable test cases

---

