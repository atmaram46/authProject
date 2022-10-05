# authProject

Details for Creating Okta Account:

1. Create a Okta account using email id.
2. Click on getting started under Dashboard.
3. Select create a web application option.
4. Select Create New App option and select OIDC - OpenID connect and Web application options.
5. Enter the details:
    Ex: App Integration Name: MyFirstApp
        Controlled Access: Allow everyone.

6. Client Id is generated.
    Client ID: 0oa68j2weqYh2zxfX5d7
    Client Secret: E8xrhoaIvCBF5kI6rNON23LWL4oqcEs-MCrtrDW9


7. We need an authorization server as we don't have one available with us.
    7.1 This can be found under Getting Started, Create an API Token.
    7.2 Select Authorization Servers.



Details for Creating OAuth 2.0 account:
1. Before your application can use Google's OAuth 2.0 authentication system for user login, you must set up a       project in the Google API Console to obtain OAuth 2.0 credentials, set a redirect URI, and (optionally) customize the branding information that your users see on the user-consent screen. You can also use the API Console to create a service account, enable billing, set up filtering, and do other tasks. For more details, see the Google API Console Help.
2. Creating a Project:
    2.1 Go to Google API console.
    2.2 Click on Select a Project option available on top left.
    2.3 Click on create a New Project.
    2.4 Provide Name and other details.
3. Create the Consent page.
4. Click on Credentials Options.
    4.1 Click on create Credential Option available on top.
    4.2 Click on Create OAuth client ID and enter the required details.

5. Copy the client id and secret. 
    Client id: 1000736276059-t5p3ordcah2ufmisqrdh6u554rj1scpm.apps.googleusercontent.com
    Client Secret: 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
6. Include Google APIs Client Library for Java in pom.xml
