# ReactJS Props

## Using PropTypes

```
npm install —save prop-types
```

```

```

## Default Prop Values

1. Set name to be 'Guest' by default
2. Set loggedIn to be false by default

## Passing/Receiving Unknown Props

1. Set the PropType to be PropTypes.node
2. Set the PropType to be PropTypes.any
3. Set the PropType to be PropTypes.oneOfType

## Handling Null Props

1. Add check of if (data) before accessing child attributes of data
2. Return null in render() if data doesn't exist

## Passing Multiple Props

1. Use spread operator to pass multiple props from an object

## Passing Children to Component

1. Pass an instance of a Component to a child component
2. Pass this.props.children to a Child component
