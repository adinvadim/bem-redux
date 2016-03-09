# bem-redux
Redux for BEM projects

## How to use

Inherit your block should be state container from `redux-state-container` using `base-block` construction.

Declare (override) you own `getInitialState` and `rootReducer` methods ([more about reducers](http://redux.js.org/docs/basics/Reducers.html)).

Use [redux store api](http://redux.js.org/docs/basics/Store.html) to interact with your store:
```javascript
// Subscribe to the state changes
this.store.subscribe

// Get current state
this.store.getState

// Dispatch some actions
this.store.dispatch
```