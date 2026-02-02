# VASP Detailed Service Audit Criteria

## Trading & Derivatives

### Spot Trading
**Description:** Direct buying/selling at market price.
**Keywords:** spot trading, spot trade, spot market, buy sell crypto, trade crypto, exchange, markets
**URL Patterns:** /trade, /trading, /spot, /buy-sell, /exchange, /advanced-trade/spot, /markets
**Nav Patterns:** trade, trading, spot, buy, sell, exchange, markets

### Margin Trading
**Description:** Trading with borrowed funds.
**Keywords:** margin trading, margin trade, leverage trading, borrowed funds, cross margin, isolated margin, perpetual contract, perpetual contracts, perpetual trading
**URL Patterns:** /margin, /leverage, /margin-trading, /spot?type=cross, /spot?type=isolated, type=cross, type=isolated, type=margin, ?type=margin, tradeKind=margin, /perpetual-contract, /perpetual-contracts, /perpetual-trading, /leverage-landing-page, /spot/act/leverage
**Nav Patterns:** margin, leverage, margin trading, cross margin, isolated margin, perpetual contract, perpetual trading
**Exclusions:** Avoid futures-specific pages

### Futures
**Description:** Contracts to buy/sell at a future date.
**Keywords:** futures, futures trading, derivatives, perpetual, perpetuals, contract trading, perpetual contract, contract, perpetual contracts
**URL Patterns:** /futures, /futures_trading, /derivatives, /perpetual, /perpetuals, /advanced-trade/perpetuals, /contract, /contracts, /new/contract, /perpetual-contract
**Nav Patterns:** futures, derivatives, perpetual, perpetuals, contract, contract trading, perpetual contract

### Options
**Description:** Contracts giving the right (not obligation) to buy/sell.
**Keywords:** options trading, call option, put option, strike price, expiration date, options chain, derivatives trading
**URL Patterns:** /options, /option, /derivatives, /about/options, /about/option, /en/about/options, /us/en/about/options
**Nav Patterns:** options, option, derivatives
**Exclusions:** account options, payment options, security options, display options, language options, privacy options, settings options, card options, crypto card, debit card, payment card, card features, card settings
**Exclude URLs:** /card, /crypto-card, /debit-card, /payment-card, /gift-card, /deposit, /withdraw, /payment, /tag/, /blog/, /article/, /news/
**Note:** Require trading context (not settings/preferences pages)

### Leveraged Tokens
**Description:** Assets like "BTCDOWN" or "1000PEPE."
**Keywords:** leveraged tokens, leverage tokens, bull token, bear token, 3L, 3S, ETF, leveraged ETF, leveraged etf
**URL Patterns:** /leveraged-tokens, /tokens, /etf
**Nav Patterns:** leveraged tokens, tokens, etf
**Exclusions:** futures, margin trading, perpetual, liquidation, custom leverage, borrowing, articles, support
**Exclude URLs:** /blog/, /article/, /news/, /support/, /hc/

### OTC Desk
**Description:** High-volume "Block Trades."
**Keywords:** otc desk, over the counter desk, institutional trading, otc trading desk, professional otc, otc services, fiat otc, pre-market trading, pre market trading, exclusive otc, wealth management otc
**URL Patterns:** /otc, /institutional/otc, /fiat/otc, /fiat, /pre-market, /premarket, /wealth, /institutional
**Nav Patterns:** otc, institutional, fiat otc, pre-market, premarket, pre market, wealth otc, exclusive otc
**Exclusions:** otc markets, otc data, otc information, general otc, otc news, wealth planning, investment advice, financial planning, portfolio management, general wealth
**Priority URLs:** /otc, /institutional/otc, /fiat/otc

## Automation Tools

### Trading Bots
**Description:** General automated trading.
**Keywords:** trading bots, automated trading, algo trading, bot trading, swap bot, swapbot
**URL Patterns:** /bots, /automated, /algo, /tradingbot, /trading-bot, /bot, /swap-bot, /swapbot
**Nav Patterns:** bots, automated, algo, tradingbot, trading bot, swap bot, swapbot
**Search Patterns:** trading bot, trading bots, automated trading, algo trading, bot trading, swap bot, telegram bot, t.me/, pancakefi_bot, swap on the, bot interface

### Copy Trading
**Description:** Mimicking other traders.
**Keywords:** copy trading, social trading, follow traders, mirror trading, copy trades, trader leaderboard, top traders, portfolio copying
**URL Patterns:** /copy, /social, /follow, /copy-trading, /social-trading, /mirror-trading
**Nav Patterns:** copy, social, follow, copy trading, social trading, mirror trading
**Exclusions:** charity, donation, donate, fundraising, charitable, giving, social cause, charity wallet, charity-wb, social impact, social responsibility
**Exclude URLs:** /charity, /donate, /donation, /fundraising, /charitable, /giving, /charity-wb, /social-cause, /impact
**Note:** Require trading context

### Grid Trading
**Description:** Specific buy/sell grid strategy.
**Keywords:** grid trading, grid bot, grid strategy, futures grid, spot grid, automated grid, grid algorithm, strategic trading, strategy
**URL Patterns:** /grid, /grid-trading, /trading-bot/spot, /trading-bot/futures, /futures/trading-bots/grid, /trading-bots/grid, /exchange/grid, /exchange/strategy
**Nav Patterns:** grid, grid trading, futures grid, spot grid, strategic trading, strategy

### Auto-Investing (DCA)
**Description:** Recurring buys.
**Keywords:** auto invest, dca, dollar cost averaging, recurring buy, auto-investing, auto-invest plan, strategies, grow crypto assets, effortlessly, 暗号資産積立, 自動積立, つみたて, 積立, accumulated, reserves, crypto asset accumulation, automatic accumulation, tsumitate
**URL Patterns:** /auto-invest, /dca, /recurring, /strategy, /strategies, /reserves_lp, /tsumitate, /積立, /つみたて, /accumulated
**Nav Patterns:** auto invest, dca, recurring, strategy, auto-invest plan, つみたて, 積立, tsumitate, accumulated, reserves
**Exclusions:** terms of use, terms and conditions, privacy policy, legal disclaimer, user agreement, service agreement, terms of service, cookie policy, compliance policy, aml policy, kyc policy, risk disclosure, legal notice, disclaimer, prohibited use, acceptable use

### P2P Platform
**Description:** Peer-to-peer trading.
**Keywords:** p2p, peer to peer, p2p trading, peer-to-peer, otc, fiat, buy crypto, sell crypto
**URL Patterns:** /p2p, /peer-to-peer, /otc
**Nav Patterns:** p2p, peer to peer, otc, fiat
**Exclusions:** otc desk, institutional, block trade, large orders, pre-market, announcements

## Yield & Finance

### Crypto Staking
**Description:** On-chain PoS locking.
**Keywords:** staking, stake, staking rewards, proof of stake, validator, delegation, pos staking, ethereum staking, cake staking, earn
**URL Patterns:** /staking, /stake, /validator, /delegation, /pos, /cake-staking, /earn
**Nav Patterns:** staking, stake, validator, delegation, earn
**Exclusions:** yield farming, liquidity farming, farm pools, lp farming, learn and earn, learn to earn, educational rewards, education earn, learn earn

### Saving Accounts
**Description:** Interest on idle assets.
**Keywords:** savings, saving account, flexible savings, fixed savings, powerpiggy, power piggy, earn, earn+, interest, flexible yield
**URL Patterns:** /savings, /save, /saving, /powerpiggy, /earn, /pro/earn, /earn+
**Nav Patterns:** savings, save, saving, powerpiggy, power piggy, earn, earn+, interest
**Exclusions:** save the date, save-the-date, ethereum developers, testnet timeline

### Crypto Loans
**Description:** Borrowing against collateral.
**Keywords:** crypto loans, lending, borrow, loan, finance, loans
**URL Patterns:** /loan, /lending, /borrow, /finance, /loans
**Nav Patterns:** loan, lending, borrow, finance, loans
**Exclusions:** p2p, peer-to-peer, margin trading, futures, perpetual, savings, deposit, staking

### Flash Loans
**Description:** Instant uncollateralized loans.
**Keywords:** flash loans, flash lending, instant loan
**URL Patterns:** /flash-loan, /flash
**Nav Patterns:** flash loan, flash

### Unsecured Loans
**Description:** Loans without collateral.
**Keywords:** unsecured loans, unsecured lending, no collateral
**URL Patterns:** /unsecured, /no-collateral
**Nav Patterns:** unsecured, no collateral

### Cloud Mining
**Description:** Renting hardware power.
**Keywords:** cloud mining, mining contract, hash rate, mining pool, bitcoin mining, crypto mining
**URL Patterns:** /mining, /cloud-mining, /mining-pool
**Nav Patterns:** mining, cloud mining, mining pool, bitcoin mining
**Exclude URLs:** /tag/, /blog/, /article/, /news/

### Yield Farming
**Description:** Automated DeFi returns.
**Keywords:** yield farming, liquidity farming, farm pools, lp farming, farming rewards, yield generation, stake lp tokens, farms, liquidity pools earn
**URL Patterns:** /farms, /yield-farming, /farming, /farm, /yield
**Nav Patterns:** farms, yield farming, farming, farm
**Exclusions:** cake staking redeem, unstake, staking rewards only
**Priority URLs:** /farms

### Liquidity Pools
**Description:** Token reserves.
**Keywords:** liquidity pools, liquidity pool, liquidity provider, amm, automated market maker
**URL Patterns:** /pool, /liquidity, /amm, /liquidity-pool
**Nav Patterns:** liquidity pool, liquidity, amm, liquidity provider
**Exclude URLs:** /tag/, /blog/, /article/, /news/

## Launch & Distribution

### Launchpad
**Description:** Purchasing new tokens before listing.
**Keywords:** launchpad, ido, initial offering, token launch, ifo, initial farm offering
**URL Patterns:** /launchpad, /ido, /launch, /ifo
**Nav Patterns:** launchpad, ido, launch, ifo
**Priority URLs:** /ifo
**Exclude URLs:** /blog/, /article/, /news/, /support/

### Launchpool
**Description:** Staking assets to earn new tokens for free.
**Keywords:** launchpool, launch pool, token farming
**URL Patterns:** /launchpool, /launch-pool
**Nav Patterns:** launchpool, launch pool

### Airdrops
**Description:** Free token distribution events.
**Keywords:** airdrops, airdrop, free tokens, token distribution, campaigns, bot-airdrop, token drops
**URL Patterns:** /airdrop, /airdrops, /free, /campaigns
**Nav Patterns:** airdrop, airdrops, free, campaigns
**Exclusions:** marketing campaign, promotional campaign, trading campaign, general campaign, campaign without airdrop, campaign without drop, campaign without tokens

## NFT & Digital Assets

### NFT Marketplace
**Description:** Minting/trading NFTs.
**Keywords:** nft, nft marketplace, non-fungible, collectibles, vinci, bluevinci
**URL Patterns:** /nft, /marketplace, /collectibles, /footerPage, /blueVinci
**Nav Patterns:** nft, marketplace, collectibles, vinci, bluevinci
**Exclude URLs:** /blog/, /article/, /news/, /support/, /topic/, /hc/

### NFT Loans
**Description:** Using NFTs as collateral.
**Keywords:** nft loans, nft lending, nft collateral
**URL Patterns:** /nft-loan, /nft-lending
**Nav Patterns:** nft loan, nft lending
**Exclude URLs:** /trade/nft_loans, /blog/, /article/, /news/, /support/

### NFT Staking
**Description:** Locking NFTs for rewards.
**Keywords:** nft staking, nft stake, nft rewards
**URL Patterns:** /nft-staking, /nft-stake
**Nav Patterns:** nft staking, nft stake
**Exclude URLs:** /trade/nft_staking, /blog/, /article/, /news/, /support/

## Cards & Payments

### Gift Card / Red Envelope
**Description:** Crypto vouchers.
**Keywords:** gift card, gift cards, voucher, prepaid card
**URL Patterns:** /gift-card, /voucher, /prepaid
**Nav Patterns:** gift card, voucher, prepaid

### Crypto Debit/Credit Cards
**Description:** Physical/Virtual cards.
**Keywords:** crypto card, debit card, visa card, mastercard, payment card, card services, credit card, gold card
**URL Patterns:** /card, /crypto-card, /debit, /visa, /mastercard, /payment-card, /creditcard, /credit-card
**Nav Patterns:** card, crypto card, debit, visa, payment card, credit card
**Exclusions:** deposit, checkout, payment flow, transaction, buy crypto, sell crypto
**Exclude URLs:** /deposit, /checkout, /payment?, /buy, /sell, /transaction
**Priority URLs:** /crypto-card, /creditcard, /card
**Note:** Require dedicated service page (not just payment option)

### Custody Services
**Description:** Institutional storage.
**Keywords:** custody, custodial, asset custody, secure storage, self-custody
**URL Patterns:** /custody, /custodial, /storage, /institution/custody, /institutional/custody, /en/institutional/solutions/digital-assets/custody, /solutions/digital-assets/custody
**Nav Patterns:** custody, custodial, storage

## Ecosystem & Support

### dApp Connectivity
**Description:** Web3 wallet support.
**Keywords:** dapp, web3, defi, decentralized app, wallet connect, dapp browser, blockchain apps, connect wallet
**URL Patterns:** /dapp, /web3, /defi, /connect, /wallet-connect, /dapp-browser, /blockchain-apps
**Nav Patterns:** dapp, web3, defi, connect, wallet connect, dapp browser, blockchain apps
**Exclusions:** homepage, landing page, main page, home, index, general, marketing
**Exclude URLs:** /, /index, /home, /main, /en, /en/
**Note:** Require web3 context (not just homepage mentions)

### Referral/Affiliate Programs
**Description:** Rewards for invites.
**Keywords:** referral, refer friend, referral program, invite, affiliate program, affiliate
**URL Patterns:** /referral, /refer, /invite, /affiliate, /affiliates
**Nav Patterns:** referral, refer, invite, affiliate
**Subdomain Patterns:** affiliates.

### Educational Services
**Description:** Guides/Articles.
**Keywords:** education, learn, academy, tutorial, blog, news, insights, knowledge, course, information
**URL Patterns:** /education, /learn, /academy, /tutorial, /blog, /news, /insights, /knowledge, /course, /information, /category/information
**Nav Patterns:** education, learn, academy, tutorial, blog, news, insights, information
**Note:** Blog/news sections count as educational services

### Learn and Earn
**Description:** Crypto rewards for courses.
**Keywords:** learn and earn, learn to earn, educational rewards, learn crypto, cashback vouchers, free crypto, crypto rewards, quiz rewards, campaigns, sand-learn-and-earn, put your crypto knowledge to the test, showcase your knowledge by taking a quiz
**URL Patterns:** /learn-earn, /learn-and-earn, /learn-crypto, /campaigns, /rewards, /support/articles/rewards
**Nav Patterns:** learn and earn, learn to earn, learn crypto, learn-crypto, campaigns, rewards
**Exclusions:** academy, pure education, blog, news, general learning, marketing campaign, promotional campaign, trading campaign, general campaign, campaign without learn, campaign without earn
**Note:** Requires actual reward mechanism, not just educational content

### Tax Assistance
**Description:** Tax reporting tools.
**Keywords:** tax, tax report, tax assistance, tax calculation, campaigns, tax-tools, featured-tax-tools, tax tools
**URL Patterns:** /tax, /tax-report, /taxes, /campaigns
**Nav Patterns:** tax, taxes, tax report, campaigns
**Exclusions:** marketing campaign, promotional campaign, trading campaign, general campaign, campaign without tax, campaign without tools, campaign without assistance

## Speculative Markets

### Gambling
**Description:** Betting on games.
**Keywords:** gambling, casino, betting, gamblefi, gaming
**URL Patterns:** /gambling, /casino, /betting, /gaming
**Nav Patterns:** gambling, casino, betting, gaming

### Prediction Markets
**Description:** Betting on events.
**Keywords:** prediction, prediction markets, forecast, predict
**URL Patterns:** /prediction, /predictions, /forecast
**Nav Patterns:** prediction, predictions, forecast
