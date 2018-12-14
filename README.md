# YOLO-Annotation-Tool
## This is for creating the training set of images for YOLO

###### Commands on terminal:
```
git clone https://github.com/ManivannanMurugavel/YOLO-Annotation-Tool.git

cd YOLO-Annotation-Tool
```
### Create 001 folder in Images folder and put your class one images

### Convert to .JPEG from any type of images. Use this command(Ubuntu)

```mogrify -format jpg *.JPEG```
or
```mogrify -format jpg *.jpeg```
or
```mogrify -format jpg *.png```

### Run Main python script 

 ``` python main.py ```

### Run convert python file for create final text file for yolo images 

```python convert.py```
# -------Progress-------
