# REAPER privacy notice

This notice applies to the REAPER 0.4.6 public preview by MadReaper16.

## Data on your PC

REAPER keeps its library database on your PC. It can contain settings, scan folders, game titles and launch paths, collections, favorites, and local activity history. A library carried over from another build can also contain previously imported Steam titles or catalog matches. You can turn off local play-session tracking or clear local activity in Settings.

Support drafts are kept on this PC. Contact drafts save as you type. Problem-report drafts save when you choose **Save Draft**. You can discard either draft. Portable backups contain the local library and settings, including any saved scan folders, launch paths, and local activity. REAPER writes exports to the location you choose and creates a local safety backup before replacing your library during a restore. Portable backups exclude credentials and support drafts.

## Connections outside REAPER

- **Storefronts.** Discovery reads local installation information. When you open a game through a storefront, REAPER passes the launch target to the installed client. That client handles its own sign-in, updates, and network activity.
- **Account lookups and artwork.** This preview uses placeholder covers and has Steam account lookups, Steam stats, and IGDB search disabled. If an earlier REAPER build saved Steam credentials, they may remain in Windows Credential Manager until you choose **Forget Steam credentials**.
- **Installation and updates.** If Windows WebView2 is missing, the installer can download the runtime bootstrapper from Microsoft. REAPER updates are downloaded manually. [Microsoft WebView2 distribution](https://learn.microsoft.com/en-us/microsoft-edge/webview2/concepts/distribution)
- **Support.** You can review, copy, save, or open an email draft for a message or report. You choose whether to include the REAPER version and Windows build number. Your email service handles the message if you send it, and MadReaper16 receives it. If you post a public issue, anyone may be able to read what you share. Leave credentials and private paths out of support submissions.

REAPER does not run analytics or require a REAPER account for the local launcher. External providers apply their own privacy terms. Questions about REAPER’s handling of data can go to madreaper016@gmail.com.
