# ***API Deployment***

## Configuring Django Settings: Best Practices

### Managing Django Settings: Issues

Different environments. Usually, you have several environments: local, dev, ci, qa, staging, production, etc. Each environment can have its own specific settings (for example: DEBUG = True, more verbose logging, additional apps, some mocked data, etc). You need an approach that allows you to keep all these Django setting configurations.

Sensitive data. You have SECRET_KEY in each Django project. On top of this there can be DB passwords and tokens for third-party APIs like Amazon or Twitter. This data cannot be stored in VCS.

Sharing settings between team members. You need a general approach to eliminate human error when working with the settings. For example, a developer may add a third-party app or some API integration and fail to add specific settings. On large (or even mid-size) projects, this can cause real issues.

Django settings are a Python code. This is a curse and a blessing at the same time. It gives you a lot of flexibility, but can also be a problem – instead of key-value pairs, settings can have a very tricky logic.


## How Does SSH Work
SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet. The service was created as a secure replacement for the unencrypted Telnet and uses cryptographic techniques to ensure that all communication to and from the remote server happens in an encrypted manner. It provides a mechanism for authenticating a remote user, transferring inputs from the client to the host, and relaying the output back to the client.


### How Does SSH Work

For Mac and Linux users, head over to your terminal program and then follow the procedure below:

The SSH command consists of 3 distinct parts:

```
ssh {user}@{host}
```
The SSH key command instructs your system that you want to open an encrypted Secure Shell Connection. {user} represents the account you want to access. For example, you may want to access the root user, which is basically synonymous for system administrator with complete rights to modify anything on the system. {host} refers to the computer you want to access. This can be an IP Address (e.g. 244.235.23.19) or a domain name (e.g. www.xyzdomain.com).

### Understanding Different Encryption Techniques
There are three different encryption technologies used by SSH:

1. Symmetrical encryption

Symmetric encryption is a form of encryption where a secret key is used for both encryption and decryption of a message by both the client and the host. Effectively, any one possessing the key can decrypt the message being transferred.

2. Asymmetrical encryption

Unlike symmetrical encryption, asymmetrical encryption uses two separate keys for encryption and decryption. These two keys are known as the public key and the private key. Together, both these keys form a public-private key pair.

3. Hashing.

One-way hashing is another form of cryptography used in Secure Shell Connections. One-way-hash functions differ from the above two forms of encryption in the sense that they are never meant to be decrypted. They generate a unique value of a fixed length for each input that shows no clear trend which can exploited. This makes them practically impossible to reverse.
