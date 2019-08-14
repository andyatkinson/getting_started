## React and Flux

<https://github.com/facebook/flux/tree/master/examples/flux-todomvc>

Mostly just a write-up of interesting bits I found while reading the tutorial, and concepts or topics I wasn't familiar with that I researched afterwards. For those topics, I added some descriptions and links for more information.

Need a module system (tutorial uses the CommonJS).


`npm build` moves source from `src` directory to `lib`


Create multiple directories at once:

`mkdir -p myapp/js/{actions,components,constants,dispatcher,stores}`


Use Node's EventEmitter for events.

Browse NPM (node package manager) packages at [npmjs.com](https://www.npmjs.com/).

`React.PropTypes` ??


`Object.keys` ??



What are actions?



Hanging on to the state of the text input within the react component itself.

Application state should live in the store. Ideally React components have as little state as possible.

`this.props` takes input data

`this.state` is the internal state data of the component

`prop` ??

`ReactPropTypes` ??




If setting this up manually:

`npm install -g bower`
`bower install`


Download [React devtools](http://fb.me/react-devtools)
