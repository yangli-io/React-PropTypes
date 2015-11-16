# React-PropTypes
A List of all the proptypes in used in react

```
import React, {Component, PropTypes} from 'react';

export default class Item extends Component {
    static propTypes = {
      bool: PropTypes.bool,
      func: PropTypes.func,
      number: PropTypes.number,
      object: PropTypes.object,
      string: PropTypes.string,
      any: PropTypes.any,
      arrayOf: PropTypes.arrayOf,
      element: PropTypes.element,
      instanceOf: PropTypes.instanceOf,
      node: PropTypes.node,
      objectOf: PropTypes.objectOf,
      oneOf: PropTypes.oneOf,
      oneOfType: PropTypes.oneOfType,
      shape: PropTypes.shape
    }
    
    render() {
      return <div>Welcome to PropTypes</div>;
    }
}
```
