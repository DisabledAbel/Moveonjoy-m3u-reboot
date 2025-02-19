## What is MoveOnJoy?

MoveOnJoy is a service provider offering access to live TV channels across various categories, including movies, entertainment, news, sports, kids, and documentaries, through the Flussonic Admin UI software.

For added flexibility, this repository provides an M3U playlist featuring MoveOnJoy's channels. With this, you can load the streams into any IPTV application that supports M3U-formatted playlists.


You can view the full list of channels provided by MoveOnJoy [Here](https://github.com/DisabledAbel/Moveonjoy-m3u-reboot/blob/main/Channel-list)


## How to Use the M3U Playlist

To use M3U playlist in your IPTV application, look for the option to import an M3U playlist within the app's settings. Once you find the import option, simply copy and paste the Playlist URL/EPG URL listed below into the respective fields.

### Playlist/EPG URL
    http://m3u4u.com/m3u/4z2xnjk284a2qek9yv15
### open in dropbox below 

[![Open in Dropbox](https://img.shields.io/badge/Open%20in%20Dropbox-blue?style=for-the-badge&logo=dropbox)](https://www.dropbox.com/scl/fi/j118ojnr54hfsugugo47s/m3u4u-141326-596733-Playlist.m3u?rlkey=ho24qiha8bcxz435xft5q4arq&st=po3mewrk&dl=1)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Copy M3U URL</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 50px; }
        input { width: 80%; padding: 10px; font-size: 16px; text-align: center; }
        button { padding: 10px 20px; font-size: 16px; cursor: pointer; margin-top: 10px; }
    </style>
</head>
<body>

    <h2>Copy M3U URL</h2>
    <input type="text" id="copyText" value="http://m3u4u.com/m3u/4z2xnjk284a2qek9yv15" readonly>
    <br>
    <button onclick="copyToClipboard()">Copy</button>
    <p id="message" style="color: green;"></p>

    <script>
        function copyToClipboard() {
            const inputField = document.getElementById("copyText");
            inputField.select();
            inputField.setSelectionRange(0, 99999);
            navigator.clipboard.writeText(inputField.value).then(() => {
                document.getElementById("message").innerText = "Copied!";
            }).catch(err => console.error("Copy failed:", err));
        }
    </script>

</body>
</html>

## Disclaimer:

This repository has no control over the streams, links, or the legality of the content provided by MoveOnJoy.com. It is the end user's responsibility to ensure the legal use of these streams, and we strongly recommend verifying that the content complies with the laws and regulations of your country before use.
