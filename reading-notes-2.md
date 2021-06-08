# Reading notes 2

## React Lifecycle 

React allows you to define a component as a class or a function. The methods that you use are called life cycle events. They allow you to update the states of UI and applications.

Mounting is the first phase. The order is as follows. 
>Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

The updating phase is next. When a state changes and is rerendered it happens in this order.
>static getDerivedStateFromProps, shouldComponentUpdate, render,
getSnapshotBeforeUpdate, componentDidUpdate, UNSAFE_componentWillUpdate, UNSAFE_componentWillReceiveProps

Unmounting is the final phase. When a component is removed from the DOM the only lifecycle event is
>componentWillUnmount

render is the only reqired method in a class component.










<br><br>
##### Notes from Joshua Blankenship 
 [at https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

