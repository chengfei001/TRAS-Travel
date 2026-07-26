# TARS Travel Privacy Policy

Effective date: July 26, 2026  
Last updated: July 26, 2026

TARS Travel (the “App”) respects your privacy. This policy explains how information is handled when the App provides travel text translation, voice input, speech playback, and a local translation model.

## 1. Overview

The App is currently free, with no ads, subscriptions, or in-app purchases. It does not require an account and does not provide cloud sync.

## 2. Information Handling

### 2.1 Voice and Microphone

The App requests microphone access only when you choose voice input. Audio is recorded on your device and provided to Apple Speech. The App requests on-device recognition first; fully offline recognition depends on the iPhone, iOS version, language, and installed Apple speech resources. Apple may process speech online when on-device recognition is unavailable.

Temporary recordings are deleted after recognition finishes, is cancelled, or fails. They are not sent to your configured translation provider. Recognized text is sent to that provider only if you then request online translation.

### 2.2 Offline Translation

After you download and install the local translation model, text and results are processed on your device and are not sent to an online translation service. The model is about 1.28 GB and can be deleted in Settings.

### 2.3 Online Translation

When you request online translation, or Automatic mode calls an online service, the App sends the text, language information, and necessary model parameters over HTTPS to the compatible service you configure.

The developer does not embed a production API key and does not operate an account or translation-history server. Your provider may process an IP address, request time, and necessary service logs under its own terms. Avoid entering passwords, API keys, identity or payment details, or detailed medical information unless translation is necessary.

### 2.4 API Keys, Settings, and Local Content

- Your API key is stored in the iOS Keychain and used only to authenticate with your configured provider. You can remove it in Settings.
- Service settings, translation mode, interface preferences, and reminder state are stored on your device.
- Conversation history, saved items, and phrases are stored locally and can be deleted in the App. Deleting the App removes its removable local data.
- Final Keychain removal behavior is also governed by iOS Keychain lifecycle rules.

### 2.5 Model Downloads

The local model is downloaded only after you choose to do so. The App tries ModelScope first and Hugging Face as a fallback. These services may receive standard request information such as an IP address, request time, and User-Agent. The model is SHA-256 verified, stored locally, and removable in Settings.

### 2.6 Speech Playback

Playback uses iPhone system voices. The App does not send playback text to a developer-operated server. Offline playback depends on whether the relevant system voice is installed.

## 3. Features Not Used

The current version has no advertising identifiers, behavioral analytics or tracking SDKs, user accounts, cloud sync, subscriptions, or in-app purchases. It does not access precise location, contacts, photos, Health data, or fitness data.

## 4. Retention and Deletion

- Temporary recordings are deleted after recognition finishes, is cancelled, or fails.
- Conversation history, saved items, phrases, settings, and models remain locally until you delete them in the App or delete the App.
- The API key remains in Keychain until you clear it in the App or through an applicable system method.
- Online translation, Apple Speech, and model-download providers may process or retain necessary logs under their own policies.

## 5. Your Choices

You can revoke microphone access, use offline mode, delete conversations and saved items, clear the API key, remove the model, or delete the App. Because the developer operates no account database, there is generally no developer-held cloud profile to access, export, or delete.

## 6. Security and Translation Notice

The App uses system permissions, iOS Keychain, HTTPS, and model verification. No measure guarantees absolute security. Machine translation can contain errors; for emergencies or matters involving health, allergies, law, finance, or personal safety, confirm the meaning with a local professional or trusted person.

## 7. Children’s Privacy

The App is a general travel utility and is not specifically designed for children. It does not ask children to create accounts or profiles.

## 8. Updates and Contact

If these practices change, we will update this page and applicable App Store privacy disclosures.

Privacy questions: **chengfei001@gmail.com**  
Support: [TARS Travel Support](support.en.md)
