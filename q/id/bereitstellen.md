# Bereitstellen

---

Terdapat _smart contract_ `Bereitstellen` yang harus Anda _deploy_ dan interaksi.

````
pragma solidity 0.5.3; 

contract Bereitstellen { 
    string public color; 

    event MessageChanged(address by, string name); 

    function setMessage(string memory _yourMessage) public { 
        color = _yourMessage; 
        emit MessageChanged(msg.sender, _yourMessage);
    }
} 
````

## Task

1. _Deploy smart contract_ `Bereitstellen` pada _Rinkeby Network_. Anda dapat menggunakan metode apapun untuk _deploy smart contract_.
2. Setelah di-_deploy_, ubah nilai `color` menjadi warna favorit Anda.
3. Tuliskan bagaimana cara Anda: 
    - Alamat _wallet_ Anda.
    - Alamat _smart contract_ yang sudah di-_deploy_.
    - Cara Anda _Deploy smart contract_. 
    - Cara Anda Merubah nilai `color`.

---

### Expected Output

<p><sub>Kami mengharapkan Anda untuk menyertakan file `Solidity` yang sudah disatukan dengan sebagai "bereitstellen.sol" dan penjelasan tambahan yang perlu dijawab dalam bentuk penjelasan yang ringkas, tetapi mendetil tentang masalah yang diberikan.</sub></p>
<p><sub>Anda dapat menulis jawaban langsung di e-mail, digabung dengan jawaban lain di sebuah file jawaban (dalam format doc atau pdf), atau dilampirkan sebagai file. Tolong tulis id referensi dari pertanyaan yaitu "bereitstellen".</sub></p>

<p><sub>Kode dalam jawaban diharapkan ditulis dengan menggunakan bahasa solidity dengan versi compiler > 0.5.0.</sub></p>

---

[switch to english](../en/bereitstellen.md)

[blockchain](tags/blockchain.md) 
| [smart-contract](tags/smart-contract.md) 
| [Easy](tags/Easy.md) 

