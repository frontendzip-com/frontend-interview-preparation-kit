## Array and Object methods

Arrays and objects in JavaScript offer a rich set of methods to manipulate, iterate over, and transform their data. Here's a breakdown of some commonly used methods for interview preparation:

**Array Methods:**

- **`forEach(callbackFunction)`:** Executes a provided function once for each array element. Useful for side effects like logging or modifying elements in-place.
- **`map(callbackFunction)`:** Creates a new array with the results of calling the callback function on every element in the original array. Ideal for transforming elements.
- **`filter(callbackFunction)`:** Constructs a new array containing only elements from the original array that pass a test implemented by the callback function. Excellent for filtering based on conditions.
- **`reduce(callbackFunction, initialValue)`:** Applies a function against an accumulator and each element in the array (from left to right) to reduce it to a single value. Powerful for summarizing data.
- **`find(callbackFunction)`:** Returns the value of the first element in the array that satisfies the provided testing function. Useful for finding specific elements.
- **`findIndex(callbackFunction)`:** Returns the index of the first element in the array that passes the test implemented by the callback function. Handy for finding element positions.
- **`sort(compareFunction)`:** Sorts the elements of an array in place according to a comparison function (optional). Essential for ordering data.
- **`slice(start, end)`:** Extracts a section of an array and returns a new array (copies elements). Great for creating sub-arrays.
- **`concat(array1, ..., arrayN)`:** Merges multiple arrays into a single new array. Helpful for combining arrays.

**Object Methods:**

- **`Object.keys(object)`:** Returns an array containing the enumerable property names (own properties) of an object. Useful for iterating over object keys.
- **`Object.values(object)`:** Returns an array containing the enumerable property values of an object. Handy for accessing object values.
- **`Object.entries(object)`:** Generates an array of key-value pairs (as arrays) for the object's enumerable properties. Ideal for destructuring objects.
- **`hasOwnProperty(property)`:** Determines whether an object has a specific property as its own property (not inherited). Important for property existence checks.
- **`Object.assign(target, source1, ..., sourceN)`:** Copies enumerable own properties from source objects to a target object. Effective for merging object properties.

**Remember During Interviews:**

- Explain the purpose and usage of each method with clarity.
- Provide code examples to illustrate how they work in practice.
- Discuss potential use cases and scenarios where these methods would be beneficial.
- Be prepared to answer questions about immutability (some methods create new arrays/objects, while others modify them in-place).

By understanding these core array and object methods, you'll demonstrate your proficiency in manipulating and transforming data in JavaScript, showcasing your problem-solving skills to potential employers.
