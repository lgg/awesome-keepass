# Awesome KeePass Projects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

KeePass is a password manager ecosystem built around encrypted local database files. This list curates clients, libraries, plugins, tools, security research, and documentation for KeePass-compatible projects.

## Contents

- [Clients](#clients)
  - [Cross-platform Clients](#cross-platform-clients)
  - [Windows Clients](#windows-clients)
  - [macOS Clients](#macos-clients)
  - [Web Clients](#web-clients)
  - [iOS Clients](#ios-clients)
  - [Android Clients](#android-clients)
  - [Browser Extensions](#browser-extensions)
  - [Other Clients](#other-clients)
- [API Libraries](#api-libraries)
- [Plugins](#plugins)
- [Tools](#tools)
- [Security](#security)
- [Docs and Articles](#docs-and-articles)
  - [Docs and Articles RU](#docs-and-articles-ru)

## Clients

### Cross-platform Clients

- [KeePass](https://sourceforge.net/projects/keepass/) - Official KeePass client. ([source](https://github.com/dlech/KeePass2.x))
- [KeePassXC](https://keepassxc.org/) - Cross-platform community fork of KeePass. ([source](https://github.com/keepassxreboot/keepassxc))
- [KeeWeb](https://keeweb.info/) - Free cross-platform password manager compatible with KeePass. ([source](https://github.com/keeweb/keeweb))
- [AuthPass](https://github.com/authpass/authpass) - Password manager based on Flutter for all platforms with KeePass 2.x compatibility.
- [KeePass Electron](https://github.com/IlyaPomaskin/KeePass-electron) - Desktop HTML5 client for KeePass 2 databases.
- [OneKeePass](https://github.com/OneKeePass/desktop) - Secure password manager for macOS, Linux, and Windows.

### Windows Clients

- [KeePass](https://keepass.info/download.html) - Official Windows desktop client.
- [ModernKeePass](https://github.com/wismna/ModernKeePass) - KDBX password manager for the Windows Store.
- [KeePass4D](https://github.com/evpobr/KeePass4D) - KeePass password manager written in Delphi with KDBX format support.

### macOS Clients

- [MacPass](https://macpassapp.org/) - Native macOS KeePass client. ([source](https://github.com/MacPass/MacPass/))
- [KeePassium](https://keepassium.com/) - Open-source commercial password manager for macOS with a free tier. ([source](https://github.com/keepassium/KeePassium))
- [Strongbox](https://strongboxsafe.com/) - Source-available commercial password manager for macOS with a free tier. ([source](https://github.com/strongbox-password-safe/Strongbox))
- [KyPass Companion](http://www.kyuran.be/software/kypass4mac/) - Closed-source native KeePass-compatible client for macOS database formats 1 and 2.

### Web Clients

- [KeeWeb](https://github.com/keeweb/keeweb) - Free cross-platform password manager compatible with KeePass.
- [keepass4web-rs](https://github.com/lixmal/keepass4web-rs) - Rust rewrite of keepass4web.
- [BrowsePass](https://bitbucket.org/namn/browsepass/overview) - Web application for reading KDBX files.
- [keepass-node](https://github.com/gesellix/keepass-node) - KeePass 2 editor for Node.js with a browser frontend.
- [Kee Vault](https://github.com/kee-org/keevault) - Web browser password manager that encrypts databases with the KeePass storage format before synchronization.

### iOS Clients

- [Strongbox](https://apps.apple.com/app/strongbox-keepass-pwsafe/id897283731) - Source-available commercial password manager for iOS with a free tier.
- [KeePassium](https://apps.apple.com/app/keepassium-keepass-passwords/id1435127111) - Open-source commercial password manager for iOS with a free tier.
- [KyPass 4](http://www.kyuran.be/software/kypass/) - Closed-source password manager for iPhone and iPad.
- [KeePass Touch](https://apps.apple.com/ru/app/keepass-touch/id966759076) - KeePass-compatible password manager for iPhone and iPad.

### Android Clients

- [Keepass2Android](https://play.google.com/store/apps/details?id=keepass2android.keepass2android) - Password manager app for Android. ([source](https://github.com/PhilippC/keepass2android))
- [KeePassDroid](https://play.google.com/store/apps/details?id=com.android.keepass) - KeePass implementation for Android. ([source](https://github.com/bpellin/keepassdroid))
- [KeePassDX](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.free) - KeePass password manager for Android. ([source](https://github.com/Kunzisoft/KeePassDX))
- [TinyKeePass](https://github.com/sorz/TinyKeePass) - Simple read-only KeePass Android app written in Java and Kotlin.
- [KeePassVault](https://play.google.com/store/apps/details?id=com.ivanovsky.passnotes) - KeePass password manager for Android. ([source](https://github.com/aivanovski/keepassvault))

### Browser Extensions

- [Kee](https://github.com/kee-org/browser-addon) - Browser add-on for linking Firefox and Chrome to Kee Vault or KeePass.
- [KeePassXC-Browser](https://github.com/keepassxreboot/keepassxc-browser) - Browser extension for using KeePassXC with Chrome and Firefox.
- [keepass-chrome](https://github.com/btd/keepass-chrome) - Proof-of-concept extension for loading KDBX files and managing passwords.
- [passifox](https://github.com/pfn/passifox) - Browser extension for filling forms from KeePass through KeePassHTTP.

### Other Clients

- [kpcli](http://kpcli.sourceforge.net/) - Command-line interface for KeePass 1.x and 2.x database files.
- [WinPass](https://github.com/gkardava/WinPass) - KeePass password manager client for Windows Mobile.
- [KeePassTouch](https://github.com/DannyGB/KeePassTouch) - Ubuntu Touch version of KeePass.
- [passhole](https://github.com/Evidlo/passhole) - Command-line password manager inspired by pass.
- [keepmenu](https://github.com/firecat53/keepmenu) - Dmenu, Rofi, and Wofi-style frontend for auto-type and managing KeePass databases.
- [Pastilda](https://www.crowdsupply.com/third-pin/pastilda) - Open-source hardware password manager that works with KeePass 2.x databases and emulates a USB keyboard. ([source](https://bitbucket.org/thirdpin_team/pastilda))
- [kdbxviewer](https://luelista.net/kdbxviewer/) - Command-line tool for viewing KeePass 2 database files. ([source](https://github.com/luelista/kdbxviewer))

## API Libraries

- [pykeepass](https://github.com/libkeepass/pykeepass) - Python library for interacting with KeePass databases with KDBX3 and KDBX4 support.
- [kdbxweb](https://github.com/keeweb/kdbxweb) - High-performance TypeScript library for reading and writing KeePass 2 databases in Node.js and browsers.
- [keepass-rs](https://github.com/sseemayer/keepass-rs) - Rust library for reading KeePass database files.
- [keepass.io](https://github.com/snapserv/keepass.io) - Node.js library for reading and writing KeePass databases.
- [KeePassKit](https://github.com/MacPass/KeePassKit) - Objective-C framework for loading, storing, and manipulating KeePass databases.
- [KeePassJava2](https://github.com/jorabin/KeePassJava2) - Java API for reading and writing KeePass 2.x databases and reading KeePass 1.x databases.
- [openkeepass](https://github.com/cternes/openkeepass) - Java library for reading and writing KeePass 2.x database files.
- [kotpass](https://github.com/Anvell/kotpass) - Kotlin library for reading and writing KDBX 3.x and 4.x files.

## Plugins

- [KeeAnywhere](https://github.com/Kyrodan/KeeAnywhere) - KeePass plugin that provides access to cloud storage providers.
- [KeePassHTTP](https://github.com/pfn/keepasshttp) - KeePass plugin for securely exposing password entries over HTTP.
- [Keebuntu](https://github.com/dlech/Keebuntu) - KeePass 2.x plugins for Linux desktop integration.
- [KeeAgent](https://github.com/dlech/KeeAgent) - KeePass 2.x plugin that lets other programs access SSH keys stored in a KeePass database.
- [KeePassRPC](https://github.com/kee-org/keepassrpc) - KeePass plugin used by the Kee browser add-on to connect browsers to KeePass.
- [KeeTrayTOTP](https://github.com/KeeTrayTOTP/KeeTrayTOTP) - KeePass 2.x plugin for TOTP codes, including Steam TOTP support.
- [AdvancedConnectPlugin](https://github.com/aalbng/AdvancedConnectPlugin) - KeePass plugin for configuring application-specific direct connections.
- [SIC2KeePass](https://github.com/Alezy80/SIC2KeePass) - KeePass plugin for importing SafeInCloud databases directly or from exported XML.
- [QuickConnectPlugin](https://github.com/cristianst85/QuickConnectPlugin) - KeePass plugin for connecting to Windows, Linux, and ESXi hosts.
- [HIBP Offline Check](https://github.com/mihaifm/HIBPOfflineCheck) - KeePass plugin for checking passwords against Have I Been Pwned breach lists online or offline.
- [KPSimpleBackup](https://github.com/marvinweber/KPSimpleBackup) - KeePass plugin for backing up KDBX files with advanced options.
- [KeePassWinHello](https://github.com/sirAndros/KeePassWinHello) - KeePass 2 plugin for quick database unlock with Windows Hello biometrics.
- [FluentPassFinder](https://github.com/yusei36/FluentPassFinder) - KeePass plugin with a fluent design search window for finding entries and triggering autotype.
- [KeePassQuery](https://github.com/Mikescher/KeePassQuery) - KeePass plugin for querying databases with SQL expressions.

## Tools

- [pass import](https://github.com/roddhjav/pass-import) - Extension for pass that imports data from existing password managers.
- [KeePass2 to KeePassX Converter](https://github.com/dvorka/keepass2-to-keepassx) - Java tool for converting KeePass 2 databases to KeePassX databases.
- [enpass-to-keepass](https://github.com/jsphpl/enpass-to-keepass) - Tool for converting Enpass CSV exports for import into KeePass databases with KeePassXC.
- [ulauncher-keepassxc](https://github.com/pbkhrv/ulauncher-keepassxc) - Ulauncher extension for quickly searching a KeePassXC database.
- [git-credential-keepassxc](https://github.com/Frederick888/git-credential-keepassxc) - Git credential helper that uses KeePassXC as a credential store.
- [keepass-2-file](https://github.com/Dracks/keepass-2-file) - Command-line tool for generating plaintext config files from secrets stored in a KeePass database.
- [keepass-diff](https://github.com/Narigo/keepass-diff) - Command-line tool written in Rust for showing differences between two KeePass database files.
- [kp-diff](https://github.com/aivanovski/kp-diff) - Command-line tool written in Kotlin for showing differences between KeePass database files.
- [keepass-print](https://github.com/mojoaxel/keepass-print) - Command-line tool written in JavaScript for printing password lists for long-term backup.
- [secrets-dispatcher](https://github.com/nikicat/secrets-dispatcher) - Secret Service proxy that adds per-application approval and an audit log in front of any Secret Service keyring, including KeePassXC's, showing which apps read stored entries.

## Security

- [mod0keecrack](https://github.com/devio/mod0keecrack) - KeePass 2 database master-password cracker.
- [John the Ripper keepass2john](https://github.com/openwall/john/blob/bleeding-jumbo/src/keepass2john.c) - Tool for extracting KeePass database hashes for John the Ripper and Hashcat.
- [KeeFarce](https://github.com/denandz/KeeFarce) - Tool for extracting passwords from KeePass 2.x databases directly from memory.
- [KeeThief](https://github.com/GhostPack/KeeThief) - Tool for extracting KeePass 2.x key material from memory and enumerating KeePass trigger-system behavior.
- [KeePassHax](https://github.com/HoLLy-HaCKeR/KeePassHax) - Tool for extracting master passwords from KeePass 2.x databases directly from memory.

## Docs and Articles

- [KeePass Help Center](https://keepass.info/help/base/index.html) - Official KeePass documentation and tutorials.
- [KDBX 4](https://keepass.info/help/kb/kdbx_4.html) - Official documentation for the KDBX 4 file format.
- [Reverse Engineered KeePass (KDBX 3) File Format](https://max-weller.github.io/kdbx-viewer/kdbx_format.html) - Reverse-engineered documentation for the KDBX 3 file format. ([local copy](./doc/))
- [Reading a KeePass 2 file with Go](https://www.sysorchestra.com/2015/06/20/reading-a-keepass-file-from-go/) - Article about parsing KeePass 2 database files with Go.
- [KeePass file format explained](https://gist.github.com/lgg/e6ccc6e212d18dd2ecd8a8c116fb1e45) - Notes explaining the KeePass database file format.
- [KeePass v2.x (KDBX v3.x) file format](https://gist.github.com/msmuenchen/9318327) - Notes about the KeePass v2.x KDBX v3.x file format.
- [KeePassXC Specs](https://github.com/keepassxreboot/keepassxc-specs) - Schema and documentation for KeePassXC database handling.
- [KeePassJava2 Format Notes](https://github.com/jorabin/KeePassJava2#keepassjava2-and-keepass) - Schema and diagram for KeePassJava2 database handling.
- [KDBX V4 format](https://palant.info/2023/03/29/documenting-keepass-kdbx4-file-format/) - Detailed article documenting the KeePass KDBX 4 file format.
- [How difficult to crack KeePass master password?](https://security.stackexchange.com/questions/8476/how-difficult-to-crack-keepass-master-password) - Discussion of KeePass master password brute-force resistance.

### Docs and Articles RU

- [Настраиваем URL Overrides в Keepass2](https://habr.com/ru/articles/303894/) - Guide to KeePass 2 URL Overrides for SSH, RDP, VNC, and other connections.
- [Пример базы Keepass для сетевого администратора](https://habr.com/ru/articles/304680/) - Practical KeePass database structure and automation examples for network administrators.
