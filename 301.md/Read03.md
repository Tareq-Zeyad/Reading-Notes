## **Passing Functions as Props.**
![react](https://miro.medium.com/max/1024/1*h5UGPzaL1E4dIy_JWDrsAw.png)
- ### *What does .map() return?*
### **In ReactJS, the use of map() method is to create a new array which can contains a modified values from a pre-determined one.**
<>
- ### *If I want to loop through an array and display each value in JSX, how do I do that in React?*
### **By the map() function**
<>
- ### *Each list item needs a unique* **Component.**
<>
- ### *What is the purpose of a key?*
### **Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity** [source](https://reactjs.org/docs/lists-and-keys.html).
<>

## **The Spread Operator.**
![Spread](https://miro.medium.com/max/2000/1*24ayqOY008AvW_VmkqsYdA.png)
- ### *What is the spread operator?*
### **The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functionβs arguments.** [source](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
<>
- ### *List 4 things that the spread operator can do.*
### **1- Copying an array.**
### **2- Concatenating or combining arrays.**
### **3- Using Math functions.**
### **4- Using an array as arguments.**
<>
- ### Give an example of using the spread operator to combine two arrays.
### const objectOne = {hello: "π€ͺ"}
### const objectTwo = {world: "π»"}
### const objectThree = {...objectOne, ...objectTwo, laugh: "π"}
### console.log(objectThree) // Object { hello: "π€ͺ", world: "π»", laugh: "π" }
### const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("π".repeat(5))}}
### objectFour.laugh() // πππππ

<>
- ### Give an example of using the spread operator to add a new item to an array.
### const fewFruit = ['π','π','π']
### const fewMoreFruit = ['π', 'π', ...fewFruit]
### console.log(fewMoreFruit) //  Array(5) [ "π", "π", "π", "π", "π" ]
<>
## **How to Pass Functions Between Components**
- ### In the video, what is the first step that the developer does to pass functions between components?
### By creating a map() array.
<>
- ### In your own words, what does the increment function do?
### it is a counter function that will increased the count for each name when it is selected.
<>
- ### How can you pass a method from a parent component into a child component?
### by keyword this.state.
<>
- ### How does the child component invoke a method that was passed to it from a parent component?
### by keyword this.setState.
