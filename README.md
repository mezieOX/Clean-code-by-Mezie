
# **Clean-code-by-Mezie**<img src="https://images.unsplash.com/photo-1534972195531-d756b9bfa9f2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" />


## What's clean code all about?
### Preface
In this book what's clean code all about?, you will understand and be enlighten fully about everything that has to do with Clean code.

## Definition
In my own world i tell you that "Clean code refers to code that is easy to understand, modify, extend and maintain".
According to **Martin Fowler** he wrote that "Any fool can write code that a computer can understand. Good programmers write code that human understand". In a situation where Programmed Code is - Hard to test, Hard to change, Has long file symptoms etc. All these things is a characteristics/features of **unclean code**, as a good programmer you don't have to let your Code to have all these symptoms. The best part that interest me so much in this **Martin Fowler** book is when he say's **"Write a Code that human understand"**

## Examples of Clean code
+ it must be easy to understand, change, test
+ Must follow general principle - eg. 
+ No matter what approach you're following, be sure to arrange things in the same way
+ Make the component short and concise
+ Choose a word with meaning in naming your functions, variables etc
+ Make necessary comments

## Note
The most frustrating thing about **Unclean code** is that when you want to apply a simple change to the existing code, even if you know that it's only one-line change. it's nearly impossible to make the change without braking something else, or sometimes not disgusting yourself. Another possibility is that you need to modify another place, and so on. it's a kind of **rabbit hole** to make that simple one-liner. The dead loop is that, because it's hard to change people tend to not change it but just add patches on it, which in turn make it even harder to change again 😞.

## What have you learnt so far in this book (Juntao Qui)?
+ I learnt that for me to become a bad ass developer, i must be familiar to a Clean code
+ I learnt that a popular way to split my project is to divide it by feature first
+ I also learnt that the Kebab case is a popular one (naming convention) in the JS community overall, and you would name a component like generic-card.tsx and i can use ESlint and FolderLint to ensure that my team has the same naming standard for files and folders, and so on...

## Test-Driven Development
**TDD** means Test-Driven Development
whats is TDD? Simply it means write a test first and see it fail, make the test pass with minimal effort(changes), and **refactor** if necessary/is a programming practice that instructs developers to write new code only if an automated test has failed.
whats **Refactor**? is the Source code of an application or piece of software, so as to improve operation without altering functionality.
So the idea here is very simple, once you add your first test , With react-testing -library eg. 👇

test("render greeting message", () => {
render(<App />);
const element = screen.getByText("Hello Ventlio");
expect(elememt).toBeInTheDocument();
});

To fix the test and also verify our code and test are connected, we can simply create a one-line component like this 👇

const App = () => { <>Hello Ventlio</> }
export default App;

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRkCP4yDcpNJOzczoOP9AhYUHVMOElAHTYNRg&usqp=CAU"/>

But if the test aren't passing don't get angry, don't panic, chill 😄, you can randomly change something that would fail to check eg. 👇

const App = () => { <>Hello Next</> }
export default App;
