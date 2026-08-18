# Privacy Policy for OmniBox Notes

**Effective Date**: August 6, 2026

OmniBox Notes ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how your information is handled when you use the OmniBox Notes Android application.

## 1. Information Collection and Use
OmniBox Notes is designed with a privacy-first architecture:
- **Local Device Storage**: All notes, text clips, and attached images are stored locally on your device in a private SQLite database (`note_database`) and internal storage (`context.filesDir/note_images/`).
- **No Third-Party Analytics or Ad Tracking**: OmniBox Notes does not collect, send, sell, or monetize any user content or usage analytics to external advertising or tracking services.

## 2. Google Drive Data Sync
If you choose to sign in with your Google Account within OmniBox Notes:
- **Scope Used**: We request access strictly to the `https://www.googleapis.com/auth/drive.appdata` scope.
- **Private App Folder Access**: This scope allows OmniBox Notes to read and write backup data (`notes_backup.json`) strictly within your private, hidden Google Drive App Data folder (`appDataFolder`).
- **Data Protection**: We cannot access your main Google Drive files, documents, photos, or any data outside of the OmniBox private folder.

## 3. Permissions Requested
- **Internet / Network Access**: Required solely for Google Sign-In and syncing your encrypted backup payload directly to your personal Google Drive account.
- **Photo Picker / Storage**: OmniBox uses Android's native system Photo Picker to allow you to attach images to notes without requesting invasive storage permissions.

## 4. Children's Privacy
OmniBox Notes does not knowingly collect personal information from children.

## 5. Contact Us
If you have any questions or feedback regarding this Privacy Policy, please contact us at support@omnibox.app.
