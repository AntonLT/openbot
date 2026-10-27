### Fixed

- Connect Railway works again. OpenBot now registers as a public client when the sign-in server
  supports it. Before, Railway refused the client secret that it gave, and the sign-in stopped with
  "Existing OAuth client information is required when exchanging an authorization code".
- Show a clear message when a sign-in server refuses OpenBot at the end of an MCP sign-in. Before,
  the message did not say what went wrong.
