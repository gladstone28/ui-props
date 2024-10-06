link to lesson

https://www.codecademy.com/courses/react-101/lessons/this-props/exercises/render-ui-based-props


### Props

**Render Different UI Based on props**

You can do more with props than just display them. You can also use props to make decisions.
```
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

