# FizzBuzz

**Exercise: Write a simple fizz-buzz REST server**.

The original fizz-buzz consists in writing all numbers from 1 to 100, and just replacing all multiples of 3 by "fizz", all multiples of 5 by "buzz", and all multiples of 15 by "fizzbuzz". The output would look like this: "1,2,fizz,4,buzz,fizz,7,8,fizz,buzz,11,fizz,13,14,fizzbuzz,16,...".

Your goal is to implement a web server that will expose a REST API endpoint that:  
Accepts five parameters: three integers int1, int2 and limit, and two strings str1 and str2.
Returns a list of strings with numbers from 1 to limit, where: all multiples of int1 are replaced by str1, all multiples of int2 are replaced by str2, all multiples of int1 and int2 are replaced by str1str2.

The server needs to be:  
Ready for production  
Easy to maintain by other developers

Add a statistics endpoint allowing users to know what the most frequent request has been. This endpoint should:  
- Accept no parameter  
- Return the parameters corresponding to the most used request, as well as the number of hits for this request


# Getting Started
Download file, open and run `npm i`   
Then start the server with `npm start`  
Run the unit tests with the following command `npm test`

To test the first endpoint, you can copy and paste this url http://localhost:3000/customisedFizzBuzz/3/5/100/bella/donna into your browser search bar.

To test the second endpoint, you can copy and paste this url http://localhost:3000/stats into your browser search bar.

# Author
Aude Rouaux

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
