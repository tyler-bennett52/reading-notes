# Class 3 Notes

1 - Map returns another array, with one item for each item in the original.

2 - To turn the items of an array into JSX use `.map(item => <div> {item} </div>)`.

3 - Every item needs a unique key

4 - The purpose of a key is related to the purpose of a component. Components are meant to be used again and again, so we pass a unique key so we have a way to reference a specific instance of a component. 

1 - The spread operator is ...cool. It's for taking the contents of an iterable and displaying them again, but outside of the iterable. For example Math.max wants a bunch of arguements, not one array. So you could use `Math.max(...numarray)`.

2 - Here is the list of uses for the spread operator from the article. Copying an array
    Concatenating or combining arrays
    Using Math functions
    Using an array as arguments
    Adding an item to a list
    Adding to state in React
    Combining objects
    Converting NodeList to an array

3 - Combinging arrays with the spread operator would look like `[...arr1, ...arr2]`.

4 - You could add an item to an array in a similar fashion like this `[...arr, newitem]`.

5 - Combining objects is very similar to array. It looks like this `{...obj1, ...obj2}

1 - First thing he does to pass the function is in the child set `increment = {this.increment}

2 - The increment function changes hasChanged to true and slaps an update badge/span on the component, as well as updating the count.

3 - Passing a function is as easy as including it in the props

4 - The function has to be called via props like this `this.props.increment()`