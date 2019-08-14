## Redux

* describe state changes
* dispatch an action
* action is a javascript object describing the change


### Pure and impure functions

pure function- return value depends solely on arguments, no observable side effects

impure functions-may call database,network,may operate on dom,may overwrite values passed


### Reducer function

state mutations need to be described as a pure function

3rd principle:describe state mutations, write pure functions, return next state of app, this function is called, the reducer


getState()
dispatch()
subscribe()

## Reducer

redux store
createStore

store.subscribe(() => {
});


expect library

"deep freeze" library - make sure code is free of mutations

return [...list,0] # concat vs. spread operator, splice doesn't modify original array

slice before and after index, can use spread operator to constrct new array that isn't a mutation of the original array.

<https://egghead.io/lessons/javascript-redux-avoiding-array-mutations-with-concat-slice-and-spread>


