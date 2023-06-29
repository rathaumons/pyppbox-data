# 📥 `pyppbox-data`

* `pyppbox-data` can dynamically create individual data package for the supported dectors/trackers/reiders of [`pyppbox`](https://github.com/rathaumons/pyppbox) V3 -> Learn more about the new structure of `pyppbox` V3 in the [official documentation](https://rathaumons.github.io/pyppbox/).

* `pyppbox-data` relies on its configurations inside [`setupconfig`](setupconfig) in order to create individual Python wheel installers.

* We only inlcude very minimal amount of the neccessary pretrained weight/model in our prebuilt `.whl` files, and you can download these individual `.whl` files from the GitHub releases: https://github.com/rathaumons/pyppbox-data/releases

* We don't include the pretrained weight/model files in this GitHub repo as they are big and consume over 1 GB of storage space.

## Installation (Only for `pyppbox` V3)

* `YOLO_Classic` | [License/Repo](https://github.com/AlexeyAB/darknet):
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.0/pyppbox_data_yolocls-1.0-py3-none-any.whl
    ```

* `YOLO_Ultralytics` | [License/Repo](https://github.com/ultralytics):
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.0/pyppbox_data_yoloult-1.0-py3-none-any.whl
    ```

* `DeepSORT` | [License/Repo](https://github.com/deshwalmahesh/yolov7-deepsort-tracking):
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.0/pyppbox_data_deepsort-1.0-py3-none-any.whl
    ```

* `FaceNet` | [License/Repo](https://github.com/davidsandberg/facenet):
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.0/pyppbox_data_facenet-1.0-py3-none-any.whl
    ```

* `Trochreid` | [License/Repo](https://github.com/KaiyangZhou/deep-person-reid):
    ```
    pip install https://github.com/rathaumons/pyppbox-data/releases/download/v1.0/pyppbox_data_torchreid-1.0-py3-none-any.whl
    ```

