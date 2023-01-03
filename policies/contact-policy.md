# GPU-Killers Contact Policy

***This document describes the contact policy of GPU-Killers. It is important to read this document carefully, as it contains important information about the way we communicate with you.***

## 1. Introduction
We, GPU Killers, are a privately owned company that provides open sourced software and services. Given this fact, all emails sent to and from you are considered to be private and confidential. We will not share your email address with any third party without your consent. We will not send you any unsolicited emails, and we will not send you any emails that you have not explicitly agreed to receive. We will not send you any emails that are not related to the services we provide. We will never ask for any confidential details **EVER**.All emails sent by a representative should also include a PGP signature made using the sender's key. All public keys are available in the [keys](../keys) directory. An example of a signed message will look like [this][signMsgEx] with the detached sig looking like [this][signMsgSig]. To confirm the signature, download the sender's key, the developer's key, the admin's key, the message itself, and the provided `sig.asc` file. Then, run the following command: `gpg --verify sig.asc message.txt`. If its valid, this should be the output:
```sh
gpg: Signature made mm/dd/yyyy hh:mm:ss AM/PM <Timezone>
gpg:                using RSA key <Key ID>
gpg:                issuer "<Email Address>"
gpg: Good signature from "<Issuer Name> <Email>" [ unknown ]
```

## 2. Contacting Us
If you receive any emails from us that you believe are not related to the services we provide or to be suspicious, please contact us immediately at [our support email][support]. We will investigate the matter and take the appropriate action.

[support]: mailto:support@sparty18.me?subject=Support%20Request
[admin]: mailto:admin@sparty18.me?subject=Admin%20Request
[signMsgEx]: ../examples/message.txt
[signMsgSig]: ../examples/sig.asc