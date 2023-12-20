# ES6 Data Manipulation

This repository contains tasks focusing on data manipulation in ECMAScript 2015 (ES6).

## Tasks Overview

### 0. Basic list of objects

[**0-get_list_students.js**](0-get_list_students.js) exports a function named `getListStudents` that returns an array of objects. Each object has attributes `id` (Number), `firstName` (String), and `location` (String) representing student details.

### 1. More mapping

[**1-get_list_student_ids.js**](1-get_list_student_ids.js) exports a function named `getListStudentIds` that takes an array of student objects and returns an array of their ids using the `map` function.

### 2. Filter

[**2-get_students_by_loc.js**](2-get_students_by_loc.js) exports a function named `getStudentsByLocation` that filters and returns an array of students located in a specific city from the provided list using the `filter` function.

### 3. Reduce

[**3-get_ids_sum.js**](3-get_ids_sum.js) exports a function named `getStudentIdsSum` that calculates and returns the sum of all student ids from the provided list using the `reduce` function.

### 4. Combine

[**4-update_grade_by_city.js**](4-update_grade_by_city.js) exports a function named `updateStudentGradeByCity` that updates the grades of students in a specific city and returns an array of students with their new grades.

### 5. Typed Arrays

[**5-typed_arrays.js**](5-typed_arrays.js) exports a function named `createInt8TypedArray` that creates a new `ArrayBuffer` with an `Int8` value at a specific position using the provided length, position, and value. It throws an error if adding the value is not possible.

### 6. Set data structure

[**6-set.js**](6-set.js) exports a function named `setFromArray` that converts an array into a `Set` and returns the `Set` instance.

### 7. More set data structure

[**7-has_array_values.js**](7-has_array_values.js) exports a function named `hasValuesFromArray` that checks if all elements in an array exist within a `Set`.

### 8. Clean set

[**8-clean_set.js**](8-clean_set.js) exports a function named `cleanSet` that returns a string of set values starting with a specific string, joined by `-`.

### 9. Map data structure

[**9-groceries_list.js**](9-groceries_list.js) exports a function named `groceriesList` that returns a map of groceries with specified items and quantities.

### 10. More map data structure

[**10-update_uniq_items.js**](10-update_uniq_items.js) exports a function named `updateUniqueItems` that updates the quantity of items in a map to 100 for those with an initial quantity of 1.

### 11. Weak link data structure

[**100-weak.js**](100-weak.js) exports a `const` instance of `WeakMap` named `weakMap` and a function `queryAPI` that tracks the number of times it's called for each endpoint within the `weakMap`. If the number of queries is >= 5, it throws an error with the message `Endpoint load is high`.

## Resources

- [Array](https://intranet.alxswe.com/rltoken/bcXqK1IaIHtrZ45sv0RxsQ)
- [Typed Array](https://intranet.alxswe.com/rltoken/YZ5RtzAPTaWtF00MYbXuVw)
- [Set Data Structure](https://intranet.alxswe.com/rltoken/Ch8vq39y9QnlTMr8CymgEg)
- [Map Data structure](https://intranet.alxswe.com/rltoken/W29MV3f8Ii4HmeJSALNIpw)
- [Weakmap](https://intranet.alxswe.com/rltoken/pSetFVFeIR660GPE0flPdg)