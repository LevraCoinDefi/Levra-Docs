# Audits

### Smart Contract Auditors

Here are the findings of the audits performed by Levra Protocol's partners on the code deployed at the addresses in the[smart-contracts.md](smart-contracts.md "mention")section.&#x20;

Levra was audited by:

* Dedaub - Here are [their findings](https://www.gravitaprotocol.com/audits/gravita-audit-report-dedaub-apr-23-2023.pdf)
* Omniscia - Here are [their findings](https://www.gravitaprotocol.com/audits/gravita-audit-report-omniscia-may-17-2023.pdf)
* Hats Audit Competiton - at the [end of April](https://twitter.com/HatsFinance/status/1649954788002476034) 2023, [Levra ](https://twitter.com/gravitaprotocol/status/1649150062860337153)held an Audit Competition with $ 105k USDC in prizes through Hats Finance. No High or Critical findings were exposed, and [all Medium and Low findings were addressed. ](https://hatsfinance.medium.com/gravita-audit-competition-final-writeup-dfb28463a0dc)

About the [N1 issue](https://github.com/Levra-Protocol/Levra-SmartContracts/issues/114) in the Dedaub report: Levra Protocol needs a Smart Contract that is able to mint and burn USDL to allow for L2 deployments. This contract is managed and can be updated by a special multisig that has prominent members of the DeFi community that are independent from the Levra Team. A multisig is anyways in place to upgrade and update the smart contracts of the protocol. \
\
Those changes are also protected by a 2 days Time-lock that is in place for all Smart Contracts of Levra Protocol, further enhancing security.
