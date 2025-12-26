# App Store Submission Validator

This agent helps you pre-validate your iOS app against Apple's App Store Review Guidelines. It acts as a strict reviewer to help you catch issues that would lead to a rejection before you submit.

## Capabilities

- **Guidelines Check**: Fetches and applies the latest App Store Review Guidelines.
- **Privacy Manifest Analysis**: Verifies your `PrivacyInfo.xcprivacy` against your code's API usage.
- **Metadata Review**: Critiques your App Store description, keywords, and screenshots.
- **Technical Audit**: Checks `Info.plist`, Entitlements, and build settings for common errors.

## Usage

1. Open `app-store-validator.md`.
2. Scroll to the bottom to the **Project Specific Context** section.
3. Replace the placeholder text with details about your specific app (e.g., "This is a fitness tracking app using HealthKit and CoreLocation...").
4. Copy the entire file content.
5. Paste it into your LLM chat (Cursor, Claude, ChatGPT, etc.) while your project is open.
6. Ask the agent: *"Please check my project for App Store submission readiness."*
