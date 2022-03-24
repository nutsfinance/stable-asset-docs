# Existing Works

Synthetic token is a common practice on Ethereum to hedge against risks over any single asset.  Examples include USDx/USD++/mUSD for stable coins and BTC++ for ERC20 BTCs.

## USDx

USDx from dForce is a synthetic indexed stable coin pegged into a basket of constituents at predetermined weighting, which is adjustable through on-chain governance. The fixed weighting makes USDx susceptible to the price fluctuations of the underlying assets, and those assets stay idle in the basket without generating values. Therefore, newer synthetic assets seek innovative approaches to better manage their basket.

## USD++

USD++ from PieDAO attempts to balance its basket using Balancer. It places its underlying  assets into a managed Balancer pool so that the traders can help to maintain the relative stability between assets. Therefore, these assets are generating values by serving as a swap instead of staying idle in the basket. However, Balancer/Uniswap generates enormous slippage for assets with similar prices, which is exactly the case for the underlying assets in a basket. Moreover, earning protocol fees from the swap effectively turning USD++ into a yield token which will gradually lose its peg with USD.

## mUSD

mStable, on the other hand, constrains each underlying asset with a maximum weight. Any basket operation, including minting, redeeming and swapping, cannot force any asset to exceed its maximum weight. This effectively makes “bad money drives out good”. For example, mUSD contains four underlying assets: USDT, USDC, DAI and TUSD, and their maximum weights are all 55%. In most of the time, the mUSD basket contains 55% USDT and 45% USDC or TUSD, depending on which token is less expensive. There is never DAI left in the basket, and users have no incentive to mint additional mUSD with DAI.

In short, we need a better approach to manage the asset basket and make the synthetic token reliable to short term price fluctuations.
