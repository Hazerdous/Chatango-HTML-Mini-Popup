Chatango HTML Mini Popup

[Chatango](http://chatango.com) is a basic chat site, with a user interface
based around HTML5 and JavaScript. However, before the HTML5/JS interface
was created, the interface was made with Flash.  
This version had one major feature. Many user still use the outdated Flash
version because this feature is missing from the new version.  
The feature is a simple overlay, which appears near the cursor when
you hover over another user's profile picture. This overlay would show
information about the user. Their age, gender, location, and a small description
would appear here if they added it to their profile. As well as an enlarged
version of their thumbnail.

I was bored one day, and decided to figure out how to make a UserScript.
I decided to try to make my own overlay for the HTML5 chat, to fill in for
the one that was not added by the developers (yet, probably).


Benefits over the flash version:
- The overlay will automatically scale to fit the window. If your window is
wide and tall, the overlay will be wide, and the maximum height will be tall.
- More of the user's mini profile will be shown. The content shrinks to fit
smaller windows. It however, does not grow to fill the area.
- The profile image shown is the user's full image, not the thumbnail.
The image also scales to the original dimensions.

Installation:

1. Install a UserScript manager for your browser.
- [GreaseMonkey](http://www.greasespot.net/) and
[TamperMonkey](http://tampermonkey.net/) are two popular choices.
2. Visit the [Greasey Fork Page](https://greasyfork.org)(WIP) and click the Green
"Install this script" button.
3. This step varies on your manager. But generally, there should be a
button to Install the script.