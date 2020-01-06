# Max Kelly - T3A1 WorkBook

## Q1: Provide an overview and description of a standard source control process for a large project

  - A standard source control process of a large project would be Git. Some platforms that help make the management of versions with Git easier as well as ensuring that quality of the code is up to the company standards is Github and BitBucket. A typical process for a large project would be to a Git process where a number of developers can have the most up-to-date code and ensure that the quality of it is up to standard. Git helps you do this by pushing and pulling code as well as giving the option for another developer to review and approve code before it has been merged with the master branch.

## Q2: What are the most important aspects of quality software?

  1. Understandability - This is when the structure, components and source code should all be understandable and easy for everyone to understand. If your code isn't understandable then it makes it very difficult for other developers to come in and pick up what has been left. 

  2. Efficiency - Quality software should be memory efficient, consumes few CPU cycles, minimizes the amount of database calls, uses little battery life and code is not repeated. Efficient code runs and performs well on both the machine and for the developer. 

  3. Maintainability - This is the "ease with which changes can be made to satisfy new requirements or to correct deficiencies". The bigger the project gets the more maintenance the developers will have to do to ensure the code is up to date and effective. This means the code should be flexible enough to accommodate future changes that will be needed, while also ensuring the understandability has not been lost. 

  4. Portability - This is the ease in which a program can be used across computer configurations other than its original one. This is important because hardware changes constantly and has a much shorter life span then the code that being said its important the code can adapt for the future.

## Q3: Outline a standard high level structure for a MERN stack application and explain the components

  - MERN stack is a combination of technologies which are then used to create web applications MERN is a Javascript stack that is designed to make the development process smoother, it includes four open-source components: MongoDB, Express, React and Node.js. 
  
  MongoDB is a NoSQL document-oriented database. MongoDB is known for being flexible and easy to scale. While many databases have a typical schema design based on columns and tables, MongoDB does not. Data is stored in flexible documents with making it quick and easy to get set up. 
  
  Express is a back-end web application framework. Instead of writing full web server code by hand on Node.js, developers can instead use Express to simplify the task of writing server code saving time and improving code. 

  React is a JavaScript library for the front-end of the website. React can be used  for creating views rendered in HTML. This means that developers don't have to worry about managing the effects of changes in the views state. With React the same code can run on both the server and the browser. 

  Node.js is a cross-platform JavaScript runtime environment. It's designed to build scalable applications as well as execute JavaScript code outside of the browser. Node.js is able to use its own module system which is based on CommonJS. 

## Q4: A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?

  - Depending on what website the team would be developing they would generally need to have the knowledge of a back-end, database and front-end language. A front-end is the client-side of the site. It is what the client will interact with. This team would need to have the knowledge of the languages such as JavaScript/React or Ruby as well HTML and CSS. The back-end refers to the server-side of the website, this is the part of the site which the clients cannot see or interact with but is extremely important. This team would need to have the knowledge of the back-end language such as Node.js or Ruby on Rails. The back-end also communicates with the database, in this case the team would want to pick a free and easy to use database such as PostgreSQL. Picking this database would allow them to set the small business up in a reasonable time and be of no cost to the business while it remains a small. 

## Q5: With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges



## Q6: With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature

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

## Q9: Explain data types, using examples from the JavaScript programming language

## Q10: Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language

## Q11: Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language

## Q12: Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language

## Q13: For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes

```
class Car {
  constructor(brand) {
    this.carname = brand;
  }
  present() {
    return 'I have a ' + this.carname;
  }
}

class Model extends Car {
  constructor(brand, mod) {
    super(brand);
    this.model = mod;
  }
  show() {
    return this.present() + ', it was made in ' + this.model;
  }
}

let makes = ["Ford", "Holden", "Toyota"]
let models = Array.from(new Array(40), (x,i) => i + 1980)

function randomIntFromInterval(min,max) { // min and max included
    return Math.floor(Math.random()*(max-min+1)+min);
}

for (model of models) {

  make = makes[randomIntFromInterval(0,makes.length-1)]
  model = models[randomIntFromInterval(0,makes.length-1)]
    
  mycar = new Model(make, model);
  console.log(mycar.show())
}
```

#### Reference:

- https://www.silasreinagel.com/blog/2016/11/15/the-seven-aspects-of-software-quality/