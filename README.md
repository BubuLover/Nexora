# Nexora

Nexora is an independent, personal-use utility for managing Minecraft: Java Edition accounts and interacting with supported Java Edition game-service APIs.

> **Nexora is not affiliated with, endorsed by, or sponsored by Mojang Studios or Microsoft.**

## Overview

Nexora is designed to provide a centralized interface for managing accounts that are owned and controlled by the user.

The project is intended for personal, non-commercial use.

Planned and implemented functionality includes:

- Account management
- Account enable/disable controls
- Microsoft account authentication
- Xbox Live / XSTS authentication
- Minecraft Java Edition profile authentication
- Profile information management
- Profile-name changes on accounts owned by the user
- Activity and operation logging
- Optional notifications
- A self-hosted web dashboard

## Authentication

Nexora uses Microsoft's supported OAuth authentication flow rather than asking users to provide their Microsoft passwords directly to the application.

The authentication flow involves:

1. Microsoft OAuth
2. Xbox Live authentication
3. Xbox Security Token Service (XSTS)
4. Minecraft Services authentication

Authentication credentials and tokens are intended to remain under the control of the user and are not intended to be shared with third parties.

## Privacy & Security

Nexora is designed for use with accounts owned by the user.

The project does not intentionally collect Microsoft account passwords or authentication credentials from other users.

Sensitive configuration values, authentication tokens, encryption keys, and other secrets should be stored outside the source repository and must never be committed to Git.

For self-hosted installations, users are responsible for securing their own server, configuration files, authentication data, and network access.

## API Usage

Nexora is intended to use supported Minecraft and Microsoft authentication and game-service APIs.

The project does not attempt to bypass authentication, licensing, security mechanisms, or access controls.

API requests should respect applicable service requirements, rate limits, and other restrictions.

If a requested operation is not permitted by the applicable API or service policies, Nexora should not attempt to circumvent those restrictions.

## Account Ownership

Nexora is intended to operate only on Minecraft accounts controlled by the user.

Users are responsible for ensuring that their use of Nexora complies with the applicable Minecraft, Microsoft, and Xbox policies and terms.

## Project Status

Nexora is currently a personal development project.

Some functionality may be experimental or incomplete while the project is being developed and reviewed.

Access to certain Minecraft Java Edition game-service APIs may require application approval or allow-listing by the relevant service.

## Disclaimer

Nexora is an independent third-party project.

It is not an official Minecraft, Mojang Studios, Microsoft, Xbox, or Xbox Live application.

Minecraft is a trademark of Mojang Studios. Microsoft, Xbox, and related trademarks belong to Microsoft.

Nexora does not claim any affiliation with or endorsement by Mojang Studios or Microsoft.

## License

This repository is currently provided for personal development and evaluation purposes.

See the repository for the applicable license and usage terms.
