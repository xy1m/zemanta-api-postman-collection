[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/2299a4071461aeb7339d#?env%5BZemanta-ENV%20empty%5D=W3siZW5hYmxlZCI6dHJ1ZSwia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiIiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoiY2xpZW50X3NlY3JldCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImJhc2VVUkwiLCJ2YWx1ZSI6Imh0dHBzOi8vb25lYXBpLnplbWFudGEuY29tIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImFjY291bnRJZCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImNhbXBhaWduSWQiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJidWRnZXRJZCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImdvYWxJZCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImFkR3JvdXBJZCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImJhdGNoSWQiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJjb250ZW50QWRJZCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6InB1Ymxpc2hlckdyb3VwSWQiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJlbnRyeUlkIiwidmFsdWUiOiIiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoiZnJvbSIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6InRvIiwidmFsdWUiOiIiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5Ijoiam9iSWQiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0In1d)

As Zemanta One API uses OAuth 2, you have two options to use this collection

* Select Authorization OAuth 2.0 and set your {access_token} (Recommand)
* Request {access_token} then set `Authorization Bearer {access_token}` accross every API request.
  - For requesting {access_token}, select No Auth and set `Authorization Basic base64({client_id}:{client_secret})` to Authorization, 
`application/x-www-form-urlencoded` to Content-Type, grant_type=client_credentials

See also [Zemanta Authorization](http://dev.zemanta.com/one/api/#header-authentication)

For developer convenience, you could define environment variables as I do, or just replace {{something}} with your own variable.

See [Zemanta-ENV](./ZEMANTA-ENV.jpg)

## Useful Resources

Never used Postman or the Zemanta One API before? Here's some useful links to get you started and to get help when you have questions or run into problems. <3

#### Zemanta One API

- [Zemanta Help](http://help.zemanta.com/container/show/getting-started)

- [Zemanta One API](http://dev.zemanta.com/one/api/)

#### Postman

- [Download Postman](https://www.getpostman.com/postman)

- [Postman Collection Docs](https://www.getpostman.com/docs/postman/collections/managing_collections)

- [Postman Environment Docs](https://www.getpostman.com/docs/postman/environments_and_globals/manage_environments)

- [Postman Scripting Docs](https://www.getpostman.com/docs/postman/scripts/intro_to_scripts)

- [Postman Scripting API Reference](https://www.getpostman.com/docs/postman/scripts/postman_sandbox_api_reference)
