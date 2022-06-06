**How The Project’s Backend Works** (In Dev)

C.Pay will connect to both LocalCoinSwap and LocalMonero for crypto storage. When a user deposits or withdraws crypto from C.Pay, the bot will receive/send the assets using LCS or LM wallets. There are a few reasons why the bot will store and send crypto using LCS and LM.
 	1. Unlike a traditional crypto exchange, the project will own the keys and not the exchange. 
	2. The C.Pay project wants to support exchanges with no KYC.
	3. Few cold storage wallets would be compatible with the bot.
