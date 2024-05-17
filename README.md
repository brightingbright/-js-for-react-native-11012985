# js-for-react-native-11012985


## Student ID
- **Student ID:** 11012985

## Overview
This project contains three primary functions that work together to process arrays of numbers and strings, and then create user profiles based on these processed arrays.

### Task 1: processArray Function
**Function:** `processArray(numbers)`

**Description:** This function takes an array of numbers as an argument and returns a new array where each even number is squared and each odd number is tripled.

**Example:**
- **Input:** `[1, 2, 3, 4, 5]`
- **Output:** `[3, 4, 9, 16, 15]`

### Task 2: formatArrayStrings Function
**Function:** `formatArrayStrings(strings, numbers)`

**Description:** This function takes two arrays as arguments: an array of strings and an array of numbers (processed by `processArray`). It modifies each string based on its corresponding number: capitalizing the entire string if the number is even, and converting the string to lowercase if the number is odd.

**Example:**
- **Strings:** `["jesus", "is", "Coming", "soon"]`
- **Numbers:** `[1, 2, 3, 4]`
- **Processed Numbers:** `[3, 4, 9, 16, 15]`
- **Formatted Strings:** `["jesus", "IS", "coming", "SOON"]`

### Task 3: createUserProfiles Function
**Function:** `createUserProfiles(originalNames, modifiedNames)`

**Description:** This function takes two arrays: an array of original names and an array of modified names (from `formatArrayStrings`). It returns an array of objects, each containing `originalName`, `modifiedName`, and an `id` (auto-incremented starting from 1).

**Example:**
- **Original Names:** `["jesus", "is", "Coming", "soon"]`
- **Modified Names:** `["jesus", "IS", "coming", "SOON"]`
- **User Profiles Output:**

  [
    { "id": 1, "originalName": "jesus", "modifiedName": "jesus" },
    { "id": 2, "originalName": "is", "modifiedName": "IS" },
    { "id": 3, "originalName": "Coming", "modifiedName": "coming" },
    { "id": 4, "originalName": "soon", "modifiedName": "SOON" }
  ]
