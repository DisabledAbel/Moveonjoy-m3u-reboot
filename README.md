## What is MoveOnJoy?

MoveOnJoy is a service provider offering access to live TV channels across various categories, including movies, entertainment, news, sports, kids, and documentaries, through the Flussonic Admin UI software.

For added flexibility, this repository provides an M3U playlist featuring MoveOnJoy's channels. With this, you can load the streams into any IPTV application that supports M3U-formatted playlists.


You can view the full list of channels provided by MoveOnJoy [Here](https://github.com/DisabledAbel/Moveonjoy-m3u-reboot/blob/main/Channel-list)


## How to Use the M3U Playlist

To use M3U playlist in your IPTV application, look for the option to import an M3U playlist within the app's settings. Once you find the import option, simply copy and paste the Playlist URL/EPG URL listed below into the respective fields.

### Playlist URL
    http://m3u4u.com/m3u/4z2xnjk284a2qek9yv15

### EPG URL<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M3U & XML Helper</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 20px; }
        .button { display: inline-block; padding: 12px 24px; font-size: 16px; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; margin: 10px; }
        .dropbox { background-color: #007ee5; }
        .icloud { background-color: #0071e3; }
        .copy { background-color: #28a745; border: none; cursor: pointer; }
        .copy:hover { background-color: #218838; }
        input { width: 80%; padding: 10px; margin: 10px 0; text-align: center; }
    </style>
</head>
<body>
    <h2>Playlist Links</h2>
    
    <!-- Dropbox Button -->
    <a class="button dropbox" href="https://www.dropbox.com/scl/fi/j118ojnr54hfsugugo47s/m3u4u-141326-596733-Playlist.m3u?rlkey=ho24qiha8bcxz435xft5q4arq&st=po3mewrk&dl=1" target="_blank">Open in Dropbox</a>
    
    <!-- iCloud Button -->
    <a class="button icloud" href="YOUR_ICLOUD_LINK_HERE" target="_blank">Open in iCloud</a>
    
    <!-- Copy-to-Clipboard Button for M3U -->
    <h3>Copy M3U Link</h3>
    <input type="text" id="m3uLink" value="https://www.dropbox.com/scl/fi/j118ojnr54hfsugugo47s/m3u4u-141326-596733-Playlist.m3u?rlkey=ho24qiha8bcxz435xft5q4arq&st=po3mewrk&dl=1" readonly>
    <button class="button copy" onclick="copyToClipboard('m3uLink')">Copy</button>
    
    <!-- QR Code for M3U -->
    <h3>Scan M3U QR Code</h3>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://www.dropbox.com/scl/fi/j118ojnr54hfsugugo47s/m3u4u-141326-596733-Playlist.m3u?rlkey=ho24qiha8bcxz435xft5q4arq&st=po3mewrk&dl=1" alt="M3U QR Code">
    
    <!-- XML Button -->
    <a class="button dropbox" href="http://m3u4u.com/xml/4z2xnjk284a2qek9yv15" target="_blank">Open XML</a>
    
    <!-- Copy-to-Clipboard Button for XML -->
    <h3>Copy XML Link</h3>
    <input type="text" id="xmlLink" value="http://m3u4u.com/xml/4z2xnjk284a2qek9yv15" readonly>
    <button class="button copy" onclick="copyToClipboard('xmlLink')">Copy</button>
    
    <!-- QR Code for XML -->
    <h3>Scan XML QR Code</h3>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=http://m3u4u.com/xml/4z2xnjk284a2qek9yv15" alt="XML QR Code">
    
    <script>
        function copyToClipboard(elementId) {
            const inputField = document.getElementById(elementId);
            inputField.select();
            navigator.clipboard.writeText(inputField.value).then(() => {
                alert("Copied to clipboard!");
            }).catch(err => console.error("Copy failed:", err));
        }
    </script>
</body>
</html>



## Disclaimer:

This repository has no control over the streams, links, or the legality of the content provided by MoveOnJoy.com. It is the end user's responsibility to ensure the legal use of these streams, and we strongly recommend verifying that the content complies with the laws and regulations of your country before use.
