# 🚗 Urban Routes – Web Functional Testing
### 📌 Project Overview

This project focuses on web application testing for the Car Sharing functionality of the Urban Routes platform.

#### The scope included:

UI testing (design validation)

Functional testing

Cross-browser testing

Test case design

Bug reporting in Jira

Execution tracking (PASS / FAIL / BLOCKED)

### 🖥 Test Environments

#### Testing was performed in:

Google Chrome – 800x600 resolution

Mozilla Firefox – 1920x1080 resolution

Design testing was executed in both environments.
Functional logic validation was performed in one environment as required.

### 📋 Test Documentation

All documentation was structured in a single Excel file containing four sheets:

Design Checklist (54+ verification points)

Payment Method & Add Card Functional Checklist

Test Cases – "Reserve" Button Logic

Test Cases – Car Reservation Flow

Each failed test case includes a linked Jira bug report.

### 🔍 Testing Scope
#### 1️⃣ UI / Design Testing

Layout validation

Typography and spelling verification

Element positioning

Map behavior validation

Modal window verification

Cross-browser comparison

Critical map-related bugs were identified and documented.

#### 2️⃣ Payment Method & Card Validation

###### Applied:

Equivalence Class Partitioning

Boundary Value Analysis

###### Validated:

Card number length and format

CVV validation rules

Button enable/disable states

Multiple card handling

Duplicate prevention

Usability issues (auto-formatting bug detected)

#### 3️⃣ "Reserve" Button Logic

###### Validated:

All possible button states

Dynamic button text changes

Behavior depending on completed fields

Positive and negative flows

###### Used structured test cases including:

ID

Preconditions

Steps

Expected Results

Actual Results

Bug link (when applicable)

#### 4️⃣ Reservation Flow Testing

###### Validated:

Complete reservation process

Cancellation workflow

Confirmation modals

Dependency on previous defects

Correct usage of BLOCKED status when required

### 🐞 Bug Reporting

#### Defects were reported in Jira with:

Clear reproduction steps

Expected vs Actual results

Environment specification

Proper severity identification

#### Critical bugs identified included:

Incorrect vehicle orientation on map

Map rendering issues

Payment validation inconsistencies

Incorrect button states

### 🛠 Tools Used

Excel – Test documentation & execution tracking

Jira – Bug reporting and tracking

Browser DevTools – UI inspection

Cross-browser testing (Chrome & Firefox)

### 💪 QA Skills Demonstrated

Web application testing

Cross-browser validation

Functional testing

UI validation

Defect lifecycle handling

Boundary testing

Test case structuring

Blocked test management

Professional bug reporting
