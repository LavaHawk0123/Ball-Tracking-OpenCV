# Ball-Tracking-OpenCV
An OpenCV based module to help detect an Orange ball effectively and estimate its centre in different lighting conditions

#### To find the proper HSV Values : 
```
cd Ball-Tracking-OpenCV
python3 RangeDetector.py
```
Output : 

![BitMaskCreate](https://user-images.githubusercontent.com/75236655/182964163-f2f5324a-4d43-4813-b78a-a8fc43021bab.png)
After entering the ideal HSV values,
#### To launch the node :
```
cd Ball-Tracking-OpenCV
python3 ball_tracker.py
```
<h2> Multiple Testing Environments</h2>
<h3> Regular Lighting </h3>

![ball_reg](https://user-images.githubusercontent.com/75236655/182962915-9b843b92-577c-438a-aced-448943f70869.gif)

<h3> Bright Sun Lighting </h3>

![ball_sun](https://user-images.githubusercontent.com/75236655/182963145-bea2a7fc-71d2-4f72-9a6f-c54b96d129a6.gif)

<h3> Torch Lighting </h3>

![ball_torch](https://user-images.githubusercontent.com/75236655/182963338-5a39eb1c-d3fc-435d-a98e-310910b1dd4f.gif)
