## What is REST API

    A standard set of rules that developers follow to create API.

## REST API Criteria:'

1. Client-Server
2. Stateless : All request should be independent of each other.
3. Cacheable : Should be cacheable to streamline client-server interaction.
4. Uniform Interface : Should be in a standard form.
5. Layered
6. Code-on-demand : Executable code to be sent from server to the client when requested, extending client functionality.

## RESTFUL REQUESTS:'

1. The endpoint URL : The endpoint is the URL you request.
2. The HTTP method : The type of method you send to the server.
3. The HTTP headers : Provide information to both client and server. Store things like auth-token, cookies or other meta data in http headers.
4. The body data : Contains information you want to send to the server. Only POST, PUT, PATCH or DELETE can have body data

## HTTP Methods:'

1. GET : Retrieves or "reads" resources.
2. POST : Creates or "writes" resources.
3. PUT / PATCH : Updates resources.
4. DELETE : Deletes resources.

## HTTP headers:'

    Key-value pairs that are separated by colon

i.e: "Content-Type: application/json"

## HTTP Status Codes:'

    100+ : Informational response
    200+ : Request has succeeded.
    300+ : Request has redirected to another URL.
    400+ : An error that originates from the client has occured.
    500+ : An error that originates from the server has occured.

## Express

    Is a popular framework for nodejs designed for building web application, at it's core it provides HTTP utility methods and middleware for developers to easily create powerful API's
    Makes easy to write handlers for request with different HTTP Methods like GET POST PUT PATCH DELETE etc.

## What is OAuth?

    OAuth is an open standard for authorization, commonly used as a way for Internet users to authorize websites or applications to access their information on other websites but without giving them the passwords.

## OAuth 2.0 Flow

    OAuth 2.0 is the industry-standard protocol for authorization. OAuth 2.0 focuses on client developer simplicity while providing specific authorization flows for web applications, desktop applications, mobile phones, and living room devices. This specification and its extensions are being developed within the IETF OAuth Working Group.

## Authentication vs Authorization

    Authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.

## Scopes

    Scopes are a way to limit an application's access to a user's account. If you don't have a scope listed in your application configuration, then the default scope is user:email.
    Specify exactly what type of access your application needs. This ensures that the user is asked only to grant permissions that your application actually needs.

## Tokens

    Tokens are the thing that applications use to make API requests on behalf of a user. Each token represents a specific application and a specific user, and the permissions that the application has been granted for that user.

```
Note: That since nodeJs is server side console.log() will not work in the browser console. It will show the output in the terminal.
```
