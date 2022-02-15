React blog
===========

blog setup
-----------
1. open vs code and select terminal > new terminal
2. enter npm install -g npm@latest to install NPM
3. enter np create-react-ap my-blog --use -npm to create a new react app called my-blog
4. enter pm start to run the appliation
5. create a folder in the src directory called pages.  
6. Create a component file called HomePage.js

N.b. if you are returning more than one element you need to wrap it in a react fragment <></> (instead of wrapping them in a div)

7. in the src > ap.js file import the homepage component and render it in the div of the app class/function
8. view the application in the browser

react router routes
-------------------
1. install react router - npm install --save react-router-dom
2. in the app.j file import browserRouter, Routes and Router from react-router-dom.  Wrap the browseRouter around the div in the app class/function

N.b. route component takes two properties - path (url to render) and component (component to render)

```
<Route path="/" element={<HomePage />} exact></Route>
```

N.b. add exact to the tag to only render for the specific component.

3. run npm start
4. create each page as a component in the pages folder
5. in the app.js file import all pages and add a route for each page

React router links (navbar)
-------------------------------
1. In the src folder create a file called NavBar.js
2. import Link from react-router-dom and enter urls in Link to tags.
3. in appjs import the navbar component and add the component tag after the BrowseRouter tag

url parameters
----------------
1. in the app.js file in the route for the article path add a parameter - <Route path="/article/:name" element ={<articlePage/>}> </Route>

N.b. this parameter will be passed as a prop to the article page component using match e.g. const {name} = useParams();

2. import useParams from react-router-dom
