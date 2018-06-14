# mtcnn-align

ongoing work to implement mtcnn in tensorflow.js.
base code copied from https://github.com/davidsandberg/facenet.

# current status

- load model / weights from facenet/src/align
- save loaded model / weights as savedmodel (saved_model.pb, variables.index, ...)
- convert savedmodel to tfjs loadables (tensorflowjs_model.pb, weights_manifest.json, ...)
- test load pnet from tensorflowjs_model.pb into tensorflow.js
- TBD implement glue logic (e.g.: detect_face() in detect_face.py) in javascript

