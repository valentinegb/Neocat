# Neocat iMessage Sticker Pack

An iMessage sticker pack for [Volpeon]'s [Neocat] emojis.

<!-- Sticker pack screenshot here -->

*[Neocat] and thus this project are licensed under [CC BY-NC-SA 4.0].*

## Install

Unfortunately, I don't have a build I can just hand out, you have to build it
yourself. Luckily though, the only **requirement** is Xcode (and, obviously, an
iPhone). You probably need to use **Xcode 15.2**, but I'd be very interested to
know if newer versions work, please let me know!

1. **Enable Developer Mode on your iPhone.**

   Open **Settings**, navigate to **Privacy & Security** -> **Developer Mode**,
   and make sure **Developer Mode** is enabled.
2. **Open the project in Xcode.**
3. **Select development team for signing.**

   Open the project file and for both the **Neocat** and **Neocat StickerPack**
   targets, navigate to the **Signing & Capabilities** tab and set **Team** to
   yourself. If you haven't used Xcode before, you will need to select **Add an
   Account...**

   <!-- Signing & Capabilities screenshot here -->
4. **Set Run Destination to your iPhone.**

   Select the **Run Destination** at the top middle of the window. If you have
   not used Xcode before, you will need to plug your iPhone into your computer,
   otherwise you may be able to wirelessly connect to your iPhone.

   <!-- Run Destination screenshot here -->
5. **"Run" the sticker pack.**

   Click the play icon, or press <kbd>⌘</kbd> <kbd>R</kbd>. This will build,
   upload to your iPhone, and then open Messages. When you stop "running", the
   sticker pack will remain on device until you remove it.
6. **Trust the signing development team.**

   Open **Settings**, navigate to **General** -> **VPN & Device Management**
   -> **your email**, and hit **Trust**.

After that, you're done! Unfortunately though, due to Apple's security
restrictions and this being an app not installed through an app store, you will
have have to **repeat steps 2 and 5 every week**, more or less. It may be
possible to take different steps and *sideload* the sticker pack, but I wouldn't
know, so don't ask me.

[Volpeon]: https://volpeon.ink
[Neocat]: https://volpeon.ink/emojis/neocat/
[CC BY-NC-SA 4.0]: https://creativecommons.org/licenses/by-nc-sa/4.0/
