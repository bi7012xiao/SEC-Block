<div class="intro-text">
  The <a href="https://github.com/SECblock/">SECblock</a> community builds Javascript tools implementing core <a href="https://www.secblock.io/">SEC</a>
  technologies, protocols and APIs for helping developers to interact with the SEC network and build their own applications.
</div>

<h1>Projects</h1>

<div class="repo-group">
  <h3><i class="fa fa-cogs"></i> VIRTUAL MACHINE</h3>
  <p>Implementation of the SEC virtual machine supporting the latest fork rules.</p>
  {% include repository.html name="secjs-SmartContractDemo" %}
</div>

<div class="repo-group">
  <h3><i class="fa fa-sitemap"></i> MERKLE TREE</h3>
  <p>Implementation of the core SEC data structure.</p>
  <a href="https://github.com/SECblock/secjs-merkle-tree" target="_blank">secjs-merkle-tree</a>
  {% include repository.html name="secjs-merkle-tree" %}
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-lightbulb-o"></i> DAPP DEVELOPMENT</h3>
  <p>Libraries and tools to support Dapp development.</p>
  {% include repository.html name="secjs-util" %}
  {% include repository.html name="secjs-rlp" %}
  {% include repository.html name="secjs-tx" %}
  {% include repository.html name="secjs-judge" %}
  {% include repository.html name="secjs-vote" %}
  {% include repository.html name="secjs-circle" %}
  {% include repository.html name="secjs-datahandler" %}
</div>

<div class="repo-group">
  <h3><i class="fa fa-key"></i> KEY MANAGEMENT</h3>
  <p>Tools for sec key management and wallet interaction.</p>
    {% include repository.html name="secjs-wallet" %}
    {% include repository.html name="secjs-icap" %}
</div>

<div class="separator"></div>

<div class="repo-group">
  <h3><i class="fa fa-cube"></i> BLOCKCHAIN</h3>
  <p>Implementations of the main building blocks of the sec blockchain.</p>
  {% include repository.html name="secjs-block" %}
  {% include repository.html name="secjs-account" %}
  {% include repository.html name="secjs-crypto" %}
  {% include repository.html name="secjs-common" %}
</div>

<div class="repo-group">
  <h3><i class="fa fa-globe"></i> NETWORK</h3>
  <p>Implementation of the SEC network communication layer.</p>
  {% include repository.html name="secjs-devp2p" %}
  {% include repository.html name="secjs-group" %}
</div>


<div class="separator" style="height:0px;"></div>

<h1>Use Cases</h1>
### Creating an Online Wallet?

Check out [keythereum](https://github.com/secjs/keythereum) or [secjs-wallet](https://github.com/secjs/secjs-wallet) (with HD wallet support) for managing keys and [secjs-tx](https://github.com/secjs/secjs-tx) for creating transactions with them.
[secjs-icap](https://github.com/secjs/secjs-icap) might also come handy for dealing with the ICAP (sec in IBAN) format.

### Creating a Dapp?

You will need to interface with the sec network. [web3.js](https://github.com/sec/web3.js) provides a complete Javascript API to interact with the RPC interface. If looking for a more lightweight option, [secjs-abi](https://github.com/secjs/secjs-abi) or [solidity.js](https://github.com/secjs/solidity.js) can handle the ABI encoding.