# Authentication

> ## What is OAuth

1. What is OAuth?
   * An open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

2. Give an example of what using OAuth would look like.
   * using render and loging in with your github credentials so you dont have to make a whole new password with render.

3. How does OAuth work? What are the steps that it takes to authenticate the user?
   * OAuth only works using HTTPS. The steps are :
      * The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
      * The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
      * The first site gives this token and secret to the initiating user’s client software.
      * The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
      * If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
      * The user approves (or their software silently approves) a particular transaction type at the first website.
      * The user is given an approved access token (notice it’s no longer a request token).
      * The user gives the approved access token to the first website.
      * The first website gives the access token to the second website as proof of authentication on behalf of the user.
      * The second website lets the first website access their site on behalf of the user.
      * The user sees a successfully completed transaction occurring.
      * OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

4. What is OpenID?
   * OpenID is about authentication.

* OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.

References:
[What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

> ## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
   * authorization is for machines to long into other machines to get information on behalf of humans. Authentication just a human to prove who he is to a machine when loging in.

2. What is Authorization Code Flow?
   * exchanges an Authorization Code for a token.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
   * During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).

4. What is Implicit Flow with Form Post?
   * An alternative to the Authorization Code Flow. It is intended for Public Clients, or applications which are unable to securely store Client Secrets

5. What is Client Credentials Flow?
   * With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user.

6. What is Device Authorization Flow?
   * With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.

7. What is Resource Owner Password Flow?
   * Requests that users provide credentials (username and password), typically using an interactive form.

References:
[Authorization and Authentication flows](https://auth0.com/docs/flows)

> ### Other good reads/watch

* [Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react)

[Return home](../README.md)
