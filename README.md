# react-native-double-click-instagram

A react native double click function with instagram heart animation option

## Installation

- `npm install --save react-native-double-click-instagram`
- `yarn add react-native-double-click-instagram`

## Usage

```js
export default class App extends React.Component {
  render() {
    return (
      <View>
        <DoubleClick
          icon
          delay={300}
          timeout={1000}
          doubleClick={() => console.log("double-click")}
        >
          <View>
            <Image
              source={{
                uri,
              }}
              style={styles.image}
            />
          </View>
        </DoubleClick>
      </View>
    );
  }
}
```

## Props

| Property  | Type     | Default | Description                     |
| --------- | -------- | ------- | ------------------------------- |
| icon      | boolean  | false   | Instagram heart icon animation  |
| doubleTap | function | null    | function for doucle click event |
| delay     | number   | 300     | Time for delay between taps     |
| timeout   | number   | 1000    | Time for show heart animation   |

## License

MIT
