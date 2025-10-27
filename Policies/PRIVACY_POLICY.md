# Privacy Policy for Wise SMS

**Last Updated:** October 27, 2025

**Effective Date:** October 27, 2025

## Introduction

Wise SMS ("we," "our," or "the App") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our Android messaging application. Please read this privacy policy carefully. If you do not agree with the terms of this privacy policy, please do not use the application.

## App Overview

Wise SMS is a messaging application that provides SMS/MMS functionality with enhanced features including AI assistance, translation services, theme customization, and parental controls.

## Information We Collect

### 1. Messages and Communications

**What We Collect:**
- SMS and MMS messages (text content, timestamps, delivery status)
- Message metadata (read receipts, reactions, thread information)
- Message attachments (photos, videos, audio files)

**How We Use It:**
- To send, receive, and display messages
- To provide conversation threading and organization
- To enable message search and filtering
- To display message delivery and read status

**Storage:** All messages are stored locally on your device in an encrypted SQLite database. We do not transmit your message content to our servers.

### 2. Contacts Information

**What We Collect:**
- Contact names, phone numbers, and email addresses from your device
- Contact photos and avatars
- Custom contact tags and notes you create within the app

**How We Use It:**
- To display contact information in conversations
- To enable contact search and selection when composing messages
- To synchronize with your device's contact database
- To provide contact-based features like conversation organization

**Storage:** Contact data is stored locally on your device. We access your device contacts through Android's Contacts API but do not transmit this information to external servers.

### 3. Location Information

**What We Collect:**
- Precise location (GPS coordinates) when you use location sharing features
- Approximate location for map-based features
- Background location when explicitly enabled for specific features

**How We Use It:**
- To share your location in messages when you choose to do so
- To display location information on maps within conversations
- To provide location-based features you explicitly enable

**Third-Party Services:** Location data shared in messages uses Google Maps API. When you share location, Google's privacy policy applies to map display and geocoding services.

**Control:** Location access is always optional and requires explicit permission. You can revoke location permissions at any time through your device settings.

### 4. Camera and Media

**What We Collect:**
- Photos and videos you capture using the in-app camera
- Images and media files you select from your device gallery
- Audio recordings for voice messages (if enabled)

**How We Use It:**
- To include photos and videos in MMS messages (with parental controls)
- To create custom themes from images
- To enable voice messaging features
- To support media attachments in conversations

**Storage:** Media files are stored locally on your device. When sent in messages, they are transmitted directly through your carrier's MMS service.

**Privacy-First Processing - NO IMAGES SENT TO SERVERS:**
- **All image analysis happens on your device** - no external servers involved
- **NSFW content detection** runs entirely locally using on-device AI models
- **For incoming media:** Automatic NSFW detection on received images
- **For outgoing media:** Parents can enable NSFW checks before sending (optional)
- **Sending Gate:** If NSFW check is enabled and fails, the image cannot be sent via MMS
- **Theme extraction:** Color palette extraction from images is performed locally
- **Zero server uploads:** No images are ever uploaded to our servers or third-party services for analysis

**Parental Controls for Photo Sharing:**
- Photo/video sharing is **OFF by default** for child accounts
- Parents must knowingly enable photo sharing through Carer Controls
- Parents can enable optional NSFW checks on outgoing images before sending
- Parents can disable photo sharing at any time
- All controls are managed by the parent/guardian, not the child

### 5. Google Services Integration

#### Google Maps
- **Purpose:** Display location information and enable location sharing in messages
- **Data Shared:** Location coordinates when you explicitly share your location
- **Privacy Policy:** [Google Maps Privacy Policy](https://policies.google.com/privacy)

#### Google Translate API
- **Purpose:** Translate messages between different languages
- **Data Shared:** Message text you choose to translate (sent to Google's servers)
- **Privacy Policy:** [Google Cloud Privacy Policy](https://cloud.google.com/terms/cloud-privacy-notice)

#### Google Gemini AI
- **Purpose:** Provide regional style transfer and creative language transformation
- **Data Shared:** Message text you choose to transform (sent to Google's servers)
- **Privacy Policy:** [Google AI Privacy Policy](https://ai.google/responsibility/principles/)

**Important:** Translation and style transfer features require sending message text to Google's servers. These features are entirely optional and require explicit user action.

**Note:** Cloud backup features are not currently implemented in this version.

### 6. AI Assistant and Conversation Tracking

**Optional Cloud AI Feature:**
- When you use the AI Assistant feature, messages are sent to Google Gemini
- AI usage is tracked for daily limit enforcement
- This feature is entirely optional and requires explicit user action

**Local Processing:**
- Conversation tracking and analytics run locally on your device
- **NSFW content detection** uses local AI models running entirely on your device
  - Checks received images automatically
  - Can check outgoing images (if parent enables this feature)
  - **NO images are ever sent to external servers for analysis**
  - All processing happens locally before any image is sent via MMS

**Data Retention:** All conversation tracking data is stored locally and never transmitted to our servers. You can clear this data at any time through the app settings.

### 7. Device Information

**What We Collect:**
- Device model and Android version
- App version and build information
- Network connectivity status
- Screen size and display density

**How We Use It:**
- To ensure compatibility and optimal performance
- To provide appropriate UI layouts for your device
- To troubleshoot technical issues
- To determine network availability for features that require connectivity

**Storage:** This information is used within the app and is not transmitted to external servers except as part of standard Google Play Services functionality.

### 8. Premium Features and Billing

**What We Collect:**
- Google Play purchase tokens and transaction IDs
- License activation and validation timestamps
- Feature usage statistics for premium features
- Device fingerprint (for license portability, not restriction)

**How We Use It:**
- To validate premium feature access
- To enable license portability across your devices
- To prevent unauthorized feature access
- To provide customer support for billing issues

**Third-Party Processing:** All payment processing is handled by Google Play Billing. We do not collect or store credit card information.

**Data Shared with Google:** Transaction verification data is shared with Google Play for license validation.

### 9. Theme Customization (Local Only)

**What We Collect:**
- Custom theme configurations you create
- Theme metadata (name, colors, creation date)
- Theme preferences and settings

**How We Use It:**
- To provide personalized app appearance
- To save and apply your custom themes
- To enable theme customization features

**Storage:** All theme data is stored locally on your device. Theme sharing features are not currently implemented in this version.

### 10. Notifications

**What We Collect:**
- Notification preferences and settings
- Badge count data for unread messages
- Notification interaction history (local only)

**How We Use It:**
- To display message notifications
- To show unread message counts on the app icon
- To provide customizable notification sounds and vibrations

**Storage:** Notification data is stored locally on your device.

## How We Use Your Information

### Primary Uses
1. **Core Messaging Functionality:** To send, receive, and display SMS/MMS messages
2. **Contact Management:** To organize and display your conversations with contacts
3. **Feature Enhancement:** To provide optional features like translation, AI assistance, and theme customization
4. **App Improvement:** To identify and fix bugs, improve performance, and enhance user experience

### Local Processing
The vast majority of data processing occurs entirely on your device:
- Message storage and retrieval
- Contact synchronization
- **NSFW content detection** (for both received and outgoing media)
  - All image analysis happens on your device
  - No images ever sent to external servers
  - Protects children from inappropriate content
  - Optional pre-send checks for outgoing images
- Conversation tracking and analytics
- Theme customization and color extraction

### Cloud Processing (Optional)
Only when you explicitly use these features:
- Message translation (Google Translate)
- Style transfer (Google Gemini)
- Cloud AI Assistant (Google Gemini)
- Location sharing (Google Maps)

## Data Sharing and Disclosure

### We DO NOT:
- Sell your personal information to third parties
- Share your messages with advertisers
- Transmit your message content to our servers
- **Upload photos or images to our servers or third-party services**
- **Send images to external servers for analysis (all NSFW detection is on-device)**
- Share your contacts with third parties
- Use your data for advertising purposes
- Track your location without explicit permission

### We DO Share Data With:

#### 1. Your Mobile Carrier
- SMS/MMS message content and metadata are transmitted through your carrier's network
- Your carrier's privacy policy and terms of service apply to this data transmission
- We have no control over how carriers process or store this data

#### 2. Google Services (When You Use Optional Features)
- **Google Maps:** Location coordinates when you share your location
- **Google Translate:** Message text when you use translation features
- **Google Gemini AI:** Message text when you use AI assistant or style transfer features
- **Google Play:** Billing and license validation data for premium features

#### 3. Legal Requirements
We may disclose your information if required to do so by law or in response to:
- Valid legal processes (subpoenas, court orders)
- Requests from law enforcement
- Protection of our rights and safety
- Compliance with applicable laws and regulations

**Note:** Since messages are stored only on your device and transmitted through your carrier, we do not have access to your message content and cannot provide it to third parties.

### We DO NOT Share Data With:
- Advertising networks
- Data brokers
- Social media platforms
- Analytics companies (beyond standard Google Play Services)
- Marketing companies
- Any other third parties not explicitly mentioned above

## Data Security

### Encryption and Protection
- **Local Database:** All data stored on your device is protected by SQLCipher encryption with AES-256
- **Encryption Keys:** Device-specific encryption keys stored securely in Android KeyStore
- **Secure Storage:** Sensitive settings and API keys are stored using Android's Secure Storage
- **In-Transit:** Communications with Google services use TLS/SSL encryption
- **File Provider:** Secure file sharing using Android's FileProvider architecture

### Security Measures
- HMAC-based verification for premium license validation
- Signature-only permissions for internal broadcast receivers
- Network security configuration for secure API communications
- Regular security updates and patches

### Limitations
While we implement strong security measures for local data storage, please note:
- Your device's security depends on your screen lock and device settings
- We cannot guarantee security of data in transit through your carrier's network
- Third-party services (Google) have their own security measures and policies

## Data Retention

### Local Data
- **Messages:** Stored on your device (soft-deleted when removed, see Deletion Methods below)
- **Contacts:** Synchronized with your device contacts; removed when you delete them from your device
- **Media:** Stored on your device (soft-deleted when removed)
- **Settings:** Retained until you uninstall the app or clear app data
- **Conversation Tracking:** Stored locally; can be cleared through app settings
- **Themes:** Stored locally (soft-deleted when removed)

### Deletion Methods

**Important: Understanding Data Deletion**

The app uses a **soft-delete system** for normal deletion operations:

**When you delete messages or conversations within the app:**
- Items are marked as deleted and hidden from view
- Data remains in the encrypted database (not immediately purged)
- This allows for potential recovery features and system integrity
- Deleted items are not displayed in the app interface

**To permanently remove all data from your device:**
- **Clear Cache/Data:** Android Settings > Apps > Wise SMS > Storage > Clear Cache and Clear Data
- **Uninstall:** Uninstalling the application removes all local data permanently
- These methods completely erase all information from the encrypted database

**Why Soft Delete?**
- Maintains database integrity and referential relationships
- Allows for system recovery and troubleshooting
- Prevents corruption of conversation threads
- Data remains encrypted and inaccessible through the app interface

**Data Protection:**
- Even "soft-deleted" data remains encrypted in the local database
- Deleted items cannot be viewed or accessed through the app
- Only accessible through direct database inspection with proper tools
- Completely removed when you clear app data or uninstall

## Children's Privacy

**Wise SMS is specifically designed for children and families, including children under the age of 13.**

The app is intended to be a safe, supervised messaging environment for children to communicate with family members and approved contacts under parental supervision.

### Parental Control and Supervision

**Parent/Guardian Role:**
- Parents or guardians set up and configure the app on their child's device
- All personal information is entered by the parent/guardian, not the child
- Parents control all privacy settings and permissions
- Parents designate approved contacts (typically family members)
- Children cannot independently modify privacy settings or add contacts without parental approval

**How Information Is Collected:**
- **Parent-Provided Data:** Parents/guardians enter contact information, configure settings, and set up the child's account
- **Child's Use:** Children use the app to send/receive messages only with parent-approved contacts
- **No Independent Registration:** Children cannot sign up for the app independently - it must be set up by a parent/guardian
- **Supervised Environment:** All app features are under parental control

### COPPA Compliance

We comply with the Children's Online Privacy Protection Act (COPPA):
- We do not collect personal information directly from children
- Parents provide all personal information and configuration
- Parents have full control over what data is accessible
- Parents can review and delete all data at any time through the app
- We do not share children's information with third parties for marketing purposes
- We do not display advertisements to children

### Parental Control Features

The app includes comprehensive parental control features:
- **Time Restrictions:** Parents can set when the app can be used
- **Contact Whitelisting:** Parents control who the child can message
- **Photo/Video Sharing Controls:**
  - Photo sharing is **OFF by default** - parent must enable it
  - Parents can completely disable photo/video sharing
  - Parents can enable optional NSFW checks on outgoing images
  - All image analysis runs locally on device (never sent to servers)
- **Content Filtering:**
  - Automatic NSFW detection for received media (runs locally on device)
  - Optional NSFW checks for outgoing media before sending
  - Failed checks prevent image from being sent
- **Message Monitoring:** Parents can review message history
- **AI Assistant Limits:** Parents control if and when AI features are accessible
- **Location Controls:** Parents control location sharing capabilities

### Parental Rights

Parents and guardians have the right to:
- **Review:** Access all data collected about their child through the app interface
- **Delete:** Permanently remove all child data at any time
- **Control:** Manage all privacy settings and permissions
- **Revoke:** Uninstall the app and remove all data
- **Contact Us:** Request information about data practices

### Data Minimization for Children

For child users specifically:
- Only essential contact information (provided by parents)
- Messages stored locally on the child's device
- Photos/videos processed entirely on-device (never uploaded to servers)
- NSFW detection runs locally to protect children (no server uploads)
- Photo sharing OFF by default (parent must enable)
- No online profiles or social features
- No data sharing with third parties (except parent-approved messaging)
- No behavioral tracking or advertising
- No collection of data for marketing purposes

If you have questions about how we handle children's information, please contact us using the information provided at the end of this policy.

## Your Rights and Choices

### Access and Control
You (or parents/guardians for child users) have the right to:
- **Access:** View all data stored by the app through its interface
- **Modify:** Edit or delete messages, contacts, and settings at any time
- **Delete:** Permanently remove all app data by clearing app data or uninstalling

### Permission Management
You can manage permissions at any time through Android Settings:
- **Revoke Permissions:** Settings > Apps > Wise SMS > Permissions
- **Location Controls:** Choose "While using the app" or "Deny" for location access
- **Notification Controls:** Customize notification settings through the app or system settings
- **Storage Controls:** Manage storage permissions for camera and gallery access

### Opt-Out Options
- **AI Features:** Don't use the AI Assistant or disable it in settings (parents can disable for children)
- **Translation:** Don't use the translation feature; no data is sent if you don't use it
- **Location Sharing:** Don't use the location sharing feature (parents control for children)
- **Google Services:** Opt out of optional Google service features

### Advertising
We do not display advertisements, so there are no advertising IDs or tracking for advertising purposes.

## International Data Transfers

### Data Location
- **Local Data:** Stored on your device (location depends on your physical location)
- **Cloud Services:** Data sent to Google services may be processed in various countries where Google operates data centers

### Google Services
When you use optional features that rely on Google services (Maps, Translate, Gemini, Firebase, Drive), your data may be transferred to and processed in countries outside your own. Google complies with applicable data protection laws including GDPR for European users.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in:
- App features and functionality
- Legal requirements
- Privacy practices

**Notification of Changes:**
- The "Last Updated" date at the top of this policy will be updated
- Significant changes will be announced within the app
- Continued use of the app after changes constitutes acceptance of the new policy

**Version History:** Previous versions of this policy are available upon request.

## Third-Party Services and Links

### Third-Party Privacy Policies
This app integrates with several third-party services. Each service has its own privacy policy:

- **Google Maps:** https://policies.google.com/privacy
- **Google Translate:** https://cloud.google.com/terms/cloud-privacy-notice
- **Google Gemini AI:** https://ai.google/responsibility/principles/
- **Google Play Services:** https://policies.google.com/privacy

**Your Responsibility:** We encourage you to review the privacy policies of these third-party services to understand how they collect, use, and share your data.

### No Control Over Third Parties
We are not responsible for the privacy practices of:
- Your mobile carrier
- Google and its services
- Other apps on your device
- Websites linked from messages

## Compliance and Legal Framework

### Android Permissions
We request only the permissions necessary for app functionality:
- **SMS Permissions:** Required for core messaging features
- **Contacts:** Optional; required only if you want contact integration
- **Camera:** Optional; required only if you want to capture photos in the app
- **Storage:** Optional; required only for accessing gallery images
- **Location:** Optional; required only for location sharing features
- **Notifications:** Optional; recommended for message alerts

### Google Play Policy Compliance
This app complies with:
- Google Play Developer Program Policies
- Google Play's User Data Policy
- Android's permissions best practices
- Appropriate use of sensitive permissions

### Data Protection Laws
We are committed to complying with applicable data protection laws including:
- GDPR (General Data Protection Regulation) for European users
- CCPA (California Consumer Privacy Act) for California users
- Other applicable regional privacy laws

### User Rights Under GDPR (European Users)
If you are located in the European Economic Area (EEA), you have the following rights:
- **Right to Access:** Request a copy of your personal data
- **Right to Rectification:** Request correction of inaccurate data
- **Right to Erasure:** Request deletion of your personal data
- **Right to Restriction:** Request restriction of processing
- **Right to Data Portability:** Request transfer of your data
- **Right to Object:** Object to processing of your personal data
- **Right to Withdraw Consent:** Withdraw consent at any time

To exercise these rights, please contact us using the information provided below.

## Contact Us

If you have questions or concerns about this Privacy Policy or our data practices, please contact us:

**Developer Contact:**
- **App Name:** Wise SMS
- **Contact Method:** info@xeduportal.com
- **Support:** Available through Google Play Store listing

**Response Time:** We will respond to privacy-related inquiries within 30 days.

**Data Protection Officer:** For privacy matters, contact us at the email address above.

## Additional Information

### California Privacy Rights (CCPA)
California residents have additional rights under the California Consumer Privacy Act:
- Right to know what personal information is collected
- Right to know whether personal information is sold or disclosed
- Right to say no to the sale of personal information (We do not sell personal information)
- Right to access personal information
- Right to equal service and price

### Do Not Track
Our app does not track users across third-party websites or apps and therefore does not respond to Do Not Track (DNT) signals.

### Automated Decision Making
We do not use automated decision-making or profiling that produces legal effects or similarly significant effects on users.

### Data Minimization
We practice data minimization by:
- Collecting only data necessary for app functionality
- Processing most data locally on your device
- Using cloud services only for optional features you explicitly enable
- Not collecting data for advertising or analytics beyond basic app functionality

## Consent

By using Wise SMS, you consent to:
- This Privacy Policy
- Our collection and use of information as described
- Data processing by third-party services when you use optional features
- Transmission of messages through your mobile carrier

You can withdraw consent at any time by:
- Revoking app permissions through Android settings
- Disabling optional features within the app
- Uninstalling the application

---

## Summary for Google Play Store

**Privacy Summary:**
Wise SMS is a privacy-focused messaging app that stores all message data locally on your device. We do not transmit your messages to our servers. Optional features like translation, AI assistance, and location sharing use Google services with your explicit consent. We do not sell your data or use it for advertising. Your carrier handles SMS/MMS transmission according to their privacy policy.

**Data Safety:**
- **Collected:** Messages (local only), Contacts (local only), Location (optional), Photos (optional)
- **Shared:** Only with Google services when you use optional features (translation, AI, maps)
- **Security:** Local encryption, secure storage, TLS for cloud communications
- **Deletion:** Full control - delete data anytime through app settings or uninstall

---

**Last Updated:** October 27, 2025

This privacy policy is effective immediately for all users of Wise SMS.

