# Pydantic Tutorial and Examples

## 📌 Introduction

This repository demonstrates how to use **Pydantic** for type validation and data validation in Python.

Pydantic is a powerful library that ensures the correctness of data using **Python type hints**.
It is widely used in **data science, machine learning, APIs (FastAPI), and backend development** to validate user input and prevent runtime errors.

---

## 🚀 Features Covered

### 1. Pydantic Basics

* Installing Pydantic
* Introduction to type and data validation
* Creating models using `BaseModel`

### 2. Type Validation

* ✅ Built-in Types: `int`, `float`, `str`, `bool`
* ✅ Combined Types: `List`, `Dict`, `Set`, `Tuple` (from `typing` module)
* ✅ Special Types: `EmailStr`, `AnyUrl`, `HttpUrl`, `StrictInt`, `StrictFloat`, `StrictBool`, `StrictStr`

### 3. Data Validation

* `Field()` with constraints like `gt`, `lt`, `min_length`, `max_length`, `pattern`, `strict`, `const`
* Default values (2 different approaches)
* Optional fields (`typing` module)
* Custom validation using:

  * `@field_validator` (before/after modes)
  * `@model_validator` (before/after modes)
  * `@computed_field` for derived attributes
* Nested models
* Serialization: `include`, `exclude`, `exclude_unset`

---

## 📂 Project Structure

```
pydantic_tutorial/
│── pydantic.ipynb   # Jupyter Notebook with all examples
│── CheatSheet.png   # Visual summary of Pydantic concepts
│── README.md        # Project documentation
```

---

## 🛠️ Installation

Install the required package:

```bash
pip install pydantic
pip install "pydantic[email]"
```

---

## 🎯 Applications

* ✅ **FastAPI**: Request/response validation
* ✅ **Machine Learning**: Validating dataset schema
* ✅ **ETL Pipelines**: Ensuring data consistency
* ✅ **Config Management**: Validating environment variables

---

## 📖 References

* [Pydantic Documentation](https://docs.pydantic.dev)
* [CampusX Tutorial (YouTube)](https://youtu.be/lRArylZCeOs?si=6LigIPFstzCYvc_y)

---

✨ Created by **Mohd Maaz**
