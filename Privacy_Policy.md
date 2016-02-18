<h1>Privacy Policy</h1>
*Last updated 18 February 2015*
<br>
<br>
This privacy policy ("Policy") governs how Technologies Peerio Inc. (“Peerio”, "we," "us," "our," etc.) handles and processes users ("you," "your," etc.) data in the Peerio application and on our website and servers (collectively, the "Services").
<br>
<br>
This policy is subject to our <a href="https://github.com/PeerioTechnologies/peerio-documentation/blob/master/Terms_of_Use.md">Terms of Use</a> as well as any other agreements or notices that may be associated with a particular Peerio product, service, or website ("Peerio offering") and may provide additional information about how Peerio handles your data. Your use of Peerio services or offerings indicates your consent to this Privacy Policy and our Terms of Use. You may not use Peerio if you do not agree to the terms described in this policy.
<br>
<br>Peerio aims to provide ambitious security assurances. As a result, we want to be as open and transparent as possible about our technology and how your data is handled when using Peerio Services. The Peerio app is open source and our client source code is publicly available for review on <a href="https://github.com/PeerioTechnologies">GitHub</a>.
<br>
<br>Philosophically, Peerio endeavors to collect, use and disclose the minimum amount of personal information that is necessary to operate the Services.  
<br>
<br>If you have any other questions, please contact us at peerio@peerio.com.
<br>
<br>
<h3>1. What the Peerio app can do to protect your privacy</h3>

<br>Peerio provides message sharing, file sharing, and cloud storage with end-to-end encryption that makes your data inaccessible to anyone other than you and your intended recipient(s), even Peerio cannot access the contents of your messages and files. The confidentiality, integrity and authenticity of the ciphertext (your encrypted data) is designed to be protected by Peerio against:
<br>
<br> 
+ **Server compromise** — If Peerio's server network is ever compromised, the content of your messages and files will remain inaccessible to any third party, including Peerio and its employees.

+ **Malicious Host** — The Peerio app protects against message forgery, file modification, and artificial read receipts of messages that have not been read.
 
+ **Man-in-the-middle attacks**  — The Peerio app provides means for users to securely authenticate each other’s cryptographic identities (see <a href="https://peerio.zendesk.com/hc/en-us/articles/202729949">“avatars”</a> and <a href="https://peerio.zendesk.com/hc/en-us/articles/204394135">“Peerio Public Key”</a>).

+ **Unauthorized account access** — Peerio protects a user’s account and identity by using authentication challenges, including a passphrase, device specific passcodes, and optional <a href="https://peerio.zendesk.com/hc/en-us/articles/203665635">two-factor authentication (2FA)</a>.
<br>
<br>

<h3>2. What the Peerio app does not do</h3>

Peerio does not anonymize connections, geolocation, or the identity of users. Peerio is compatible with certain anonymizing software, however we cannot recommend or guarantee any claims such tools may make. We can only provide assurances about the things we control.
<br>
<br>Peerio cannot protect against key-loggers or other similar malware and backdoors that may exist on a user’s machine. It is the user’s responsibility to ensure their device is free of such software.
<br>
<br>Peerio cannot protect you from passphrase mismanagement, such as telling others your passphrase or storing your passphrase in an insecure location.
<br>
<br>Peerio cannot protect you from environmental concerns, such as leaving your device unattended with Peerio open or people looking over your shoulder.
<br>
<br>Peerio offers a passcode feature that allows device-specific passwords. It should be noted that passcodes store an encrypted copy of the passphrase on the device where they are configured, and thus are more vulnerable if the device itself is stolen and compromised. For this reason, passcodes should only be used on trusted, well-protected devices.
<br>
<br>
<h3>3. How Peerio protects your privacy</h3>
<h4>Technology</h4>
Peerio uses state-of-the-art encryption to offer high security standards in an intuitive, easy-to-use application.
<br>
<br>The Peerio app is built off the miniLock encryption system, which was designed specifically to tailor to Peerio’s use-cases. Peerio relies on the following cryptographic primitives, or “building blocks”: 
<br>
<Br>
+ **Curve25519** — is used to provide public key agreement over elliptic curves.
  
+ **XSalsa20** — is used in order to provide encryption and confidentiality.
  
+ **Poly1305** — is used in order to ensure the integrity of encrypted data.

+ **Scrypt** — is used in order to provide memory-hard key derivation.

+ **BLAKE2** — is used for various operations requiring hash function operations.

+ **miniLock’s header construction** — is used in order to provide some additional cryptographic features and guarantees, including efficient encryption to multiple recipients.

<br>
For in-transit encryption, Peerio Services use Transport Layer Security (TLS) with best-practice cipher suite configuration, including support for perfect forward secrecy (PFS). You can view a detailed and up-to-date independent review of Peerio’s TLS configuration on <a href="https://www.ssllabs.com/ssltest/analyze.html?d=app.peerio.com&latest">SSL Labs</a>.
<br>
<br>The Peerio network manages public key exchange and verification, while also offering users independent out-of-band public key authentication. When you sign up for Peerio, you are assigned a randomly generated passphrase. This is then used to derive your unique private encryption key. Your passphrase, along with your username, is used to derive the Public Key assigned to your account. You can independently verify a user’s cryptographic identity via their Public Key or Peerio avatar.
<br>
<h4>Accountability</h4>
<h5>Open source</h5>
Peerio’s client code is open source to provide transparency and strengthen Peerio’s security through ongoing public review, testing, and evaluation. Peerio’s client code is available for review on <a href="https://github.com/PeerioTechnologies">GitHub</a>. 
<br>
<br>
<h5>Bug bounty</h5>
To encourage community peer review and security research, Peerio offers a <a href="https://peerio.zendesk.com/hc/en-us/articles/203981385">Bug Bounty</a> of up to $5000 for anyone able to successfully identify a critical security vulnerability in Peerio. 
<br>
<br>Peerio’s bug bounty operates with a policy of responsible disclosure. Bug reports must not publicly disclose a security vulnerability before allowing Peerio a reasonable amount of time to address the issue. This policy also holds us responsible for swiftly fixing ‘high’ or ‘critical’ vulnerabilities that affect user security, and disclosing reported bugs and fixes within a reasonable amount of time. 
<br>
<br>
<h5>Security audits</h5>
To ensure Peerio’s security in its most recent iteration keeps pace with contemporary technological standards, Peerio’s client and server code undergo an independent third-party security audit at least once every six months. 
<br>
<br>Peerio was last audited 28 September 2015 by expert cryptographers and penetration testers at <a href="https://cure53.de/">Cure53</a>. 
<br>
<br>
<h5>Organizational structure</h5>
All our employees undergo security training for in-office procedures, online practices, and responding to attempts to obtain data through phishing or other forms of social engineering. 
<br>
<br>Access to information and operational structures, including user data, servers, and support services, is regulated to as few employees as is necessary to provide you with Peerio services. 
<br>
<br>
<h3>4. What information Peerio has access to and how it may be used</h3>

We retain only basic information needed to provide Peerio services to users and to improve Peerio’s operations. More information about this is provided below.
<br>
<br>
<h4>User-provided information</h4>
When you sign up for the Peerio App, we collect the information you provided to open your account, including your username, first and last name (legal name not required), and contact information such as email addresses or phone numbers (optional). This information is used to help you connect with your contacts on Peerio, send you important updates about your account, and to offer support with account services.
<br>
<br>When you invite your contacts to join Peerio with the "Add Contacts" or "Import Contacts" feature, you provide us with the email addresses and/or phone numbers of your contacts. This information will be used only to send the invitation you have requested via email or SMS. We will not use this information for any other purpose. If your contact does not register for Peerio, their contact information will be securely removed automatically after ninety (90) days. If the contact does join Peerio, they will receive a contact request from your Peerio account.
<br>
<br>When you send messages to our support team, your email will be filed for follow-up correspondence, and any information you directly provide in your support request will be used to assist you in your support request. Please do not send any sensitive information through our support center, such as your Peerio passphrase, passcode, credit card or other payment information. 
<br>
<br>
<h4>Ciphertext</h4>
Peerio has access to the ciphertext (encrypted data) of messages and files you share or upload. The contents of this encrypted data can only be read by a user and their intended recipients, and cannot be read by Peerio or any other third parties. Peerio has access to ciphertext only for the purposes of delivering, receiving, and/or storing users’ encrypted messages and files. We cannot decrypt this ciphertext and we (and teams of independent auditors) believe that it is resistant to highly sophisticated attacks. 
<br>
<br>
<h4>Metadata</h4>
Some metadata of Peerio messages is accessible by Peerio’s servers and needed in order to provide services. This includes, the sender’s and recipient(s)’ usernames and Peerio Public Keys; the time at which messages and files are sent and received; the size of files uploaded to Peerio; the message ID that a file is attached to; and a user's Peerio contacts’ usernames and public keys. 
<br>
<br>
<h4>Account information</h4>
Peerio has access to your Peerio account settings and information, such as language preferences, notification settings, storage usage information, logs of authentication errors, timestamps of server requests, and users’ sent, received, and rejected contact requests.
<br>
<br>
<h4>IP Addresses</h4>
The Peerio App and website are able to identify a user's IP address, which can be used to determine user connections, geolocation, and identities. 
<br>
<br>Peerio collects IP address information to connect to our data centers, as well as help users review connection attempts, and identify any possible suspicious activity with their account in order to protect Peerio and its users.
<br>
<br>IP address information may also be used to protect users’ ability to connect to Peerio network by identifying and preventing attacks on the Peerio server network.
<br>
<br>
<h4>Crash Reports</h4>
Peerio clients for mobile devices offer optional crash and exception reports. You have the choice of whether to submit such a report to Peerio, and reporting is disabled by default. These reports are completely anonymous and are used to help Peerio improve services and support for Peerio’s mobile and desktop clients. Crash and exception reports will include the device platform, device type, device model, operating system version, Peerio client version, stack track, and the exception name and type. 
<br>
<br>
<h4>Opt-in Analytics</h4>
Users are able to opt-in for anonymous non-content data collection that aids Peerio's ongoing usability research and design work.  This option is off by default and can be enabled or disabled by the user at any time through their account settings. If enabled, the user agrees to allow the Peerio client to collect non-identifying and non-content data; such as the amount of time spent on a given page or between actions, or which actions are taken or not taken on a page. Data collected in this way is stored on Peerio-hosted servers. This data will never be sold to third parties. Peerio may choose to share this data with other researchers free of charge in the pursuit of improving public knowledge on issues related to security and design.
<br>
<br>
<h3>5. What information Peerio shares with third parties</h3>
We do not sell, trade, or rent any user information to any third parties. There are limited situations in which Peerio will share user data in order to provide our services. These include:
<br>
<br>
<h4>Peerio support services</h4>
When you make an emailed request to Peerio support, your email as well as the content of your request will be available to our support services provider.
<br>
<br>
<h4>Email and SMS notifications and invitations</h4>
Your email and/or phone number will be shared with the message service we use to deliver such notifications. Such messages cannot be delivered without communicating such information to the message services provider. Notifications are used to deliver Peerio confirmation codes, invitations to contacts, and (optionally) notices about the number of new messages or contact requests you may have. No Peerio message or file content is ever shared. This information will not be used for any purpose other than message delivery.
<br>
<br>When you send an invitation to one of your contacts, the message will include the name you have registered with Peerio as well as your Peerio username. This is to inform your contacts of who is inviting them and how to connect with you on Peerio. You control what information you provide to Peerio for such purposes.
<br>
<br>
<h4>Payments</h4>
All payments made to Peerio, along with payment information (date, amount, sender, recipient, etc) are shared with and processed through a third party payment service. Peerio does not host any payment information.
<br>
<br>
<h3>6. Account Removal</h3>
You may delete your Peerio account at any time, for any reason. However, to prevent third-party requests to delete user data, Peerio cannot delete your account for you.
<br>
<br>Deleting your account will disassociate any contact information, such as email addresses or phone numbers registered to that account. 
<br>
<br>Any data that is owned only by you and has not been shared with other users will be removed completely from Peerio’s servers and network.
<br>
<br>Data that has not been destroyed and has been shared with other users will remain on the Peerio network until all users with whom it has been shared have destroyed the data in question.
<br>
<br>
<h3>7. Data Retention and Removal</h3>
Peerio retains user data only as long is necessary to provide Peerio’s services to users. While your account is registered and in use, this includes the data Peerio has access to, as outlined above. Activity logs are securely wiped after 30 days. 
<br>
<br>If you delete a message or a file that you have previously shared, it will not be removed from our servers until all recipients have also removed it from their account(s), at which point the message or file and its metadata will be securely wiped within 24 hours. If you delete a message or file that you have not shared with anyone,  that data and associated metadata will be securely wiped from Peerio’s servers within 24 hours. 
<br>
<br>If you destroy a file, it will be removed from Peerio’s servers, network, and all users immediately. However, we cannot destroy evidence that a file with a particular encrypted file ID was once sent in a message. The message it was sent in will have a trace of this ID, as it is in the encrypted body of the message. Because it is encrypted, we are unable to remove it from such messages. This allows the Peerio app to verify that files the server has sent with a message were put there by the designated sender, and not a third party. Peerio cannot read the plaintext name of the file.
<br>
<br>Upon account deletion, Peerio removes all your data from our servers and network, except for your account username, your Peerio Public Key, and any messages and files you have shared with other users that you have not destroyed. This information is necessary for your former contacts to be able to identify and decrypt messages they have received from you. This information also helps us prevent attempts to create fraudulent accounts representing a previous user.
<br>
<br>The Peerio Service runs on servers operated by our contractors and those servers may be located outside of Canada. 
<br>
<br>Information related to users you have invited to join Peerio, but who have not subsequently created an account with Peerio, will be removed after ninety (90) days. This time is solely used to help deliver contact requests and referral rewards to you and your contacts and will never be used for any other purpose.
<br>
<br>
<h3>8. Law Enforcement Policies</h3>
We recognize that law enforcement agencies may make legitimate requests for user data from Peerio. Peerio is located in Quebec, Canada and all of our information systems are managed from Canada. We are of the view that we can only be compelled to provide information to third parties according to the federal laws of Canada and the provincial laws in Quebec. We are also of the view that we can only be compelled to provide the limited user information we have according to the federal laws of Canada and the provincial laws in Quebec. We will only provide user information to a third party where we are of the view that we are compelled to do so by applicable legal process. 
<br>
<br>Law enforcement agencies outside of Canada should use letters rogatory or procedures established under any applicable Mutual Legal Assistance treaty. 
<br>
<br>Users will be notified if a request has been made to provide their data to a law enforcement agency, unless Peerio is legally unable to do so.
<br>
<br>Any law enforcement request can only retrieve, as a maximum, information available to Peerio. As Peerio does not handle users private encryption keys, Peerio cannot provide law enforcement agencies with plaintext or unencrypted messages or files a user may have uploaded, downloaded, sent, or received in Peerio. However, certain metadata may be subject to seizure – see above, “What Information Peerio Has Access to”.
<br>
<br>Please view our <a href="https://github.com/PeerioTechnologies/peerio-documentation/blob/master/Law_Enforcement_Guidelines.md">Law Enforcement Guidelines</a> for full details.
<br>
<br>
<h3>9. Peerio’s Use by Children or Minors</h3>
Peerio does not have access to any information that would identify a user's age, nor do we retain any information that might be able to do so. However, Peerio is not intended to be used by children or persons who are not capable of entering into a legally binding contract between themselves and Peerio. Any person who is under the age of majority in the jurisdiction in which they reside must obtain the consent of their legal guardian to create a Peerio account and to consent on their behalf to this Policy. 
<br>
<br>
<h3>10. Privacy Policy is Subject to Change</h3>
This privacy policy may be updated at any time, and for any reason. We will post updates to the policy here and notify users of updates through other publicly-available communication channels. We will always note where changes are made, as well as provide a history of previous versions of our privacy policy.
<br>
<br>
<h3>11. Contact Us</h3>
We have done our best to thoroughly outline the ways in which Peerio handles your data within this privacy policy. If you have any questions or complaints about Peerio’s handling of your personal information or if you want access to your personal information in the custody or control of Peerio, please contact us at peerio@peerio.com 
