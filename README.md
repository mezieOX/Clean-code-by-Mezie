
# **Summary-of-Clean-code-by-Mezie**<img src="https://images.unsplash.com/photo-1534972195531-d756b9bfa9f2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" />


## What's clean code all about?
## Definition
In my own world i tell you that "Clean code refers to code that is easy to understand, modify, extend and maintain".
According to **Martin Fowler** he wrote that "Any fool can write code that a computer can understand. Good programmers write code that human understand". In a situation where Programmed Code is - Hard to test, Hard to change, Has long file symptoms etc, All these things mentioned is a properties of **unclean code**, as a good programmer you must try to avoid them. The best part that calls my attention/interest me so much in this **Martin Fowler** book is when he say's **"Write a Code that human understand"**. Code is clean if it can be understood easily — by everyone on the team

## Some of the Characteristics/Features of Clean code
+ It must be simple
+ it must be easy to understand, change, test
+ Must follow general principle - eg. Once you have established a conversation as a team, stick with it and try to make everthing organised the same way
+ No matter what approach you're following, be sure to arrange things in the same way
+ Make the component short and concise
+ Choose a word with meaning in naming your functions, variables etc
+ Make necessary comments

## Note
The most frustrating thing about **Unclean code** is that when you want to apply a simple change to the existing code, even if you know that it's only one-line change. it's nearly impossible to make the change without braking something else, or sometimes not disgusting yourself. Another possibility is that you need to modify another place, and so on. it's a kind of **rabbit hole** to make that simple one-liner. The dead loop is that, because it's hard to change people tend to not change it but just add patches on it, which in turn make it even harder to change again 😞.

## Lessons
+ Learnt that obedient is very important, hard-working etc
+ For me to become a bad ass developer, i must be familiar with Clean code
+ The popular way to split my project is to divide it by features first
+ I also learnt that the Kebab case is a popular one (naming convention) in the JS community overall, and i would name a component like generic-card.tsx and i can use ESlint and FolderLint to ensure that my team has the same naming standard for files and folders
+ I also learnt that once i have established a conversation as a team that i must stick with it and try to make everthing organised the same way
+ I learnt also that naming my component like eg. 👇
<code> 
components/Button
index.test.tsx
index.tsx
style.css
<code/>
That Some people hate it, as the editor will return a million index when trying to search for component, Another way i'll be using in naming my file is to explicitly name the component while keeping index.tsx for the default export eg. 👇
<code> 
components/Button
Button.test.tsx
Button.tsx
Button.css
<code/>
+ No matter what approach i'll be following, i'll be sure to arrange things in the same way. For example, if i put a style file next to the component, i'll must keep the convention across all the components in my codebase. similarry, if i use __tests__folder, i must ensure  all other folders follow the same pattern and so on...
