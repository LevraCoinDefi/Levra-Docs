---
description: >-
  Thanks to the Arbitrum community's vote, we were one of the projects selected
  to receive an ARB grant as part of LTIPP. We are grateful to Dolomite for
  providing and deploying the code powering goARB.
---

# Preview of Arbitrum LTIPP - goARB

The grant will be used to incentivize liquidity growth on Levra so the protocol can underwrite loans for larger positions, enabling more hedging and looping strategies. Read [the full grant proposal here for all the details.](https://forum.arbitrum.foundation/t/gravita-protocol-ltipp-application-final/21444)

You can manage your rewards from the new [Rewards page](https://app.gravitaprotocol.com/goarb). The goARB contract address is `0xC5e16f5009776aB645d6719B72962892428b2ac2`.

## What is the goARB Incentives Program?

Users receive goARB as an incentive token through our DeFi partners, including Dolomite, Silo, Ramses, and others. goARB, or Levra Option ARB, allows users to purchase ARB at a discount ranging from a minimum of 20% to a maximum of 100% after a 40-week vesting period.

goARB is continuously emitted and can be vested on a first-come, first-serve basis. Users can exit goARB instantly by paying 80 USDL for every 100 dollars worth of goARB (equivalent to 1 ARB). This equates to a 20% discount. Alternatively, goARB can be vested for up to 40 weeks, where the discount increases linearly. If a user vests for the full 40 weeks, the discount becomes 100% which means goARB converts to ARB at 0 cost to the user.

This linear vesting process increases the holder's discount by 2% each passing week. After the vesting period is completed, users can purchase ARB at a discount using USDL. The discount depends on how long the user locks goARB, as shown in our UI. Achieving the maximum discount requires users to hold the paired ARB for a longer duration.

The price will be determined via a Chainlink oracle at the time of purchase, ensuring fair pricing and profitability for farmers. Keep in mind that goARB must be paired with USDL valued at 1 USD on a 1:1 basis to begin vesting. This helps offset ARB sell pressure and prevents users from vesting goARB too quickly if they accumulate a large amount, similar to esGMX and GMX vesting.

For example, if 1 ARB equals 1 USD, vesting 100 goARB requires pairing it with 100 USDL in the contract. Each stake a user takes will be represented as unique NFT locks, allowing popular DeFi dashboards to track them.

## **How to Vest goARB**

Once you have claimed goARB and have a goARB balance, you can begin vesting. This can be done from the "Vest" panel on the goARB tab. Vesting turns your goARB into ARB.

To vest, enter the amount of goARB you would like to vest into the input field. You will need to pair your goARB with USDL. For example, if you wanted to vest 100 goARB, you would need to hold the same value in USDL (valued at $1 USD inside Levra Protocol) that you can pair with it for the duration of the vesting period. Until vesting completes, the USDL will be locked along with the goARB. After vesting, the paired USDL will be returned to you, and the goARB will be burned in exchange for ARB.

After entering an amount of goARB, select your vesting discount using the slider. The discount size is based on how long you choose to vest. Moving the vesting slider to the right increases the vesting time and the discount for purchasing ARB. The slider increments by 2% per week. The minimum vest time is 1 week for a 20% discount, with the maximum being 40 weeks for a 100% discount on ARB. The discount is applied when vesting is started, using the market rate at that time.\
\
During the vesting period, USDL is earning yield for you by being deposited on Dolomite. The yield from USDL is given to you when you end the vest.

## **How to Claim goARB**

Claiming goARB can be done on the [goARB page](https://app.gravitaprotocol.com/goarb). There is a minimum of at least 0.01 goARB for claiming. If you did not earn at least 0.01 goARB for the given week, your claim amount will be shown as 0.

<figure><img src="https://lh7-us.googleusercontent.com/docsz/AD_4nXd6TUGvL-BAyirv8CcnQIjxHpukUWVBHXTDAJ5kn3HYJa0sq0VbY8U4QlzfgGydKMbYsf9A_IhCBEXLsi2Fo2vGBeKcTx185O1z_AP59SnPt73sRpdhFzf2Rh6flPW9d6bL_fDHB71Fw1vVX3eSeV__7tI?key=Ix1qwLj8iqn6_Q3wepQ5UQ" alt=""><figcaption></figcaption></figure>

### **How to Execute (Claim) Vested goARB**

You can see goARB that you have currently vesting in the "Currently Vesting" section of the goARB page. Each vest shows the amount of goARB being vested, the discount that will be received, and the remaining vesting time.

When the vesting period has completed, you have four weeks to execute your vest. You can do so by clicking the "Execute" button for the completed vest. This will bring up an Execution Summary, showing what will be sent when you execute, including the Vesting NFT for that specific vest and the amount of USDL needed to purchase the vested ARB at the discounted price. The discount is based on the market price at the time of execution. Details of the cost and discount are displayed in the execution summary.

## Security Notice for goARB Contracts

**Understanding the Risks**

While the goARB contracts have been forked from oARB and developed by Dolomite, which boasts an excellent security track record and run a very successful oARB STIPP program, they have not been formally audited for security vulnerabilities. This means that participating in unaudited contracts carries a higher financial risk. Therefore, we strongly advise conducting your own research and considering advice from trusted experts before participating.

**Levra’s Commitment to Security**

1. **Internal Reviews**: Our development team conducts thorough internal code reviews.
2. **Open Source and Community Engagement**: We encourage community reporting of any bugs or vulnerabilities.

## **Why Was the Program Designed This Way?**

This rewards program was designed to distribute ARB while avoiding mercenary ARB farming that harms the Arbitrum ecosystem and ARB market. It rewards users committed to the long-term health of ARB. We believe that Levra’s growth shouldn't come at the expense of ARB. Pairing goARB with USDL during the vesting period and using a discounted ARB model aligns the reward incentives with the long-term health of the ARB market and Arbitrum ecosystem while providing incentives to users who help Levra grow in TVL.

We're excited for you to try out this program and start earning ARB rewards!
