# iris-one-vs-all-logistic-regression
Multiclass Logistic Regression implemented completely from scratch using NumPy and the One-vs-All (OVR) strategy on the Iris dataset.

# Multiclass Logistic Regression (One-vs-All) from Scratch

This repository contains an implementation of Multiclass Logistic Regression using the One-vs-All (One-vs-Rest) strategy, built entirely from scratch with Python and NumPy.

## Overview

The notebook covers the extension of binary logistic regression to multiclass classification problems using the **Iris dataset**:
- **One-vs-All Strategy:** Converts a multi-class problem into multiple binary classification tasks using one-hot encoded labels (`label_binarize`).
- **Matrix Formulation:** Implements vector/matrix-based sigmoid activation, weight matrices, and multi-class Binary Cross-Entropy loss.
- **Gradient Descent Optimization:** Trains the weight matrix from scratch using full-batch gradient descent.
- **Evaluation:** Uses `argmax` over predicted probabilities to compute multi-class accuracy.

## Requirements

- Python 3
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook



# رگرسیون لجستیک چندکلاسه (روش One-vs-All) از صفر

این مخزن شامل پیاده‌سازی رگرسیون لجستیک چندکلاسه با استفاده از استراتژی One-وس-All (یا One-vs-Rest) است که کاملاً از صفر با پایتون و NumPy پیاده‌سازی شده است.

## بررسی اجمالی

این نوت‌بوک گسترش رگرسیون لجستیک دوتایی به مسائل دسته‌بندی چندکلاسه با استفاده از **دیتاست Iris** را پوشش می‌دهد:
- **استراتژی One-vs-All:** تبدیل یک مسئله چندکلاسه به چندین مسئله دسته‌بندی دوتایی با استفاده از برچسب‌های وان-هات (`label_binarize`).
- **فرمول‌بندی ماتریسی:** پیاده‌سازی فعال‌سازی سیگموید بر اساس بردار/ماتریس، ماتریس وزن‌ها و تابع هزینه کراس‌انتروپی دوتایی چندکلاسه.
- **بهینه‌سازی گرادیان نزولی:** آموزش ماتریس وزن از صفر با استفاده از گرادیان نزولی دسته‌ای (Full-batch).
- **ارزیابی:** استفاده از تابع `argmax` روی احتمالات پیش‌بینی‌شده برای محاسبه دقت چندکلاسه.

## پیش‌نیازها

- پایتون ۳
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
