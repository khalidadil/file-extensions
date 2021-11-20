# file-extensions

Is a file a video? an image? a text file? a spreadsheet? a 3D file? This repo is meant to help resolve the "type" of a certain file by providing lists of certain file extensions for files in various categories. This is a simple list of file extensions that I find myself embedding in code repeatedly to show certain icons for web applications.

I'm using this [source repo](https://github.com/sindresorhus/video-extensions) as a base and expanding it to fit my needs.

This repo is starting with these as some of the source files:
- List of [video files](https://github.com/sindresorhus/video-extensions/blob/main/video-extensions.json) extensions
- List of [text file](https://github.com/sindresorhus/text-extensions/blob/main/text-extensions.json) extensions
- List of [image-file](https://github.com/arthurvr/image-extensions/blob/master/image-extensions.json) extensions

## Install

```
$ npm install file-extensions
```

## Usage

```js
const { videoExtensions, imageExtensions, textExtensions } = require('file-extensions');
```
## PR Policy

Is this repo missing a certain extension that you need? Open a pull request, and let's get it added! 

Note that I can't guarantee that all pull requests will be accepted for ambiguous file extensions that fall outside the general use case for that extension. For example, if you open a pull request adding "MP4" to the text extensions list, no matter how technically sound your argument may be, this goes against the general use case of that extension (which is generally used for video), and the pull request would not be accepted.

## Sources

- [sindresorhus/video-extensions](https://github.com/sindresorhus/video-extensions) - Simple and small module providing video extensions
- [sindresorhus/text-extensions](https://github.com/sindresorhus/text-extensions) - Simple and small node module providing text extensions
- [arthurvr/image-extensions](https://github.com/arthurvr/image-extensions) - Simple and small node module providing image extensions
