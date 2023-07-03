# Vote Lock

Vote-lock is a mechanism to acquire voting power on Solace. In order to do so, a user needs to get BPT tokens by providing liquidity on Balancer’s SGT80/ETH20 pool and then lock it on Solace for a period of time. A user will receive veSGT tokens, which represent their share of the voting power. Voting power allows users to vote on lending markets, governance proposals and boost up their rewards.

Min. lock period is 1 week and the max. is 1 year. The longer the lock, the more veSGT a user receives. However, the veSGT quantity starts immediately decaying with time. If the user does not extend the lock period, this will decay to 0 after the period is complete, at which point the user can redeem their SGT80/ETH20 BPT.
