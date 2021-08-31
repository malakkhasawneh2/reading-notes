## Lists and Keys
**map() function take an array of numbers and assign the new array returned by map()**

**Rendering Multiple Components**
- You can build collections of elements and include them in JSX using curly braces {}.

**Basic List Component**
- Usually you would render lists inside a component.

- We can refactor the previous example into a component that accepts an array of numbers and outputs a list of elements.
- A “key” is a special string attribute you need to include when creating lists of elements.
**Keys**
- Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity
- The best way to pick a key is to use a string that uniquely identifies a list item among its siblings. Most often you would use IDs from your data as keys
- We don’t recommend using indexes for keys if the order of items may change. This can negatively impact performance and may cause issues with component state
**Extracting Components with Keys**

- Keys only make sense in the context of the surrounding array.

- For example, if you extract a ListItem component, you should keep the key on the < ListItem /> elements in the array rather than on the <li> element in the ListItem itself.

**Keys Must Only Be Unique Among Siblings**
- Keys used within arrays should be unique among their siblings. However, they don’t need to be globally unique. We can use the same keys when we produce two different arrays
- Keys serve as a hint to React but they don’t get passed to your components. If you need the same value in your component, pass it explicitly as a prop with a different name


# How to Use the Spread Operator (…) in JavaScript
## What is the spread operator?
- JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
- When ...arr is used in the function call, it ‘expands’ an iterable object arr into the list of arguments.

**What is ... used for?**

- Spread operator to the rescue! It looks similar to rest parameters, also using ..., but does quite the opposite.
- find the largest number in an array with Math.max()
- pass an array to a JavaScript function expecting separate arguments does not work. In this case it produces a NaN result.  
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

**Copying an array**
- using the … spread operator is a convenient way to copy an array or combine arrays, and it can even add new items
