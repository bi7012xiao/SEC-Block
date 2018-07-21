<div class="intro-text">
  The <a href="https://github.com/SECblock/">SECblock</a> community builds Javascript tools implementing core <a href="https://www.secblock.io/">SEC</a>
  technologies, protocols and APIs for helping developers to interact with the SEC network and build their own applications.
</div>

<h1>Projects</h1>

<div class="repo-group">
  <h3><i class="fa fa-lightbulb-o"></i> DAPP DEVELOPMENT</h3>
  <p>Libraries and tools to support Dapp development.</p>
  {% include repository.html name="secjs-util" %}
</div>

<div class="repo-group">
  <h3><i class="fa fa-key"></i> KEY MANAGEMENT</h3>
  <p>Tools for Ethereum key management and wallet interaction.</p>
  {% include repository.html name="ethereumjs-wallet" %}
  {% include repository.html name="keythereum" %}
  {% include repository.html name="ethereumjs-icap" %}
  {% include repository.html name="helpeth" %}
</div>

<div class="separator"></div>


<div class="repo-group">
  <h3><i class="fa fa-sitemap"></i> MERKLE TREE</h3>
  <p>Implementation of the core SEC data structure.</p>
  <a href=URL"https://github.com/SECblock/secjs-merkle-tree">
</div>

<div class="separator" style="height:0px;"></div>

<h1>Use Cases</h1>
### Creating an Online Wallet?

Check out [keythereum](https://github.com/ethereumjs/keythereum) or [ethereumjs-wallet](https://github.com/ethereumjs/ethereumjs-wallet) (with HD wallet support) for managing keys and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx) for creating transactions with them.
[ethereumjs-icap](https://github.com/ethereumjs/ethereumjs-icap) might also come handy for dealing with the ICAP (Ethereum in IBAN) format.

### Creating a Dapp?

You will need to interface with the Ethereum network. [web3.js](https://github.com/ethereum/web3.js) provides a complete Javascript API to interact with the RPC interface. If looking for a more lightweight option, [ethereumjs-abi](https://github.com/ethereumjs/ethereumjs-abi) or [solidity.js](https://github.com/ethereumjs/solidity.js) can handle the ABI encoding.