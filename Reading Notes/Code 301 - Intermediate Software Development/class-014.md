## What is OAuth?
OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.
## Give an example of what using OAuth would look like.
when you go to log onto a website 
## How does OAuth work? What are the steps that it takes to authenticate the user?

Step 1 – The User Shows Intent
Step 2 – The Consumer Gets Permission
Step 3 – The User Is Redirected to the Service Provider

## What is OpenID?
OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.

## What is the difference between authorization and authentication?
authentication is the process of who a user is, while authorization is the what they have access to.

## What is Authorization Code Flow?
which exchanges an Authorization Code for a token. Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure, and you will have to store it in your client.

## What is Implicit Flow with Form Post?

As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens,

## What is Client Credentials Flow?

 With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow .
