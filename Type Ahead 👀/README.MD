
const endpoint = 'https://gist.githubusercontent.com/Miserlou/c5cd8364bf9b2420bb29/raw/2bf258763cdddd704f8ffd3ea9a3e81d25e2c6f6/cities.json';

Declared a variable which will contain an array and fetch the data from the provided endpoint, pushing the return values into the array.

Fetch method that fetches resources and returns a *Promise* containing the response in a Response object.Used this method to get data from the provided endpoint, convert the response to JSON, and then push the items into our array.

Used this command in combination with the 'then' property to retrieve the json data from the given city-state website.

'…' is spread. It is used to spread all arguments passed to the array as their own elements.

fingMatches():
This function will accept two parameters; wordToMatch text and the array containing the data from the endpoint. In the body of the function, filter through the array(Used filter to apply a function to every single element in the array), using a new instance of a Regular Expression object.

const regex = new RegExp(wordToMatch, ‘gi’);

where g is for global,
and i is for case insensitive,
wordToMatch is our variable.
