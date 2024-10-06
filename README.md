# 📥 `pyppbox-data`

* `pyppbox-data` can dynamically create individual data packages of the supported dectors/trackers/reiders for [`pyppbox V3`](https://github.com/rathaumons/pyppbox) -> Learn more about [the new structure here](https://rathaumons.github.io/pyppbox/pyppbox/structure.html).

* `pyppbox-data` relies on the configurations inside [`setupconfig`](setupconfig) in order to create individual Python wheels.

* Only a few pretrained weight/model files are included in the prebuilt `.whl` [files on GitHub releases](https://github.com/rathaumons/pyppbox-data/releases).

* The pretrained weight/model files are not included in the repo as they are too big (Over 1GB).

## Installation (Only for `pyppbox` V3)

* `YOLO_Classic` | [License/Repo](https://github.com/AlexeyAB/darknet)
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.2.0/pyppbox_data_yolocls-1.2.0-py3-none-any.whl
    ```

* `YOLO_Ultralytics` | [License/Repo](https://github.com/ultralytics)
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.2.0/pyppbox_data_yoloult-1.2.0-py3-none-any.whl
    ```

* `DeepSORT` | [License/Repo](https://github.com/deshwalmahesh/yolov7-deepsort-tracking)
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.2.0/pyppbox_data_deepsort-1.2.0-py3-none-any.whl
    ```

* `FaceNet` | [License/Repo](https://github.com/davidsandberg/facenet)
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.2.0/pyppbox_data_facenet-1.2.0-py3-none-any.whl
    ```

* `Trochreid` | [License/Repo](https://github.com/KaiyangZhou/deep-person-reid)
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.2.0/pyppbox_data_torchreid-1.2.0-py3-none-any.whl
    ```

