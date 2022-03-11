# What are text records and how do they work?

## Text Records

Text records allow you to attach and store publicly available and arbitrary text data to your Ethereum Name. Your text records are essentially user-controlled, human-readable metadata for applications to reference and use. Because your text records are created by you and stored on the Ethereum blockchain, they enable a self-sovereign and decentralized user profile. This means that your information and profile can begin to escape the centralized architecture of Web2.

With the [ENS Metadata Service](https://metadata.ens.domains/docs) these text records are not confined to the Ethereum Blockchain and can be referenced by DNS.

For technical data on the EIP that makes this possible, see: [EIP-634](https://eips.ethereum.org/EIPS/eip-634).

### How can I add a text record?

In the [ENS App](https://app.ens.domains), you can add a record by clicking the ‘+’ button in the ‘records’ tab:

![](<../../../.gitbook/assets/image (2).png>)

You should see some drop down boxes appear that will allow you to choose to add a “TEXT” record, the kind of text record (e.g. “URL”), and then enter the information for that record:

![](<../../../.gitbook/assets/image (1).png>)

Once you’re ready, click "Confirm" to send the transaction, and once it’s mined you should see it appear below.

{% hint style="info" %}
**Note:** Text records, like all ENS records, are publicly visible.
{% endhint %}

### Type of Text Fields.

Although users can easily define new text records, there are several keys established on the ENS Domain Manager.

#### Common Global Keys

Global Keys should only consist of lowercase letters, numbers, and hyphens.

* **Avatar** - An all lowercase URL to an image used as an avatar or logo. All lowercase.
* **Description** - A description of the name.
* **Display -** A canonical display name for the ENS name.
* **E-mail -** An e-mail address
* **Keywords -** A list of comma-separated keywords, ordered by most significant first.
* **URL -** A website URL

#### Other Service Keys

Service Keys must be made up of a reverse dot notation (see below examples), and contain at least one dot. A user can create their own service key adhering to this format.

* **com.github** - A Github username.
* **com.twitter** - A Twitter username.
* **io.keybase -** A Keybase Username.
* **org.telegram -** A Telegram Username.

{% hint style="info" %}
**Note:** Usernames should **NOT** include the "@" symbol or contain the full URL to the user profile.
{% endhint %}

\
