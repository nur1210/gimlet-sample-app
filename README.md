## Gimlet sample app

A webserver with a few configuration options.

## Usage

```
docker run -it --rm \
  -p 80 \
  -e TITLE=CoffeBreak \
  -e COLOR=lightgreen \
  ghcr.io/gimlet-io/gimlet-sample-app:v1.0.0
```

## Configuration

As its a 12factor app it can be configure with environment variables:

- TITLE: the main header message of the webpage
- COLOR: background color of the page
- BODY: optional text/html displayed as the content
