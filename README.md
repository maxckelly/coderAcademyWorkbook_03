# Max Kelly - T3A1 WorkBook Answers

## Q1: Provide an overview and description of a standard source control process for a large project

  - A standard source control process of a large project would be Git. Some platforms that help make the management of versions with Git easier as well as ensuring that quality of the code is up to the company standards is Github and BitBucket. A typical process for a large project would be to a Git process where a number of developers can have the most up-to-date code and ensure that the quality of it is up to standard. Git helps you do this by pushing and pulling code as well as giving the option for another developer to review and approve code before it has been merged with the master branch.

## Q2: What are the most important aspects of quality software?

  1. Understandability - This is when the structure, components and source code should all be understandable and easy for everyone to understand. If your code isn't understandable then it makes it very difficult for other developers to come in and pick up what has been left. 

  2. Efficiency - Quality software should be memory efficient, consumes few CPU cycles, minimizes the amount of database calls, uses little battery life and code is not repeated. Efficient code runs and performs well on both the machine and for the developer. 

  3. Maintainability - This is the "ease with which changes can be made to satisfy new requirements or to correct deficiencies". The bigger the project gets the more maintenance the developers will have to do to ensure the code is up to date and effective. This means the code should be flexible enough to accommodate future changes that will be needed, while also ensuring the understandability has not been lost. 

  4. Portability - This is the ease in which a program can be used across computer configurations other than its original one. This is important because hardware changes constantly and has a much shorter life span then the code that being said its important the code can adapt for the future.

  5. Testability - The process of testing your software must be verifiable. It must be easy and simple to understand and implement the tests. This includes automated tests suits and only pushing the code once the necessary tests have occurred.

  6. Usability - The software must be easy and simple to use for the user. A user should be able to view the software and have a clear indication of what the software can do and the benefit it provides them. Bad usability would result in the user searching for help and understanding of how to use your platform.

## Q3: Outline a standard high level structure for a MERN stack application and explain the components

  - MERN stack is a combination of technologies which are then used to create web applications MERN is a Javascript stack that is designed to make the development process smoother, it includes four open-source components: MongoDB, Express, React and Node.js. 
  
  MongoDB is a NoSQL document-oriented database. MongoDB is known for being flexible and easy to scale. While many databases have a typical schema design based on columns and tables, MongoDB does not. Data is stored in flexible documents with making it quick and easy to get set up. 
  
  Express is a back-end web application framework. Instead of writing full web server code by hand on Node.js, developers can instead use Express to simplify the task of writing server code saving time and improving code. 

  React is a JavaScript library for the front-end of the website. React can be used  for creating views rendered in HTML. This means that developers don't have to worry about managing the effects of changes in the views state. With React the same code can run on both the server and the browser. 

  Node.js is a cross-platform JavaScript runtime environment. It's designed to build scalable applications as well as execute JavaScript code outside of the browser. Node.js is able to use its own module system which is based on CommonJS. 

## Q4: A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?

  - Depending on what website the team would be developing they would generally need to have the knowledge of a back-end, database and front-end language. A front-end is the client-side of the site. It is what the client will interact with. This team would need to have the knowledge of the languages such as JavaScript/React or Ruby as well HTML and CSS. The back-end refers to the server-side of the website, this is the part of the site which the clients cannot see or interact with but is extremely important. This team would need to have the knowledge of the back-end language such as Node.js or Ruby on Rails. The back-end also communicates with the database, in this case the team would want to pick a free and easy to use database such as PostgreSQL. Picking this database would allow them to set the small business up in a reasonable time and be of no cost to the business while it remains a small. 

## Q5: With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges

  - The project that I have recently worked on was Ruby on Rails marketplace app. My app was called `Sitter` and involved a two sided marketplace 1. For the parent looking for a baby sitter and 2. The sitter looking for work. The tech stack involved in building this platform was HTML, CSS, Ruby, Ruby on Rails, Heroku, Bootstrap and PostgreSQL. The knowledge I needed in order to build this platform out was the terminology of databases and the syntax knowledge in order to create it. Along with this I needed an understanding of my audience and why I was building the platform as well as the problem I was solving.

  The skills that were required to complete the Sitter app was firstly Ruby, this involved the knowledge of using if statements, manipulating over objects/arrays and handling forms/data. Along with Ruby I also had to have the skill of Rails, this involved routing, controllers, views and more. Rails allowed me to create a functional and working application very quickly, however I had to have the correct knowledge/skill of how to further build out the platform. The third skill that I needed to have in order to build my application was PostgreSQL - PostgreSQL is a schema database, in order to correctly build this out I need to plan and build the design of the schema and from there implement and create the database on the application. After the database was established and the app was taking shape I need to gain the skill to implement Stripe and accept payments as well as mail gun for confirm emails and a GEM called devise to sign users up and accept their email and password. While a majority of the skills needed to develop the project was coding related I also needed to gain the skills to design the application for all devices and ensure the view is pleasing and functional for the user. 

  A challenge which I had to overcome was the implementation of the payment system and how to have it so the sitter user would to send a payment request, notifying the parent and then allowing the parent to pay the full amount. I overcame this by reading Stack overflow, testing and breaking code and guidance from teachers. 
   
## Q6: With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature

  - With reference to my Ruby on Rails project I believe coming into my project my skill of coding in Ruby was minimal and especially around PostgreSQL. I was unsure and novice in creating the database and worried that I could greatly damage effect the integrity of my app with the lack of knowledge around commands and how to create and structure the schema. However with experimentation and confidence that I won't effect my application I was able to gain the confidence and knowledge that I can always manage and rollback the database. 
  
  Another challenge which I faced was migrations. With my project I used two computers (my laptop and home desktop), through this I noticed that the migrations were out of sync a lot of the time and that greatly effected the application. However I learnt of new commands where you can re run the migration from the start making it so every computer is up to date regardless of how many migrations and changes you make to the database.

  The changes and improvements I would make if I was to re do the project would be to plan out and take my time with my schema design. This limits the need to change it constantly through out the application while in development and reduce the chances of creating unnecessary coding debt. Along with this I think I can improve the testing of the application and automate that area which will be able to save time and allow for more development.

## Q7: Explain control flow, using an example from the JavaScript programming language

  - Control flow is the oder in which the code executes statements in a script. With JavaScript the code is run in order from the first line in the file to the last line in the file. However the control flow can have exceptions when there are conditionals and loops within the code. 

  - An example of a traditional control flow within JavaScript is the below. As you can see this it runs in an order from top down.

  ```
  console.log("This is the start of the code")

  let name = "Max Kelly" 

  console.log(name)

  console.log("This is the end of the code)
  ```

  - An example of using a loop within the code makes it so it can re run a particular condition continually until it equals that condition or it breaks. 

  ```
  console.log("This is the start of the code")

  let name = "Max Kelly" 

  let count = 10

  while (count > 0) {
    console.log("Hello");
    count -= 1
  };

  console.log(name)

  console.log("This is the end of the code)
  ```

## Q8: Explain type coercion, using examples from the JavaScript programming language

  - Type coercion is the process of converting one type of value to another type. For example: string to an integer, object to boolean. There are three types of conversions 1. To string, 2. To boolean and 3. To integer.

  1. To convert to a string in javascript you must use the String() function this is explicitly e.g. `String(123)`. While on the other hand you can do an implicit coercion which includes "+" this can be done like `123 + ''`.

  2. Boolean conversion can be done explicitly by applying `Boolean(2)` function. This then returns either `true` or `false`. Implicit conversion happens in logical context or is triggered by logical operators such as `||`, `&&`, `!`.

  3. Integer conversion can be done explicitly by applying the `Number("123")` function. Implicit conversion however can be more difficult as it is triggered in more cases. These cases are things such as comparison operators (`>`, `<`, `<=`, `=>`) 

## Q9: Explain data types, using examples from the JavaScript programming language

  - Usually in JavaScript a datatype is assigned to a variable which can store any of the 7 datatypes within JavScript. The 6 types are:

  1. The first datatype is number - This can be a integer which is a whole number such as `17`, `8` etc... or a floating number such as `12.45` or `1.99`. However with JavaScript a number cannot represent integer values larger than 2^53 or less than -2^53.
  2. Due to the above limitations on numbers a BigInt is another datatype within JavaScript this is usually about a 16 decimal digit and contains an `n` on the end e.g. `1234567895177653456789012345678901234567890n`
  3. The third datatype is a String. A String is surrounded by quotes this can be either double `""`, single `' '` or `back-ticks`. An example of a string is `let string = "hello"`
  4. The fourth datatype is a boolean this has two values and is either `true` or `false`. An example of this is `let boolean = true`.
  5. The fifth datatype is the `null` value. This is a specific value that references an non-existing object.
  6. Finally the sixth datatype is the `undefined` value. This datatype means that a value is not assigned and there for undefined. 

## Q10: Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language

  - Arrays in JavaScript is a single variable that is used to store different and multiple elements. They can be manipulated in JavaScript a number of ways some of these ways can be seen below.

  - To create an array you do: `let arrayOne = ["a", "b", "c", "d"]`

  - Removing Elements:
    - To remove an element from the array you can use `pop()` just like: `arrayOne.pop()`
    - To remove the first element from the array you can use `shift()` just like: `arrayOne.shift()`
    - To remove specific indexes within the array you can use `splice()` just like: `arrayOne.splice(0, 2)`
  
  - Adding Elements:
    - To add an element to then end of the array you can use `push()` just like: `arrayOne.push('j')`
    - You can add it at the beginning of the array using `unshift()` just like: `arrayOne.unshift('l')`

  - You can also iterate through the array a number of ways. For example using `.map()` this can be done by doing the below.

    ```
    let arrayTwo = ['M', 'A', 'X']

    let letters = arrayTwo.map((letter) => {
      return console.log(letter)
    }); 
    ```
    

## Q11: Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language

  - An object in JavaScript is a variable that holds a group of comma separated key value pairs which is also called a hash. There are two JavaScript objects 1. Object literal this is just a single object and 2. constructor objects, this involves the use of a function and the key word `this`. Objects can contain both data and functions. As seen below you can see how to create an object as well as manipulate it. 

  - Example of an object literal.

  ```
  const person = {
    name: "Max Kelly",
    age: 21,
    height: 187.9,
    alive: true
  }
  ```
  - Example of a constructor object. A constructor object allows us to easily make multiply objects

  ```
  function Person(name, age, height, alive) {
    this.name = name;
    this.age = age;
    this.height = height;
    this.alive = alive;
  }

  // To create an object we can do the below:

  let max = new Person("Max", 21, 187.98, true)
  ```

  - To display the keys in an object (these are `name`, `age` etc...) you can do the below:

  ```
  console.log(Object.keys(person));

  // This will print out `name`, `age`, `height`, `alive`
  ```

  - You can change object data by doing the below: You will notice that you call the name of the object that being `person` then you select the key `age` and then you set its new value.

  ```
  person["age"] = 22
  console.log(person);
  ```

## Q12: Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language

  - JSON short for JavaScript Object Notation is entirely text-based. It is a key value data format that is typically rendered in curly braces. Some ways in which you can manipulate JSON in JavaScript is below:

  1. `JSON.stringify()` - This function converts an object to a JSON string. This can be used like:
  
  ``` 
  var obj = {"first_name" : "Sammy", "last_name" : "Shark", "location" : "Ocean"}

  var s = JSON.stringify(obj)
  ```

  2. `JSON.parse()` - This function allows you to convert JSON text to a javascript object. 

  ```
  let people = '{ "people" : [' +
  '{ "firstName":"Max" , "lastName":"Kelly" },' +
  '{ "firstName":"Alex" , "lastName":"Smith" },' +
  '{ "firstName":"Alexis" , "lastName":"Jones" } ]}'; 

  let obj = JSON.parse(people);
  ```

## Q13: For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognize and identify functions, ranges and classes

```
// The below is a class which acts as a "special function".
class Car {
  // A constructor can be used to set the default values of the object. This initializes the method.
  constructor(brand) {
    this.carname = brand;
  }

  // The below is a function within the class that returns the string place the brand of the car. 
  present() {
    return 'I have a ' + this.carname;
  }
}

// This is a class which extends it's 'reach' to the parent class being the Car. It can access it's functionality from the parent class
class Model extends Car {
  constructor(brand, mod) {
    // The super is being used to call functions on the object.
    super(brand);
    this.model = mod;
  }

  // The below is a function
  show() {
    return this.present() + ', it was made in ' + this.model;
  }
}

// The below is a variable containing arrays of brand names.
let makes = ["Ford", "Holden", "Toyota"]
let models = Array.from(new Array(40), (x,i) => i + 1980)

// The below is a function which sets a number range with a min and max.
function randomIntFromInterval(min,max) { // min and max included
  return Math.floor(Math.random()*(max-min+1)+min);
}


for (model of models) {

  make = makes[randomIntFromInterval(0,makes.length-1)]
  model = models[randomIntFromInterval(0,makes.length-1)]
  
  // The below is calling the class and creating a new object
  mycar = new Model(make, model);
  console.log(mycar.show())
}
```

#### Reference:

- https://www.silasreinagel.com/blog/2016/11/15/the-seven-aspects-of-software-quality/
- https://javascript.info/types
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
- https://medium.com/@TK_CodeBear/manipulating-objects-in-javascript-59fefeb6a738
- https://clubmate.fi/javascript-manipulating-objects-with-object-keys/
- https://www.digitalocean.com/community/tutorials/how-to-work-with-json-in-javascript
- https://www.w3schools.com/js/js_json.asp