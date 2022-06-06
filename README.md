# Oculus-Link-Passthrough-Home
Replaces Oculus Home with a passthrough version that lets you see the real world using Oculus' passthrough API over Link
# Installation Instructions:
Step 1: Open the Oculus PC software, then go to settings then beta and enable "Developer Runtime Features", then there should be an option to enable Passthrough over Link.

Step 2: Using Oculus Debug Tool, stop the Oculus service

Step 3: Open File Explorer, then go to where your Oculus installation is, then go to Support > oculus-worlds > Home2 > Binaries > Win64

Step 4: In the Win64 folder, rename "Home2-Win64-Shipping.exe" to "Home2-Win64-Shipping.exe.old"

Step 5: Copy the files from the zip into the Win64 folder

Thats it! Now you should be able to use Oculus Dash while in a passthrough home enviroment!

# Issues

Issue 1: Application will NOT close automaticly when Oculus Link is disabled, you should be able to close it manually just fine though.

Issue 2 / Inconvenience: Since this is a Unity application and I don't have Unity Pro, There is a mandatory splash screen that has to stay enabled, I've replaced the default Unity logo with my brand logo. I would omit this if I could but like I said, Unity will not let me, sorry.

# Note

Please let me know if you find any issues other than the ones mentioned, I'm new to developing so I don't know a lot. Thanks!
