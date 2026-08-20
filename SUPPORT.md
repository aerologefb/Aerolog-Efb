# Aerolog EFB — Support

Thanks for using Aerolog EFB. This page is for help, feedback, and bug reports.

## Contact

For all support, billing, or feature questions:

**[NAV-INT-llc@pm.me](mailto:NAV-INT-llc@pm.me)**

We typically respond within 48 hours.

For bug reports and feature requests you can also use [GitHub Issues](https://github.com/aerologefb/Aerolog-Efb/issues).

## Frequently asked questions

### My OFP didn't import correctly

Aerolog EFB supports LIDO, Jeppesen, NavBlue, and Sabre OFP formats. If your file fails to parse:

- Confirm the OFP is a text-based PDF (not a scanned image).
- Check the format badge on the import screen — if it says "Unknown", tap **Share Sample** to send the file so we can extend support.
- Re-export the OFP from your operations system if possible.

### Live weather isn't loading

Aerolog EFB pulls METAR / TAF / airport data from AviationWeather.gov (US gov source). Check:

- Your internet connection.
- Whether the ICAO code is valid (e.g., `KJFK`, `EGLL`).
- Whether the source site is reachable at <https://aviationweather.gov>.

### D-ATIS isn't showing for my airport

D-ATIS decodes worldwide. US airports come from the FAA D-ATIS network. Airports outside it are served by a second source that republishes D-ATIS messages **overheard from ACARS**, so coverage depends on whether another aircraft recently requested that airport's ATIS.

If the card is empty, the most likely reasons are:

- No recent ACARS pickup for that airport. Nothing is published rather than something stale being shown.
- The airport does not publish a datalink ATIS at all. Use the regional ATIS frequency.

Every non-US report is labelled with the flight whose request was overheard and how old it is, so you can judge it before you use it.

### The ATIS and the METAR disagree on pressure

They are two different observations taken at two different times — sampling six airports live, the gap ran from 1 to 28 minutes and not one matched. Where both state a QNH and they differ by 2 hPa or more, Aerolog names the METAR figure as the current one.

Runway in use, approach and transition level are never suppressed because of a pressure difference: they exist nowhere else, and losing them would cost you more than the drift does.

### A storm cell says "DEPICTED" instead of a flash rate

Lightning flash counts come from the Geostationary Lightning Mapper aboard the GOES satellites, which see the Americas, the Atlantic and the eastern Pacific. There is no equivalent coverage over the Gulf, Europe, Africa or Asia.

Outside that footprint the cell still animates — a still icon on a thunderstorm reads as "nothing here" — but it is driven by the storm tops your flight plan states rather than by observed flashes, and it is labelled **DEPICTED**. A flash rate appears only where lightning was actually counted.

### A volcano shows a colour code but no ash cloud

Those are two different facts. The aviation colour code describes the volcano's state; whether there is an ash cloud is a separate question the advisory answers separately. An advisory centre will often report a volcano at ORANGE while stating the ash is not identifiable on satellite, or forecasting none.

Aerolog draws the cloud only where one was observed or forecast. Where a message's own text and the advisory centre disagree, the detail card shows you both.

### A card says "source unavailable"

That is the app telling you the truth. Weather, NOTAM, pilot-report and forecast-wind providers each distinguish a genuinely empty result from a source it could not reach. A feed that is down reports itself as down, so it never reads as clear skies or no NOTAMs.

Check your connection and refresh. If the source is out, the card stays honest until it returns.

### The text is too small (or too large)

Your device text-size setting scales Aerolog's own type, not just system controls. Set it in iOS Settings → Display & Brightness → Text Size, or per-app under Accessibility. Aerolog also has its own Font Size control in Settings.

Scaling is clamped so that dense operational surfaces stay legible rather than clipping figures — the two settings compound, so if you already run a large system size, a smaller in-app size may read better.

### Importing my logbook from another app

Aerolog EFB accepts CSV exports from:

- ForeFlight Logbook
- LogTen Pro
- MCC Pilot Log
- eCrew

Tap **Logbook → Import CSV** and select the file. Column mapping is automatic for these four sources.

### Subscription management

Aerolog EFB Premium comes in two plans, each with a **7-day free trial**:

- **Monthly** — $9.99/month USD
- **Yearly** — $99.99/year USD, about 17% less than twelve monthly payments

Both sit in the same subscription group, so you can switch between them in iOS Settings → Apple ID → Subscriptions. Apple applies an upgrade straight away and a downgrade at your next renewal date.

To **manage or cancel** your subscription:

1. Open the iOS Settings app.
2. Tap your name at the top.
3. Tap **Subscriptions**.
4. Select **Aerolog EFB** to manage or cancel.

To **restore a previous purchase** on a new device:

1. Open Aerolog EFB.
2. Go to the **Subscription** tab.
3. Tap **Restore Purchase**.

Make sure you're signed in with the same Apple ID that made the original purchase.

### Refunds

App Store refunds are handled by Apple, not by Aerolog EFB. Request a refund at <https://reportaproblem.apple.com/>.

## Important

Aerolog EFB is a **reference and planning tool**. It is **NOT certified for primary navigation, dispatch, or operational use**. Always cross-check all data against your company's official OFP, dispatch documentation, and authoritative aviation sources (FAA, EASA, NOTAM offices, METAR/TAF providers, airline operations).

## Privacy

We do not collect, store, or transmit any personal data. See the full [Privacy Policy](./PRIVACY_POLICY.md).
