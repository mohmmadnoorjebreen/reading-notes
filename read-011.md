# What is OAuth

## What is OAuth?

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial

## Give an example of what using OAuth would look like.

The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon

## How does OAuth work? What are the steps that it takes to authenticate the user?

- The first website connects to the second website on behalf of the user

-  The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

- The first site gives this token and secret to the initiating user’s client software.

- The client’s software presents the request token and secret to their authorization provider.

- If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

- The user approves a particular transaction type at the first website.

- The user is given an approved access token

- The user gives the approved access token to the first website.

- The first website gives the access token to the second website as proof of authentication on behalf of the user.

- The second website lets the first website access their site on behalf of the user.

- The user sees a successfully completed transaction occurring.


- OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. 


## What is OpenID?

OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."


# Authorization and Authentication flows

## What is the difference between authorization and authentication?

### Authentication

- Determines whether users are who they claim to be

- Usually done before authorization	

### Authorization

- Determines what users can and cannot access


- Usually done after successful authentication


## What is Authorization Code Flow?

is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space

![](https://images.ctfassets.net/cdy7uua7fh8z/2nbNztohyR7uMcZmnUt0VU/2c017d2a2a2cdd80f097554d33ff72dd/auth-sequence-auth-code.png)

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

is an OpenId Connect flow specifically designed to authenticate native or mobile application users. 

## What is Implicit Flow with Form Post?

As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets.

## What is Client Credentials Flow?

typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow  in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.


## What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.

## What is Resource Owner Password Flow?

Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form.