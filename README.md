# cc-jsx-html

Forked from https://gist.github.com/ericboehs/1dd34d61540272a37dbe6e9d2aba60dd

A script for converting Claude .jsx artifacts to standalone .html files.

## Installation
```
curl -o jsx-html https://github.com/th1685/cc-jsx-html/jsx-html
chmod +x jsx-html
```

## Usage
```
# Convert to HTML (outputs input.html next to the .jsx)
jsx-html ~/Downloads/my-artifact.jsx

# Specify a custom output path
jsx-html ~/Downloads/my-artifact.jsx ~/presentations/demo.html

# Then just open it
open ~/Downloads/my-artifact.html
```
