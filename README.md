# EasyVizAR supported ImVoxelNet 3D Object Detection Module

This module interfaces with the [EasyVizAR Edge Server](https://github.com/EasyVizAR/edge-server), facilitating automated object detection on images captured by AR headset devices like the Microsoft Hololens2. Leveraging the capabilities of the monocular/multi-view 3D object detector, [ImVoxelNet](https://github.com/SamsungLabs/imvoxelnet), it ensures precise identification of objects within the AR environment. Aligned with [REST API principles](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design), our module integrates with the EasyVizAR server implementation, enabling standardized and streamlined communication protocols.

This implementation was based upon EasyVizAR supported YOLOv8 Object Detection add-on module.
<https://github.com/EasyVizAR/detect>

## Installation

Install dependencies.

```console
python3.6 -m pip install --upgrade pip
python3.6 -m pip install -r requirements.txt
```

Make a choice of configuration and checkpoint file to use from [ImVoxelNet dataset](https://github.com/SamsungLabs/imvoxelnet/blob/master/README.md#models).

Run the detector.
```console
python3.6 -m detect
```
