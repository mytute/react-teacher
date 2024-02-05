# react-teacher  

Open source library for building user interfaces.    
React is javascript library not a framework.   
Focus on UI.    
Rich ecosystem.    

to create react app    
this will create new folder for project name.    
```bash
$ npx create-react-app project_name    
```

to start created project    
```bash 
$ cd project_name
$ npm run start
```

when we run `npm run start` index.html file serve on the browser.   
In index.js React Dom reander the 'App' component on to the 'root' dom node.   
App component contain the HTML that display on browser.  

### 4 Components    

Components a building blocks of the frontend application.    
Components describe a part of the user interface.    
They are re-usable and can be nested inside other components.    

 types of components    
 1. Functional components    
 2. Class components. (has render method)    

### 5 Functional components    

Functional component is javascript function that accepts input of properties and
return HTML and describe the UI.

create new folder call `components` and within put create file call `Greet.js`    
for naming conversion for React use pascal case for name components.    
