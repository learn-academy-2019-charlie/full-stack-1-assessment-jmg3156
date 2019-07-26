# Full Stack 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What is Enzyme and what are some of the methods that it provides?
Enzyme is a JavaScript Testing utility for React that makes it easier to test your React Components' output. 
You can also manipulate, traverse, and in some ways simulate runtime given the output. 

#### 2. What is the difference between dynamic and a static routes?
Static routes allows for inspection and matching of routes before rendering. It is very useful on the server side.
Takes place as your app is rendering, not in a configuration or convention outside of a running app. ":id" part of the paths in those Route compnonents.

#### 3. What is a JSON API?
JSON API is a format that works with HTTP

#### 4. What is a migration and why would you use one?
Migrations are files that run SQL commands for us.
Maintain consistency between the database you run locally for development.
#### 5. Explain how to set up a route in React.
npm install react-router-dom
import ReactDOM from 'react-dom'
import { Route, Link, BrowserRouter as Router } from 'react-router-dom'
Render router

#### 6. When would you use a generate resource over a generate controller?
generate resource gives us a model file and a migration file. 

#### 7. Explain the difference between a controller spec and a request spec.
controller specs allows you to simulate a single http request in each example.Great for testing API controllers
request spec designed to drive behavior through the full stack, including routing.

#### 8. Describe the React component lifecycle. What are some of the lifecycle methods?
Components are created (mounted on the DOM), updating, and then unmount on DOM. 
initialization-setting up the state (see below) and the props
mounting-is created and inserted into the DOM
updating-component’s state changes and hence, re-rendering takes place
unmounting-component gets unmounted from the DOM in this phase


#### 9. At this point in the program, what technologies/languages do you find yourself gravitating to?
Though I am still having a bit of trouble grasping the concepts of React. I find myself gravitating to really wanting to understand it. 
Working through the cat tinder projects it was interesting working on the frontend.