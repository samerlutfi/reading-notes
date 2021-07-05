### Charts:
![s](https://res.cloudinary.com/practicaldev/image/fetch/s--Tmx9gqIx--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://i2.wp.com/blogreact.com/wp-content/uploads/2020/06/charts.png%3Ffit%3D750%252C398%26ssl%3D1)
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

* The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options listed in the documentation.

- there is differents types of charts:
1-bar chart
2-line chart
3-radar chart
4-pie chart
5-dounnt chart
6-area chart..etc

**Create Chart:**
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single canvas node to render the chart.

In this example, we create a bar chart for a single dataset and render that in our page. You can see all the ways to use Chart.js in the usage documentation.

**The rendering context:**
The canvas element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES

* **Checking for support:**
The fallback content is displayed in browsers which do not support canvas. Scripts can also check for support programmatically by testing for the presence of the getContext() method. 

**Drawing text:**
>* fill text
>* storked text

* **styling text**
The current text style being used when drawing text. This string uses the same syntax as the CSS font property.

**Drawing paths:**
Now let's look at paths. A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

First, you create the path.
Then you use drawing commands to draw into the path.
Once the path has been created, you can stroke or fill the path to render it.
Here are the functions used to perform these steps:

beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
closePath()
Adds a straight line to the path, going to the start of the current sub-path.
stroke()
Draws the shape by stroking its outline.
fill()
Draws a solid shape by filling the path's content area.
The first step to create a path is to call the beginPath(). Internally, paths are stored as a list of sub-paths (lines, arcs, etc) which together form a shape. Every time this method is called, the list is reset and we can start drawing new shapes.

Note: When the current path is empty, such as immediately after calling beginPath(), or on a newly created canvas, the first path construction command is always treated as a moveTo(), regardless of what it actually is. For that reason, you will almost always want to specifically set your starting position after resetting a path.
The second step is calling the methods that actually specify the paths to be drawn. We'll see these shortly.

The third, and an optional step, is to call closePath(). This method tries to close the shape by drawing a straight line from the current point to the start. If the shape has already been closed or there's only one point in the list, this function does nothing.

Note: When you call fill(), any open shapes are closed automatically, so you don't have to call closePath(). This is not the case when you call stroke().


