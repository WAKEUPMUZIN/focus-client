# Focus Client

Focus Client is an independent Minecraft: Java Edition launcher for Windows, currently in development. It is not affiliated with or endorsed by Mojang or Microsoft.

## Current functionality

- Minecraft version selection and installation from official sources.
- Vanilla and Fabric installation support.
- Automatic Java runtime installation.
- Separate game directories for each version and loader.
- Microsoft sign-in implemented using OAuth Authorization Code Flow with PKCE.

## Microsoft authentication

Users sign in through Microsoft's official website in their browser. Focus Client does not collect Microsoft passwords.

The launcher requests Minecraft game services API access to verify Java Edition ownership, retrieve the player's Minecraft profile, and launch an authenticated game session. Account session data is stored locally using Windows-provided encryption.

Minecraft Services API approval is pending. Microsoft account sign-in cannot currently complete the Minecraft authentication process because the application receives HTTP 403: Invalid app registration.

## Development status

The launcher is under active development. Custom menus, HUD customization, and cosmetic features are currently interface prototypes and are not yet implemented as in-game mods.

This repository currently provides project information. Source code and downloadable releases have not yet been published here.
