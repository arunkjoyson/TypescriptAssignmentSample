# Volume Calculation of a Prism

This project provides a utility to programmatically calculate the volume of a rectangular prism while validating input dimensions.


##  Formula
The volume of a prism is calculated as:

```
Volume = width × length × height
```


---
## What This Project Does

- **Calculates the Volume**: 
```
Volume = width × length × height
```
 
    For example:
```
30 = 2 × 3 × 5
```
where `width = 2`, `length = 3`, and `height = 5`.

- **Validates Input**:
  - Ensures width, length, and height are all positive and non-zero.
  - Throws descriptive errors if the input is invalid (e.g., negative or zero values).
- **Includes Tests**:
  - Comprehensive tests to ensure the calculator works perfectly.


---
## Prerequisites

Before getting started, ensure the following are installed on your system:
1. [Node.js](https://nodejs.org/) (v14 or later)
2. [npm](https://www.npmjs.com/) (comes with Node.js)
3. [TypeScript](https://www.typescriptlang.org/) (v4 or later)

If you don’t have these installed, download and install them first.

---


## Usage 

Ensure you have **Node.js** and **npm** installed.

1. Clone the repository:
   ```bash
   git clone git@github.com:arunkjoyson/TypescriptAssignmentSample.git
   
   ```
  goto src
  ```bash

  cd src
  ```

### 2. Install Dependencies
Run this command to install all necessary dependencies:
```bash
npm install
```


---

## Running the Tests

This project uses Jest to test the functionality of the volume calculation function. To run the tests:

1. **Install Jest (if not already installed)**:
   ```bash
   npm install --save-dev jest @types/jest ts-jest
   ```

2. **Run Tests**:
   Execute the test suite using the following command:
   ```bash
   npm test
   ```

The test results will show whether the program is calculating volumes correctly and handling invalid inputs properly.

---


