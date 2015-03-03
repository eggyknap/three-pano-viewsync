# three-pano-viewsync
Three.js example pano viewer, modified for LG use

To use, stick these files in a web server somewhere. Run "perl
ViewSyncEffect/server.pl" (you'll need the Net::WebSocket::Server Perl module
for this). Connect your browser to
http://your-server/webgl_panorama_equirectangular.html. Connect another browser
to the same URL, but append "?slave=true" to it so it will run in slave mode.
Append instead "?slave=true&yaw=50" to have the slave yawed 50 degrees.
