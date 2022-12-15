# Fedotov Petr k4112c Introduction to distributed technologies

## Question 1

**double spending (Проблема двойной траты, параметры транзакции, пропускная способность сети.)**

The problem of digital money is double spending.

The situation when the same money spent twice.

The way to prevent the problem is centralizing. Examples (eCash)

Mr. I sends with encrypted info money to Bank.

Bank make money arrear in e-wallet add it's encrepted info.

Mr. I decrypts his info and uses them by bying somthing from Mr. II and infor about the info

Mr. II receives the money and sand the info to Bank to make the money apper in his e-wallet.


*The clients (Mr. I and Mr. II) are dependend of Bank. That is bad.*


The decentrizied system like *blockchain* are more reliable.

After the transation is proofed the conins couln't be spent twice.


**Double spending in BTC**

Race attack:

- Send coins.

- Don't wait until proof.

- Send it back with higher fee.

51% attack

- 51% of compromised nodes proof the false info.

Finni attack:

- First block start to be processing but not translated to the network.

- Double spending.

- Translation of the first block to the network.

Bandwidth

It is how many transactions per second (TPS)

BTC about 5 TPS

## Question 2

**Staking (Механизм стейкинга токенов в различных сетях.)**

Less resource hugry alternative to mining.

Is a proccess of storing the cryptocurrency on e-wallet for security and activity of the network.

The member of network blocks the portion of coins and after the algorith chooses the one of these members to validate the block.  
The higher count of staked coins as higher the probability of choosing the memember.

This is why the speed is higher.

Etherieum reuires 32 ETH to become a validator.

Ddelegated stake

this is DPoS algorithm (d-like democracy)

|PoS|PoW|
|---|---|
|validators|miners|
|have tokens|have equipment|
|energy efficient|not energy efficient|
|Security through community control|Robust security due to expensive upfront requirement|
|Validators receive transactions fees as rewards|Miners receive block rewards|
