To install the apps listed in ./what-to-brew.txt, install homebrew by running the following command on your terminal

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

To install all the packages described in ./what-to-brew.txt, clone this repository to your local machine and run the following command inside the generated directory:

```xargs brew install < what-to-brew.txt```
