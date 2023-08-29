# sottopoco VScode



<div style="text-align:center">
	<img src="https://raw.githubusercontent.com/tommasosansone91/sottopoco_vscode/main/images/sottopoco_vscode1.png" style="width:100%;" align="middle" alt="cover of sottopoco_vscode python package" >
</div>

<br>

sottopoco is a simple python package containing objects which are useful to practice with python opencv on VScode.

Generally, it is preferable to use Jupiter Notebook to practice with opencv.
This is because JN allows easy ways to manage and display images.
But in case one wants to do the practice with VScode instead of JN, here comes this package.

The objects in this package are grouped into different categories:

- loaders:       They load an image and directly apply some transformation (recoloring, resizing).<br>
- converters:    They convert an image from a format to another ( objects handled by matplotlib.pyplot.plot() into objects handled by cv2.imread() )
- painters:      They allow to paint many images at once, save time in defining windows names, setting the conditions to close the windows, etc.   

Please note that the function 'cyclical_drawing' might be very CPU and RAM consuming, 
and should be used only to display images we want to 'real-time' draw on.

