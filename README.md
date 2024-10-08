# Method 1 - PowerShell (Windows 8 and later) ❤️
  Open PowerShell (Not CMD). To do that, right-click on the Windows start menu and select PowerShell or Terminal.
  Copy and paste the code below and press enter
  
      irm https://get.activated.win | iex
      
or (deprecated, will be retired on Dec 31 2024, use above instead)

      irm https://massgrave.dev/get | iex
      
You will see the activation options. Choose [1] HWID for Windows activation. Choose [2] Ohook for Office activation.
That's all.

On older Windows builds you may need to run the below command before,

[Net.ServicePointManager]::SecurityProtocol=[Net.SecurityProtocolType]::Tls12

The Powershell method does not work on Windows 7.

**Use the Method 2 - Traditional instead.**

The URL get.activated.win may be blocked by some DNS services because it is a new domain.

**Method 2 - Traditional (Windows 7 and later)**

Download the file under the code button from GitHub / Azure DevOps / Self-hosted Git
Right-click on the downloaded zip file and extract
In the extracted folder, find the folder named All-In-One-Version
Run the file named MAS_AIO.cmd
You will see the activation options, follow the on-screen instructions.
That's all.
To run the scripts in unattended mode, check here


Latest Version: 2.7
Release date: 6-Sep-2024
