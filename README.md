## Segment Anything Simple Web demo

## It's complete, I didn't test it because of problems with python, but whoever tests it, leave me a message

This **front-end only** React based web demo shows how to load a fixed image and corresponding `.npy` file of the SAM image embedding, and run the SAM ONNX model in the browser using Web Assembly with mulithreading enabled by `SharedArrayBuffer`, Web Worker, and SIMD128.

<img src="https://github.com/facebookresearch/segment-anything/raw/main/assets/minidemo.gif" width="500"/>

## Run the app

Install Yarn

```
npm install --g yarn
```

Build and run:

```
yarn && yarn start
```

Navigate to [`http://localhost:8081/`](http://localhost:8081/)

Move your cursor around to see the mask prediction update in real time.
