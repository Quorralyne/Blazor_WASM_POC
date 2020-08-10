# Blazor_WASM_POC

This repo follows the Blazor WebAssembly Individual Authentication template, Standalone with Authentication library, selected as a Progressive Web App/SPA.

This example uses an Okta developer account as the authority, configured as a Web app/SPA with the callback URIs defined in the Okta portal, and added to the appsettings file.

Additional functionality integrated beyond basic auth includes:

1. Successful logout from Okta and a redirect to the Blazor app
2. Additional scopes added to the OIDC request in Program.cs
3. Added razor page to display the user's claims from the JWT
4. The Counter page updated to display a custom claim for the user configured within Okta
