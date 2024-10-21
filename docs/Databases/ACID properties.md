# ACID Properties
1. **Atomicity**: either **the entire transaction takes place at once or doesn’t happen at all**. There is no midway i.e. transactions do not occur partially. Each *transaction is considered as one unit and either runs to completion or is not executed at all.* Two operations of Atomicity are:
	—Abort: If a transaction aborts, changes made to the database are not visible. 
	—Commit: If a transaction commits, changes made are visible. 
	Atomicity is also known as the ‘All or nothing rule’. 

2. **Consistency** : **integrity constraints must be maintained so that the *database is consistent before and after the transaction.** It refers to the correctness of a database.*

3. **Isolation** : This property **ensures that multiple transactions can *occur concurrently without leading to the inconsistency of the database state. Transactions occur independently without interference*. Changes occurring in a particular transaction will not be visible to any other transaction until that particular change in that transaction is written to memory or has been committed.** This property ensures that the **execution of transactions concurrently will result in a state that is equivalent to a state achieved these were executed serially in some order.**

4. **Durability** : This property ensures that once the transaction has completed execution, **the updates and modifications to the database are stored in and written to disk and they persist even if a system failure occurs.** These **updates now become permanent and are stored in non-volatile memory.** The effects of the transaction, thus, are never lost. 