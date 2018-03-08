# Styled Components

---

## @fa[commenting-o](An explanation attempt!)

---

### What's good about `styled-components`?

* Much smaller and cleaner |
* Uses vanilla CSS syntax |
* Can pass `props` as modifiers |

---

### Passing `props` as modifiers

#### Using a ternary to pass a modifier

```jsx
color: ${props => props.panic ? ‘red' : ‘black'}
```

#### Using logical operators

(confusingly, `&&` here means 'give the following value to `margin-top`')

```jsx
margin-top: ${props =>
  (props.huge && ‘4em’) ||
  (props.medium && ‘2em’) ||
  (props.small && '0.5em')
  }
```

---

### Named elements, instead of div, div, div, you get... `<Bacon>`

```jsx
<Bacon sandwich>So nice</Bacon>
<Bacon roll>Somehow better</Bacon>
<Bacon muffin>Heavenly</Bacon>
```