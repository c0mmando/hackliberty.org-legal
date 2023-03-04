Please read this document carefully before accessing or using this service!

## 1. Introduction

### 1.1 English, Not Legalese

Most Privacy Policy documents are unreadable. They are written by lawyers and for lawyers, and in our opinion are not very effective.
Data protection and privacy are important, and we want you to understand the issues involved. For that reason we decided to use plain English instead as much as possible, to make our terms as clear as possible.

When you read 'the Matrix.org homeserver' or 'the Service' below, it refers to the services made available at https://hackliberty.org which store your account and personal conversation history, provide services such as bots and bridges, and communicate via the open Matrix decentralised communication protocol with the public Matrix Network.

The public Matrix Network is a decentralised and openly federated communication network. This means that user messages are replicated on each participant's server and messages posted to a room are visible to all participants including in some cases any new joiners. This is further explained at 2.3.

Where you read Hackliberty.org or Hack Liberty, it refers to hackliberty.org and the organization's agents. 

The Matrix protocol is licensed by the Matrix Foundation which makes it available to third parties who set up their own homeserver. This privacy policy does not apply to such Matrix servers run by anyone else - Matrix is an open network like the Web and this agreement only applies to the server (hackliberty.org) provided by Hack Liberty.

hackliberty.org is the Data Controller for the Service. We can be contacted as per the details below:

Email: [contact@hackliberty.org](mailto:contact@hackliberty.org)

Should you have other questions or concerns about this document, please send us an email at [contact@hackliberty](mailto:contact@hackliberty.org).

### 1.2 This Is a Living Document

This is a living document. With your help, we want to make it the best in the industry.

If you read something that rubs you the wrong way, or if you think of something that should be added, please get in touch! We're all ears! Email contact@hackliberty.org and we'll chat.

We don't amend this document for any specific users or use case, but if your proposed changes apply to all of our users, we'll be happy to update it for everyone. Scroll to the bottom to see the history so far.

We will likely improve this document over time and we will take steps to inform our users about any updates. By continuing to use the Service, you will implicitly accept the changes we make. If updates to this document are ever associated with significant changes to the way we collect our process your data, we will promptly notify you.

Your access and use of the Service is always subject to the most current version of this document.

## 2. Access to Your Data / Privacy Policy

### 2.1 What is the legal basis for processing my data and how does this affect my rights under GDPR (General Data Protection Regulation)?

#### 2.1.1 Legal Basis for Processing

hackliberty.org processes your data under a Legitimate Interest basis of processing, to provide our Service to you in an efficient and secure manner and to ensure the legal compliance and proper administration of our business. Essentially, this means that we process your data only as necessary to deliver the Service and for internal administration purposes, and in a manner that you understand and expect. We also carry out processing that is necessary to provide our Service to you under our hackliberty.org Homeserver [Terms and Conditions](https://git.hackliberty.org/hackliberty.org/hackliberty.org-legal/src/branch/main/terms-of-service.md) and processing that is necessary to comply with our legal obligations. Where consent is required by law in relation to certain processing, we will ask for your consent.

We process your information for the purposes of providing our decentralised, openly-federated and end-to-end encrypted communication Service, getting in touch with you, responding to your requests, working with our suppliers to deliver the Service and enabling its features, ensuring the security of our Service, developing, fixing and improving our Service, administering our business and complying with the law.

The nature of the Service and its implementation results in some caveats concerning this processing, particularly in terms of GDPR Article 17 Right to Erasure (Right to be Forgotten). We believe these caveats (discussed in the section below in detail) are in line with the broader societal interests served by providing the Service.
In situations where the interests of the individual appear to be in conflict with the broader societal interests, we will seek to reconcile those differences guided by our policy.

#### 2.1.2 Your Rights as Data Subject

You have rights in relation to the personal data we hold about you. Some of these only apply in certain circumstances. Some of these rights are explored in more detail elsewhere in this document. For completeness, your rights under GDPR are:

1. The right to be informed
1. The right of access
1. The right to rectification
1. The right to erasure
1. The right to restrict processing
1. The right to data portability
1. The right to object
1. Rights in relation to automated decision making and profiling.

For more details about these rights, please see the guidance provided by the ICO. If you have any questions or are unsure how to exercise your rights, please contact us at [contact@hackliberty.org](mailto:contact@hackliberty.org).

#### 2.1.3 Right to Erasure
You can request that we forget your copy of messages and files by instructing us to deactivate your account (using a Matrix client such as the Element chat app) and selecting the option instructing us to forget your messages. What happens next depends on who else had access to the messages and files you had shared.

Any messages or files that were only accessible by your account will be deleted from our servers within 30 days.

Where you shared messages or files with another registered Matrix user, that user will still have access to their copy of those messages or files. Apart from state events (see 2.1.3.1 below), these messages and files will not be shared with any unregistered or new users who view the room after we have processed your request to be forgotten.

State events are processed differently to non-state events. State events are used by the Service to record, amongst other things, your membership in a room, the configuration of room settings, your changing of another user's power level and your banning a user from a room. Were we to erase these state events from a room entirely, it would be very damaging to other users' experience of the room, causing banned users to become unbanned, revoking legitimate administrator privileges, etc. We therefore share state events sent by your account with all non-essential data removed ('redacted'), even after we have processed your request to be forgotten. This means that your username will continue to be publicly associated with rooms in which you have participated, even after we have processed your request to be forgotten. We are actively working on a solution to work around this restriction and allow you to be fully forgotten while maintaining a high quality experience for other users. If this is not acceptable to you, please do not use the Service.

#### 2.1.3.1 Exceptional Erasure

As described above, erasing a state event may result in our needing to erase the entire conversation at the same time. Deciding whether to take this drastic step will require a balancing exercise to be carried out at the time of the request, and will depend on:

1. the nature of the Personal Data that the user is requesting to be erased;
1. how many other users would have their fundamental rights and freedoms put at risk if the Right to Erasure were to be exercised
1. to what degree these other users would have their fundamental rights and freedoms put at risk if the Right to Erasure were to be exercised

The Personal Data contained in a state event is usually limited to the username, the timestamp and the conversation in which the state event was issued. State events only represent that a user participated in a given conversation at a given time. It is rare that this data is sensitive enough to warrant its erasure given the drastic impact this will have on other users.

Each case will be decided based on the factors listed above. In most situations we will not erase state events. In extreme situations, where not erasing state events will place people at material risk of harm, we may choose to erase state events or remove the entire conversation.

#### 2.1.3 Data Portability

Under GDPR you have a right to request a copy of your data in a commonly-accepted format. If you would like a copy of your data, please send a request over Matrix to contact@hackliberty.org. In the future we will provide a better interface for this!

#### 2.2 What Information Do You Collect About Me and Why?

The information we collect is purely for the purpose of providing your communication service via Matrix. We do **not** profile users or their data on the Service.

Be aware that while we do not profile users on the Service, third party Matrix clients may gather usage data. 

#### 2.2.1 Information you provide to us:

We collect information about you when you input it into the Service or otherwise provide it directly to us.

#### 2.2.1.1 Account and Profile Information

We collect information about you when you register for an account. This information is kept to a minimum on purpose, and is restricted to:
* Username
* Password
* Display Name (if you choose to provide one)
* Your username and password is used to authenticate your access to the Service and to uniquely identify you within the Service.
* Your password is stored until you change it or your account is deactivated (see 2.5 for details on how passwords are handled securely). Your username is stored indefinitely to avoid account recycling.

#### 2.2.1.2 Content you provide through using the Service

We store and distribute the messages and files you share using the Service (and across the wider Matrix ecosystem via federation) as described by the Matrix protocol and according to the access rules configured within the system. Storing and sharing this content is the reason the Service exists.

This content includes any information about yourself that you choose to share.

#### 2.2.2 Information we collect automatically as you use the Service:

**Device and Connection Information**

Each device you use to access the Service is allocated a (user-configurable) identifier. When you access the Service, we record the device identifier, the **anonymized** IP address it used to connect, and the time at which it last connected to the service.

This information is gathered to help you to manage your devices - you can view and manage the list of devices by connecting to the Service with a Matrix client such as the Element app.

### 2.3 What Information is Shared With Third Parties and Why?

#### 2.3.1 Sharing Data with Connected Services

The hackliberty.org homeserver is a decentralised and open service. This means that, to support communication between users on different homeservers or different messaging platforms, your username, display name and messages and files are sometimes shared with other services that are connected with the Matrix.org homeserver.

##### 2.3.1.1 Federation

Matrix homeservers share user data with the wider ecosystem over federation.

When you send messages or files in a room, a copy of the data is sent to all participants in the room, including (depending on room settings) participants who join the room in future. If these participants are on remote homeservers, your username, display name, messages and files may be replicated across each participating homeserver.

We will forget your copy of your data upon your request. We will also forward your request to be forgotten onto federated homeservers. However - these homeservers are outside our span of control, so we cannot guarantee they will forget your data.

Federated homeservers can be located anywhere in the world, and are subject to local laws and regulations.

Access control settings are shared between homeservers, as well as any requests to remove messages by "redactions", or remove personal data under GDPR Article 17 Right to Erasure (Right to be Forgotten). Federated homeservers and Matrix clients which respect the Matrix protocol are expected to honour these controls and redaction/erasure requests, but other federated homeservers are outside of the span of control of Hack Liberty, and we cannot guarantee how this data will be processed. Federated homeservers can also be located in any territory, and will be subject to the local regulations of that territory.

##### 2.3.1.2 Bridging

Some Matrix rooms are bridged to third-party services, such as IRC networks, Twitter, Discord, XMPP, or Telegram. When a room has been bridged, your username, display name, messages and file transfers may be duplicated on the bridged service where supported.

It may not be technically possible to support your management of your data once it has been copied onto a bridged service.

Bridged services can be located anywhere in the world, and are subject to local laws and regulations.

Access control settings, requests to remove messages by "redactions" or remove personal data under GDPR Article 17 Right to Erasure (Right to be Forgotten) are shared to bridging services, which are expected to honour them to the best of their ability. Be aware that not all bridged networks or bridges support the necessary technical capabilities to limit, remove or erase messages. If this is not acceptable to you, please do not use bridged rooms.

###### 2.3.1.3 Integration Services (Bots and Widgets)

The hackliberty.org homeserver provides a range of integrations in the form of Widgets (miniature web applications accessed as part of a Matrix Client) and Bots (automated participants in rooms).

Bots and Widgets currently have access to all the messages and files in any room in which they participate.

### 2.4 Transfers of your Data

If you use our Service your data will be transferred outside of the EU to other homeservers and services connected with hackliberty.org as this is necessary to provide the Service to you. By the very nature of our Service, such transfers will occur regularly and we have no control over the safeguards adopted by third party recipients.

### 2.5 How Do You Handle Passwords?

We never store password data in plain text; instead they are stored hashed (with at least 4096 rounds of bcrypt, including both a salt and a server-side pepper secret). Passwords sent to the server are encrypted using SSL.

It is your sole responsibility to keep your user name, password and other sensitive information confidential. Actions taken using your credentials shall be deemed to be actions taken by you, with all consequences including service termination, civil and criminal penalties.

If you become aware of any unauthorised use of your account or any other breach of security, you must notify Hack Liberty immediately by sending an email to [contact@hackliberty.org](mailto:contact@hackliberty.org). Suspicious devices can be deleted using the User Settings management tools in a Matrix client such as https://element.hackliberty.org, and users should manage good password hygiene (e.g. using a password manager) and change their password if they believe their account is compromised.

You can manage your account by using a Matrix client such as https://element.hackliberty.org

We will never change or reset a password for you.

### 2.6 Our Commitment to Children's Privacy

We never knowingly collect or maintain information in the Service from those we know are under 16, and no part of the Service is structured to attract anyone under 16. If you are under 16, please do not use the Service.

### 2.7 How Can I Access or Correct My Information?

You can access all that we collect about you by using any compatible Matrix client (such as https://element.hackliberty.org) and managing your User Settings. You can download a copy of all your data as per section 2.1.3.

### 2.8 Who Can See My Messages and Files?

In unencrypted and encrypted rooms, users connecting to the hackliberty.org homeserver (directly or over federation) will be able to see messages and files according to the access permissions configuration of the relevant room. This data is stored in the format it was received on our servers, and can be viewed by Hack Liberty administrators under the conditions outlined below.

In encrypted rooms, the data is stored in our databases but the encryption keys are stored only on your devices or by yourself. Users can optionally backup an encrypted copy of their keys on the Service to aid recovery if they lose all their keys and devices. This key backup is encrypted by a recovery key that only the user has access to. Hack Liberty (the organization) is unable to read your message content in our database. If you lose access to your encryption keys, you lose access to your messages forever.

We use HTTPS to transfer all data. End-to-end encrypted messaging data is stored encrypted using AES-256, using message keys generated using the Olm and Megolm cryptographic ratchets.

### 2.9 What Are the Guidelines Hackliberty.org Follows When Accessing My Data?

We restrict who at Hack Liberty can access user data to roles which require access in order to maintain the health of the Service;

We have technical procedures in place to prevent unauthorised access to user data;

We never share what we see with other users or the general public.

### 2.10 Who Else Has Access to My Data?

Hack Liberty uses full disk encryption on all services to limit physical access to user data. 

Hack Liberty is a Processor of your data, managing the homeserver on behalf of hackliberty.org. We host all services in 1984 data centres. Here's 1984's privacy policy: https://1984.hosting/GDPR/. 1984 controls physical access to their locations.

We use secure private keys when accessing servers via SSH and store credentials in password managers on air-gapped systems.

### 2.11 What happens if Hackliberty.org is sold?

Hackliberty.org is a labor of love and will never be sold to a third party entity.

### 2.12 How Is My Data Protected from Another User's Data?

All of our users' data for the Service currently resides in the same database cluster which is due to the nature of our Service. We use software best practices to guarantee that only people who you designate as viewers of your data can access it. In other words, we segment our user data via software. We do our best and are very confident we're doing a good job at it, but, like every other service that hosts their user data on the same database, we cannot guarantee that it is immune to a sophisticated attack.

### 2.13 What Should I Do If I Find a Security Vulnerability in the Service?

If you have discovered a security concern, please email us at contact@hackliberty.org. We'll work with you to make sure that we understand the scope of the issue, and that we fully address your concern. We consider correspondence sent to contact@hackliberty.org our highest priority, and work to address any issues that arise as quickly as possible.

Please act in good faith towards our users' privacy and data during your disclosure. White hat security researchers are always appreciated.

## Making a Complaint

We try to meet the highest standards when collecting and using personal information. For this reason, we take any complaints we receive about this very seriously. We encourage people to bring it to our attention at [contact@hackliberty.org](contact@hackliberty.org) if they think that our collection or use of information is unfair, misleading or inappropriate. We would also welcome any suggestions for improving our procedures.

## Document History

2022, June 1st: document created

**A note to other startups**: this document was heavily inspired by Balsamiq's plain English ToS document. We were impressed by their championing of plain English, and wanted to reproduce that as much as possible in our own legal documentation. Feel free to draw similar inspiration from this document, though be sure to get any documents you produce checked over by a lawyer. Good luck!
