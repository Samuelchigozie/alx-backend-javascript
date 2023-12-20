# ES6 Promises

This repository is designed for mastering the usage of Promises in ECMAScript 2015 (ES6) through practical tasks.

## Tasks Overview

### 0. Keep every promise you make and only make promises you can keep

[**0-promise.js**](0-promise.js) exports a function `getResponseFromAPI()` that returns a Promise.

### 1. Don't make a promise...if you know you can't keep it

[**1-promise.js**](1-promise.js) exports a function `getFullResponseFromAPI(success)` returning a Promise. It resolves or rejects based on the `success` parameter.

### 2. Catch me if you can!

[**2-then.js**](2-then.js) exports `handleResponseFromAPI(promise)`, appending handlers to the provided Promise and logging appropriate messages.

### 3. Handle multiple successful promises

[**3-all.js**](3-all.js) imports functions from [utils.js](utils.js) to collectively resolve promises, logging `body firstName lastName` on success and `Signup system offline` on error.

### 4. Simple promise

[**4-user-promise.js**](4-user-promise.js) exports `signUpUser(firstName, lastName)`, returning a resolved promise with the specified object structure.

### 5. Reject the promises

[**5-photo-reject.js**](5-photo-reject.js) exports `uploadPhoto(filename)`, returning a Promise rejecting with an error message.

### 6. Handle multiple promises

[**6-final-user.js**](6-final-user.js) imports functions from [4-user-promise.js](4-user-promise.js) and [5-photo-reject.js](5-photo-reject.js) to handle promises and return an array with the status and value or reason.

### 7. Load balancer

[**7-load_balancer.js**](7-load_balancer.js) exports `loadBalancer(chinaDownload, USDownload)`, returning the value of the first resolved promise.

### 8. Throw error / try catch

[**8-try.js**](8-try.js) exports `divideFunction(numerator, denominator)`, throwing an error for division by 0 and returning the result otherwise.

### 9. Throw an error

[**9-try.js**](9-try.js) exports `guardrail(mathFunction)`, creating an array, executing the function, and adding the result or error message to the array.

### 10. Await / Async

[**100-await.js**](100-await.js) imports functions from [utils.js](utils.js) and exports `asyncUploadUser`, calling the functions and returning an object on success or an empty object on failure.

## Resources

- [PROMISE](https://intranet.alxswe.com/rltoken/j_0FTFbkTg42JMcAbNPOVQ)
- [Javascript Promise: An introduction](https://intranet.alxswe.com/rltoken/2Q2LzNFokcUwpA2u3FKG6Q)
- [Await](https://intranet.alxswe.com/rltoken/UXb3S2PMBe-SLJ55isMcow)
- [Async](https://intranet.alxswe.com/rltoken/_K0C7pgEjwaIzU9RpwCb8g)
- [Throw/Try](https://intranet.alxswe.com/rltoken/UTjDgvKk5l892Xslh0vqcQ)