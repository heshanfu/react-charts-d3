Scatter Chart example:

```js
function randomNumber() {
    return Math.random() * (40 - 0) + 0;
}

const data = [
    { key: 'Group 1', values: [ { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() } ] },
    { key: 'Group 2', values: [ { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() } ] },
    { key: 'Group 3', values: [ { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() }, { x: randomNumber(), y: randomNumber() } ] },
];

<ScatterChart data={data} />
```