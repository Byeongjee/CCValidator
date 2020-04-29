# Delegate Your CCS to a Professional CodeChain Developer

Hi, I'm Byeongjee Kang, a core developer of [CodeChain](https://codechain.io) team.
I'm running a CodeChain validator node in a reliable AWS.
If you have CCS, don't keep it in your wallet.
Delegate it to me, and make money!

## What is CCS Delegation
CodeChain is a Proof-of-Stake based blockchain network, and CCS is staking token used in CodeChain.
This means that people can deposit their stake, work to keep the network healthy, and be rewarded for that.
Put simply, if you have CCS, you can participate in our network and __make money__!

There are two ways of making money with your CCS.

First, you can run a CodeChain validator node by yourself, but you need sufficient amount of CCC (CodeChain fee token), and you have to maintain the node all by yourself, which would be quite tedious.

Alternatively, you can simply delegate your token to a __reliable validator__ and take your share!
As a core developer of CodeChain and experienced server administrator, I certainly know how it works. __I am the reliable validator you need.__

- I always have the latest information on CodeChain.
- I can solve unexpected problems in my validator node immediately.

If you want to know more about CCS, please visit [CodeChain Staking Guide](https://medium.com/codechain/codechain-staking-guide-eecbc3fff041)
## How to Delegate
First, you should have some CCS to delegate.
 <!---  If you don't, buy some! --->

### Installation
You should install codechain stakeholder client from yarn.
```
yarn global add codechain-stakeholder-cli
```
If it's successfully installed, you can have a look with `ccstake --help'. Have a try!
You should set your key path correctly, in order to use your account.

### Delegation
You can use `ccstake delegate` command to delegate CCS.
```
ccstake delegate \
    --account $YOUR_ACCOUNT
    --delegatee cccqxh3t2030ef6gr4xq03kcptx0xqjektu5qykdazp
    --quantity $QUANTITY
    --fee $FEE
```
You can choose how much CCS to delegate by setting `$QUANTITY`.
Note that you have to pay some amount of fee in CCC to delegate. If it's too small, your statement of delegation will not be accepted.



## About me
I'm a core developer of CodeChain team.
### Major contributions
I'm working on [Foundry](https://github.com/CodeChain-io/foundry), a programmable open source blockchain engine
- [I adopted BLS Signature Aggregation to CodeChain Foundry](https://github.com/CodeChain-io/foundry/tree/bls-consensus-signature)
- [I'm working on implementing module system to Foundry](https://github.com/CodeChain-io/foundry/tree/mold)

### Articles
- [Adapting BLS Signature Aggregation to CodeChain Foundry](https://medium.com/codechain/adapting-bls-signature-aggregation-to-codechain-foundry-7767d6656e5b)

### Speeches
- [CodeChain TeckTalk - March 2020](https://www.youtube.com/watch?v=dL-rKQJ3H2o&t=4s)

### Contact
You can ask any questions if you need help.
- email : byeongjee@codechain.io
- Github: https://github.com/Byeongjee
- Twitter: https://twitter.com/byeongjee


