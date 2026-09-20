# GlycoLess — Legal & Privacy

Official legal and privacy documentation for the **GlycoLess Android application** by **Sensora Labs**.

---

## Documents

| Document | Link |
|---|---|
| Privacy Policy | [Privacy Policy](privacy-policy.html) |
| Terms & Conditions | [Terms & Conditions](terms-and-conditions.html) |
| Data Safety | [Data Safety](data-safety.html) |
| Account Deletion | [Account Deletion](account-deletion.html) |

---

## Live Website

After GitHub Pages is enabled:

**https://sensoralabs.github.io/glycoless-legal/**

### Direct URLs

- Privacy Policy  
  https://sensoralabs.github.io/glycoless-legal/privacy-policy.html

- Terms & Conditions  
  https://sensoralabs.github.io/glycoless-legal/terms-and-conditions.html

- Data Safety  
  https://sensoralabs.github.io/glycoless-legal/data-safety.html

- Account Deletion  
  https://sensoralabs.github.io/glycoless-legal/account-deletion.html

---

## About GlycoLess

GlycoLess is an Android application designed to help users:

- Track daily sugar intake
- Log food and nutrition information
- Monitor personal progress
- Understand sugar and nutrition concepts
- Use supported barcode/product lookup features
- Access premium features where available

GlycoLess is developed by **Sensora Labs**.

---

## Data Architecture

GlycoLess is designed around a local-first approach.

### Guest Mode

Guest users can use supported tracking features without creating a normal cloud account.

Guest tracking data is intended to remain local to the user's device.

### Signed-in Users

Authenticated users may use local storage together with cloud synchronization for supported application data.

Cloud data is intended to be scoped to the authenticated user's account.

### Premium

Premium functionality may depend on Google Play purchase or subscription entitlement.

Payment processing is handled through the applicable Google Play billing system.

---

## Third-Party Services

Depending on the production build and enabled features, GlycoLess may use services such as:

- Firebase / Google services
- Google Play Billing
- Open Food Facts
- Advertising services
- Analytics or crash-reporting services

The exact services and data practices must match the production Android build.

---

## Data Safety Notice

The information published on this website is intended to provide a plain-language explanation of GlycoLess data practices.

The **Google Play Console Data Safety declaration is authoritative for Google Play submission** and must be completed according to the exact production Android AAB, including all enabled SDKs, permissions, services and data flows.

Before publishing a production release, the legal documentation and Play Console declarations should be reviewed against the actual application implementation.

---

## Account Deletion

Registered GlycoLess users can request account deletion.

Preferred path inside the application:

```text
Profile
→ Settings
→ Data & Privacy
→ Delete Account
