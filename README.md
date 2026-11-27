# Magic session planner app

React Native mobile application for discovering nearby Magic: The Gathering sessions, hosting games, and managing seat requests.

## Planned stack

React Native with Expo and TypeScript, Expo Router, Expo Location, TanStack Query, and secure device token storage. iOS and Android through Expo are confirmed. Google and Apple are the only sign-in methods: native Google on both platforms, native Apple on iOS and secure browser Apple on Android, with NestJS-owned application sessions. Use Expo development builds, MapLibre with Geoapify Free, English/Italian UI and 18+ onboarding. Discovery starts at current location and shows only the city; approved detail reveals the precise map. Push events update UI directly without polling.

## Development plan

Start with the [shared development plan](../magic-session-planner-docs/README.md), then follow the [development roadmap](../magic-session-planner-docs/development-roadmap.md). The documentation is maintained in the separate `magic-session-planner-docs` repository. Clone it alongside this repository to use these relative links locally.

Use feature branches from the protected default `dev` branch and pull requests; `main` contains release milestones. Framework setup, dependency installation, and application code are planned for roadmap step 1; there are no run or build commands yet.

See the [accepted authentication policy](../magic-session-planner-docs/authentication.md), [operating/retention policy](../magic-session-planner-docs/operations.md), and [implementation roadmap](../magic-session-planner-docs/development-roadmap.md). Support all format families through the [versioned format/configuration specification](../magic-session-planner-docs/formats.md), including official, community, historical, custom and physical device-play gatherings. No product decision remains open. Unit, integration and E2E suites are required from scaffolding; none exists yet.
