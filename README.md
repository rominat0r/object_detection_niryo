
# Using custom object detection with Niryo

This project uses Tensorflow object detection model to identitfy objects and interact with them using Niryo robot. 


## Installation

After cofiguring virtual enviroment and installing requirements.txt.  
Run the following commands: 

```bash
sudo apt install -y protobuf-compiler
cd models/research/
protoc object_detection/protos/*.proto --python_out=.
cp object_detection/packages/tf2/setup.py .
python -m pip install .
```
    
