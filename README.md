### Post-install message from chromedriver-helper:
NOTICE: chromedriver-helper is deprecated after 2019-03-31.\
Please update to use the 'webdrivers' gem instead.\
See https://github.com/flavorjones/chromedriver-helper/issues/83\
\
## Okta practice from this post:
https://medium.com/@abhisheksp/integrating-your-rails-application-with-okta-2e77ebe02528 \

## TIL:
**OIDC or SAML?**\
https://developer.okta.com/docs/guides/build-sso-integration/saml2/overview/ \
\
**What is OAuth 2.0?**\
https://oauth.net/2/ \
\
**Okta SAML FAQ**\
https://developer.okta.com/docs/concepts/saml/faqs/ \
\
**Okta Developer Forum - SAML**\
https://devforum.okta.com/search?q=saml \
\
**Stack Overflow - Okta SAML**\
https://stackoverflow.com/search?q=saml+okta \
\
**Create Your Integration**\
https://developer.okta.com/docs/guides/build-sso-integration/saml2/create-your-app/ \
\
**Prepare a SAML integration**\
In a SAML integration, Okta is the Identity Provider (IdP), and your application is the Service Provider (SP). If you need more background on the protocol or for SAML best practices for your application, review our SAML concept documentation.\
\
**Before you create a new SAML integration in Okta:**
1. Determine the default Assertion Consumer Service (ACS) URL for your integration. This is often referred to as the SP sign-in URL. This is the endpoint on your application where the SAML responses are posted.
2. Find your Audience URI. This is sometimes referred to as the SP Entity ID or the Entity ID of your application.
3. (Optional). Set up a Default Relay State page, where users land after they successfully sign in to the SP using SAML. This must be a valid URL.
4. Gather any required SAML attributes. You can choose to share Okta user profile field values as SAML attributes with your application.
Note: SAML integrations must use SHA256 encryption for security. If you are using SHA-1 for encryption, see our guide on how to [Upgrade SAML Apps to SHA256](https://developer.okta.com/docs/guides/updating-saml-cert/overview/).<br>
<br>
**Rails session**\
https://www.justinweiss.com/articles/how-rails-sessions-work/ \
\
**Rails CSRF deep dive**\
https://medium.com/rubyinside/a-deep-dive-into-csrf-protection-in-rails-19fa0a42c0ef#:~:text=Briefly%2C%20Cross%2DSite%20Request%20Forgery,their%20authenticity%20with%20each%20submission.