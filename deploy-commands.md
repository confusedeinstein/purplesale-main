## [Airdrop](https://mumbai.polygonscan.com/address/0x4b50fc16b517b37c49a863d110f08d587b4644be)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Extras/Airdrop.sol:Airdrop

## [MultiSender](https://mumbai.polygonscan.com/address/0x2672286973353a1a593014e75c307673273d8717)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Extras/MultiSender.sol:MultiSend

## [PrivateSale](https://mumbai.polygonscan.com/address/0xFF95083d4D3d692c7d85dcD33C779b9247DcE23b)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Extras/PrivateSale.sol:PrivateSale

## [TokenLock](https://mumbai.polygonscan.com/address/0x76bAE38A066D14DEdB7A33C5EA328cc49763fB62)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Extras/TokenLock.sol:TokenLock

## [Quickswap](https://mumbai.polygonscan.com/address/0x85FfC6790e379d461fEB9A341F2b7ed800564C3a)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--constructor-args 0x76bAE38A066D14DEdB7A33C5EA328cc49763fB62 \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Extras/Quickswap.sol:QuickswapV2

## [DutchAuctionD](https://mumbai.polygonscan.com/address/0xc951C8Ab079b48666416d427918560196b94DC85)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Degen/DutchAuctionD.sol:AuctionD

## [FairLaunchD](https://mumbai.polygonscan.com/address/0x38def32EE2D5AB0DEf70CbFEFCfF8ab486208E40)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Degen/FairLaunchD.sol:FairLaunchD

## [PreSaleD](https://mumbai.polygonscan.com/address/0x684ffd6c3efcae6d1eada27d2b40cc0e48a5dbf8)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--constructor-args 0x76bAE38A066D14DEdB7A33C5EA328cc49763fB62 \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Degen/PresaleD.sol:PresaleD

## [SubscriptionD](https://mumbai.polygonscan.com/address/0xe5380928687a9D2BbE16d87C118DcB87A250Ca3B)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Degen/SubscriptionD.sol:SubscriptionD

## [AntiBotFactory](https://mumbai.polygonscan.com/address/0x87dC002e6856d2Ae9E82F13AfC077e51aE1531A8)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Tokens/AntiBot/AntiBotFactory.sol:AntiBotFactory

## [AntiBotTokenFactory](https://mumbai.polygonscan.com/address/0x7190Dec0e9148E2C4fFC1803bc8dEC6dD97987fC)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Tokens/AntiBot/AntiBotTokenFactory.sol:AntiBotTokenFactory

## [BabyTokenFactory](https://mumbai.polygonscan.com/address/0x7190Dec0e9148E2C4fFC1803bc8dEC6dD97987fC)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Tokens/BuybackBabyTokenGenerator.sol:BabyTokenFactory

## [StandardTokenFactory](https://mumbai.polygonscan.com/address/0x07c0c1eFdCEd3E8E9Bc631c099e924FD95A32731)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Tokens/StandardTokenFactory.sol:StandardTokenFactory

## [Auction](https://mumbai.polygonscan.com/address/0x25bBa9e4dA55fB7a48913A36A5F7b4F7Fe8b65C3)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/DutchAuction.sol:Auction

## [FairLaunch](https://mumbai.polygonscan.com/address/0x646E28dc77DD4df8A84245446b7d1aEDb991f21f)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/FairLaunch.sol:FairLaunch

## [Presale](https://mumbai.polygonscan.com/address/0x9EFAeF588710c72E8cC5E82AC5b20ddb52de01BA)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--constructor-args 0x76bAE38A066D14DEdB7A33C5EA328cc49763fB62 \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Presale.sol:Presale

## [Subscription](https://mumbai.polygonscan.com/address/0xac3Aa1de737c0Be361501Bb386603ea592d2f160)

forge create --rpc-url https://polygon-mumbai.g.alchemy.com/v2/<ALCHEMY_API_KEY> \
--private-key <YOUR_PRIVATE_KEY> \
--etherscan-api-key <ETHERSCAN_API_KEY> \
--verify \
src/Launchpads/Subscription.sol:Subscription
