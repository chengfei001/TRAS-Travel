# TARS Travel Support

TARS Travel is designed for communication during international travel. It currently supports Simplified Chinese, English, and Bahasa Melayu.

## Current Release

The current release is free, with no ads, subscriptions, in-app purchases, or paid unlocks.

## Frequently Asked Questions

### Can I translate without internet?

Yes, for text translation after you download the local model (about 1.28 GB) while online. Before a flight, before obtaining a local SIM, or before visiting a remote area, complete the download and run the local-model test once.

### Is voice input always offline?

No. Voice input uses Apple Speech and requests on-device recognition first. Fully offline recognition depends on the iPhone, iOS version, language, and installed Apple speech resources. Apple may process speech online when necessary. This release does not include a downloadable offline speech-recognition model.

### What is the difference between online and offline translation?

- Online translation sends the text to the compatible provider you configure.
- Offline translation processes text on your device and does not send it to an online translation service.
- Automatic mode can try the installed local model when the online service is unavailable.

### Why download a model?

The model enables text translation without internet. The App tries ModelScope first and Hugging Face as a fallback, then verifies the file before installation. You can pause, resume, remove, or download it again in Settings.

### What if online translation is unavailable?

Check your connection, API Base URL, Model Name, and API key. The App does not include a production API key. If the local model is installed, switch to Always Offline.

### What if voice input returns no result?

Confirm microphone and speech-recognition permissions, select the correct language, and speak clearly near the phone. Noise, low volume, or missing system language resources can affect recognition.

### Can I rely on a translation for an emergency, medical, or legal decision?

Machine translation can be wrong. For emergencies or matters involving health, allergies, law, finance, or personal safety, confirm the meaning with a local professional or trusted person.

## Contact Support

Email: **chengfei001@gmail.com**

Include the iPhone model, iOS and App versions, online or offline mode, reproduction steps, and error text. Do not send API keys, passwords, or other sensitive information.

Privacy policy: [TARS Travel Privacy Policy](privacy-policy.en.md)  
Last updated: July 26, 2026
