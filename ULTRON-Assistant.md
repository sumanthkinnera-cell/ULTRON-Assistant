# ULTRON / NOCTOM AI --- Personal Assistant

## Vision

A mobile-first Android-friendly personal AI assistant with a futuristic
cybernetic interface, voice interaction, chat, search, reminders, and an
animated 2D face.

## Intended features

-   Conversational AI using a configured provider API.
-   Telugu and English-friendly interactions.
-   Speech-to-text and text-to-speech where browser/device support
    allows.
-   Optional web search integration with source links.
-   In-app reminders and notification support where available.
-   Camera tools only after explicit permission.
-   Dark interface, animated eyes/mouth, listening/speaking indicators.
-   Installable PWA with manifest and service-worker caching.
-   Optional model controls such as temperature/top-p only if supported
    by the chosen API.

## Important technical limits

A browser PWA generally cannot reliably wake from a closed state,
continuously listen for a wake phrase, or turn on the phone screen while
locked. Reliable background wake-word detection and alarms may require a
native Android app, foreground services, and explicit permissions.

## Suggested architecture

Frontend: HTML/CSS/JavaScript. PWA: manifest and service worker.
Backend: server/serverless functions for API calls and secret
protection. Never expose secret keys in frontend code or GitHub.

## Status to fill in

-   Working and tested:
-   Partially working:
-   Planned:
-   Known issues:
-   Device/browser tested:
