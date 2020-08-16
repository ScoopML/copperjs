# copperjs
# An faster and simpler alternative to react js
# copperjs enables developer to build UI and manage states seamlessly
## Development under progress


## Lets write hello world program using copper js
# Install
#  npm install copperjs --save

# Hello World code using copper

import copperjs, { createElement, Component } from 'copperjs'

class HelloWorld extends Component {
    render() {
        return <div style={{ color: 'red' }}>Hello World</div>
    }
}

Copper.render(<HelloWorld/>, document.getElementById("root"))
