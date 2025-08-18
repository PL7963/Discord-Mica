<div align=center>
<img alt="I chose wrong backdrop type when I was writing this theme. So picture you see is actually Mica tabbed not Mica" src="https://github.com/user-attachments/assets/2f65dca2-481f-4bc3-9dcd-0f6282cb4e37" />

# Discord Mica
</div>

#### Discord Mica focus on brining Mica material and WinUI 3 standard to Discord. Also keeping Discord aesthetic at the same time. Without fancy animations or overwhelming colorful background. Provide just enough customization.

## Requirement
* ![BetterDiscord](https://betterdiscord.app/) or ![Vencord](https://github.com/Vendicated/Vencord) (You should know this one)
* ![MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone) (For Mica backdrop)

## Get Started
1. Patch your Discord with BetterDiscord or Vencord
2. Add Discord process to MicaForEveryone and set backdrop type to Mica
3. Enable transparency in BetterDiscord/Vencord settings

That's it :D

## Note
* You could use any backdrop material, like Acrylic, with a Discord-Mica theme. However, this is not recommended since Acrylic is a transparent material, which blurs the contents behind windows. This can be performance-heavy and cause visibility issues. Acrylic should only be used in small areas.
* Both Mica and Mica Tabbed are tested recommended.
* I don't recommend enabling the blur-behind feature. Mica does a great job creating contrast between background and foreground elements. However, with certain backgrounds, it can still cause visibility issues and is also performance-intensive, similar to Acrylic.
* The screenshot I took above is actually Mica tabbed. I did not realize I was using Mica tabbed when I was writing this theme. And I was trying to replicate Mica look. If you want to get a similar appearance you can use the dark-bg values in the comments
* You may want to add more blur effects with a backdrop filter, but when transparency is enabled, backdrop-filter breaks. I recommend tweaking colors to make elements fit into the wallpaper, instead of using transparent elements without blur.
* **Mica with WinDynamicWallpaper is AWESOME**

## Customization
You can find all the customizable variables in the :root field of /src/main.css. Below is a list of common variables you may want to use  
`--dark/light-bg` Allows you to tweak transparency of the background for personal preference or accessibility  
`--dark/light-accent` Allows you to tweak accent color of primary button or toggles. You can get current accent color in Windows color settings. And retrieve it with PowerToy color picker.
