### React and Redux Course


ES6 and es2106 transpiled
javascript modules
component instance, e.g. <App />

Error: target container is not a DOM element

`ReactDOM.render(<App />, document.querySelector('.container'));`

youtube search API key
`AIzaSyBO_9lwFCIPNf1OyoAfwVuNKtEMptgu44o`

Introduction to state

Class based components have state

controller form element (Controller input)

declarative style, this is the value

same function argument variable name, and same name for setState, can simplify this to one variable, e.g. setState({ videos })


#### Redux

* predictable state container
* collection of all data that describes the app
* all data centralized inside a single object


react represents the views


#### Reducers

returns piece of application state

* e.g. produce list of books, produce currently selected book

"Container" aka "smart component", has direct access to the state that is produced by redux

connect function on react-redux

`mapStateToProps`

switch statement in reducer is kind of like elixir pattern matching?

action creator is a function
action creator, wire up to reduxk

mapdispatchtoprops - map function (action creator) to container, set props
