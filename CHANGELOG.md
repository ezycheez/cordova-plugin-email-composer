## ChangeLog
#### Version 0.8.1 (not yet released)
- Make use Cordovas NSData+Base64 extension.
- Log error message if attachment path does not exist.

#### Version 0.8.0 (02.03.2014)
- [enhancement:] New `absolute://` and `relative://` attachment prefixes.
- [feature:] New `base64://` prefix to attach base64 encoded data streams.

#### Version 0.7.2 (01.03.2014)
- [enhancement:] Attachments are added with their real name.

#### Version 0.7.1 (17.12.2013)
- [bugfix:] Only the last attachment was added to the email composer on android.

#### Version 0.7.0 (05.12.2013)
- Release under the Apache 2.0 license.
- [***change:***] Removed the `callback` property from the `open` interface.
- [***change:***] Renamed the properties `recipients`, `ccRecipients`, `bccRecipients`.
- [bugfix:] Plugin under WP8 throws an error, if recipients were given as arrays.
- [enhancement:] `open` does not block the ui thread on iOS & Android anymore.

#### Version 0.6.0 (17.11.2013)
- Added WP8 support
- [***deprecated:***] The `callback` property will be removed with v0.7.0.

#### Version 0.4.2 (17.11.2013)
- [feature:] Added alias `openDraft` to the `open` interface.

#### Version 0.4.1 (03.11.2013)
- [bugfix]: On Android, the `isServiceAvailable()` interface has returned string values instead of boolean values.
- [bugfix]: Sometimes the device said that no email app is available because of the missing mime type.

#### Version 0.4.0 (20.08.2013)
- Added Android support<br>
  *Based on the EmailComposerWithAttachments Android plugin made by* ***guidosabatini***

#### Version 0.2.1 (15.08.2013)
- [bugfix]: Email was not send in HTML format, if the `isHtml` flag was set.
- [bugfix]: `email.open()` without a parameter throw an error.

#### Version 0.2.0 (13.08.2013)
- Added iOS support<br>
  *Based on the EmailComposer(WithAttachments) iOS plugin made by* ***Randy McMillan*** *and* ***guidosabatini***