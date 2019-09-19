
Put haarcascade.xml and .py into the same folder.
Change the path of filepath, point it to where files located.

For final.py:
	If you want output pictures with more emphasizing on the edge with sober filter, remove # on the row where sobelFilter() is.
	If you want to change images' sizes, change x and y in the function resize(, (x,y).
	Output will create in the folder where .py file is.

For dataAugmentation.py:
	In function dataAugmentation, 
		change save_to_dir="folder name" in the loop condition.
		change if > "number" if you want to change the number of output.
	