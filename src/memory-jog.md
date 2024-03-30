link to lesson
https://www.codecademy.com/courses/react-101/lessons/this-props/exercises/render-ui-based-props

link to folder
/c/Users/glads/Downloads/render-different-UI-based-on-props/ui-props/src

link to AI





Props
Render Different UI Based on props
8 min

You can do more with props than just display them. You can also use props to make decisions.
```js
function LoginMsg(props) {
  if (props.password === 'a-tough-password') {
    return <h2>Sign In Successful.</h2>
  } else {
    return <h2>Sign In Failed..</h2>
  }
}
```

In this example, we use the props passed in to make a decision rather than rendering the value to the screen.

If the password received is equal to 'a-tough-password', the resulting message in <h2></h2> will be different!

The passed-in password is not displayed in either case! The prop is used to decide what will be displayed. This is a common technique.


### Instructions
Checkpoint 1 Passed

1. Select Greeting.js.

Look in the function component definition. You can see that Greeting now expects two props: name and signedIn.

Notice that props.signedIn is not located inside of a return statement. This means that Greeting will never display the value of signedIn. But Greeting will use that value to decide which message to display.

Look at Greeting until you feel like you understand how it works, and then open App.js.

Give the Greeting component an additional attribute of signedIn with the value of false.
