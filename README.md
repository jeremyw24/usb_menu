# usbMenu - HTML5 USB Menu #

usbMenu is a HTML5 DVD Style Menu clone to allow you to distribute your videos on USB Stick.

Simply copying files to a USB Stick lacks presentation, specially for a wedding video - usbMenu provides a nice way to present and play video leveraging the HTM5 <video> element.

### Naming Conventions ###

It is important your file naming conventions are correct for usbMenu to deploy correctly.

As usbMenu was primarily designed around the delivery of wedding videos, current naming conventions are as follows:

* **Highlights:** The video file must be named highlights.mp4 and is called via `href="media/player.html?highlights"`
* **Ceremony:** The video file must be named ceremony.mp4 and is called via `href="media/player.html?ceremony"`
* **Preparations:** The video file must be named preparations.mp4 and is called via `href="media/player.html?preparations"`
* **Reception:** The video file must be named reception.mp4 and is called via `href="media/player.html?reception"`

If you wish to change the video names you must ensure the href query is changed to match the video name. This change should also be relfected in the `<a>` element.

Provided both the `href` link and the `<a>` element text are changed to match the file name, the video will play in player.html

### Included Files ###

| File        | Purpose           |
| ------------- | ------------- |
| index.html      | Main Page - dislays main menu and buttons. The only page that needs editing. |
| player.html      | Video Player logic including HTML5 Video element and JS |
| background.jpg      | Full size background image |
| background-mobile.jpg      | Mobile background image |

### Customising Menu Titles ###

You can personalise your USB Menu by simply doing a search for customTitle. 
Replace any existing text with your new custom text.

### Background Images ###

There are two background images, one for desktop/fullscreen devices and one for mobile devices.

Using two images makes resizing the window a little smoother.

* **background.jpg:** Desktop background image, anything over 1920x1080 will be sufficient.
* **background-mobile.jpg:** Mobile background image, this image should be around 700x500.

### Fonts ###

As usbMenu could potentially be used offline or on a SmartTV with no internet connection, it is best fonts are local.

If you want custom fonts, you can pull down Google Fonts, or use default fonts. I have two custom fonts loaded by default, these are included via `main.css`

### License ###