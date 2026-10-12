# Qinglong Panel Pro Privacy Policy

Updated: October 12, 2026
Effective: October 10, 2026

Qinglong Panel Pro ("the app") is provided by the developer Shibo Zhang ("we"). The app is a client tool that connects to and manages a Qinglong panel you deploy yourself. We take the protection of your personal information seriously; please read this policy before using the app.

## 1. We do not collect your personal information

- The app has no servers of its own and no account registration, and never asks for your phone number, email or other identity information.
- The app does not collect or upload any personal information, device identifiers, usage statistics or behavior data, and performs no analytics or ad tracking of any kind.
- The app contains no third-party SDKs (no analytics, advertising, push or crash-reporting SDKs).

## 2. Information stored on your device

The following stays on your device only and is never sent to us or any third party:

- Servers you add: name, panel address, sign-in method, username or Client ID, kept in the app's private storage.
- Credentials: the sign-in password, the Client Secret and the access token returned by the panel, encrypted with the system Asset Store Kit and readable only by this app. If you untick "Remember username and password" when signing in, the username, password and token are kept in memory only for the current session and are cleared when the app closes.
- Offline data: so you can still browse when the server can't be reached, the app keeps the data it last read from your Qinglong panel (such as task lists, environment variables, script contents, logs and statistics) in its private storage and uses it only for offline display. It is deleted when you sign out of that server, delete the server, or withdraw consent to this policy.
- App settings: theme, accent color, background, immersive light and frosted glass, UI language, log font size, refresh interval and similar preferences.
- Background picture: if you choose a custom background, a copy of the selected picture is stored in the app's private storage and used only to draw the background.
- Panel avatar: if you change the avatar in Qinglong System, the selected picture is cropped and compressed on the device and uploaded only to your own Qinglong server as that account's avatar; it is never sent to anyone else.
- Crash logs: when an uncaught exception occurs, the app records the error, app version, device model and system version locally so you can investigate. Crash logs are never uploaded; they leave the app only when you tap "Copy", "Share" or "Save as", to the clipboard, the app or the location you choose.

Uninstalling the app deletes all of the above. You can also delete servers, sign out ("Overview → Server management" or "App settings → Servers") and clear crash logs inside the app; deleting a server or signing out also deletes its offline data.

## 3. Network access

- The app requests the network permission (ohos.permission.INTERNET). Apart from the case below, requests go only to the Qinglong panel address you enter, to sign in and to read and change scheduled tasks, environment variables, subscriptions, scripts, dependencies, logs, config files and system information.
- Account and security: changing the panel username and password, turning two-factor authentication on or off in "Qinglong System → Account & security", and the two-factor code you enter when signing in are sent only to your own Qinglong server; the app does not store the two-factor secret or codes on the device.
- Actions you take in the app (such as running a task, editing a script or installing a dependency) are carried out by your own Qinglong server, and the related data stays on that server under your control.
- Update check: only when you tap "App settings → About → Check for updates" does the app ask the AppGallery update service whether a new version exists; the system then shows its update prompt. AppGallery handles this request under its own privacy policy, and the app sends no additional personal information.
- Home screen card: if you add the "Task overview" card to your home screen, the system wakes the app about once an hour to read today's run statistics and failed tasks from your currently selected Qinglong panel with the credentials saved on this device. The results are shown on the card and cached on the device only. Removing the card stops these reads.
- Notification settings: push parameters you enter under Qinglong panel system → Maintenance → Notifications (such as push keys or bot tokens) are saved directly to your own Qinglong panel, which sends notifications through the push service you choose. The app does not keep these parameters on the device.
- Backup: backup files you export are produced by your Qinglong panel and saved through the system "Save as" picker to a location you choose. The app keeps no copy.
- Apart from the above, the app sends no data to us or to any other server.

## 4. Use of device capabilities

- Saving and sharing files: done through the system "Save as" picker and the system share sheet, only for log or script content you export yourself; no storage permission is needed.
- Picture selection: a custom background or a panel avatar is chosen with the system photo picker, so the app can read only the one picture you select; no gallery permission is needed.
- Clipboard: written only when you tap "Copy"; the app never reads the clipboard.
- Reading files: when you import environment variables from a file, you pick one file in the system file picker and the app reads only that file. No storage permission is needed.
- Notifications: requested only when you turn on Software settings → Alerts → Task failure alerts, to show a local notification when a task fails today. Notifications are created on the device and pass through no push server. Turn the switch off, or turn off notifications in system settings, to stop them.

## 5. Your rights

You can view, change or delete your servers and settings in the app at any time; withdraw consent under "App settings → About → Withdraw privacy consent", after which the app deletes every server, credential and all offline data and asks for consent again next time; or simply uninstall the app to delete all local data.

## 6. Minors

The app is meant for users who deploy and operate their own servers. It is not directed at minors and collects no personal information from minors.

## 7. Changes to this policy

If this policy changes, we will update it in the app and on this page, and ask for your consent again where required.

## 8. Contact us

For any questions about this policy, email the developer at zhisibi@163.com or join the feedback QQ group 1127250124.
