Krux Android app is intended for learning about Krux and Bitcoin air-gapped transactions.
Vulnerabilities inherent in Android phones such as the OS, other apps and wireless connectivity make using any phone insecure. Krux app should NOT be used to manage savings or important keys and mnemonics. For that, a dedicated device is recommended.

## Versions
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

