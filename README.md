# PickupKaro Privacy Policy

Last updated: 25th Oct 2025

This Privacy Policy describes how PickupKaro ("Company", "we", "our", or "us") collects, uses, discloses, and protects information when you use our mobile application and related services (collectively, the "Service"). By using the Service, you agree to the collection and use of information in accordance with this Policy.

## Information We Collect

- **Account Information**
  - Name, email, phone number, address, profile photo, and user ID collected during registration and profile updates.

- **Authentication and Device Identifiers**
  - Access tokens and refresh tokens (stored on-device), device identifiers used for security, fraud prevention, and session management.

- **Location Information**
  - Foreground device location (latitude/longitude, accuracy, speed, timestamp) to find nearby captains, display pickup/destination, track rides in real time, and improve maps. Reverse geocoding requests are sent to Google Maps APIs to obtain addresses from coordinates.

- **Ride Information**
  - Ride creation details, pickup/drop locations and addresses, ride status, assigned captain details, fare estimates, ride completion including OTP verification, and ride history.

- **Favorites and Search**
  - User-saved favorite locations and search inputs to improve convenience.

- **Notifications**
  - Firebase Cloud Messaging (FCM) token to deliver push notifications (e.g., driver selection, ride status). Local notification interactions (e.g., accept/reject actions) may be processed to update ride state.

- **Usage and Log Data**
  - Basic app event logs, request metadata, and error reports to diagnose issues and improve functionality.

## How We Use Your Information

- **Provide and Operate the Service**
  - Account creation, authentication, session management, matching with nearby captains, estimating fares, completing rides (including OTP flow), and showing maps/addresses.

- **Communications**
  - Sending transactional notifications (ride status, driver assignment) and service-related messages (security or policy updates).

- **Safety, Security, and Support**
  - Detecting, preventing, and responding to fraud, abuse, and safety incidents; troubleshooting and improving performance.

- **Legal and Compliance**
  - Complying with applicable laws and enforcing our Terms and policies.

## Legal Basis for Processing

Where required by law, we process your information based on:
- **Contractual necessity** to provide the Service you request.
- **Legitimate interests** in safety, security, and service improvement.
- **Consent** for permissions such as notifications and location access.
- **Legal obligations** where applicable.

## Sharing and Disclosure

We share your information only as described below:

- **Service Providers**
  - Cloud hosting, analytics, customer support, notification delivery, and mapping/geocoding providers who process data on our behalf under confidentiality obligations.

- **Drivers/Captains**
  - Limited ride-related details necessary to facilitate a ride (e.g., pickup/drop locations, relevant contact/name details, and identifiers).

- **Third‑Party APIs and SDKs**
  - Google Maps Platform (maps, geocoding) and Firebase Cloud Messaging (notifications). See Third‑Party Services below.

- **Legal and Safety**
  - When required by law, legal process, or to protect rights, safety, or property.

- **Business Transfers**
  - In connection with a merger, acquisition, or asset sale, subject to this Policy.

We do not sell your personal information.

## Third‑Party Services

- **Google Maps Platform**
  - Used for maps and geocoding. Data sent may include location coordinates and addresses.
  - Policy: https://policies.google.com/privacy

- **Firebase Cloud Messaging**
  - Used to deliver push notifications. Data sent may include FCM tokens and notification metadata.
  - Policy: https://firebase.google.com/support/privacy

Please review their privacy policies for details on their processing.

## Permissions We Request and Why

- **Location (ACCESS_FINE_LOCATION, ACCESS_COARSE_LOCATION)**
  - To find nearby captains, display pickup/destination, and track rides in real time. Requested at runtime.

- **Notifications (POST_NOTIFICATIONS on Android 13+)**
  - To inform you about driver selection, ride updates, and important alerts. Requested at runtime for supported Android versions.

- **Internet (INTERNET)**
  - To communicate securely with our backend (e.g., https://api.pickupkaro.in) and third‑party services such as Google Maps.

- **Vibrate (VIBRATE)**
  - To add vibration feedback for critical notifications.

- **Receive Boot Completed (RECEIVE_BOOT_COMPLETED)**
  - To ensure notification channels and required services are restored after reboot, if needed.

## Data Retention

We retain account, ride, and location records for as long as your account is active or as needed to provide the Service, comply with legal obligations, resolve disputes, and enforce agreements. If you delete your account or request deletion, we will delete or anonymize your personal information, subject to legal retention requirements.

## Data Security

We use industry‑standard security measures, including HTTPS/TLS in transit, token‑based authentication, and access controls. No method of transmission or storage is 100% secure; we work continuously to protect your information.

## Your Rights and Choices

- **Access, Update, Delete**
  - Access and update your profile in‑app. Request deletion of your account and associated data via the Contact section below.

- **Permissions**
  - Grant or revoke location and notification permissions via device settings; some features may not function without these permissions.

- **Communications**
  - Control notifications via in‑app options (where available) and device settings.

## Children’s Privacy

The Service is not directed to children under 13 (or as defined by local law). We do not knowingly collect personal information from children. If you believe a child has provided us data, contact us to request deletion.

## International Data Transfers

Your information may be transferred to and processed on servers located outside your country. We take steps to ensure appropriate safeguards are in place consistent with applicable law.

## Changes to This Privacy Policy

We may update this Policy from time to time. We will notify you of material changes by updating the "Last updated" date, in‑app notices, or other appropriate means. Continued use of the Service after changes means you accept the updated Policy.

## Contact Us

- Email: mayankpatidarpk@gmail.com
- Address: PicKupKaro, 16, Bagdipura, Dhamnod, Madhya Pradesh, India, 454552

---

This Policy reflects the app’s current permissions, data flows, and third‑party services, including foreground location collection, notifications via FCM, communication with https://api.pickupkaro.in, and Google Maps geocoding.
