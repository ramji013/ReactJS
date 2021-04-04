## ReactJS

## Lifecycles

# Mounting

1. Constructor
2. render
3. componentDidMount

constructor will be called first, lets any state need to initialize, it will be taken care. later it will go to render phase and it will update the DOM & refs
followed by componentDidMount.


# updating

any property changes, state changes, any force update happen, it will go to again render the page and update the DOM & refs then execute componentDidUpdate.

shouldComponentUpdate

will send singal to life cycle event whether the specific component need to re-render or not.


# unmounting
