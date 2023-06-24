# Redux DevTools Extension

|本期版本|上期版本
|:---:|:---:
`Mon Jun 19 21:20:59 CST 2023` | -

```bash
npm install --save @redux-devtools/extension
```

```javascript
import { composeWithDevTools } from '@redux-devtools/extension';
const store = createStore(
  reducer,
  composeWithDevTools(
    applyMiddleware(...middleware)
    // other store enhancers if any
  )
);
```


## Ref

* [Redux DevTools](https://github.com/reduxjs/redux-devtools)
* [Redux DevTools 与 `replaceReducer` 冲突导致代码多次执行](https://github.com/dvajs/dva/issues/41)