# Devel Central downloads

This repository holds the macOS releases of Devel Central and nothing else: each release on the
Releases tab carries the DMG to install, the zip the installed app downloads to update itself,
its blockmap and `latest-mac.yml`, the update feed. The source lives in a separate, private
repository, and develcentral.com links the latest DMG.

Install by opening the DMG and dragging Devel Central to Applications. The app is signed with a
Developer ID certificate and notarized by Apple; it checks here for a newer version when it
starts and every four hours, downloads it in the background and installs it when it quits.
