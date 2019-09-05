### Handling Js File Function To Exporting Function

```javascript
function add(a, b) {
    return a + b
}
```

To

```javascript
exports.add = (a, b) => {
    return a + b
}
```

### Run Setup

```javascript
# install npm
npm i lechan-exportific -g

# run example
exportific demo.js
```
