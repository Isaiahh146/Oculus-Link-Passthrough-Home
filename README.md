# DISCLAIMER:
The program can no longer auto start since it relied on replacing Oculus Home, which well, no longer exists

# Oculus-Link-Passthrough-Home
Replaces Oculus Home with a passthrough version that lets you see the real world using Oculus' passthrough API over Link
# Installation Instructions:
Step 1: Open the Oculus PC software, then go to settings then beta, and enable "Developer Runtime Features", then there should be an option to enable Passthrough over Link.

Step 2: Using Oculus Debug Tool, stop the Oculus service

Step 3: Open File Explorer, then go to where your Oculus installation is, then go to Support > oculus-worlds > Home2 > Binaries > Win64

Step 4: In the Win64 folder, rename "Home2-Win64-Shipping.exe" to "Home2-Win64-Shipping.exe.old"

Step 5: Copy the files from the zip into the Win64 folder

Thats it! Now you should be able to use Oculus Dash while in a passthrough home enviroment!

# Note

Please let me know if you find any issues other than the ones mentioned, I'm new to developing so I don't know a lot. Thanks!
