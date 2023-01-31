1) Download k9s from https://github.com/
https://github.com/derailed/k9s/releases/tag/v0.27.1

Download file: k9s_Darwin_arm64.tar.gz

2) Extract the file

3) Make the k9s binary executable.

chmod +x ./k9s

4) Move the k9s binary to a file location on your system PATH.

sudo mv ./k9s /usr/local/bin/k9s
sudo chown root: /usr/local/bin/k9s
Note: Make sure /usr/local/bin is in your PATH environment variable.
5) Test to ensure the version you installed is up-to-date:

k9s version