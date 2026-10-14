---
permalink: /privacy/
---

# Sudarshan Pump Backup — Privacy Policy

**Last updated: 15 October 2026**

### 1. Overview

Sudarshan Pump Backup is a private backup utility used by Sudarshan Trading Co. to securely store and recover database backups using the authorized owner's Google Drive account.

The utility is intended for internal business use and is not offered as a public service.

### 2. Google Drive Access

The utility uses Google OAuth authorization to connect to Google Drive through Rclone.

The current authorization grants broad Google Drive access. The intended operation is limited to the designated database backup folders, although the OAuth permission itself is not restricted to those folders.

### 3. Information Accessed and Stored

The utility may access backup files, folder metadata, and Google Drive information required to upload, verify, retrieve, and manage database backups.

Database backups may contain business transactions, accounting records, employee information, and authentication-related data.

### 4. How Information Is Used

Google Drive access is used to:

- Upload database backups.
- Verify backup integrity.
- Retrieve backups for restoration.
- Manage backup retention when configured.

Google Drive information is not used for advertising or marketing.

### 5. Data Security

New database backups are intended to be encrypted before upload using Rclone Crypt.

OAuth credentials and encryption settings are stored in protected configurations. When scheduled backups are enabled, approved automation infrastructure may temporarily process backup data.

### 6. Data Retention and Deletion

Backup files are retained in the designated Google Drive account until deleted by the owner or by explicitly configured retention automation.

The owner can revoke Google Drive access through Google Account security settings and delete stored backup files.

### 7. Data Sharing

The utility does not sell Google user data or share it with advertisers. Google Drive acts as the storage provider, and authorized infrastructure providers may process data as necessary to perform backup operations.

### 8. Changes to This Policy

This policy may be updated when the utility's functionality, permissions, or data-handling practices change.

### 9. Contact

For questions, contact the repository owner through [GitHub](https://github.com/agrawalkunal2).
