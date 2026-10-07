# Nu_PhasmoOverlay â€” releases

Download the latest build from the [Releases](../../releases) page.

**This repository holds releases only. There is no source code here**, and that is
deliberate: GitHub has no "private repository with public releases" mode, so the source lives in
a private repository (`DiscantusProductions/phasmo-overlay`) and the built app is published here,
where anyone can download it without an account, a token, or an invitation.

## For the app

Nu_PhasmoOverlay checks this repository for updates. It needs no GitHub account and no
credentials to do so â€” the update check hits this repo's `releases/latest` endpoint
unauthenticated and compares the tag to the running build's version.
