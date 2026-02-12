# Connor Cursor Rules — iOS

Shared [Cursor](https://cursor.com) project rules for iOS/Swift/SwiftUI. Use them in your own projects so the AI follows consistent style, structure, and patterns.

## How to import

**Recommended (stays in sync):**

1. Open **Cursor Settings → Rules, Commands**
2. Click **+ Add Rule** next to Project Rules, then **Remote Rule (Github)**
3. Paste this repo’s URL: `https://github.com/connorcates/connor-cursor-rules-ios.git`

Cursor will pull and sync the rules; updates to the repo are reflected in your project.

**Alternative (one-time copy):**

Clone the repo and copy the rules into your project:

```bash
git clone https://github.com/connorcates/connor-cursor-rules-ios.git
mkdir -p /path/to/your/project/.cursor/rules
cp -r connor-cursor-rules-ios/.cursor/rules/* /path/to/your/project/.cursor/rules/
```

## Rules included

| Rule | Description |
|------|-------------|
| `connor-accessibility.mdc` | Accessibility (VoiceOver, Dynamic Type, UI tests) for iOS projects |
| `connor-async-concurrency.mdc` | Async/await and concurrency patterns for iOS projects |
| `connor-error-handling.mdc` | Error handling and user-facing errors for iOS projects |
| `connor-localization.mdc` | Localization and user-facing strings for iOS projects |
| `connor-logging.mdc` | Logging and diagnostics for iOS projects |
| `connor-privacy-security.mdc` | Privacy and security (secrets, keychain, PII) for iOS projects |
| `connor-style-documentation.mdc` | Swift/SwiftUI documentation style for iOS projects |
| `connor-style-structure.mdc` | Swift/SwiftUI file structure and organization for iOS projects |
| `connor-style-swift-patterns.mdc` | Swift/SwiftUI code and dependency patterns for iOS projects |
| `connor-swiftui-views.mdc` | SwiftUI view composition and layout for iOS projects |
| `connor-testing.mdc` | Swift test naming and structure for iOS projects |

Rules apply when relevant files are open: most use `**/*.swift`; the testing rule uses `**/*Tests*.swift`. None are set to always apply.

## License

MIT — see [LICENSE](LICENSE).
