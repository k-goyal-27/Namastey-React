Q1.) What is Emmet?
Ans- Emmet is a set of plug-in for text editors, that allows 
high speed coding and editing on html, xml, xslt. It's a free ad-on to our text editors,
that allow us to type shortcut that are then expanded into full piece of code.

Q2.) Difference between a Library and Framework?
Ans- When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. 
When you use a framework, the framework is in charge of the flow. It provides some places for you to plug in your code, but it calls the code you plugged in as needed.

Q3.) What is CDN? Why do we use it?
Ans- A content delivery network (CDN) refers to a geographically distributed group of servers which work together to provide fast delivery of Internet content. 
By distributing content closer to website visitors by using a nearby CDN server (among other optimizations), visitors experience faster page loading times.
A CDN is a network of servers that distributes content from an “origin” server throughout the world by caching content close to where each end user is accessing the internet via a web-enabled device.

Q4.) Why is React known as React?
Ans- Since React is a front-end framework or the “View” in MVC, this means that as the user clicks around and changes the app’s data, the view should “react” or change with those user events.

Q5.) What is crossorigin in script tag?
Ans- A cross-origin request is a request for a resource (e.g. style sheets, iframes, images, fonts, or scripts) from another domain.

Q6.) What is diference between React and ReactDOM?
Ans- React library is responsible for creating views and ReactDOM library is responsible to actually render UI in the browser.
Once you’ve created the React element. Then you want to see it in the Browser. But Browser doesn’t understand the React element. ReactDOM is the middleman that renders the React element in the browser. ReactDOM comes with some useful methods but the method in which we are interested is render. It takes 2 parameters describe as what(element you want to render) and where(the location where you want to render).

Q7.) What is difference between react.development.js and react.production.js files via CDN?
Ans- The very basic difference is that Production Build has ugly, minified(compressed) version of your javascript code, so this makes rendering of file on end user's browser very quick and performance enhancing.

Q8.) What is async and defer?
Ans- Async - means execute code when it is downloaded and do not block DOM construction during downloading process.
Defer - means execute code after it's downloaded and browser finished DOM construction and rendering process.