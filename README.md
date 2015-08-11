# File Info

Quick and easy file info detection in Javascript:

```js
/// The main function:
FileInfo(someVariable); // returns file info from: URL | Base64 | Blob | Buffer

/// Exposed internals that are helpful:
FileInfo.byExtension(someExtension); // returns file info from extension [ex. "gif" | "webm"]
FileInfo.byMime(someMimeType); // returns file info from mimetype [ex. "image/gif" | "video/webm"]
FileInfo.isBlob(someVariable); // true if is Blob | File
FileInfo.isSVGString(someVariable); // true if is SVG String | SVG Base64
```
--------------------------------------------------------------------------------------------------------------

The MIT License

Copyright (c) 2015 Michael Deal <https://mudcu.be>. All rights reserved.
