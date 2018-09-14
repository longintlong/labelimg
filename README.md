mylabelImge

This repository is just used to make a dataset

My own annotation file and class names file.

One row for one image.

Row format: image_file_path box1 box2 ... boxN

Box format: x_min,y_min,x_max,y_max,class_id (no space)

Here is an example:

```
path/to/img1.jpg 50,100,150,200,0 30,50,200,120,3
path/to/img2.jpg 120,300,250,600,2
...
```


usage

Under the project root file，run the following code:

    python3 labelImg.py

ps: data/predefined_classes.txt is the classes name file

you can also see the Detailed tutorial at https://github.com/tzutalin/labelImg
