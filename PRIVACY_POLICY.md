# Privacy Policy

## Introduction

Your privacy is important to us. Aerolog-Efb (“we,” “us,” or “our”) does **not collect, store, or transmit any personal information, usage data, or analytics from users of our application, regardless of your country of residence**.

We are committed to complying with all applicable international privacy laws and regulations, including but not limited to:
- Australia Privacy Act and Australian Privacy Principles (APPs)
- Brazil Lei Geral de Proteção de Dados (LGPD)
- California Consumer Privacy Act (CCPA) and California Privacy Rights Act (CPRA)
- Canada Personal Information Protection and Electronic Documents Act (PIPEDA)
- Children’s Online Privacy Protection Act (COPPA)
- European Union General Data Protection Regulation (GDPR)
- Japan Act on the Protection of Personal Information (APPI)
- Singapore Personal Data Protection Act (PDPA)
- South Africa Protection of Personal Information Act (POPIA)
- United Kingdom Data Protection Act (DPA) and UK GDPR
- Any other applicable country, state, or region-specific privacy laws

## Data Collection

We do **NOT** collect, store, or process any type of personal or device-level user data, including but not limited to:
- Personal information (such as names, email addresses, physical addresses, phone numbers)
- Account information or authentication credentials
- Device information, IP addresses, or unique device identifiers
- Usage analytics or behavioral data
- Location data (precise or approximate)
- Cookies, tracking technologies, or similar tools

## AI Features and Third-Party Processing

Starting with version 2.3.0, Aerolog EFB includes optional AI-powered features:

- **AI Briefing** generates a natural-language summary of your flight.
- **Voice Assistant** lets you ask spoken or typed questions about your briefing and hear an answer.
- **Spoken briefing** reads a briefing aloud in a human-sounding voice.

These features are optional. If you do not use them, nothing described in this section leaves your device.

### Text generation

When you use the AI Briefing or Voice Assistant, the following is sent to **DeepSeek** (`api.deepseek.com`), a third-party AI service:

- The **operational flight-plan text already computed by the app** (for example, flight number, route, aircraft type, fuel and weight figures, weather summaries, NOTAM summaries, and turbulence entries).
- Your **typed or transcribed question** when using the Voice Assistant.

Some AI processing also runs entirely **on your device** using Apple's on-device Foundation Models. Nothing is transmitted in that case.

### Speech

Speech **input** is transcribed **on your device** using Apple's Speech framework. The audio itself is never transmitted; only the resulting text is used.

Speech **output** is produced in one of two ways. Aerolog's offline voice runs entirely on your device. The optional human-sounding voice sends the **text of the briefing or answer to be spoken** to a third-party speech service — **ElevenLabs** (`api.elevenlabs.io`), or **OpenAI** (`api.openai.com`) as a fallback — which returns audio. That text is operational flight-plan content of the same kind described above.

### What is never sent

**No personal information**—such as your name, email, Apple ID, phone number, contacts, location, device identifiers, or contact list—is sent to DeepSeek, ElevenLabs, OpenAI, or to us. Aerolog EFB has no account system and never asks you to sign in.

As with any internet request, the third-party service receives the network connection itself, including your IP address. We neither collect nor receive it.

The AI summary, answers and spoken audio are generated solely to provide the requested feature. The output is advisory and must be verified against official sources before operational use.

## Aviation Data Sources

Aerolog EFB fetches weather, NOTAM, airport and imagery data directly from public aviation providers. These requests contain the **operational identifiers you are working with** — for example ICAO airport codes, route coordinates, and map tile references — and, as with any internet request, the provider receives your IP address. They contain no personal information, and no account or identifier ties a request to you.

Current providers include: aviationweather.gov (METAR, TAF, SIGMET, G-AIRMET, PIREP), notams.online and SkyLink (NOTAMs), datis.clowd.io (FAA D-ATIS), atis.guru (D-ATIS outside the FAA feed, republished from ACARS), Open-Meteo (time zones and pressure-level winds), OurAirports (airport reference data), sunrise-sunset.org, NOAA NCEI (geomagnetic reference), avmet.ae (UAE METAR/TAF), and Esri World Imagery (map tiles).

Each provider operates under its own privacy policy. We do not send them anything about you beyond the request itself.

## Children’s Privacy

This app is intended for adults. We do not knowingly collect or request information from anyone under the age of 18. If you believe a child has provided us with personal information, please contact us immediately, and we will take prompt action to delete such information.

## Your Privacy Rights

Since we do not collect, store, share, or sell any personal or usage data, all user rights under global privacy laws (such as access, correction, deletion, objection, or portability) are inherently observed by default. If you have privacy concerns or believe your rights may have been violated, you may contact us at any time.

## No Resale and No Third-Party Marketing

We do not sell, trade, rent, or otherwise transfer any user information to third parties for marketing, advertising, analytics, or other commercial purposes.

## Security

We do not store or process personal data on our servers. Data you import into the app remains on your device, apart from two cases described above: the optional AI features transmit operational flight-plan text and your question to DeepSeek, and the optional human-sounding voice transmits the text to be spoken to ElevenLabs or OpenAI. Aviation data requests go directly to the providers listed above. Please review those services' own privacy policies for how they handle data sent to their APIs.

## Changes to This Privacy Policy

We may update this policy to reflect changes in law or our app’s practices. If updated, the latest version will be available on this page and will be effective immediately.

## Contact Us

If you have any questions, requests, or concerns about this Privacy Policy or your privacy rights, please contact:
**NAV-INT-llc@pm.me**
