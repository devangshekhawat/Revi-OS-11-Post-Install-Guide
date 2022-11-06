# Revi OS 11 Post Install Guide

## GPU Drivers

<details>
<summary>NVIDIA</summary>

* Install [NVCleanInstall](https://www.techpowerup.com/download/techpowerup-nvcleanstall/)
* Open the program, and tick Install the best driver for my hardware, then click Next.
* Tick Minimum or Recommended in the bottom right, after that hit Next.
  * No need to tick the Visual Runtimes as they're already included in the ISO.
  * PhysX is only used by a handful of games, so most of you can keep this unticked.
  * If ShadowPlay is a necessity, make sure you only select the bare minimum required for it. Note that ShadowPlay adds telemetry onto your system!
* While the Driver is being downloaded you can tick a few tweaks under Additional Tweaks.
  * It is advised to tick everything except Unattended Express Installation.
* Use this [script](https://github.com/Moyster/BaiGfe) to remove GeForce Expterience telemetry after installation.

</details>

<details>
<summary>AMD</summary>

* AMD GPU drivers aren't as bloated by default so it is advised to install them as is from the [official website](https://www.amd.com/en/support) .

</details>

## Direct X 
* Download and run the [Direct X Runtime Installer](https://www.microsoft.com/en-us/download/details.aspx?id=35) 
* Make sure to the untick "Install the Bing Bar" in the following prompts as this is considered advertising bloatware.

## Visual C++ Runtimes 
Like DirectX Runtimes, it is recommended that you install Visual C++ now to avoid program errors in the future.
  * Go to the [vcredist GitHub Page](https://github.com/abbodi1406/vcredist/releases).
  * Under Assets, download the latest VisualCppRedist.zip file.
  * Once downloaded, extract the .zip file and run the installer.

## Packages 
* Use WinGet to Install these packages automatically.
> 7zip
> Brave
> CTT Windows Utility
> Ferdium
> HWinfo
> Logseq
> Pcloud
> OBS Studio
> Motrix
> OnlyOffice
> Playnite
> Firefox
> Powertoys
> Microsoft PCManager
> Redgear Drivers
> Ryzen Controller
> Stremio
> Telegram
> Whatsapp
> VLC Media Player
