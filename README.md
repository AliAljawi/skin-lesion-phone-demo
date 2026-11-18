# Skin lesion check: MobileNetV3-Large on the phone

**Live demo:** LIVE_URL

A MobileNetV3-Large classifier for 8 skin-lesion types (the ISIC 2019 classes), fine-tuned on ISIC 2019 and PAD-UFES-20 with the training recipe from our MAAI901 group project. The model is exported to ONNX and runs inside the browser with ONNX Runtime Web, so photos are processed on the device and never uploaded. It works on phones and desktop browsers.

- `docs/`: the web page, served by GitHub Pages
- `training/`: the notebook that downloads the data, trains and evaluates the model, and exports it

Research demo for teaching (MAAI901 Deep Learning for Visual Data, University of Wollongong in Dubai). It cannot diagnose skin cancer.

**Data:** ISIC 2019 (CC BY-NC 4.0) and PAD-UFES-20 (CC BY 4.0). The sample images in `docs/samples` come from the held-out test split of these datasets.
