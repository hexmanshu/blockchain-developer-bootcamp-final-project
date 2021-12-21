# Rebasooor

This dapp will allow users to deposit stablecoins like USDC and DAI on Polygon in order to earn interest in the form of staked rebase tokens like sKLIMA or wsOHM on Polygon side chain. Overall flow:
* User deposits supported stablecoins in the vault.
* Vault deposists stablecoin in Polygon aave. 
* Vault harvests WMATIC rewards from Aave and swaps for sKLIMA / gOHM via Sushi Swap.
* User can claim the rewards.
* User can claim their stablecoin deposit.
