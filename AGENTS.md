# Mobile project boundaries

Read this file before changing the mobile client. Keep TypeScript, React Native, Expo SDK 57, Expo Router, shared contracts, and the API boundary. Native work must preserve the product roles, listing states, authentication behavior, and Burmese/English support defined by the parent specification.

Keep device-specific concerns in this repository. Do not add server code or direct SQLite access. Web-only server rendering belongs in the web app.
