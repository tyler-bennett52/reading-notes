# Class 2 Notes

1 - Based on the diagram the render portion happens first.

2 - The first thing that happens is your constructor function executes. 

3 - componentDidMount, render, constructor, componentWillUnmount, React Updates
1. constructor
2. render
3. React updates
4. ComponentDidMount
5. ComponentWillUnmount

4 - The article says this about ComponentDidMount: This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM.

1 - Props should be data you want your component to be initialized with, like a Title.

2 - Props are external to the component and updates must come from outside the component as well, while state is internal to the component and allows the component to update itself.

3 - Applicaiton gets re-rendered whenever state is changed

4 - You could alot in state but some things I have seen are form values, score in a game, number of times a button is clicked.

## Things I want to know more about

Is it common to store most state items in the App component since everything will be internal to that, or is it supposed to be the lowest possible child?

Is such a behind-the-scenes look at React crucial for development, most of this seems like gee-whiz information and not something I will think about very often.