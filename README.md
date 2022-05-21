# Visual Inspection of Motorcycle Connecting Rods
Software system aimed at visual inspection of motorcycle connecting rods. The system should be able to analyze the dimensions of two different types of connecting rods to allow a vision-guided robot to pick and sort rods based on their type and dimensions. The two rod types are characterized by a different number of holes: Type A rods have one hole whilst Type B rods have two holes. 

## Task 1
We consider the following condition for each image:
1. Images contain only connecting rods, which can be of both types and feature significantly diverse dimensions.
2. Connecting rods have been carefully placed within the inspection area so to appear well separated in images (i.e. they do not have any contact point).
3. Images have been taken by the backlighting technique so to render rods easily distinguishable (i.e. much darker) from background. However, for flexibility reasons the system should not require any change to work properly with lighting sources of different power. 

For each connecting rod appearing in the image, the vision system provides the following information:
1. Type of rod (A or B).
2. Position and orientation.
3. Length, Width, Width at the barycenter.
4. For each hole, position of the centre and diameter size.

## Task 2
While still meeting the requirement of the First Task, the system has been modified in order to deal with one (or more) of the following three changes in the characteristics of the working images:
1. Images may contain other objects (i.e. screws and washers) that need not to be analysed by the system (such kind of objects are often referred to in computer vision as “distractors”).
2. Rods can have contact points but do not overlap one to another.
3. The inspection area may be dirty due to the presence of scattered iron powder

## Working Images
The available working images can be distinguished into two different groups in order to provide a better understanding of the overall activity carried out.

**Task 1**: Tesi00.bmp, Tesi01.bmp, Tesi12.bmp, Tesi21.bmp, Tesi31.bmp, Tesi33.bmp. 

**Task 2**:
1. Tesi44.bmp, Tesi47.bmp, Tesi48.bmp, Tesi49.bmp.
2. Tesi50.bmp, Tesi51.bmp.
3. Tesi90.bmp, Tesi92.bmp, Tesi98.bmp

## Running
To execute the program is required to install all the imported Python packages. After that, it is necessary to run the "main.py" script, making sure to be located in the same directory of the "images" folder.
