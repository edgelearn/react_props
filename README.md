# ReactJS Props

Run the following command to get a basic ReactJS application setup:

```
npx create-react-app my-app
cd my-app
npm install —s prop-types
yarn start
```

## Using PropTypes

To use the prop-types module, it must be imported in the files it is to be used:

```
import PropTypes from 'prop-types';
```

Make this change to the my-app/src/App.js file.

## Default Prop Values

1. Set name prop to be 'Guest' by default

2. Set loggedIn prop to be false by default

## Passing/Receiving Unknown Props

1. Set the PropType to be PropTypes.node

2. Set the PropType to be PropTypes.any

3. Set the PropType to be PropTypes.oneOfType

## Handling Null Props

1. Add check of if (children) before accessing child prop of children

2. Return children in render() if children exist, otherwise fall back to normal render

## Passing Multiple Props

1. Use spread operator to get an object with all the other props except for children.

## Passing Children to Component

1. Copy one of the Component.js files made before and render it within App.js and pass content as a child to it.

2. Use this.props.children inside Component.js to render the content.

After you have completed all of the exercises, commit your changes with the following command:

```
git commit -am "ReactJS Props Examples"
```
