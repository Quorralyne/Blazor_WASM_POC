# Blazor WebAssembly SPA App - Okta Sample

This repo follows the Blazor WebAssembly Individual Authentication template in Visual Studio 2019 (File > New), Standalone with Authentication library (Individual account), selected as a Progressive Web App/SPA.

This example uses an Okta developer account as the authority, configured as a Web app/SPA with the callback URIs defined in the Okta portal, and added to the appsettings file. Only OIDC was used, no Okta SDK. This is just the front end solution, so there is no token validation done, as it would be expected a backend API would do that. (Future project showing validation forthcoming).

Additional functionality integrated beyond basic auth includes:

1. Successful logout from Okta and a redirect to the Blazor app
2. Additional scopes added to the OIDC request in Program.cs
3. Added razor page to display the user's claims from the JWT
4. The Counter page updated to display a custom claim for the user configured within Okta

An Okta developer account is required to run this successfully. Sign up for a free account at https://developer.okta.com
