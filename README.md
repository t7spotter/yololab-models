# yololab-models

Model artifacts for [YOLOLab](https://github.com/t7spotter)'s Smart tool, published as releases.
This repository holds no code: each release carries the files one model version runs, with their
licences.

| Release | What | Licence |
|---|---|---|
| `sam2.1-tiny-1` | SAM 2.1 tiny as two ONNX graphs (`encoder.onnx`, `decoder.onnx`), converted by YOLOLab from Meta's `sam2.1_hiera_tiny` checkpoint; onnxruntime-web 1.30.0's runtime files, unmodified | Apache-2.0 (the model, `LICENSE`, with Meta's copyright and our statement of changes in `NOTICE`); MIT (onnxruntime-web) |

YOLOLab's `manage.py fetch_sam` downloads a release's files and checks each one against the
SHA-256 values its manifest pins, so a file here is only ever used if it is exactly the one
expected. YOLOLab is not affiliated with or endorsed by Meta.
