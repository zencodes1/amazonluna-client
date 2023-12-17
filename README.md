# amazonluna-linux
An amazon luna client for linux.
# How to install
1. Download the file from releases.
2. Uncompress the downloaded file.
3. Move "amazonluna" into /opt/ (Recommended) or any other path.
4. Execute the following commands:
`$ sudo chown root:root chrome-sandbox`
`$ sudo chmod 4755 chrome-sandbox` in the install directory and:
`$ sudo ln -s /path/to/install/dir/AmazonLuna /usr/bin/AmazonLuna`.
5. Move luna.desktop into /usr/share/applications or /home/yourusername/.local/share/applications.
6 (Not requiered if installed into /opt): Replace Exec and Icon in the luna.desktop with: /path/to/install/dir/AmazonLuna and /path/to/install/dir/luna.jpg.
7. Enjoy!

