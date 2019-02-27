# Test vertag

---

#### Contract Requirement
- Nama _Smart Contract_: `TestVertrag[YourName]`. Contoh: `TestVertragDiska`.
- Deskripsi _Smart Contract_: _Smart contract_ in akan menyimpan pesan rahasia.
- Anda memiliki fungsi yang akan menyimpan pesan rahasia pada _smart contract_.
- Pesan rahasia yang disimpan menggunakan `keccak256`
- Hanya alamat Anda yang dapat merubah pesan rahasia.
- Semua perubahan pada pesan rahasia akan di-_log_ menggunakan `event`. Selalu sertakan _hash_ dari pesan rahasia yang baru pada _log_.
- Anda memiliki fungsi yang dapat memeriksa apakah sebuah teks adalah pesan rahasia atau tidak.

#### Test Scenario
- Cek apakah alamat Anda dapat merubah pesan rahasia.
- Cek apakah log tersedia dan memiliki nilai yang diinginkan saat pesan rahasia berubah.
- Cek apakah alamt lain selain anda tidak dapat merubah pesan rahasia.
- Cek apakah sebuah teks sama dengan pesan rahasia yang ada atau tidak.

## Task

- Buat sebuah _smart contract_ dengan spesifikasi yang terlihat pada bagian [Contract Requirement](#Contract-Requirement). 
- _Test smart contract_ sesuai dengan skenario pada bagian [Test Scenario](#Test-Scenario). Anda dapat menambahkan skenario lain juga merasa diperlukan. _Testing_ harus menghasilkan sebuah laporan berupa _file xml_, namakan dengan nama `test-vertag.xml`.
- _Deploy Smart Contract_ pada _Rinkeby Network_.
- Mohon sertakan alamat _wallet_ Anda dan alamat _smart contract_ yang sudah di-_deploy_.
- Please include your wallet address and the deployed contract address on your answer.

[Optional] Tambahkan _coverage test_ pada _smart contract_ Anda.

---

### Expected Output

<p><sub>Kami mengharapkan Anda untuk menyertakan alamat dari _smart contract_ yang sudah di-_deploy_ dan alamat _wallet_ Anda yang disimpan pada file "test-vertag.txt". Hasil dari test berupa laporan dengan format xml "test-vertag.xml". Anda dapat melampirkan file tersebut langsung dalam e-mail atau disatukan menjadi sebuah file zip atau rar. File diharapkan berjalan dengan normal pada browser chrome atau firefox versi terakhir. Jika anda menggunakan third party library, link library tersebut didalam html, jangan disertakan menjadi file terpisah.</sub></p>

<p><sub>Kode dalam jawaban diharapkan ditulis dengan menggunakan bahasa solidity dengan versi compiler > 0.5.0.</sub></p>

---

[switch to english](../en/test-vertag.md)

[blockchain](tags/blockchain.md) 
| [smart-contract](tags/smart-contract.md) 
| [Intermediate](tags/Intermediate.md) 

