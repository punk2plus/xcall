# xcall/介绍
Call X-Callback-URLs From the Command Line. Outputs the `x-success` and `x-error` responses to `stdout`/`stderr`.

给其他平台提供调用mac app的能力。通过app提供的（X-Callback-URLs）

## Download/下载

 [latest](https://github.com/lulinglm/xcall/releases/download/1.0.0/xcall.app.zip).版本

## Usage/用法

```bash
xcall.app/Contents/MacOS/xcall -url "myapp://x-callback-url/my-action?foo=bar" -activateApp YES
```

The `url` parameter is required. The optional `activateApp` parameter controls whether the target app is brought to the foreground. If omitted, it is `NO`.

## License

Copyright (c) 2019 lulinglm

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Links

xcall is used in node  [ll-node-call-mac](https://github.com/lulinglm/ll-node-call-mac)!