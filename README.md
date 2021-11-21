* Video input command also helps you to extract the face in a frame

* For face detection, you should download the pre-trained YOLOv3 weights file which trained on the [WIDER FACE: A Face Detection Benchmark](http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/index.html) dataset from this [link](https://drive.google.com/file/d/1xYasjU52whXMLT5MtF7RCPQkV66993oR/view?usp=sharing) and place it in the `model-weights/` directory.

* Run the following command:

>**image input**
```bash
$ python yoloface.py --image samples/outside_000001.jpg 
```

>**video input**
```bash
$ python yoloface.py --video samples/subway.mp4 
```

>**webcam**
```bash
$ python yoloface.py --src 1 --output-dir outputs/
```


