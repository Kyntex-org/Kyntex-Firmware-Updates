# Firmware update feeds

This directory preserves the existing signed firmware images and the two compatibility feeds. Each manifest retains its existing version, digest, compatibility requirements and release notes; only the package repository location changes.

Do not replace the legacy manifest with the profile-capable manifest. Existing clients require their corresponding feed.

A valid signature and matching digest do not establish physical-device validation. No new firmware is built, signed or released by this migration.
