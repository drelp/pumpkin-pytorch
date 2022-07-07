# pumpkin-pytorch
pumpkin-pytorch

```shell script
python /code/src/fashion_mnist/train.py

git clone --recurse-submodules https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch.git
git submodule update --init
pip3.9 install -r requirements.txt -i https://pypi.doubanio.com/simple/
python3.9 track.py --source 0
python3.9 track.py --source 0 --show-vid
python3.9 track.py --source 0 --save-vid

python3.9 track.py --source 'k3008u2szwb.mp4' --show-vid
python3.9 track.py --source 'k3008u2szwb.mp4' --save-vid

du -ah
du -h -d 1
./deep_sort_pytorch/deep_sort/deep/checkpoint/ckpt.t7

wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5l.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5n.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5s.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5m.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5x.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5n6.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5s6.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5m6.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5l6.pt
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5x6.pt
```

```
https://pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html

https://pjreddie.com/darknet/yolo/

yolov5l.pt

https://dl.teamviewer.com/download/version_15x/TeamViewer.dmg
https://dl.teamviewer.cn/download/version_15x/TeamViewer.dmg

vim ./yolov5/utils/downloads.py
assets = ['yolov5n.pt', 'yolov5s.pt', 'yolov5m.pt', 'yolov5l.pt', 'yolov5x.pt',
                      'yolov5n6.pt', 'yolov5s6.pt', 'yolov5m6.pt', 'yolov5l6.pt', 'yolov5x6.pt']

Real-time multi-object tracker using YOLO v5 and deep sort

real time object track

virtualenv

rtmp 测试地址
rtmp test address

rtmp server

cd /model
python /code/src/fashion_mnist/train.py
mv model pytorchModel
```

```
python3.9 track.py -h                         
usage: track.py [-h] [--yolo_weights YOLO_WEIGHTS [YOLO_WEIGHTS ...]] [--deep_sort_weights DEEP_SORT_WEIGHTS]
                [--source SOURCE] [--output OUTPUT] [--imgsz IMGSZ [IMGSZ ...]] [--conf-thres CONF_THRES]
                [--iou-thres IOU_THRES] [--fourcc FOURCC] [--device DEVICE] [--show-vid] [--save-vid]
                [--save-txt] [--classes CLASSES [CLASSES ...]] [--agnostic-nms] [--augment] [--evaluate]
                [--config_deepsort CONFIG_DEEPSORT] [--half] [--visualize] [--max-det MAX_DET] [--dnn]

optional arguments:
  -h, --help            show this help message and exit
  --yolo_weights YOLO_WEIGHTS [YOLO_WEIGHTS ...]
                        model.pt path(s)
  --deep_sort_weights DEEP_SORT_WEIGHTS
                        ckpt.t7 path
  --source SOURCE       source
  --output OUTPUT       output folder
  --imgsz IMGSZ [IMGSZ ...], --img IMGSZ [IMGSZ ...], --img-size IMGSZ [IMGSZ ...]
                        inference size h,w
  --conf-thres CONF_THRES
                        object confidence threshold
  --iou-thres IOU_THRES
                        IOU threshold for NMS
  --fourcc FOURCC       output video codec (verify ffmpeg support)
  --device DEVICE       cuda device, i.e. 0 or 0,1,2,3 or cpu
  --show-vid            display tracking video results
  --save-vid            save video tracking results
  --save-txt            save MOT compliant results to *.txt
  --classes CLASSES [CLASSES ...]
                        filter by class: --class 0, or --class 16 17
  --agnostic-nms        class-agnostic NMS
  --augment             augmented inference
  --evaluate            augmented inference
  --config_deepsort CONFIG_DEEPSORT
  --half                use FP16 half-precision inference
  --visualize           visualize features
  --max-det MAX_DET     maximum detection per image
  --dnn                 use OpenCV DNN for ONNX inference
```
