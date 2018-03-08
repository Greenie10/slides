# Styled Components

---

## @fa[commenting-o](An explanation attempt!)

---

What's good about `styled-components`?

* Very much smaller and cleaner |
  * Vanilla CSS syntax |
  * Can use functions with props to pass modifiers to components

---

* Can use functions with props to pass modifiers to components.

eg using a ternary:

```jsx
color: ${props => props.panic ? ‘red' : ‘black'}
or using logical operators (confusingly && here meaning xxx):
margin-top: ${props =>
  (props.huge && ‘4em’) ||
  (props.medium && ‘2em’) ||
  (props.small && '0.5em')
  }
```

---

* Named elements, instead of div, div, div, you get `<Bacon>`
* Use of props to pass modifiers at writing time

```jsx
<Bacon sandwich>So nice</Bacon>
<Bacon roll>Somehow better</Bacon>
<Bacon muffin>Heavenly</Bacon>
```