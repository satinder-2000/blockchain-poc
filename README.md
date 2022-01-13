# blockchain-poc

This post has been inspired by the following tutorial

https://www.baeldung.com/java-blockchain

The mining of the Block reside within the Block. These was a considerable improvemnt in mining time as compared to the code in Debajani's book. So let's try again and if this POC works as exected, this little piece of code will lay the foundation of my real Project for BJM.

Here are my results:
Case 1: prefix=4

Running demo.blockchain.BlockchainUnitTest
Jan 13, 2022 4:41:47 PM demo.blockchain.Block mineBlock
INFO: Time taken to mine the Block: 7999 milliseconds
Jan 13, 2022 4:41:47 PM demo.blockchain.Block mineBlock
INFO: The Block was: Block{previousHash=0, data=The is the Genesis Block., timeStamp=1642092099146, nonce=57909}
Jan 13, 2022 4:41:50 PM demo.blockchain.Block mineBlock
INFO: Time taken to mine the Block: 2803 milliseconds
Jan 13, 2022 4:41:50 PM demo.blockchain.Block mineBlock
INFO: The Block was: Block{previousHash=0000b6bf0c9d1bd178a8b871b1b5bc20d9747b2b2f332a44e5eb872fc35e80f1, data=The is the First Block., timeStamp=1642092107346, nonce=57474}
Jan 13, 2022 4:41:50 PM demo.blockchain.Block mineBlock
INFO: Time taken to mine the Block: 267 milliseconds
Jan 13, 2022 4:41:50 PM demo.blockchain.Block mineBlock
INFO: The Block was: Block{previousHash=000095ed1dea29d7408eb4a974d0e140cde9218dbddba87d490fec5f3ad59f9a, data=The is a New Block., timeStamp=1642092110159, nonce=11061}

Case 2: prefix=5
Running demo.blockchain.BlockchainUnitTest
Jan 13, 2022 4:45:07 PM demo.blockchain.Block mineBlock
INFO: Time taken to mine the Block: 16195 milliseconds
Jan 13, 2022 4:45:07 PM demo.blockchain.Block mineBlock
INFO: The Block was: Block{previousHash=0, data=The is the Genesis Block., timeStamp=1642092291318, nonce=388763}
Jan 13, 2022 4:45:19 PM demo.blockchain.Block mineBlock
INFO: Time taken to mine the Block: 12194 milliseconds
Jan 13, 2022 4:45:19 PM demo.blockchain.Block mineBlock
INFO: The Block was: Block{previousHash=00000a300f634ff387846e1b3909392e4ab598af09253a1f5ff92f21ce8ac43f, data=The is the First Block., timeStamp=1642092307788, nonce=383344}
Jan 13, 2022 4:45:37 PM demo.blockchain.Block mineBlock
INFO: Time taken to mine the Block: 17342 milliseconds
Jan 13, 2022 4:45:37 PM demo.blockchain.Block mineBlock
INFO: The Block was: Block{previousHash=000003b574b7834c810454ecdbfaa9919b0fcd64064bb2d97dff71502490b1f8, data=The is a New Block., timeStamp=1642092319993, nonce=545776}
Tests run: 2, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 46.327 sec

