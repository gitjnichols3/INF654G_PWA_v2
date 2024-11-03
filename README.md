# INF654G_PWA_v2
Version 2 of PWA with Manifest
Service Worker assures that files are cached and sets up fetch to ensure reading data to and from cache vs online.
Manifest is configured and app is fully installable. I have it installed on a Windows PC and an iPhone. It includes icons, screenshots, themes, etc.

One issue I had is that the hamburger menu on some (not all) of the pages stopped working spontaneously although neither the pages nor that portion of ui.js were edited. The Materialize carousel stopped working as well. I tried to troubleshoot for a few hours before giving up.

IndexDB works to allow users to create and delete concerts from a personal todo list. It is currently tied closely to the task manager demo code as I had difficulty troubleshooting original implementations. You do need to reload after creating elements before the delete button will function. 
