This repository contains PKGBUILDs for pyReScene. Mostly for personal use. pyReScene is already in the AUR, but I was having problems when reconstructing compressed RARs. The difference between these PKGBUILDs and the AUR package is:

* Removes a size check when reconstructing compressed RARs, which causes a bug that crashes the program even though it successfully found the correct RAR version (the "Still not fine :(." message). I have no idea what other effects this may have nor have I investigated the cause of the bug. All I know is that removing it altogether gives me a higher success rate at reconstructing compressed RARs.
* Adds more RAR versions including beta versions. I haven't tested them.
* Patches the oldest RAR versions to make them work on my system.
