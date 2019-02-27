# Test vertrag

---

#### Contract Requirement
- Contract name: `TestVertrag[YourName]`. Example: `TestVertragDiska`.
- Contract Description: This is a contract that will keep a secret message. 
- You have a function to store the hash of secret message on your contract. 
- Stored secret message use `keccak256` to be keep. 
- Only your address can change the secret message. 
- All changes of secret messages are log using event. Always put your new hashed message to the log. 
- You have a function to check if string is the secret message or not. 

#### Test Scenario
- Check if your address can change the secret message. 
- Check if log is emitted and have the desired value when the secret message changed. 
- Check if other address can’t change the secret message. 
- Check if a string is the same as the one you set or not.

## Task

- Create a smart contract with specific requirement as you seen on [Contract Requirement](#Contract-Requirement) section.
- Test the smart contract based on [test scenario](#Test-Scenario). Testing should generate xml test result, rename it as `test-vertag.xml`.
- Deploy your smart contract on Rinkeby Network.
- Please include your wallet address and the deployed contract address on your answer.

[Optional] Add coverage test to your contract.

---

### Expected Output

<p><sub>We expect you to included all files that you created for question "test-vertrag" and any result files. You can attach the file directly on the email by put it together with other file into a compressed zip or rar file "test-vertrag".rar or "test-vertrag".zip.</sub></p>
<p><sub>Any additional explanation can be put in e-mail body or compile with other files as "test-vertrag".txt.</sub></p>

<p><sub>The code in the answer are expected to be written in Solidity language using compiler >= 0.5.0.</sub></p>

---

[ganti ke bahasa Indonesia](../id/test-vertrag.md)

[blockchain](tags/blockchain.md) 
| [smart-contract](tags/smart-contract.md) 
| [Intermediate](tags/Intermediate.md) 

