# Neocat iMessage Sticker Pack

An iMessage sticker pack for [Volpeon]'s [Neocat] emojis.

<img width="293" alt="IMG_4547" src="https://github.com/user-attachments/assets/769656ea-2b47-4f72-9d46-541682d13f5d">

*[Neocat] and thus this project are licensed under [CC BY-NC-SA 4.0].*

## Install

Unfortunately, I don't have a build I can just hand out, you have to build it
yourself. Luckily though, the only **requirement** is Xcode (and, obviously, an
iPhone). You probably need to use **Xcode 15.2**, but I'd be very interested to
know if newer versions work, please let me know!

> [!IMPORTANT]
> Xcode 15.2 doesn't like to run on newer versions of macOS, like macOS 15 for
> example. However, we can sort of trick it into running anyway. Here's how I
> do it: I install a newer version of Xcode, like Xcode 16, I backup
> Xcode 15.2's `Info.plist` (`Xcode.app/Contents/Info.plist`), duplicate Xcode
> 16's `Info.plist` in the place of Xcode 15.2's, run Xcode 15.2 once, then
> restore the backed up `Info.plist`, and it stops complaining.

1. **Enable Developer Mode on your iPhone.**

   Open **Settings**, navigate to **Privacy & Security** -> **Developer Mode**,
   and make sure **Developer Mode** is enabled.
2. **Open the project in Xcode.**
3. **Select development team for signing.**

   Open the project file and for both the **Neocat** and **Neocat StickerPack**
   targets, navigate to the **Signing & Capabilities** tab and set **Team** to
   yourself. If you haven't used Xcode before, you will need to select **Add an
   Account...**

   <img width="1552" alt="Screenshot 2024-10-14 at 4 37 54 PM" src="https://github.com/user-attachments/assets/3be106da-5f90-4636-bd7e-0829000f777c">
4. **Set Run Destination to your iPhone.**

   Select the **Run Destination** at the top middle of the window. If you have
   not used Xcode before, you will need to plug your iPhone into your computer,
   otherwise you may be able to wirelessly connect to your iPhone.

   <img width="1552" alt="Screenshot 2024-10-14 at 4 42 05 PM" src="https://github.com/user-attachments/assets/7b25f72b-e3a9-45aa-8dcb-2dc0dea2df56">
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
