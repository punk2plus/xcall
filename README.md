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

MIT

## Links

xcall is used in node  [ll-node-call-mac](https://github.com/lulinglm/ll-node-call-mac)!