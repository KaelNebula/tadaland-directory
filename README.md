# Tadaland encrypted partnership directory

https://kaelnebula.github.io/tadaland-directory/

The current website requires the shared password. The directory, application and downloads are encrypted with AES-256-GCM; the browser derives the key with PBKDF2-SHA256, 600,000 iterations and a random salt. The password is not stored in this repository. Refresh or Lock directory clears the unlocked page. Shortlists remain browser-local.

This is shared-password encryption for a static website, not individual server-side accounts. It cannot revoke earlier public copies or prevent an authorised viewer from sharing downloaded data. Earlier commits contained the public-source snapshot before password protection; private workflow notes were never published.

The decrypted snapshot retains source attribution, dates, suppressed-record exclusions and contact uncertainty. No analytics or outreach is used.
