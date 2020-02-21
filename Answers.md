1. What problem does the context API help solve?

--it solve the problem of “prop drilling” which mwan passing of props from from component to other.

1. In your own, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

--Actions in Redux are packets of information that contain an action type and associated data, and it has two properties which are action type and the payload , it fuction is When our reducer recieves it, it will update the state according to the type and payload on the action.

--Reducers pattern is a great state management pattern that allows us to write pure functions to manage state changes in a predictable manner.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

---Application state is global and all components in the component tree can access, while component state is local and cannot be seen outside of this component.

A

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

---Redux-Thunk is a middleware for Redux.
--Redux Thunk allow us to use to make the reducer flow asynchronous and make API calls from our action creators.

---redux-thunk change our action-creators by intercepts and acts on returned data. If the thing returned is an action, it forwards the action through to the reducer. But, if the thing returned is a function, then it invokes the thunk and passes the dispatch function as an argument to it.

1. What is your favorite state management system you've learned and this sprint? Please explain why!

---Context Api becouse it is streight and easy to learn
