# A Mathematical Model of Financial Bookkeeping

In [this paper](accounting.pdf) we introduce a mathematical model for an entire bookkeeping system.
Building on the work of Ellerman, we define objects representing value, accounts, and transactions,
and introduce a convenient notation for each of the above.
This notation allows you to define transactions locally – without knowing, a priori,
all possible value types, and accounts.
We then use these mathematical objects to formally prove known accounting results.

We also extend transactions to temporal transactions, add a tree structure to the set of accounts,
and create an object representing an entire ledger.
These allow you to express as single objects financial events that are conceptually a single event,
but must be expressed as multiple objects in standard financial bookkeeping
(such as depreciation).
