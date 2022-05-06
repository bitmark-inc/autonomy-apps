**Why does Autonomy collect usage data?**

We collect usage data to improve Autonomy’s user experience and performance. Since we can’t (and definitely don’t want to) look over anyone’s shoulders to see what they’re doing, the usage data provides an anonymous way for you to contribute to making Autonomy better. 

**How does Autonomy protect my privacy while still collecting usage data?**

Autonomy sets a new standard for protecting the privacy of any usage data you contribute. As far as we know, no other app or crypto wallet does as much to conceal your privacy. 
If you opt in to sending us usage data, the mobile app will generate a new random number to mask your identity every day. This number is completely random and is therefore absolutely unrelated to your Autonomy account number, your profile information, or your device in any way. It’s not even related in any way to any previous day’s random number. 

Here’s an example of such a random number:
```
f0c63b1c38cfb46ddca43c02a0b1b29808f3747bc6c7bc399848de7e602b96b1
```

Anytime you use one of Autonomy’s main features during that day, such as sending bitcoin to a contact or adding a contact, your mobile app will anonymously send a message to our analytics server that logs the general type of action and any relevant details, such as the amount of bitcoin in the payment and the time of the interaction. 
Here’s an example of a log message for a bitcoin payment to another Autonomy contact: 

`
Send-payment-info, c71760433833a905f8bbf4dc172c82725a08574462c2bbb3e393d52a1c7c07df,		0.0001,	dd3ce73b536b8c4951d59048e2a4da0578489adab9c14e37a72cce67edad7390,	2021-01-06T4:42:53.2260Z
`

But that’s just the start. All messages in Autonomy are end-to-end encrypted before leaving your mobile device. Additionally, all messages are sent over Tor to further obscure all details about the sender and recipient. Tor is open-source software for enabling anonymous communication by directing Internet traffic through a free, worldwide, volunteer overlay network consisting of more than seven thousand relays in order to conceal a user's location and usage from anyone conducting network surveillance or traffic analysis. This means that anyone attempting to intercept a message from your mobile app not only cannot read the content of the message (due to end-to-end encryption), but they also cannot know who or where it was sent from or to whom or where it is going (thanks to Tor).

At the end of each day, all of the analytics messages from all Autonomy users are stripped of users’ daily random identifiers and aggregated into a big pool for analysis. This means that we don’t even keep users’ random identifiers more than a day. This allows us to get a big-picture view of how the Autonomy system is performing as a whole. It also allows us to discover long-term trends in what features people are using most without needing to know anything about the contributors. 

**Why even bother assigning me a random number each day if the usage data is anonymous?**

The only reason for assigning you a random number each day is that it helps us identify when the same person is repeatedly trying to accomplish the same action in a short period of time. This is important because it is usually a flashing alert that we need to fix something. For example, if we notice that you tried to add the same contact repeatedly over the course of a few minutes, it’s a big red flag to us that there’s something that we need to review and fix the contacts adding process.

**What kinds of usage data are contributed?**

Autonomy currently logs usage data for the following actions: 
- Deposits and withdrawals from/to external Bitcoin addresses
- Payments to and from other Autonomy contacts
- Adding contacts
- Backing up and restoring your account

**Will Autonomy ever share this usage data with anyone?**

Absolutely and unconditionally not. We will never sell your data to any third parties. We will never allow any third-party advertisers or data collectors to track any of your behaviors in Autonomy. 
If the Autonomy servers get hacked, could my usage data or bitcoin be compromised? 
Absolutely not. We will never collect any personally identifiable information about you, such as your name, email address, or geographic location. Your Autonomy subscription information is completely controlled by Apple, and we will never have any access to it. Contributing analytics can in no way put you at personal risk. Since you and only you control the keys to your bitcoin, no one can ever gain control of your bitcoin by hacking the Autonomy servers. 
