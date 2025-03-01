## What is MoveOnJoy?

MoveOnJoy is a service provider offering access to live TV channels across various categories, including movies, entertainment, news, sports, kids, and documentaries, through the Flussonic Admin UI software.

For added flexibility, this repository provides an M3U playlist featuring MoveOnJoy's channels. With this, you can load the streams into any IPTV application that supports M3U-formatted playlists.


You can view the full list of channels provided by MoveOnJoy [Here](https://github.com/DisabledAbel/Moveonjoy-m3u-reboot/blob/main/Channel-list)


## How to Use the M3U Playlist

To use M3U playlist in your IPTV application, look for the option to import an M3U playlist within the app's settings. Once you find the import option, simply copy and paste the Playlist URL/EPG URL listed below into the respective fields.

### Playlist URL
    http://m3u4u.com/m3u/4z2xnjk284a2qek9yv15

### EPG URL
    http://m3u4u.com/epg/4z2xnjk284a2qek9yv15

### XML URL
    <!-- Copy-to-Clipboard Button for XML -->
    <h3>Copy XML Link</h3>
    <input type="text" id="xmlLink" value="http://m3u4u.com/xml/4z2xnjk284a2qek9yv15" readonly>
    <button class="button copy" onclick="copyToClipboard('xmlLink')">Copy</button>
    
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
