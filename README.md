# copy-images-with-python
This python code will read all the images names stored in an excel column and copy those images from one folder to another. 

### Libraries used in this codes are:
1. openpyxl
2. load_workbook
3. shutil
4. os
5. tqdm

<br />

### How this code works?
- The code will first read an excel workbook (this workbook will include the names of images in first column that you want to copy from a directory to a new directory).
- It will then read the worksheet in the excel workbook
- Using python libraries it will access the images and copy from origin directory to destination
- You can easily copy or move images by using shutil.copy or shutil.move

<br />

**Working with machine learning datasets a stage definetly come when you only want to copy hundreds of images from a direcotry that has thousand of images.
Doing this task manually is really tedious. Using this code you can easily automate the copy mechanism by only putting the names of images in an excel 
sheet column.**

<br />

*I was doing a project where I have pnemonia images and normal x-ray images mixed in a folder. The dataset has an excel file where the name of images and
it's class was mentioned. Using this code I was able to separate those images in 2 folders where first folder was normal and second has the infected images.*
