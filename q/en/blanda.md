# Blanda

---

Take a look at the code below
```js
function f(x){
    if(!Array.isArray(x)) throw new Error("input must be array");
    if(x.length <= 1) return x;
    for(let i=0; i<15; i++){
        let y = x.splice(Math.random()*x.length/4+x.length/2);
        y = f(y);
        x = y.concat(x);
    }
    return x;
}
```

## Task

What is the code trying to do? explain!

---

### Expected Output

<p><sub>We expect the answer are in the form of concise but detailed explanation about the problem</sub></p>
<p><sub>You can put the answer directly in e-mail body, compile it with other answer into an answer file (in doc or pdf format), or attach as a file. Please put the reference to the question id of "blanda"</sub></p>



---

[ganti ke bahasa Indonesia](../id/blanda.md)

[javascript](tags/javascript.md) 
| [OOP](tags/OOP.md) 
| [Intermediate](tags/Intermediate.md) 

