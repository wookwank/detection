# EasyVizAR supported ImVoxelNet 3D Object Detection Module

This module interfaces with the [EasyVizAR Edge Server](https://github.com/EasyVizAR/edge-server), facilitating automated object detection on images captured by AR headset devices like the Microsoft Hololens2. Leveraging the capabilities of the monocular/multi-view 3D object detector, [ImVoxelNet](https://github.com/SamsungLabs/imvoxelnet), it ensures precise identification of objects within the AR environment. Aligned with [REST API principles](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design), our module integrates with the EasyVizAR server implementation, enabling standardized and streamlined communication protocols.

This implementation was based upon EasyVizAR supported YOLOv8 Object Detection add-on module.
<https://github.com/EasyVizAR/detect>

## Installation & Setup

Install dependencies.

```console
python3 -m pip install -r requirements.txt
```

Initialize the ImVoxelNet model by downloading [configuration](https://github.com/SamsungLabs/imvoxelnet/blob/master/configs/imvoxelnet/imvoxelnet_total_sunrgbd_fast.py) and [checkpoint file](https://github.com/saic-vul/imvoxelnet/releases/download/v1.2/20211007_105247.pth).
