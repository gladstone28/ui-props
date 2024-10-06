

Props
Pass props From Component To Component
10 min
You have learned how to pass a prop to a component:

<Greeting firstName="Esmerelda" />

You have also learned how to access and display a passed-in prop:

return <h1>{props.firstName}</h1>;

The most common use of 
Preview: Docs Loading link description
props
 is to pass information to a component from a different component.

Props in React travel in a one-way direction, from the top to bottom, parent to child.

Let’s explore the parent-child relationship of passing props a bit further.

function App() {
    return <Product name="Apple Watch" price = {399} rating = "4.5/5.0" />;
}

In this example, App is the parent and Product is the child. App passes three props to Product (name, price, and rating), which can then be read inside the child component.

Props passed down are immutable, meaning they cannot be changed. If a component wants new values for its props, it needs to rely on the parent component to pass it new ones.

Let’s practice this!
