# Custom local authenticator for WSO2 Identity Server

The default authenticator in the WSO2 Identity Server is the Basic authenticator. It is a local authenticator that authenticates the end users using a connected user store and the provided user name and password.

WSO2 Identity Server comes with extensibility which allows you to change the authentication logic which the local users are validated. You only have to write a local authenticator with the customized authentication logic and deploy it in the WSO2 Identity Server.

This project contains a sample custom local authenticator which implemented for **WSO2 Identity Server 5.11.0.**

You can refer to my medium blog "[Writing a custom local authenticator for WSO2 IS 5.11.0](https://medium.com/identity-beyond-borders/writing-a-custom-local-authenticator-for-wso2-is-5-11-0-50332baf7668)" to get a complete understanding on the scenario covered by this sample and how you do the implementation and deployment in the WSO2 Identity Server.