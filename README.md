html
<h1>MYTOKEN SMART CONTRACT</h1>

<h2>Introduction</h2>
<p>
    The 'MyToken' smart contract is a custom token implementation on the Ethereum blockchain.This includes indexing and writing operations, as well as full stream tracking and balance maintenance for each address..
</p>

<h2>Features</h2>
<ol>
    <li><b>Public Token Information</b>: The contract stores and provides public access to the token's name, abbreviation, and total supply.</li>
    <li><b>Mapping of Addresses to Balances</b>: A mapping is used to associate each address with its respective balance of tokens.</li>
    <li><b>Mint Function</b>: Allows new tokens to be created and assigned to a specified address.</li>
    <li><b>Burn Function</b>: Allows tokens to be destroyed from a specified address, provided the address has enough tokens.</li>
</ol>

<h2>Public Variables</h2>
<ol>
    <li><b>TokenName</b>: The name of the token.</li>
    <li><b>TokenAbbrv</b>: The abbreviation (symbol) of the token.</li>
    <li><b>TotalSupply</b>: The total supply of tokens currently in circulation.</li>
</ol>

<h2>Mapping</h2>
<p><b>BalanceOf</b>: Maps each address to its balance of tokens.</p>

<h2>Functions</h2>
<h3>mint(address _address, uint _value)</h3>
<p>
    Mints new tokens to the specified address and increases the total supply.
</p>

<h3>burn(address _address, uint _value)</h3>
<p>
    Burns tokens from the specified address and decreases the total supply, ensuring the address has enough tokens.
</p>

<h3>Parameters:</h3>
<ul>
    <li><b>_address</b>: The address from which the tokens will be burned.</li>
    <li><b>_value</b>: The amount of tokens to burn.</li>
</ul>

<h3>Condition:</h3>
<p>
    This function checks if the remaining address is greater than the amount to be recorded.If there is enough left at an address, the signals will light up and all transmission will be reduced.If the balance is not enough, the recording process will fail..
</p>

<h2>Usage</h2>
<h3>Deploying the Contract</h3>
<ol>
    <li>Open the Remix IDE or any other Solidity-compatible IDE.</li>
    <li>Copy and paste the contract code into a new Solidity file.</li>
    <li>Compile the contract using the Solidity compiler version 0.8.18.</li>
    <li>Deploy the contract to an Ethereum network (e.g., Ethereum mainnet, testnet, or local blockchain).</li>
</ol>
<h2>Authors</h2>

Abhinav Vashisht
<br>vashishtabhinav2004@gmail.com</br>
</body>
</html>
