# Background

Blockchain assets are inherently diversified. For example, stable coins can be divided into three categories:

* USD-backed stable coins, e.g. USDC, USDT
* Crypto-backed stable coins, e.g. DAI
* Unbacked stable coins, e.g. AMPL, FRAX

Each stable coin also differs in term of architecture and operation. Things are similar to BTC assets such as WBTC, renBTC, tBTC and etc.

The success of DeFi promotes the proliferation of blockchain assets but also introduces the problem of liquidity fragmentation. This problem applies to ERC20 BTC service providers, application developers and users.

* ERC20 BTC service providers need to compete for application usage and bootstrap liquidity for each ERC20 BTC. Most benefits are taken away by short-term traders and arbitragers;
* Application developers need to support each individual ERC20 BTC. This requires extensive work to research, develop and monitor;
* Users need to hold multiple ERC20 BTC and find yield opportunities for each of them. This is highly user-unfriendly to mass market users.

Stable asset protocol aims at solving these problems:

* By introducing a synthetic asset backed by assets with the same peg, stable asset aggregates liquidity from these assets so that application developers and users can work with a single asset;
* By leveraging arbitragers to adjust basket proportion, stable asset can provide a much stronger peg than any of the underlying asset, which ease the adoption to application developers and users;
* By creating a synthetic asset on top of a swap, stable asset provides a swap application for the underlying assets as well as further usage when the stable asset is adopted by other applications.
