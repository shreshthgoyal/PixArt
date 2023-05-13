# PixArt - Pixel Art Cross-Platform Desktop App
									
![pixart_screenshot](https://i.ibb.co/frfKS3N/pixart.jpg)

PixArt is a Golang-based desktop GUI application that enables users to create and save pixelated art. It utilizes the Fyne toolkit and offers users the ability to generate, save, and modify PNG-format images. Additionally, the application features swatches and a Colorpicker as supplementary tools. Currently, only pixel brushtype is supported, but the underlying architecture can be extended to support other brush types.

## Getting Started

### Dependencies

All the packages are listed in *go.mod* [here](https://github.com/shreshthgoyal/PixArt/blob/main/go.mod). A GCC compiler is required to compile the code.


### Executing the program

To execute the program, one can easily clone the corresponding repository and subsequently execute the following set of commands.

```
go mod tidy
go run ./pixart
```
