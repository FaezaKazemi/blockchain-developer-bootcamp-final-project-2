Deployed on Fleek

PROBLEM:
Real estate transaction are heavily dependent upon legacy processes that expose the transaction to more risk and reduce expendiancy.
The solution is provide a disintermidiate process where all terms can be fulfilled throught the blockchain.

I had originally considered a real estate defi application(see below), but after further consideration realized that each loan is dependent upon 
both a signed contract and a deed for collateral, or to place a lien upon. This also helps to reduce risk for lenders immensely and I think a perequisite to allowing real estate defi
to undercut prevailing interest rates in conjunction with a fractional lending system.


Design Patterns:

Inheritance(ownable)
Gas optimization through lower uint size and use of calldata over in-memory where appropiate

Security Measures:
Access control design patterns using modifier and require functions
Tx.Origin transaction authentication


FORMER(Project): The aim of this application will be to decentralize real estate financing.
The first step will be to provide credentials/loan request to a financing party to be approved for a specified loan amount.
When financing, a smart contract will be produced with terms of the loan, lender(s) who agree to the terms. If multiple parties, there will be a consensus agreement process.
Further thinking, this can be sent out to multiple parties for approval, and the the loan amount can be syndicated. Buyer will then place an offer to house/apartment with their preapproved offer. Appraiser could pick up job from website and be paid out a bounty amount. Maybe website could hosted on IPFS
Questions to be considered in the long term, how will the system deal with default? How is this monetized? Who are the sellers that would accept this type of financing? What are all the laws to consider along the process? Would appraisers be required by the financies parties/government?
