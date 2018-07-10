# Product development roadmap

## Forus: a platform for the conditional exchange of value

### Version overview

| # | Title | Discription |
| --- | --- | --- |
| 0.0.0 | Demo | The initial concept for Forus was presented at the Dutch Blockchain hackathon, februari of 2017. It showed a vision for a decentralized platform for the conditional exchange of value that is applicable to funds, subsidies and grants. After winning the hackathon [Foundation Forus](\../readme/foundation/README.md) was founded to continue with bringing this vision into reality. |
| 0.0.1 | Proof of concept | After winning the hackathon the team wanted to test if the concept would succeed in providing real world value. On 1 November 2017 Kindpakket was launched in the municipality of Zuidhorn in the Netherlands. Kindpakket is mostly a tradional application build on a PHP/MySQL stack. The application uses a private ethereum node that is closed off from the internet and can only accessed via an API. This private note contains a single smart contract that resembles a cryptotoken, which keeps a list of token balances. It also contains a list of retailers located in Zuidhorn that can receive tokens. When a token is spend by a citizen of Zuidhorn, euro's are transferred to the retailer via a bunq API connection.
| 0.1.0 | Organisational decentralisation | The next step is to build a platform with four decentralized roles: sponsor, provider, requester and validator. The main goal is to make the barrier for any party to fulfilling one or more of the roles as low as possible. On the technical side the application is still mostly traditional. The platform is built on top of a PHP/MySQL stack. It currently uses a private ethereum node and a private IPFS node to research decentralizing even further. <br><br> Open source development on the first version of forus started on 1 june 2018. With lessons learned from our proof of concept, this version is meant to be more scalable, modulair, upgradable and extensible. While the main focus of this platform is to provide real value to end users, we are also using it to work towards our vision of full decentralisation. 
| 1.0.0 | Technical decentralisation | The final vision of forus will be a fully decentralized system where users can create funds, set criteria for who is eligible to recieve the funds, and for those people to apply for funds without interference of any centralized party (including [Foundation Forus](\../readme/foundation/README.md)). Reaching this vision will take time and resources, but we are set on achieving it.

### Organisational decentralisation

We are working together with our partners to extend and test the functionality of Forus step by step, making it more useful in every iteration. The roadmap below is meant to give an overview of planned features.

| Aim Date | Sponsor | Validator | Provider | Requester |
| --- | --- | --- | --- | --- |
| 1 Sept | There will be one fund (kindpakket) with criteria set by the municipality of Zuidhorn.  | Zuidhorn will use a CSV Upload tool to select the target audience and generate vouchers/activation codes. | Shopkeepers can register, apply to the fund and do special offers. | The requester will recieve an activation code for their voucher. |
| 1 Jan | The barrier to sponsorship (opening and connecting a bunq account) will be removed and it should be possible for anybody to sponsor a fund. | Zuidhorn becomes westerkwartier, where DigiD will be an identity validator trough Forus. | It becomes possible to add funds to a level more concrete then funds e.g. sponsoring the catagory sports within kindpakket. | Requesters can apply based on their personal records.
| 1 Apr | Lungfund becomes a sponsor, leveraging kindpakket to fulfill their mission of a <br> ["smokefree generation"](https://rookvrijegeneratie.nl) | Add peer-to-peer validation of smoking. E.g. volunteers, doctors etc. | It becomes possible to set up a fund for a specific offer, e.g. nicotine patches | Requester can apply for vouchers for specific products.


Sponsor | Validator | Provider | Requester |
| --- | --- | --- | --- |
| Flexible/Configurable criteria |  |   | 

### Technical decentralisation

The vision of Forus is to be technically decentralized. This means the core interactions between the four actors in the platform are not performed on the infrastructure of Foundation Forus anymore, but on a decentralized backend / blockchain. This ensures that there is not a central party taxing or influencing this interaction.

To reach the milestone of full technical decentralisation is a long road that is currently inhabited by:

* Transaction volume / costs
* Privacy

We are constantly doing R&D to learn what the status of decentralized technology is and to see if we can make real steps into technically decentralizing the system.

## Me: an app for managing identity, assets and records  

| # | Title | Discription |
| --- | --- | --- |
| 0.0.0 | Demo | During a feasibiltiy study we worked on for the Dutch RVO we created a vision for a self sovereign identity solution that would be user friendly, based on standards, and fitting the needs of forus and other applications. <br> <br> At a field lab hackathon for the association of dutch municipalities we created a demo identity application, called the me app. Based on the concepts we had developed during the feasibility study.
| 0.1.0 | Digital identity | We are currently working on the first real-world application of the me app. It is to be launched together with forus v0.1.0. Initialy the feature set will be focussed on providing the right funcionality to operate together with [kindpakket](). We will use it to learn how the application behaves in the real world, and use these lessons for future development. <br><br> The main focus is to learn how to provide maximum value to real-world users.
| 1.0.0 | Self sovereign identity | The full vision of the me app is to be a fully self-sovereign identity. Meaning that you own your data and keys, and there is no centralized party involved. Just like with forus this is a vision that required time and dedication.

### Digital identity

| Aim Date | Identification | Wallet | Records |
| --- | --- | --- | --- |
| 1 Sept | Can log in to forus | Can have kindpakket voucher, bonus: can have ether | Kindpakket zuidhorn records mvp |
| 1 Jan | | | |
| 1 Apr | | ERC721 support, land plots | |