## How does it work?

Like mentioned above, this tool is written in C# and can be used on Windows and OSX systems to exfiltrate Discord Tokens. Once executed it will look through the file system and attempt to locate a Discord Account Tokens. Once it finds one it will send a message to your Discord server via Discord Webhooks which will contain the token, information about the system and information about the Discord Account.C++ 17 is used (filesystem is used in this project). It searches for tokens in Discord, Discord PTB, Discord Canary, Chrome, Opera, Brave and Yandex directories. Once
it finds a token, it sends it to your Discord webhook.

# Features
* Steal Discord info
  * Username
  * E-mail
  * Phone Number
  * Nitro Type
  * ID
* Steal Discord token
  * Discord
  * Discord PTB
  * Discord Dev
* Steal Discord Password : When you change password & When you change e-mail & When you log-in in your discord account
  * Discord
  * Discord PTB
  * Discord Dev
  * -  Protection (AntiDebug, AntiEmulation, AntiWebSniffers, AntiVM, AntiSandboxie) which is controlled through the settings file.
   -  Discord webhooks & Telegram integration. 
   -  Grabs tokens from all installed clients even if the main path changed and deletes accounts duplicates.
   -  18 hardcoded known tokens locations :(.
   -  Grabs PC information + token information (IP, CPU, GPU, WINKEY).
   -  Grabs Discord password and sending the new info with every event that involves password. 
   -  Sends screenshot of all screens at the moment of the grabbing (all screens).
   -  Grabs browser cookies and passwords.
   -  Supports Brave, Chrome, Firefox, and OperaGx. [Password & Cookies stealer]
   -  WIFI passwords stealer. 
   -  Crypto-clipper.
   -  Feature to steal most of based Gecko & Chromium browsers.
   -  Self-updating, When a new account is logged or password changed will be sent again with the new information.
   -  Bypasses Anti-Token-Grabbers.
   - Supports grabbing from Firefox-based browsers (Pale Moon, WaterFox, Firefox [I will add more in the future]) <br><br>
   -  Local cache.
   -  18 hardcoded paths 😕 (Because I prefer dynamic).
 

# Disclaimer
I, the creator, am in no way responsible for any actions that you may make using this software. You take full responsibility with any action taken using this software. Please take note that this application was designed for educational purposes and should never be used maliciously. By downloading the software or source to the software, you automatically accept this agreement.
