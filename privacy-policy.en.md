# TARS Travel Privacy Policy

Effective date: July 18, 2026  
Last updated: July 18, 2026

TARS Travel (the “App”) respects your privacy. This policy explains how information is handled when the App provides travel translation, voice input, speech playback, and offline model features.

## 1. Free Use and Business Model

**The current version of the App is completely free. It contains no advertising, subscriptions, or in-app purchases, and we do not sell personal information.**

The App does not require registration or login and does not provide a user account system.

## 2. Information We Process

### 2.1 Voice and Microphone

The App requests microphone permission only when you choose to use voice input.

- Audio is recorded on your device.
- Whisper speech recognition runs on your device.
- Temporary audio files are deleted after recognition finishes, is cancelled, or fails.
- Audio recordings are not uploaded to our servers or sent to the online translation service.

If you use online translation after speech has been converted to text, the transcribed text is handled as described under “Online Translation” below.

### 2.2 Offline Translation

When offline mode is used, the text and translation results are processed on your device. The App does not send this content to the internet.

### 2.3 Online Translation

When you choose online translation, or when Automatic mode actually calls an online service, the App sends the following necessary information over an encrypted network connection:

- The text you entered or obtained through on-device speech recognition;
- The selected language or automatic language detection information;
- Instructions and model parameters required to produce the translation.

The current release is planned to use a Tencent Cloud DeepSeek online model service. The online service endpoint and model configuration may change with an App version or your settings. The App developer does not operate a separate translation server and does not separately retrieve or build a translation history from the online translation service.

The online service provider may process an IP address, request time, and standard device or network information required to provide and secure the service, subject to its own terms and privacy practices. Avoid entering sensitive information that does not need to be translated, such as government identification numbers, payment card details, passwords, API keys, or detailed medical records.

### 2.4 API Keys and App Settings

If you configure an API key in the App:

- The API key is stored locally in the iOS Keychain;
- Except for sending it as authentication to the online service you configure, we do not read, upload, or share the complete API key;
- You can remove the API key in the App's settings.

The online service endpoint, model name, translation mode, and related preferences are stored locally on your device.

### 2.5 Offline Model Downloads

Offline translation and speech recognition models are downloaded only when you request them. The App may currently connect to Hugging Face to download model files. The download service may receive an IP address, request time, User-Agent, and similar standard technical information needed to complete the network request.

Downloaded models are stored in the App's local storage and can be deleted in the App's settings.

### 2.6 Speech Playback

Speech playback uses iOS system speech synthesis. The App does not send translation text to a server operated by us for speech playback. System voices and voice resources are handled by iOS and your system settings.

## 3. Features We Do Not Use

The current version does not include:

- Advertising or advertising identifiers;
- Third-party behavioral analytics or user-tracking SDKs;
- User registration, login, or cloud synchronization;
- Subscriptions, in-app purchases, or payments;
- Access to precise location, contacts, photos, Health data, or fitness data.

If a future version changes these practices, we will update this policy and, where applicable, the App Store privacy disclosures and permission descriptions before or when the change is released.

## 4. Retention and Deletion

- Temporary audio: deleted after speech recognition finishes, is cancelled, or fails.
- Translation content: the current version does not store it on a server operated by the developer; offline content is processed locally during use.
- API key: stored in the iOS Keychain until you remove it in the App's settings or clear it through an applicable system method.
- App settings and model files: stored on your device until you change the settings, delete the models, or clear the App's data.
- Third-party services: online translation and model download providers may retain necessary service logs under their own policies. The developer does not directly control their retention periods.

## 5. Your Choices and Rights

You can:

- Deny or revoke microphone permission in iPhone Settings;
- Choose offline mode to avoid sending text to an online translation service;
- Remove your API key in the App's settings;
- Delete downloaded offline models;
- Delete the App to clear its removable local data;
- Contact us using the email below with privacy questions.

The current version has no user accounts and no cloud user-profile database operated by the developer, so there is generally no developer-held account profile to access, export, or delete.

## 6. Security

We use safeguards appropriate to the current features, including the iOS Keychain for API keys, system permission controls for microphone access, and HTTPS connections to online services. No technical method can guarantee absolute security, so do not enter highly sensitive information unless necessary.

## 7. Children's Privacy

The App is a general travel tool and is not specifically designed for children. We do not intentionally ask children to create accounts or submit profiles. A parent or guardian who believes a child sent personal information to a third-party online service through the App may contact us to discuss available steps.

## 8. Third-Party Services

Some App features may involve:

- Tencent Cloud online model services, which process necessary text requests only when online translation is used;
- Hugging Face, which is used to download offline model files on request;
- Apple iOS system services, which provide permission management, Keychain, audio recording, and system speech synthesis.

These services have their own terms and privacy policies. Before using an online feature, decide whether the text is appropriate to provide to the relevant service.

## 9. Changes to This Policy

If this policy changes materially, we will update the “Last updated” date and, when appropriate, notify users through an App update or the App Store product page.

## 10. Contact Us

For questions about this policy or TARS Travel's privacy practices, contact:

**chengfei001@gmail.com**

Support page: [TARS Travel Support](support.en.md)
