# Git Credentials Manager

Git Credential Manager (GCM) is a secure Git credential helper built on .NET that runs on Windows, macOS, and Linux. It aims to provide a consistent and secure authentication experience, including multi-factor auth, to every major source control hosting service and platform.

GCM supports (in alphabetical order) Azure DevOps, Azure DevOps Server (formerly Team Foundation Server), Bitbucket, GitHub, and GitLab. Compare to Git's built-in credential helpers (Windows: wincred, macOS: osxkeychain, Linux: gnome-keyring/libsecret), which provide single-factor authentication support for username/password only.

GCM replaces both the .NET Framework-based Git Credential Manager for Windows and the Java-based Git Credential Manager for Mac and Linux.

**To install**

`brew install --cask git-credential-manager`

This will cause a popup when you try to push your repository to the remote repository that will allow you to login on the Website and that will also log in on the Command line.