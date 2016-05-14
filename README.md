# EZPortify

Transfer all of your Spotify-playlists to Google Play Music.
Also spits out all playlists and their tracks to a text file.

### Preface

Feel free to check out my new version that runs directly in your browser. No need to download anything or give anyone your password! See **[Portify.JS](https://github.com/jordam/portify.js/)**

### Instructions

1. Run `pip install -r requirements.txt` to install dependencies.
2. Run `python ezportify.py` to run the script. It will prompt you for your Google username and password, and a Spotify Ouath Token, which you can get through [Spotify developer pages]( https://developer.spotify.com/web-api/console/get-current-user-playlists/).

__Notes:__
* If you are unable to sign in to your Google account, turn on access for less secure apps here: https://www.google.com/settings/security/lesssecureapps/  - You may turn it off after the program has completed.
* If you have two-factor authentication activated, you'll need a app password. You can create that [here](https://security.google.com/settings/security/apppasswords), and read more about it on [Googles help pages](https://support.google.com/accounts/answer/185833)

Run ezportify.py -h for help (ezportify.exe -h for windows users)

### Windows Users
I have included ezportify.exe in win32.zip. If you are not comfortable with python you can download and extract win32.zip then run ezportify.exe to get going right away. **[< WINDOWS DOWNLOAD >](https://github.com/jordam/ezportify/raw/master/win32.zip)**

### Props
This script is based on pyportify by rckclmbr https://github.com/rckclmbr/pyportify  
pyportify is based on the original portify by mauimauer https://github.com/mauimauer/portify

### Disclaimer

By using ezportify you may violate both Spotify's and Google's Terms of Service. You agree that you are using ezportify on your own risk. The author does not accept liability (as far as permitted by law) for any loss arising from any use of this tool. If you choose not to agree to these terms, then you may not use this tool.
