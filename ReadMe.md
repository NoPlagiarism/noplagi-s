# NoPlagi's [302](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/302) to PowerShell scripts

> Just `irm https://r.noplagi.xyz/s-{sth} | iex` your way

- [Scripts](#scripts)
- [Useless FAQ](#useless-faq)

## Scripts

### Chris Titus Tech's Windows Utility

- **Description:** Install Programs, Tweaks, Fixes, and Updates
- **License:**  [MIT](https://github.com/ChrisTitusTech/winutil/blob/main/LICENSE) | [Source Code](https://github.com/ChrisTitusTech/winutil)
- Stable branch (`s-winutil`)

  - ```PowerShell
    irm https://r.noplagi.xyz/s-winutil | iex
    ```

  - Original URL: `https://christitus.com/win`
- Dev Branch (`s-winutil-dev`)

  - ```PowerShell
    irm https://r.noplagi.xyz/s-winutil-dev | iex
    ```

  - Original URL: `https://christitus.com/windev`

### speedtest.net

- **Description:** Run a speedtest.net test from the cli without installing it (Wrapper by @asheroto)
- **License:** [GNU GPL v3](https://github.com/asheroto/speedtest/blob/main/LICENSE) | [Source Code](https://github.com/asheroto/speedtest)
- Script (`s-speedtest`)

  - ```PowerShell
    irm https://r.noplagi.xyz/s-speedtest | iex
    ```

  - Original URL: `https://asheroto.com/speedtest`

### Microsoft Activation Scripts (MAS)

- **Description:** A Windows and Office activator using HWID / Ohook / KMS38 / Online KMS activation methods, with a focus on open-source code and fewer antivirus detections
- **License:** [GNU GPL v3](https://github.com/massgravel/Microsoft-Activation-Scripts/blob/master/LICENSE) | [Source Code](https://github.com/massgravel/Microsoft-Activation-Scripts)
- Script (`s-mas`)

  - ```PowerShell
    irm https://r.noplagi.xyz/s-mas | iex
    ```

  - Original URL: `https://get.activated.win`

### Scoop (Installer)

- **Description:** Command-line installer for Windows (best in my opinion)
- **License:** [Unlicense or MIT](https://github.com/ScoopInstaller/Scoop/blob/master/LICENSE) | [Source Code](https://github.com/ScoopInstaller/Scoop)
- Script (`s-scoop`)

  - ```PowerShell
    irm https://r.noplagi.xyz/s-scoop | iex
    ```

  - Original URL: `https://get.scoop.sh`

### tiny11builder

- **Description:** Scripts to build a trimmed-down Windows 11 image
- **License:** None | [Source Code](https://github.com/ntdevlabs/tiny11builder)
- tiny11 (`s-tiny11`)

  - ```PowerShell
    irm https://r.noplagi.xyz/s-tiny11 | iex
    ```

  - Original URL: `https://raw.githubusercontent.com/ntdevlabs/tiny11builder/main/tiny11maker.ps1`
- tiny11-core (`s-tiny11-core`)

  - ```PowerShell
    irm https://r.noplagi.xyz/s-tiny11-core | iex
    ```

  - Original URL: `https://raw.githubusercontent.com/ntdevlabs/tiny11builder/main/tiny11Coremaker.ps1`

## Useless FAQ

### Can I request script to be added here?

You can, but

- **it's my decision to add it or not**
- Script should be open-source

### Why PRs are closed?

They are kinda useless here. At least, for now

### Can I believe you?

Why not? `:D`

### Can I use this on my job or use it in some automatization?

Please, no.

- One more unneeded redirect chain
- You sure you wanna use **3rd party** redirection, when it comes to automatization or using it on job? If yes, use it on your own risk
- No one can guarantee
  - That this domain won't expire and I will be always able to renew it
  - That URL Shortener I use will be available 24/7

### Why?

- Why not? `:D`
- It is easier to remember for me
- I can share simple redirection to PS Scripts or program installers I use daily

### Are you tracking me? :<

- Not on purpose. At least for now, since I might add refer links to interactive mode (To-Do)
- I use link shortener and it shows me some analytics :>

### Free and available 24/7?

I am not sure about available. But yeah, it's free, lol
