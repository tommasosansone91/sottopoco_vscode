# sottopoco VScode



<div style="text-align:center">
	<img src="https://raw.githubusercontent.com/tommasosansone91/canederli/main/images/sottopoco_vscode1.png" style="width:60%;" align="middle" alt="cover of Canaderli python package" >
</div>

<br>

The objects in this package are useful to practice with python opencv on VScode.

Generally, it is preferable to use Jupiter Notebook to practice with opencv.
This is because JN allows easy ways to manage and display images.
But in case one wants to do the practice with VScode instead of JN, here comes this package.

Please note that the function 'cyclical_drawing' might be very CPU and RAM consuming, and should be used only to display an image we want to 'real-time' draw on it.

The objects in this package are classified into different categories:

- loaders:       They load an image and directly apply some transformation (recoloring, resizing).<br>
- converters:    They convert an image from a format to another ( objects handled by matplotlib.pyplot.plot() into objects handled by cv2.imread() )
- painters:      They allow to paint many images at once, save time in defining windows names, setting the conditions to close the windows, etc.   

