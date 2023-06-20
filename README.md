# 📥 `pyppbox-data`

* `pyppbox-data` can dynamically create individual data packages for the supported dectors/trackers/reiders of [`pyppbox`](https://github.com/rathaumons/pyppbox) V3 -> Learn more about the new structure of `pyppbox` V3 in the [official documentation](https://rathaumons.github.io/pyppbox/).
* `pyppbox-data` relies on its configurations inside [`setupconfig`](setupconfig) in order to create individual Python wheel installers.
* We only inlcude very minimal amount of the neccessary pretrained weight/model in our prebuilt `.whl` files, and you can download these individual `.whl` files from the GitHub releases: https://github.com/rathaumons/pyppbox-data/releases
* We don't include the pretrained weight/model files in this GitHub repo. If you want other pretrained files, please refer to the original authors.
