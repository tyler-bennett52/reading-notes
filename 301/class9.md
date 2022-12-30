# Class 9 Notes

1 - Forms are one of the most common elements of interactivity on a webpage. They are how we get specific inputs from users to bring into our code.

2 - Forms should be succinct and clear in their purpose. Users can barely type their passwords correctly, so let's not ask them to type a novel for us too.

3 - Oh you know HTML? Then name all the form elements. That's this question to me. But fine here you go - form formally defines a form and attributes that determine its behavior fieldset can create groups of widgets, you can label by using a: legend which formally describes the purpose of the fieldset label is important to include if you want your forms accessible button can be used in forms to submit data

1 - I would describe events like a light switch. Some times light switches are waiting for a chain to pull or a remote control or a traditional up and down style wall switch, but they all do the same thing. They wait for some input and then they do exactly what they're wired to do.

2 - addEventListener takes two arguments. 1. the event it's waiting for and 2. a callback function.

3 - The event object is Javascript's way if showing the html behavior of an element. So when clicking a submit button, HTML wants to take you to another page. We can use the event object to stop this default behavior.

4 - Bubbling is the order in which JS will 'Handle' an Event if there are multiple listeners. It 'bubbles up' from the deepest/lowest/youngest child one at a time until it reaches the top. I do not understand why event capturing is useful at all.

## Things I want to know more about

Why are we concerned with event capturing? When is a time we would use it?

Are there security concerns with structuring our forms?
