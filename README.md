# Fork of [Zeyi-Lin/HivisionIDPhotos](https://github.com/Zeyi-Lin/HivisionIDPhotos)

Differences between original repository and fork:

* Updated Python dependencies. (🔥)
* Web interface translated to English. (🔥)
* The following errors has been fixed:
  * AttributeError: 'Image' object has no attribute 'style'.
  * AttributeError: type object 'Image' has no attribute 'update'

# Installation

```shell
pip install -r requirements.txt
```

# Usage

* Download model file ([hivision_modnet.onnx](https://github.com/clibdev/HivisionIDPhotos/releases/latest/download/hivision_modnet.onnx)) and save it in the root directory.
* Run the application:

```shell
python app.py
```
