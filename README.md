## What is REST API?

    A standard set of rules that developers follow to create API.

## REST API Criteria:

1. Client-Server
2. Stateless : All request should be independent of each other.
3. Cacheable : Should be cacheable to streamline client-server interaction.
4. Uniform Interface : Should be in a standard form.
5. Layered
6. Code-on-demand : Executable code to be sent from server to the client when requested, extending client functionality.

## RESTFUL REQUESTS:

1. The endpoint URL : The endpoint is the URL you request.
2. The HTTP method : The type of method you send to the server.
3. The HTTP headers : Provide information to both client and server. Store things like auth-token, cookies or other meta data in http headers.
4. The body data : Contains information you want to send to the server. Only POST, PUT, PATCH or DELETE can have body data

## HTTP Methods:

1. GET : Retrieves or "reads" resources.
2. POST : Creates or "writes" resources.
3. PUT / PATCH : Updates resources.
4. DELETE : Deletes resources.

## HTTP headers:

    Key-value pairs that are separated by colon

i.e: "Content-Type: application/json"

image.png
