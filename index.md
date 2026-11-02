# Personal Restic Backup

Personal Restic Backup is a private application used to store encrypted backups of my own computer files in my Google Drive account.

## How It Works

The application uses Restic and Rclone to create and manage encrypted backups.

- Restic encrypts backup data locally before uploading it.
- Rclone connects to Google Drive using OAuth authorization.
- Google Drive access is restricted to files created or managed by the application.
- The application is intended for personal use only.

## Privacy

The application does not sell or share personal information.

Backup contents are encrypted before upload. Google OAuth credentials are stored locally on the user's computer and are not published on this website.

See the [Privacy Policy](privacy.md) for additional information.

## Contact

For questions about this application, contact the application administrator through the support email displayed on Google's OAuth consent screen.
