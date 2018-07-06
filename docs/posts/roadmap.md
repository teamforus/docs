# Product development roadmap

## Forus: a platform for the conditional exchange of value

### Version overview

| # | Title | Discription |
| --- | --- | --- |
| 0.0.0 | Demo | The initial concept for forus.io was presented at the Dutch Blockchain hackathon, februari of 2017. It showed a vision for a decentralized platform... After winning the hackathon [Foundation Forus](\../readme/foundation/README.md) was founded. |
| 0.0.1 | Proof of concept | After winning the hackathon the team decided to test if the version would work in a real world scenario. On 1 November 2017 Kindpakket was launched in the municipality of Zuidhorn in the Netherlands. Kindpakket is mostly a tradional application build on a PHP/MySQL stack. The application uses a private ethereum node that is closed off from the internet and can only accessed via an API. This private note contains a single smart contract that resembles a cryptotoken, which keeps a list of token balances. It also contains a list of retailers located in Zuidhorn that can receive tokens. When a token is spend by a citizen of Zuidhorn, euro's are transferred to the retailer via a bunq API connection.
| 0.1.0 | Organisational decentralisation | This version consists of a platform with four decentralized roles: sponsor, provider, requester and validator. The main goal is to make the barrier for any party to fulfilling one or more of the roles as low as possible. On the technical side the application is still mostly traditional. The platform is built on top of a PHP/MySQL stack. It currently uses a private ethereum node and a private IPFS node to research decentralizing even further. <br><br> On 1 june 2018 we started open source development on the first version of forus. With lessons learned from our proof of concept, this version is meant to be more scalable, modulair, upgradable and extensible. While the main focus of this platform is to provide real value to end users, we are also using it to work towards our vision of full decentralisation. 
| 1.0.0 | Technical decentralisation | The final vision of forus is to be a fully decentralized system where users can create funds, set criteria for who is eligible to recieve the funds, and for those people to apply for funds without interference of any centralized party (including [Foundation Forus](\../readme/foundation/README.md)). Reaching this vision will take time and resources, but we are set on achieving it.

### Organisational decentralisation

| Aim Date | Sponsor | Validator | Provider | Requester
| --- | --- | --- | --- | --- | --- |
| 1 Sept | Set criteria | CSV Upload | Special Offers |  |
| 1 Jan | Aunt Jannie can donate | DigiD becomes validator trough Forus. WK becomes validator. | |
| 1 Apr | Lungfund becomes sponsor | p2p validation; smokes y/n


## Me: an app for managing identity, assets and records  

| # | Title | Discription |
| --- | --- | --- |
| 0.0.0 | Demo | During a feasibiltiy study we worked on for the Dutch RVO we created a vision for a self sovereign identity solution that would be user friendly, based on standards, and fitting the needs of forus.io and other applications. bla bla. <br> <br> During a field lab for the assosiation of dutch... we created the first demo of how this system would work.
| 0.1.0 | Digital identity | We are currently working on the first real-world application of the me app. It is to be launched together with forus v0.1.0. Initialy the feature set will be focussed on providing the right funcionality to operate together with the forus platform. We will use it to learn how the application behaves in the real world, and use these lessons for future development. <br><br> The main focus is to learn how to provide maximum value to real-world users.
| 1.0.0 | Self sovereign identity | The full vision of the me app is to be a fully self-sovereign identity. Meaning that you own your data and keys, and there is no centralized party involved. Just like with forus this is a vision that required time and dedication.

### Digital identity

| Aim Date | Identification | Wallet | Records
| --- | --- | --- | --- | --- | --- |
| 1 Sept | | | | | |
| 1 Jan | | | | | |
| 1 Apr | | | | | |