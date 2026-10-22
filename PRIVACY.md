# MagPortal privacy

The Windows app stores profiles, credentials, lists, and viewing progress in an encrypted file under the current Windows account. Account encryption does not protect against another application already running as that user.

The browser version uses tab-scoped session storage. Provider details are sent to the connection adapter when requested; provider sessions last only for the request. Application code does not store provider credentials in a hosted database or log them. Video is delivered directly by the provider to the viewer.

Provider and hosting platforms receive normal network information, including IP addresses. MagPortal does not implement a usage analytics service. When requested in the Windows app, subtitle search submits the current title to the configured subtitle service.

Manually exported backup files contain saved credentials in plain text. They are intended for private transfers and should not be posted publicly.

No personal provider settings, device IDs, playback history, private project history, or diagnostic logs are included in public releases.
