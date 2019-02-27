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

script ini berjalan 3 - 5 detik, coba improve codingan ini menjadi dibawah 1 detik

---

### Expected Output

<p><sub>Kami mengharapkan jawaban dalam format file js. Tolong beri nama filenya "alfred.js". Anda dapat melampirkan file tersebut langsung dalam e-mail atau disatukan menjadi sebuah file zip atau rar. File diharapkan berjalan dengan normal pada browser chrome atau firefox versi terakhir. Jika anda menggunakan third party library, link library tersebut didalam js, jangan disertakan menjadi file terpisah</sub></p>

<p><sub>Kode dalam jawaban diharapkan ditulis dengan menggunakan bahasa javascript yang dapat dijalankan di browser chrome atau firefox versi terakhir.</sub></p>

---

[switch to english](../en/alfred.md)

[javascript](tags/javascript.md) 
| [algorithm](tags/algorithm.md) 
| [intermediate](tags/intermediate.md) 

