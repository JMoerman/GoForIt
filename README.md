# Flatpak packaging files for GoForIt (elementary OS version)
The source code of _GoForIt!_ can be found here: https://github.com/JMoerman/Go-For-It

## Why does this repo exist?

1. This solves the issue with hyphens in the app ID. elementary OS uses a RDNN naming scheme for applications, which results in hyphens when using the https://github.com/JMoerman/Go-For-It code repo. (AppStream complains if the application ID contains hyphens)
2. This allows me to keep my code and packaging files separate. (From what I can see it isn't possible to publish an application on AppCenter by creating a tag pointing to a commit on a code branch. The tagged release must contain a flatpak manifest.) (_Go For It!_ is also present on flathub, Arch and FreeBSD. I do not want an appcenter specific flatpak manifest with a generic <ID>.yml name in a branch which is used for all of these platforms.)
