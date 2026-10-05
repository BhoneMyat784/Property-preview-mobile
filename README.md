# Property Portal Mobile

Independent Expo mobile project for the future iOS and Android client. It shares the React Native components, route direction, contracts, language support, and API boundary with the web project.

The current mobile repository is a native-ready foundation copied from the shared route tree. Native navigation, device-specific upload behavior, secure session storage, and mobile acceptance flows remain planned work in the parent feature roadmap.

## Setup

```bash
npm ci
npm run dev
```

Use the Expo CLI to open an iOS or Android simulator. Set `EXPO_PUBLIC_API_URL` to a reachable API host; `localhost` from a physical device refers to the device itself.

## Checks

```bash
npm run typecheck
npm run check:expo
```

Do not add web-only server rendering to this project. Native screens should call the API project through shared contracts and preserve the same listing, favorites, account, and moderation behavior.
