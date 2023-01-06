# Data Visualization

> ## [Matplotlib Tutorial](https://www.labri.fr/perso/nrougier/teaching/matplotlib/)

* **pyplot** provides a convenient interface to the matplotlib object-oriented plotting library

* How to change the color and width of a plot: 

...

plt.figure(figsize=(10,6), dpi=80)

plt.plot(X, C, color="blue", 
linewidth=2.5, linestyle="-")

plt.plot(X, S, color="red",  
linewidth=2.5, linestyle="-")

...

* If you want to set limits on the graph, use these commands:
  * xlim() command
  * ylim() command

* If you want to change ticks on a graph and set tick values, use these commands:
  * xticks() command
  * yticks() command

* Spines are the lines connecting the axis tick marks and noting the boundaries of the data area. To change just use .spines[]

* To add a legend, use .legend()
  * example: 

  plt.plot(X, C, color="blue", linewidth=2.5, linestyle="-", label="cosine")

  plt.plot(X, S, color="red",  linewidth=2.5, linestyle="-", label="sine")

  plt.legend(loc='upper left', frameon=False)

> ### Other reads

* [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

* [Seaborn Cheat Sheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Seaborn_Cheat_Sheet.pdf)

* [Bokeh Tutorial](https://mybinder.org/v2/gh/bokeh/bokeh-notebooks/master?filepath=tutorial%2F00%20-%20Introduction%20and%20Setup.ipynb)



[Return Home](../README.md)
