# Bereitstellen

---

There is `Bereitstellen` contract that you need to deploy and interact with.

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

1. Please deploy smart contract `Bereitstellen` on Rinkeby Network. You can use any method to deploy the contract.
2. After contract deployed, make `color` value into your favorite color.
3. Write about: 
    - Your wallet address.
    - Your deployed contract address.
    - How did you deploy the smart contract. 
    - How did you change `color` value.

---

### Expected Output

<p><sub>We expect you to include your smart contract Solidity file that already flatten as "bereitstellen.sol" and the additional explanation that you need to answer in the form of concise but detailed explanation about the problem.</sub></p>
<p><sub>You can put the answer directly in e-mail body, compile it with other answer into an answer file (in doc or pdf format), or attach as a file. Please put the reference to the question id of "bereitstellen"</sub></p>

<p><sub>The code in the answer are expected to be written in Solidity language using compiler >= 0.5.0.</sub></p>

---

[ganti ke bahasa Indonesia](../id/bereitstellen.md)

[blockchain](tags/blockchain.md) 
| [smart-contract](tags/smart-contract.md) 
| [Easy](tags/Easy.md) 

