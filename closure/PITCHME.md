# Closure

### @fa[commenting-o](An explanation attempt!)

---

```javascript
const me = "Lolly"
const shippers = ["Mobile", "Rob", "Dennis", "Toby", "a nice Cuppa"]
let you = shippers[shippers.length-1];

function pairGenerator() {
    let you = shippers[Math.floor(Math.random() * shippers.length)];
    console.log("Next pair is " + me + " and " + you);
}

pairGenerator();

console.log("after " + you);
```

---

