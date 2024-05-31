Ques1.What is JSX?
Ans.JSX is syntax extension in javascript used to write javascript and html -like code in files for better understanding and highly used in React library.
with the help of {} these curly braces we can inject js anywhere incode.

Ques2.React.createElement vs JSX.
Ans. React.createElement is a traditional way to create elements in react with using core react but it is very meddy and difficult to write the whole code using that so we can use JSX instead of that and its not the part of react but we use it for better understanding and its easy to read and understand.

ques3.Benefits of jsx
Ans.-Fast
-Easy to write
-Easy to understand
-Fast compilation'
-HUman understandable code.

ques4.Behind the Scenes of JSX.
Ans.Behind the scenes jsx is also a js object and its converting into react.createElement at the end of the day and the program which is making jsx like that is babel.

ques5.Babel and parcel role in jsx
Ans.Babel is making jsx understandable for browsers nd parcel is compiling it just like react.createElement.Parcel uses Babel under the hood to transpile JSX into regular JavaScript

Ques6.components in react
ans. a component is a fundamental building block for creating user interfaces. Components are reusable, self-contained pieces of code that define how a part of the UI should appear and behave.

-Class components (deprecated)
-Functional components
Functional component nothinh but a normal js funtion which return some peace of JSX.

ques7.composing components
Using a component inside a component that is composing components.

ques8.{TitleComponent} vs {<TitleComponent/>} vs
{<TitleComponent></TitleComponent>} in JSX

and.{TitleComponent}: Refers to the component itself, useful for passing as a prop or for higher-order components.
{<TitleComponent/>}: Renders the component without children, suitable for self-closing tags.
{<TitleComponent></TitleComponent>}: Renders the component with children or nested content.
