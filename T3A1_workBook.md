# Max Kelly - T3A1 WorkBook

## Q1: Provide an overview and description of a standard source control process for a large project

- A standard source control process of a large project would be Git. Some platforms that help make the management of versions with Git easier as well as ensuring that quality of the code is up to the company standards is Github and BitBucket. A typical process for a large project would be to a Git process where a number of developers can have the most up-to-date code and ensure that the quality of it is up to standard. Git helps you do this by pushing and pulling code as well as giving the option for another developer to review and approve code before it has been merged with the master branch.

## Q2: What are the most important aspects of quality software?

  1. Understandability - This is when the structure, components and source code should all be understandable and easy for everyone to understand. If your code isn't understandable then it makes it very difficult for other developers to come in and pick up what has been left. 

  2. Efficiency - Quality software should be memory efficient, consumes few CPU cycles, minimizes the amount of database calls, uses little battery life and code is not repeated. Efficient code runs and performs well on both the machine and for the developer. 

  3. Maintainability - This is the "ease with which changes can be made to satisfy new requirements or to correct deficiencies". The bigger the project gets the more maintenance the developers will have to do to ensure the code is up to date and effective. This means the code should be flexible enough to accommodate future changes that will be needed, while also ensuring the understandability has not been lost. 

  4. Portability - This is the ease in which a program can be used across computer configurations other than its original one. This is important because hardware changes constantly and has a much shorter life span then the code that being said its important the code can adapt for the future.

## Q3: Outline a standard high level structure for a MERN stack application and explain the components

## Q4: A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?

- The

## Q5: With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges

## Q6: With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature

## Q7: Explain control flow, using an example from the JavaScript programming language

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