# react-native-convert-video

This module converts iOS videos from .mov to .mp4

## Installation

```sh
yarn add https://github.com/maurocanuto/react-native-convert-video

cd ios && pod install && cd ..
```


## Usage

```js
import ConvertVideo from "react-native-convert-video";

// ...

const result = await ConvertVideo.convertToMp4(videoMovPath)
```
Response object:
```json
{
  "path": "TEMP_VIDEO_PATH.mp4"
}
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
