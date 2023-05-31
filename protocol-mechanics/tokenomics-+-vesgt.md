# Tokenomics + veSGT

Solace protocol uses ve-token (vote escrowed) model, similar to veBAL presented by Balancer. This model allows to involve and reward tokenholders in a fair and capital-efficient manner.

SGT is a governance token. Its key role is to incentivize suppliers and borrowers on Solace Lending Market.

### **veSGT**

SGT has two main uses: voting and boosting. Both of these require users to first lock (commonly it’s called “vote-lock”) their BPT (SGT80/ETH20) tokens to receive **veSGT**. Vote escrowed SGT are non-transferable tokens representing BPT (SGT80/ETH20) locked up to 1 year. The longer it is locked for, the more veSGT a user receives. veSGT tokens enable users to vote on Solace’s lending markets and direct SGT emission toward the preferred assets.

#### **Vote Lock**

Vote-lock is a mechanism to acquire voting power on Solace. In order to do so, a user needs to get BPT tokens by providing liquidity on Balancer’s SGT80/ETH20 pool and then lock it on Solace for a period of time. A user will receive veSGT tokens, which represent their share of the voting power. Voting power allows users to vote on lending markets, governance proposals and boost up their rewards.

Min. lock period is 1 week and the max. is 1 year. The longer the lock, the more veSGT a user receives. However, the veSGT quantity starts immediately decaying with time. If the user does not extend the lock period, this will decay to 0 after the period is complete, at which point the user can redeem their 1 BPT of SGT80/ETH20.

#### **Voting**

veSGT allows users to vote on lending markets and protocol improvements.

Voting power scales linearly with the amount of BPT (SGT80/ETH20) locked and with the amount of remaining lock time. The max. multiplier on governance vote weight is 4x

#### **Boosting**&#x20;

One of the main incentives for SGT holders is the ability to boost the supplier’s reward on provided PT-tokens and ETH. Vote locking BPT (SGT80/ETH20) allows you to boost SGT supply rewards up to 2.5x

#### **Earning**

In addition to granted voting and boosting powers, veSGT holders earn lending fees and SGT emission from Balancer’s SGT80/ETH20 pool.

### **Summary**

* Solace protocol uses a ve-token model, much like Balancer's veBAL, to reward its tokenholders fairly and efficiently.
* SGT, the governance token of Solace, incentivizes users in the Lending Market. Its primary functions are voting and boosting.
* To vote or boost, users must lock their BPT (SGT80/ETH20) tokens. Vote-locking involves providing liquidity to the Balancer SGT80/ETH20 pool and locking it in Solace. Users then receive veSGT tokens, granting them voting power in Solace.
* veSGT holders can vote on lending markets and governance proposals and boost their rewards on provided PT-tokens and ETH.
* Finally, veSGT holders earn lending fees and SGT emission from Balancer’s SGT80/ETH20 pool.
