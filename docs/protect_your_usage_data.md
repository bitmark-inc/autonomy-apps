**Why does Autonomy collect usage data?**

We collect usage data to improve Autonomy’s user experience and performance. Since we can’t (and definitely don’t want to) look over anyone’s shoulders to see what they’re doing, the usage data provides an anonymous way for you to contribute to making Autonomy better. 

**How does Autonomy protect my privacy while still collecting usage data?**

Autonomy sets a new standard for protecting the privacy of any usage data you contribute. As far as we know, no other app or crypto wallet does as much to conceal your privacy. 
If you opt in to sending us usage data, the mobile app will mask your identity and device uuid by hashing. This number is completely irreversible and is therefore absolutely unrelated to your Autonomy account number, your profile information, or your device in any way.

Here’s an example of such a random number:
```
f0c63b1c38cfb46ddca43c02a0b1b29808f3747bc6c7bc399848de7e602b96b1
```

Anytime you use one of Autonomy’s main features during that day, such as linking with an external wallet account, your mobile app will anonymously send a message to our analytics server that logs the general type of action and any relevant details. 
Here’s an example of a log message for linking to: 

```json
{
  "name":"link_feralfile",
  "user_id":"d593d496d6f3dccb8abb51ac7bf627f985a89595a73e037ecc6c80bd",
  "device_id":"4a8aabd47458f9a0ecbd0f26f838cd4898a915646f85d4f6b1154bb1",
  "timestamp":"1652691627636",
  "platform":"ios",
  "version":"0.27.0",
  "internal_build":false,
  "hashed_data":{
    "address":"b9fa7c430edb2e35769ff08ebfff975f5401bdfd7b576967ec4d6905"
  }
}
```

The only reason for hashing your identities is that it helps us identify when the same person is repeatedly trying to accomplish the same action in a short period of time. This is important because it is usually a flashing alert that we need to fix something. For example, if we notice that you tried to add the same wallet connection repeatedly over the course of a few minutes, it’s a big red flag to us that there’s something that we need to review and fix the wallet linking process.

**What kinds of usage data are contributed?**

Autonomy currently logs usage data for the following actions: 
- Create a wallet account
- Link to another wallet
- User survey
- Usage time

**Will Autonomy ever share this usage data with anyone?**

Absolutely and unconditionally not. We will never sell your data to any third parties. We will never allow any third-party advertisers or data collectors to track any of your behaviors in Autonomy. 
If the Autonomy servers get hacked, could my usage data be compromised? 
Absolutely not. We will never collect any personally identifiable information about you, such as your name, email address, or geographic location. Your Autonomy subscription information is completely controlled by Apple and Google, and we will never have any access to it. Contributing analytics can in no way put you at personal risk. Since you and only you control the keys to your wallet, no one can ever gain control of your wallet by hacking the Autonomy servers. 
