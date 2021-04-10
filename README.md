# dropbearbinary
Dropbear binary for chinese NVR systems (https://gist.github.com/aSmig/e50058a54ab85428915521f233ffa3d0)

Extract the zip to your usb stick, leaving the folder structure in tact (/packages/dropbear/)

Add the following line to your dvr_app or dvr_app_chain:

``/media/usb1/packages/dropbear/dropbear -R &``

Hostkey files will be generated on the fly and saved in the dropbear folder

Use at your own risk. I noticed some instability on my system. Not sure if it was caused by dropbear or the system being in debug mode. either way, be careful. i won't be held responsible if you lose footage or something explodes etc.
