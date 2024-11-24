# BKAI-IGH-NeoPolyp

[Model checkpoint link](https://drive.google.com/file/d/1kCxwcyl5qe4zPG5UpVzglQynYTPr6Kf8/view?usp=sharing). Make sure that the .pth checkpoint file is placed in the same folder as the infer.py script.

Make sure to download all required libraries in requirements.txt:
```
pip install -r requirements.txt
```
```
git clone https://github.com/buinguyenkhai/BKAI-IGH-NeoPolyp.git
```
```
cd BKAI-IGH-NeoPolyp
```
```
python3 infer.py --image_path image.jpeg
```
A new output folder will be created containing the output segmented image.
