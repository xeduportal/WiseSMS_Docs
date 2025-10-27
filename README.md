# Wise SMS

**Privacy-First Family Messaging for Android**

Wise SMS is a secure, encrypted messaging application specifically designed for children and families, with comprehensive parental controls and a privacy-first architecture that keeps your family's conversations safe and local.

---

## 🛡️ Built for Families, Designed for Privacy

Unlike traditional messaging apps that mine your data or track your communications, Wise SMS prioritizes your family's privacy above all else. Every message is encrypted and stored locally on your device, and parents maintain complete control over their children's messaging experience.

### Why Families Choose Wise SMS

- 🔒 **COPPA Compliant** - Designed for children under 13 with full regulatory compliance
- 🔐 **Military-Grade Encryption** - SQLCipher AES-256 encryption for all local data
- 👪 **Full Parental Control** - Parents manage every aspect of their child's messaging
- 🖼️ **Image Privacy** - NO images ever uploaded to servers (100% on-device processing)
- 🚫 **No Ads or Tracking** - Zero advertising, zero behavioral tracking
- 📱 **Local-First** - Your messages stay on your device, always

---

## ✨ Key Features

### Core Messaging
- **SMS/MMS Messaging** - Full-featured text and multimedia messaging
- **Contact Management** - Organized conversations with your contacts
- **Media Sharing** - Share photos and videos (parent-controlled)
- **Message History** - Encrypted local storage of all conversations
- **Notifications** - Customizable message alerts

### Privacy & Security
- **SQLCipher Encryption** - AES-256 encryption for all local data
- **Device-Specific Keys** - Unique encryption keys stored in Android KeyStore
- **Local Storage Only** - Messages never sent to our servers
- **On-Device Processing** - All image analysis runs locally (no uploads)
- **Data Deletion** - Clear control over your data

### Parental Controls 👪

**Photo Sharing Control:**
- OFF by default for child accounts
- Parents must explicitly enable photo sharing
- Granular control over camera and gallery access

**Content Safety:**
- Automatic NSFW detection on received images (on-device only)
- Optional NSFW checks on outgoing images
- Images that fail checks cannot be sent
- All processing local - no server uploads

**Communication Control:**
- Contact whitelisting - parents approve messaging contacts
- Message monitoring - parents can review conversation history
- Time restrictions - set usage windows for children

**Feature Management:**
- AI assistant controls - parents enable/disable AI features
- Location sharing - parent-controlled for children
- Translation features - parent-controlled access
- Cloud features - opt-in only, parent-managed

### Optional Cloud Features (Parent-Controlled)

All cloud features are:
- ✅ Clearly disclosed
- ✅ Parent-controlled for children
- ✅ Opt-in only
- ✅ Can be disabled at any time

**Available Features:**
- **Google Maps Integration** - Share location in messages (parent-controlled)
- **Google Translate** - Translate messages to different languages
- **AI Assistant** - Google Gemini AI for writing help and style transfer
- **Google Play Billing** - Secure premium feature purchases

---

## 🔐 Privacy Architecture

### What Makes Wise SMS Different

**Traditional Messaging Apps:**
- ❌ Upload messages to cloud servers
- ❌ Upload images for processing
- ❌ Mine data for advertising
- ❌ Track user behavior
- ❌ Sell data to third parties

**Wise SMS:**
- ✅ All messages stored locally with encryption
- ✅ All image processing on-device (NEVER uploaded)
- ✅ No data mining or advertising
- ✅ No behavioral tracking
- ✅ Your data belongs to you

### Technical Security Details

**Encryption:**
- **Algorithm:** SQLCipher AES-256
- **Key Storage:** Android KeyStore (hardware-backed when available)
- **Key Generation:** Device-specific, SHA-256 derived
- **Scope:** All messages, contacts, media, and settings

**Data Storage:**
- **Location:** Local device storage only
- **Transmission:** Only via carrier network for SMS/MMS
- **Cloud Storage:** None (messages never uploaded)
- **Third-Party Access:** Zero (except explicitly enabled features)

**Image Privacy:**
- **Processing:** 100% on-device
- **Uploads:** Never (no images sent to servers)
- **NSFW Detection:** Local TensorFlow Lite model
- **Network Calls:** Zero for image analysis
- **Sharing:** Only via carrier MMS when parent enables

---

## 👪 For Parents

### Setting Up Wise SMS for Your Child

1. **Initial Setup**
   - Parents create and configure the app
   - Parents provide all contact information
   - Children cannot independently register

2. **Configure Controls**
   - Enable/disable photo sharing (OFF by default)
   - Set up contact whitelist
   - Configure time restrictions
   - Enable AI feature access if desired

3. **Ongoing Monitoring**
   - Review message history
   - Adjust controls as needed
   - Manage feature access
   - Monitor usage patterns

### Your Control, Your Choice

- **Photo Sharing:** Completely OFF by default. You decide if and when your child can share photos.
- **Content Safety:** Automatic NSFW detection protects your child from inappropriate content.
- **Communication:** Whitelist contacts to control who your child can message.
- **Privacy:** NO images are ever uploaded to our servers or third-party services.
- **Transparency:** Every feature is clearly explained, and you control everything.

### COPPA Compliance

Wise SMS is fully compliant with the Children's Online Privacy Protection Act (COPPA):
- ✅ Parents provide all personal information
- ✅ No data collected directly from children
- ✅ Verifiable parental consent built into setup
- ✅ Data minimization for children's accounts
- ✅ No advertising or tracking of children
- ✅ Clear privacy policy and data practices

---

## 🎯 Use Cases

### For Families
- Safe communication between parents and children
- Monitored messaging for young teens
- Emergency contact capabilities
- Family coordination and planning

### For Children
- Learn responsible digital communication
- Stay connected with family safely
- Age-appropriate feature access
- Build digital literacy with guardrails

### For Parents
- Peace of mind with comprehensive controls
- Visibility into children's communications
- Gradual independence as children mature
- Privacy-preserving family messaging

---

## 📱 Requirements

- **Platform:** Android 7.0 (API 24) or higher
- **Storage:** Minimum 100MB free space
- **Permissions:**
  - SMS (required for core functionality)
  - Contacts (optional - for contact integration)
  - Camera (optional - requires parent to enable photo sharing)
  - Storage (optional - requires parent to enable photo sharing)
  - Location (optional - parent-controlled)
  - Notifications (optional - recommended)

---

## 🔒 Privacy Policy

We take your family's privacy seriously. Our comprehensive privacy policy explains:
- What data we collect (and what we don't)
- How data is stored and protected
- Your rights and controls
- Third-party service disclosures
- Children's privacy protections (COPPA)

**View our full privacy policy:** [Privacy Policy](Privacy/PRIVACY_POLICY.md)

### Quick Privacy Facts

- ✅ Messages stored locally with AES-256 encryption
- ✅ NO images uploaded to servers (all processing on-device)
- ✅ NO data mining or advertising
- ✅ NO behavioral tracking of children
- ✅ Parents provide all personal information
- ✅ Photo sharing OFF by default
- ✅ Optional cloud features clearly disclosed
- ✅ Complete data deletion available

---

## 🚀 Getting Started

### Installation

Wise SMS is available on the Google Play Store:

**[Download from Google Play Store](#)** *(Link to be added upon publication)*

### First Time Setup

1. **Download and Install** - Get Wise SMS from the Google Play Store
2. **Grant SMS Permissions** - Required for core messaging functionality
3. **Configure Parental Controls** (if setting up for a child)
   - Set photo sharing preferences (OFF by default)
   - Configure contact whitelist
   - Set time restrictions if desired
4. **Optional Permissions** - Grant camera, storage, location as needed
5. **Start Messaging** - Send your first secure, encrypted message

### Tips for Parents

- Review the parental controls before giving device to child
- Test photo sharing controls to understand how they work
- Set up contact whitelist to control communication
- Review the privacy policy to understand data handling
- Enable optional features only as needed

---

## 🛠️ Support

### Need Help?

- **Privacy Questions:** [Your Email]
- **Technical Support:** [Your Email]
- **COPPA Inquiries:** Include "COPPA" in subject line
- **Parental Control Help:** We're here to help you configure controls

**Response Time:** We typically respond within 24-48 hours.

### Frequently Asked Questions

**Q: Are images really never uploaded to servers?**  
A: Correct. ALL image processing (including NSFW detection) happens entirely on your device. No images are ever uploaded to our servers or third-party services. Images are only sent via carrier MMS when photo sharing is enabled and the image passes on-device checks.

**Q: What does "photo sharing OFF by default" mean?**  
A: For child accounts, the ability to take photos or select images from the gallery is completely disabled by default. Parents must explicitly enable photo sharing in settings before children can share any images.

**Q: How is encryption implemented?**  
A: We use SQLCipher with AES-256 encryption for the local database. Encryption keys are device-specific, generated using SHA-256, and stored securely in Android KeyStore (hardware-backed when available).

**Q: Can I review my child's messages?**  
A: Yes. Parents can review message history for child accounts through the parental controls interface.

**Q: How do I permanently delete data?**  
A: In-app deletion uses soft-delete (messages are hidden but remain encrypted). For permanent deletion, go to Android Settings > Apps > Wise SMS > Storage > Clear Data, or uninstall the app.

**Q: What data is shared with Google services?**  
A: Only when you explicitly use optional features:
- Location data when you share location (Google Maps)
- Message text when you translate (Google Translate)
- Message text when you use AI assistant (Google Gemini)
- Purchase data (Google Play Billing)
- NO images are ever shared

**Q: Is Wise SMS COPPA compliant?**  
A: Yes. We are fully compliant with COPPA. Parents provide all personal information, no data is collected directly from children, and we have comprehensive parental controls in place.

---

## 🌟 What Makes Wise SMS Unique

### Privacy-First Design
Most messaging apps upload your data to the cloud for processing, storage, or advertising. Wise SMS keeps everything on your device with military-grade encryption.

### Image Privacy Innovation
We're one of the only messaging apps that performs ALL image processing on-device. No images are ever uploaded to servers, providing unprecedented privacy for family photos.

### True Parental Control
Beyond simple content filters, we provide comprehensive controls that let parents manage every aspect of their child's messaging experience - from who they can contact to what features they can use.

### COPPA Compliance
Built from the ground up to comply with children's privacy laws, ensuring your family's data is protected according to the strictest standards.

### No Hidden Agendas
No advertising network. No data mining. No selling your information. We make money through optional premium features, not by exploiting your data.

---

## 📊 Technical Specifications

### Architecture
- **Framework:** Ionic React (TypeScript)
- **Platform:** Capacitor for Android
- **Database:** SQLite with SQLCipher encryption
- **Encryption:** AES-256 via SQLCipher
- **Storage:** Android KeyStore for keys
- **UI:** Ionic Framework components

### Security Features
- Local AES-256 encryption
- Device-specific encryption keys
- Secure key storage (Android KeyStore)
- TLS/SSL for cloud communications
- On-device NSFW detection (TensorFlow Lite)
