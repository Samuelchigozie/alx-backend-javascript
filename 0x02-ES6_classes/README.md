# ES6 Classes

This repository contains tasks aimed at mastering the use of classes in ECMAScript 2015 (ES6).

## Tasks Overview

### 0. You used to attend a place like this

[**0-classroom.js**](0-classroom.js) exports a class named `ClassRoom` with a constructor that accepts `maxStudentsSize` (Number) and assigns it to `_maxStudentsSize`.

### 1. Let's make some classrooms

[**1-make_classrooms.js**](1-make_classrooms.js) imports the `ClassRoom` class and exports a function named `initializeRooms`, returning an array of 3 `ClassRoom` objects with sizes 19, 20, and 34.

### 2. A Course, Getters, and Setters

[**2-hbtn_course.js**](2-hbtn_course.js) exports a class named `HolbertonCourse` with a constructor, getters, setters, and type verification for attributes.

### 3. Methods, static methods, computed methods names..... MONEY

[**3-currency.js**](3-currency.js) exports a class named `Currency` with a constructor, getters, setters, and a method named `displayFullCurrency`.

### 4. Pricing

[**4-pricing.js**](4-pricing.js) imports the `Currency` class and exports a class named `Pricing` with a constructor, getters, setters, a method named `displayFullPrice`, and a static method named `convertPrice`.

### 5. A Building

[**5-building.js**](5-building.js) exports a class named `Building` with a constructor, getters, and a method named `evacuationWarningMessage` to be implemented by subclasses.

### 6. Inheritance

[**6-sky_high.js**](6-sky_high.js) imports `Building` and exports a class named `SkyHighBuilding` that extends `Building` with additional attributes, getters, and an overridden `evacuationWarningMessage` method.

### 7. Airport

[**7-airport.js**](7-airport.js) exports a class named `Airport` with a constructor, getters, and a default string description.

### 8. Primitive - Holberton Class

[**8-hbtn_class.js**](8-hbtn_class.js) exports a class named `HolbertonClass` with a constructor, getters, and automatic casting to `Number` or `String`.

### 9. Hoisting

[**9-hoisting.js**](9-hoisting.js) provides a fixed version of a code snippet involving classes and objects.

### 10. Vroom

[**10-car.js**](10-car.js) exports a class named `Car` with a constructor and a `cloneCar` method to create a new object of the same class.

### 11. EVCar

[**100-evcar.js**](100-evcar.js) imports `Car` and exports a class named `EVCar` that extends `Car` with additional attributes, getters, and an overridden `cloneCar` method to return an instance of `Car` for privacy reasons.

## Resources

- [Classes](https://intranet.alxswe.com/rltoken/ke2dSL31JbpAUBW0qWE9WA)
- [Metaprogramming](https://intranet.alxswe.com/rltoken/6OgF5QGbYclp_cwATfq-0g)