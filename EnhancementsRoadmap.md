# Features requiring Android 2.0 #
Any features requiring Android 2.0 will probably necessitate a new branch, or possibly a new project to maintain compatibility with 1.6 devices.

## Bluetooth ##
This is probably the most requested feature for RemoteDroid. It would eliminate the need for a server program, and enable use with the PS3.

### Blocking issues ###
**The author doesn't own an Android 2.0 device. (Oh, the pains of being an early adopter.)**

## Multitouch ##
Maybe the second most requested feature since the release of the Droid. It'd be useful for easier dragging and dropping (Currently, you have to tap and hold, or use the right alt key to toggle mouse buttons on or off.) and multi-finger gestures.

### Blocking issues ###
**The author still doesn't have an Android 2.0 device.**

# Networking #

## Zeroconf/Bonjour ##
IMHO, this is a nice to have, rather than a priority. Most people don't really care about IP addresses, so it'd be good to have an easier mechanism for connecting people's phones to their computers. If we can't have Bluetooth, we could at least have this.

## Security/authentication ##
This requires a decent amount of thought before anything gets implemented.

# Localization #
Android is growing in popularity all over the world, and the rest of the world doesn't necessarily use the same characters that we do. Eventually, it'd be nice if RemoteDroid supported those.

# Fun features #

## Bar code/QR code scanning ##
Someone recently suggested the addition of bar code/QR code scanning, probably using ZXing. This would just take the data from the code, and send it to the computer as a series of keypresses. It could be useful as a way of storing passwords, URLs, or whatever.

I'd probably implement it as another activity which could be reached by pressing the camera button. On successful scan, it's pass the data back to PadActivity, which would have some method added for turning a string into keypresses.

## Wiimote-style motion control ##
This would either just use the accelerometer, or a combination of the accelerometer and the compass.

### Blocking issues ###
