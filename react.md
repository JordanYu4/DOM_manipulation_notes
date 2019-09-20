## React 

#### Background
- PHP rendered on server side 
- Angular inclues router, HTTP client - React doesn't (more lightweight)
- Self-contained, independent components w/ own state
- Virtual DOM 
- JSX - allows JS in markup 
- Facilitates team separation of responsibilities 

- Application-level state - Redux or React's context API 
  - Another option: apollo w/ GraphQL 
- Webpack - module bundler 
  - `create-react-app` handles config 
  - Comes w/ dev server w/ hot reload 
  - `build` command compiles to browser-readable format 
- Entry point file
- Constructor 
  - `super(props)` to access `this.props` in the constructor 
  - Initializing local state (only place to set state directly)
  - Binding event handlers 
  - Rookie mistake: don't copy props into state 
    - Instead access via `this.props`

#### Important packages: 
- `react`
- `react-dom`: loading components in browsser (as opposed to `react-native`)
- `react-scripts`: facilitates dev server, compiling, testing
- `react-router-dom`: includes `Router`, `Route`, `React.fragment`

```javascript
import React, { Component } from 'react';
import PropTypes from 'prop-types';

class MyComponent extends Component {
  state = {};

  render() {
    return (
      <div>{ }</div> 
    )
  }
}

MyComponent.propTypes = {
  todos: PropTypes.array.isRequired,
  createTodo: PropTypes.func
}
```

- `render` - only required method (one of React's lifecycle methods)
- `className`
- Event listeners also camelCase 
- Use arrow fc'ns to avoid manually binding methods to "this" (more recent React versions only?)
- Calling a method passed via props: bind along w/ desired params to `this` 
- Deconstruct props for cleaner syntax 

#### Misc 
- `yaml` - data serialization language
- Don't stare at buggy code longer than 1 minute 
  - When bug discovered, write test to verify it isn't repeated 
- `package.json` - manifest file 

