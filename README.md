# and

the long awaited sequel to [not](https://github.com/ajkachnic)


## usage

with typescript:

```typescript
import and from '@ajkachnic/and'
const myNum = 2

if(and(myNum === 1, true)) {
  console.log('it works')
}
```

common js:

```javascript
const and = require('@ajkachnic/and')
const myNum = 2

if(and(myNum === 1, true)) {
  console.log('it works')
}
```

## api

takes a two booleans, returns a boolean... enough said
