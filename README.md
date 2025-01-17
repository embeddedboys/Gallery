# Gallery of embeddedboys

## Build

1. setup npm and nodejs
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install node
```

2. setup hugo
```bash
wget https://github.com/gohugoio/hugo/releases/download/v0.141.0/hugo_extended_0.141.0_linux-amd64.deb

sudo apt install ./hugo_extended_0.141.0_linux-amd64.deb
```

3. install dependencies
```bash
npm install postcss-cli
```

4. start the local server
```bash
hugo server -D
```
