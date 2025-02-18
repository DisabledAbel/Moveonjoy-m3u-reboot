## What is MoveOnJoy?

MoveOnJoy is a service provider offering access to live TV channels across various categories, including movies, entertainment, news, sports, kids, and documentaries, through the Flussonic Admin UI software.

For added flexibility, this repository provides an M3U playlist featuring MoveOnJoy's channels. With this, you can load the streams into any IPTV application that supports M3U-formatted playlists.

You can view the full list of channels provided by MoveOnJoy 

You can view the full list of channels provided by MoveOnJoy https://github.com/DisabledAbel/Moveonjoy-m3u-reboot/blob/main/Channel-list


## How to Use the M3U Playlist

To use M3U playlist in your IPTV application, look for the option to import an M3U playlist within the app's settings. Once you find the import option, simply copy and paste the Playlist URL/EPG URL listed below into the respective fields.

### Playlist/EPG URL:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Copy Button</title>
    <script>
        function copyToClipboard() {
            const text = "http://m3u4u.com/m3u/4z2xnjk284a2qek9yv15";
            navigator.clipboard.writeText(text).then(() => {
                alert("Copied to clipboard!");
            }).catch(err => console.error("Error copying text:", err));
        }
    </script>
</head>
<body>
    <input type="text" value="http://m3u4u.com/m3u/4z2xnjk284a2qek9yv15" id="url" readonly>
    <button onclick="copyToClipboard()">Copy</button>
</body>
</html>

### Playlist file
https://www.dropbox.com/scl/fi/j118ojnr54hfsugugo47s/m3u4u-141326-596733-Playlist.m3u?rlkey=ho24qiha8bcxz435xft5q4arq&st=k301gcqb&dl=0
## Disclaimer:

This repository has no control over the streams, links, or the legality of the content provided by MoveOnJoy.com. It is the end user's responsibility to ensure the legal use of these streams, and we strongly recommend verifying that the content complies with the laws and regulations of your country before use.
