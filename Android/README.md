## Krux Modile App Dedicated Repository
Krux Mobile App is now hosted in
github.com/selfcustody/KruxMobileApp


## Old Versions log

Krux_25.01.beta12_Android_0.3
- Refactors from betas 8->12

Krux_25.01.beta8_Android_0.2
- Experimental Taproot Miniscript support

Krux_25.01.beta2_Android_0.1
- Experimental Miniscript support

Krux_24.11.1_Android_0.1
- Security bugfix - Properly use AES-CBC IV

Krux_24.11.0_Android_0.1
- Update features from 242.11.0
- Base64 Passwords (with copy to clipboard function for Android only)
- Japanese Translation

Krux_24.10_BETA_4_Android_0.1
- Read incomplete words mnemonics QR code

Krux_24.09_BETA_14_Android_0.9
- Translations code refactored
- Bugfix: QR codes started with "playoff" would be detected as pMofN

Krux_24.09_BETA_10_Android_0.8
- Font adjustments

Krux_24.09_BETA_10_Android_0.7
- Reviewed Simplified Chinese translation
- App is closed when screensaver is activated

Krux_24.09_BETA_7_Android_0.6
- Mnemonic Editor
- Double Mnemonic (new from camera)

Krux_24.09_BETA_6_Android_0.5
- Add Chinese translation (auto)

Krux_24.09_BETA_6_Android_0.4
- Add Korean translation
- Refactor in capture entropy from images
- Refactor in QR scanning status bars

Krux_24.09_BETA_5_Android_0.3
- Bugfix from last version on import/export Tiny Seed

Krux_24.09_BETA_5_Android_0.2
- bugfix: Sign messages with ":" character

Krux_24.09_BETA_3_Android_0.1
- Code refactor
- Faster QR processing
- Minor UI refactor

Krux_24.04_BETA_32_Android_0.17
- Wallet Sans Key (adresses from descriptor tool, no keys needed)

Krux_24.04_BETA_31_Android_0.16
- Code refactoring

Krux_24.04_BETA_31_Android_0.15
- Add BBQr support

Krux_24.04_BETA_31_Android_0.14
- Beta 31 Updates:
- Legacy and Nested Segwit support
- Experimental BBQr support
- High fee warnings

Krux_24.04_BETA_27_Android_0.12
- Beta 27 Udates: Taproot single-sig, path mismatch detection

Krux_24.04_BETA_25_Android_0.11
- Bugfix: module import error on descriptor parsing

Krux_24.04_BETA_25_Android_0.10
- Beta 25 Updates (Wallet customizations, status bar)

Krux_24.04_BETA_16_Android_0.9
- Bugfix on storing settings with multiple entries.
- Beta16 code refactors, rounded edges.

Krux_24.04_BETA_15_Android_0.8
- Entropy indicators, internal optimizations

Krux_24.04_BETA_9_Android_0.6
- Settings bugfix. Last version settings were completely messed, sorry!

Krux_24.04_BETA_9_Android_0.5
- Faster processing for animated QR codes

Krux_24.04_BETA_8_Android_0.4
- Bug fixes from pbkdf2 settings and for QR code and addresses UI
- BETA_8 UI improvements

Krux_24.04_BETA_5_Android_0.3
- Small UI changes

Krux_24.04_BETA_2_Android_0.2
- Sign Sparrow messages

Krux_24.04_BETA_2_Android_0.1
- IRQ based interface updates
- Change font to support more languages
- Test themes - Green, Pink

Krux_23.08_BETA_18_Android_0.15
- Bugfix: Fail to scan plaintext QR codes starting with letter "p"

Krux_23.08_BETA_15_Android_0.14
- Better touch press response when in animated QRs
- Refactoring and updates from main code

Krux_23.07_BETA_12_Android_0.13
- Bugfix on Nunchuk wallet import
- Small UI changes
- Update from main code base

Krux_23.04_BETA_10_Android_0.12
- Dutch language
- Code refactoring

Krux_23.04_BETA_9_Android_0.11
- Ask before leave encrypted mnemonic and generic QR codes
- Stored mnemonic don't require key to be deleted
- Code refactoring

Krux_23.04_BETA_8_Android_0.10
- Color themes (Dark-classic, Light, Orange)

Krux_23.04_BETA_6_Android_0.9
-  Allow QR codes as Encryption keys
- Transcript helpers for encrypted QR codes
- Transcript helpers for custom (keys, passphrases)  QR codes

Krux_23.04_BETA_5_Android_0.8
- Encrypted mnemonic QR codes

Krux_23.04_BETA_5_Android_0.7
- Colored Keypad fixed keys, they also will always be at bottom right
- Code refactoring

Krux_23.04 BETA_4 Android v0.6
- WARNING: Encrypted mnemonic seeds stored on previous versions should be deleted before update, or wipe the app before reinstall.
- From now on stored mnemonics should persist on app on updates
- Stored mnemonics version control
- Stored mnemonics configurations (AES mode and PBKDF2 iterations count)
- Capture camera's entropy for mnemonic creation
- Capture camera's entropy for AES-CBC encryption initial vector creation

Krux_23.04 BETA_3 Android v0.5
- WARNING: Seeds stored on previous versions WILL BE LOST! Expect this until we settle encryption method.
- Pbkdf2_hmac for encryption key derivation
- Dynamic font sizes to fit more screen sizes and resolutions
- Compatibility for armeabi-v7a devices (tested on a $34 Androi v6.0 phone)

23.04 BETA_1 Android v0.4
- Bugfix - Would always load last saved seed

23.04 BETA_1 Android v0.3
- WARNING: Seeds stored on previous version WILL BE LOST!
- Encryption key keypad fix
- Stored seeds will persist on updates from now on

23.04 BETA_1 Android v0.2
- Encrypted seed storage

23.04 BETA_1 Android v0.1
- Settings will persist

0.13
- Create/Scan QR passphrases

0.12
- Show receive addresses 

0.11
- SeedQR zoomed regions
- Commits from @jeff and @tadeubas pre-release

0.10
- SeedQR regions mode

0.9
- Code cleanup

0.8
- Amigo's touch gestures: Swipe keypads, menus, grid helper
- Grid helper for SeedQR (swipe to toggle)

0.7
- Improved/fixed QR decoding on Android
- Exceptions on screen
- SeedQR export

0.6
- Style standardization

0.5
- GUI alignment, monospace font

0.4 
- Fix animated QR crash
- Stackbit 1248 word confirmation

