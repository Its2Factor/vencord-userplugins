<div align="center">

# ⚡ 2Factor’s Vencord Plugins ⚡

</div>

<div align="center">

These are my **custom Vencord plugins** that haven’t landed in the official Vencord repository yet.

</div>

<br>

<div>

🔊 **[VoiceChannelLogger](voiceChannelLogger/)**  
Tracks and logs voice channel activity

</div>

<br>

# Install

If you don't know how to install userplugins in the first place please see the manual [Vencord installation guide](LINK_TO_GUIDE_HERE).

> [!TIP]
> There's also [this video by Syncxv](LINK_TO_VIDEO_HERE) which shows how to install a userplugin on Windows. Just be sure to replace the `git clone` command with the URL from the plugin you like

Clone the repository inside your Vencord `src/userplugins` folder (create the `userplugins` folder if it doesn't exist)

```bash
cd Vencord/src/userplugins
git clone [https://github.com/Its2Factor/vc-pluginName](https://github.com/Its2Factor/vc-pluginName)
pnpm build
```

# Update

To update just pull the latest changes inside the repository folder and sync the changes

```bash
cd Vencord/src/userplugins/vc-pluginName
git pull
pnpm build
```
