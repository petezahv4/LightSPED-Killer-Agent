## LightSPED Killer Agent
LightSPED is a tool made by [Blobby-Boi](https://github.com/Blobby-Boi) that allows ChromeOS users to easily disable the "Lightspeed Filter Agent" extension. This utilizes a modified version of the ExtFlood3r exploit, and it will persist until you restart your computer or flip the switch again.

### How to use
- Step 1. Go to [this link](https://lightsped-killer-agent.github.io) or open the following data URI:
```
data:text/html;charset=utf-8,%3C!DOCTYPE%20html%3E%0A%3Chtml%20lang%3D%22en%22%3E%0A%3Chead%3E%0A%20%20%3Cmeta%20charset%3D%22UTF-8%22%3E%0A%20%20%3Cmeta%20name%3D%22viewport%22%20content%3D%22width%3Ddevice-width%2C%20initial-scale%3D1.0%22%3E%0A%20%20%3Ctitle%3ELightSPED%20Killer%20Agent%3C%2Ftitle%3E%0A%20%20%3Clink%20rel%3D%22shortcut%20icon%22%20type%3D%22image%2Fpng%22%20href%3D%22https%3A%2F%2Fraw.githubusercontent.com%2FBlobby-Boi%2FLightSPED-Killer-Agent%2Frefs%2Fheads%2Fmain%2Flightspeed.png%22%3E%0A%20%20%3Cscript%3E%0A%20%20%20%20document.addEventListener(%22DOMContentLoaded%22%2C%20()%20%3D%3E%20%7B%0A%20%20%20%20%20%20const%20main%20%3D%20%22https%3A%2F%2Fraw.githubusercontent.com%2FBlobby-Boi%2FLightSPED-Killer-Agent%2Frefs%2Fheads%2Fmain%2Findex.html%22%3B%0A%20%20%20%20%20%20const%20fallback%20%3D%20%22https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FBlobby-Boi%2FLightSPED-Killer-Agent%2Findex.html%22%3B%0A%0A%20%20%20%20%20%20fetch(main)%0A%20%20%20%20%20%20%20%20.then(response%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20if%20(!response.ok)%20throw%20new%20Error(%22Primary%20URL%20failed%22)%3B%0A%20%20%20%20%20%20%20%20%20%20return%20response.text()%3B%0A%20%20%20%20%20%20%20%20%7D)%0A%20%20%20%20%20%20%20%20.catch(()%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20return%20fetch(fallback).then(response%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20if%20(!response.ok)%20throw%20new%20Error(%22Fallback%20URL%20failed%22)%3B%0A%20%20%20%20%20%20%20%20%20%20%20%20return%20response.text()%3B%0A%20%20%20%20%20%20%20%20%20%20%7D)%3B%0A%20%20%20%20%20%20%20%20%7D)%0A%20%20%20%20%20%20%20%20.then(html%20%3D%3E%20%7B%0A%20%20%20%20%20%20%20%20%20%20document.open()%3B%0A%20%20%20%20%20%20%20%20%20%20document.write(html)%3B%0A%20%20%20%20%20%20%20%20%20%20document.close()%3B%0A%20%20%20%20%20%20%20%20%7D)%0A%20%20%20%20%7D)%3B%0A%20%20%3C%2Fscript%3E%0A%3C%2Fhead%3E%0A%3C%2Fhtml%3E
```
- Step 2. Click the big "Launch" button
- Step 3. Follow the instructions on the popup
- Step 4. Lightspeed has been disabled! To re-enable it, go to `chrome://extensions/?id=adkcpkpghahmbopkjchobieckeoaoeem` again and flip the "Allow access to file URLs" switch once more.
