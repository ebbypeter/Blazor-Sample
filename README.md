# Blazor Sample

This is a Blazor Sample Solution to demonstrate how to authenticate a Blazor Wasm App with EntraId.

The source code can be found under `./src/BlazorWasmClient` location.  
The `Azure App Id`, `App Secret` and `Tenant Id` can be found under `./src/BlazorWasmClient/wwwroot/appsettings.json` file.

```json
"AzureAd": {
    "ClientId": "<Client Id here>",
    "Authority": "https://login.microsoftonline.com/chackunkal.com",
    "ValidateAuthority": true,
    "ClientSecret": "<Client Secret here>"
}
```