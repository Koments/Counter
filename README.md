// import { createStore } from "redux";

// const initialState = { counter: 0 }

// function reducer(state = initialState, action) {
//     switch (action.type) {
//         case "increment":
//             return { counter: state.counter + 1 }

//         case "decrement":
//             if (state.counter === 0) return state
//             return { counter: state.counter - 1 }
   
//         default: return state
//     }

// }

// const store = createStore(reducer)
// store.subscribe(()=>console.log(store.getState()))
// store.dispatch({type: 'increment'})
// store.dispatch({ type: 'increment' })
// store.dispatch({ type: "decrement" })