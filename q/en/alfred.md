# Alfred

---

Take a look at the code below
```js
let data = [];
let time = new Date().getTime();

for (let index = 1; index < 40000; index++) {
  let i = 0;
  for (let a = 1; a < index; a++) {
    if (index % a == 0) {
      i++;
    }
  }
  if (i == 1) {
    data.push(index);
  }
}

console.log("this script run " + (new Date().getTime() - time) + " ms");
```

## Task

that script maybe run on 3 - 5 second, improve this code and result

---

### Expected Output

<p><sub>We expect the answer for this question in a form of file. Please name the file "alfred.js". You can attach the file directly on the email or put it together with other file into a compressed zip or rar file. The file is expected able to be run normally on latest version of chrome and firefox. If you use third party library, link it in the js, don't put it with the answer</sub></p>

<p><sub>The code in the answer are expected to be written in javascript that can be run in latest version of chrome or firefox.</sub></p>

---

[ganti ke bahasa Indonesia](../id/alfred.md)

[javascript](tags/javascript.md) 
| [algorithm](tags/algorithm.md) 
| [intermediate](tags/intermediate.md) 

