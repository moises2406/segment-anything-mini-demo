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


Citar segmento cualquier cosa

Si usa SAM o SA-1B en su investigación, use la siguiente entrada de BibTeX.

@article{kirillov2023segany,
  title={Segment Anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C. and Lo, Wan-Yen and Doll{\'a}r, Piotr and Girshick, Ross},
  journal={arXiv:2304.02643},
  year={2023}
}
