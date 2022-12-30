# Class 13 Notes

1 - By storing small amounts of information on the user's system we are able to persist information from page to page without increasing load times by continually sending http requests or waiting for an API response.

2 - Information that should be secure like payment information, contact info, passwords shouldn't be stored this way.

3 - Local storage expects JSON which looks like JS but is a string. To use it in JS we have to either JSON.parse() or JSON.stringify().

## Things I want to know more about

Is there a pracatical limit to how much local storage we should use? Can I download wikipedia and store it in a user's browser if I want?

Do browsers limit websites from writing too much, too often to local storage?

Is the space we write to considered part of the browsers file tree or is there a separate one that gets made for our site?
