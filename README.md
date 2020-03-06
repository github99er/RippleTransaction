# Ripple Transaction Failure

In this example a Ripple team member has been notified of repeated transaction failures from a specific user due to lack of destination tags. How should the Ripple team member reach out to the user?

Below is the simple, detailed, and raw JSON explanation of one of the transactions. 

| [Simple](https://livenet.xrpl.org/transactions/F08770B9B3294EA11028261FE3F6D155F4699669697B7BB0C495A4E7B7EDE5DC/simple) | [Detailed](https://livenet.xrpl.org/transactions/F08770B9B3294EA11028261FE3F6D155F4699669697B7BB0C495A4E7B7EDE5DC/detailed) | [Raw JSON](https://livenet.xrpl.org/transactions/F08770B9B3294EA11028261FE3F6D155F4699669697B7BB0C495A4E7B7EDE5DC/raw)|
| ------ | ------ | ------ |
| ![](paySimp.png) | ![](payDetailed.png)  |![](payRaw.png)  |      


### Example Email Text:

```
Dear User,
Your XRP transaction made on March 02, 2020 at 11:21 PM UTC has not been processed due to lack of a destination tag.

Destination tags are special to certain ledgers such as XRP, and used by exchanges or hosted wallets to indicate 
which customer to credit. Destination tags are an optional feature, however, the address you sent your XRP to 
requires destination tags.

Because the transaction did not fully process your funds have not been received by the target address. In order to 
successfully send your XRP, please enter the destination tag provided by the receiving party into the 
transaction's "tag" field. (see below).


Curious about your transaction? Learn More

Want to know more about destination tags? Learn More

On behalf of the Ripple team, we apologize for the inconvenience and appreciate your patience!
```

### Email Hosted On Webpage:
![](RIPPLEPAGE.png)
