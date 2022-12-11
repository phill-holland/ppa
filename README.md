# Personal PPA

For cplusplus-core functionality.

Installation;

```
curl -s --compressed "https://phill-holland.github.io/ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/my_ppa.gpg >/dev/null
curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://phill-holland.github.io/ppa/my_list_file.list"
sudo apt-get update && apt-get install cplusplus-core -y
```
