# Tableau Public II - Data Sources and the Tableau Workspace

## Introduction
In the previous lesson, we used the Connect pane on the Start page to open the Superstore Sales sample data set that we downloaded from the Tableau Resources collection. This will have opened the a new Tableau workbook to the __Data Source page__. Which should look like this:
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/tab-2-1-data-source.png" alt="This is the alt-text for the image." style="width: 800px;"/>
</td></tr></table>
    </center>
</div>

In this lesson, we will discuss the components of the Data Source page. Then, we will launch the Tableau workspace, explore its components, and create our first Tableau workbook.

## Learning Objectives
In this lesson, we will:
* identify and describe the core components of the __Data Source page__
* populate the Data Source page with data from the Superstore Sales dataset
* launch the __Tableau workspace__ from the Data Source page

## Core Components of Data Source Page
Let's begin by examining the core components of the Data Source Page. 

In the image below, each of the components of the Tableau Data Source page have been assigned a number. Under the image, you will find a description for each numbered component.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/tab-2-2-data-source.png" alt="This is the alt-text for the image." style="width: 800px;"/>
</td></tr></table>
    </center>
</div>

### 1. Sheets Tab
In Tableau, sheets can be worksheets, dashboards, or stories. Each of these can be created by selecting the appropriate icon from the sheets tab. In upcoming lessons we will explore how to create the various kinds of Tableau sheets in greater detail. For now, let's get a sense of how to create new sheets by identifying each of the icons.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/tab-2-3-sheets-tab.png" alt="This is the alt-text for the image." style="width: 300px;"/>
</td></tr></table>
    </center>
</div>


<b>1. Worksheet Icon <br></b>
> A __worksheet__ is composed of one __visualization view__ along with the __shelves__, __cards__, and other tools used to create each view. 

<b>2. Dashboard Icon <br></b>
> A __dashboard__ is a collection of views from many worksheets. 

<b>3. Story Icon <br></b>
> A __story__ is a collection of worksheets or dashboards that have been organized in a presentation like format so the viewer is able to understand the data in the order the creator intended. 

### 2. Left Pane
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/tab-2-4-left-pane.png" alt="This is the alt-text for the image." style="width: 200px;"/>
</td></tr></table>
    </center>
</div>

#### 1. Connections Card
Displays the connected data source and other details about the connected data.
* When using __file based data__ (like CSV files and Excel workbooks), the __Left pane__ contains data such as the file name and worksheets in the workbook.
* When using __relational data__ (like a databases), the left pane contains server information, tables in the database, and the database schema.

#### 2. Sheets Card
Displays information about the current workbook, including the tables in the data and the relationships between table.


###  3. Canvas: logical layer
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/tab-2-5-canvas.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
    </center>
</div>

The canvas opens with the logical layer, where you can create relationships between tables. If you double-click a table in the logical layer, it opens the __Canvas physical layer__ where you can add joins and unions between tables to create a unified data source.
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/tab-2-5-canvas.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
    </center>
</div>

### 4. Command Bar
The command bar contains shortcuts to common commands. Some of these commands may seem unfamiliar, but we will cover them in upcoming lessons.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/tab-2-6-command-bar.png" alt="This is the alt-text for the image." width=75%/>
</td></tr></table>
    </center>
</div>

<b>1. Tableau Icon</b>
> Allows us to return to the Start Page <br>


<b>2. Undo/Redo</b>
> Return to the previous action or repeat the previous action <br>


<b>3. Replay Animation</b>
> Replays an animation on a dashboard <br>


<b>4. Save</b>
> Save your workbook locally or to Tableau Public <br>


<b>5. Run Update</b>
> Runs a manual query of the data to update the view with changes

<div class="alert alert-success">
<h3>Your Turn: Populate the Data Source Page</h3><br>
Now, we will populate the Data Source Page with data from our sample database.<br>

1. First, Drag the __Orders table__ from the Left pane to the Canvas. Now, your screen should look like this:
<br>
<div>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/workbook2.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="width: 800px;"/>
</td></tr></table>
</div>    
<br>
2. You should notice that two more panes appear in the lower portion of your screen. This is the __Data grid (6)__, which displays a preview of the first 1,000 rows of the data contained in the data source that we selected from the Left pane and the __Metadata grid (5)__ displays the fields in your data source as rows.
<br>
<br>
3. Since we have populated the Data Source page with at least one table from your data source, you can begin working with the data in the __Tableau Workspace__. To launch the Tableau workspace, select __worksheet__ from the Sheets tab and create a sheet.<br>

Great! Now you have populated the Data Source page and created your first sheet.
</div>

## Components of the Tableau Workspace
The Tableau workspace consists of menus, a toolbar, the Data pane, cards and shelves, and one or more sheets. Sheets can be worksheets, dashboards, or stories. In the image below, we have divided the Tableau workspace into quadrants and labeled them. Let's explore each of the quadrants. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/workspace2.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="width: 800px;"/>
</td></tr></table>
    </center>
</div>

### 1. The Data Pane/Data Tab
First, let's take a look at the __Data pane__. Keep in mind that some of these components will change slightly as we begin working with multiple data sources in future lessons.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/data-pane.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 350px;"/>
</td></tr></table>
    </center>
</div>

<b>1. Data Source</b><br>
> Displays the name of the primary table that we used to populate the Data source page. We do not need to worry about this just yet, since we are only using one able.

<b>2. Search Bar</b><br>
> Allows us to search all of the column names in our data source. If multiple data sources were loaded, we could search among the columns from all of those sources. 

<b>3. Tables</b><br>
> This is where the schema for each data source will be displayed. When there is a single data source, only the column names are displayed. When there are multiple data sources, the table name will displayed with the column names underneath.

<b>4. Dimensions and Measures</b><br>
> Below the Tables section there are two lists. Notice how how they are color coded? The first list has a blue font, while the second has green font. In addition, each of the items on the list have a special icon next to them. These are known as __<font color='blue'>Dimensions</font>__ and __<font color='green'>Measures</font>__, and they are a comprehensive list of the different columns in all of the data sources connected to the workspace. We will dive into the logic behind the colors and icons soon!

<b> 5. Analytics Tab</b><br>
> For the next few lessons, we will be focusing on the Data tab. However, it will be helpful to know where the Analytics tab is for future lessons.

### 2. Shelves and Cards
In between the Data pane and active sheets are three rectangles. The first two, __Pages__ and __Filters__ are called shelves. The third rectangle, __Marks__ is called a card. Let's briefly discuss shelves and cards in Tableau so that we can prepare to learn some of the most common operations in the upcoming lab.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/shelves.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 350px;"/>
</td></tr></table>
    </center>
</div>

### Shelves
Shelves are objects where you can drag __pills__ which are just specific data points from your dataset. Dragging a pill to shelf triggers to Tableau to execute an operation on that data point, such as adding the data to the visualization, excluding data from the visualization or performing aggregate operations.

For example, if we hover over the name of a dimension or measure in the data pane it becomes a pill (indicated by the oblong highlight around the text) that we can drag it to a shelf (in this example it is the Row and Column shelves -- read more about those in __Sheets Pane__ section).
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/pill-example.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 350px;"/>
</td></tr></table>
    </center>
</div>

<b> 1. Pages shelf </b><br>
> Helps to break up your view into multiple pages so you can better analyze the effect one specific field has on the rest of the data. 

<b> 2. Filters shelf </b><br>
> Allows you to choose which data to include and exclude from your view.

### Cards
Cards are objects that allow you to apply formatting to your visualizations.

<b> 3. Marks card </b><br>
> Allows you to add context and detail to your visualizations. You can also customize the appearance of the visualizations in the marks card such as adding color, text and adjusting the size of different features.

### 3. The Sheets Pane
The sheets pane is the primary place where your data visualizations will be displayed. However, it will remain blank until we populate the row and column shelves directly above it.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/sheets-pane.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 350px;"/>
</td></tr></table>
    </center>
</div>

#### Row and Column Shelves
At the top of the Sheets pane, When you add data to your worksheet, you do so by dragging a pill to either the Rows or Columns shelf. This is Tableau's version of an X and Y axis. In the image of the Sheets pane above, the Row and Column shelves are not populated. When we drag pills from Dimensions and Measures on the Date Pane to the row and column shelves, our Sheets pane will begin to populate. Keep in mind:

* When data is added to the Rows shelf, it will become the horizontal axis, and each entry in the data will become a row or a point on the horizontal axis in a visualization.
* When data is added to the Columns shelf, it will become the vertical axis, and each entry in the data will become a column or a point on the vertical axis in a visualization.

<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/pill-example.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 350px;"/>
</td></tr></table>
    </center>
</div>

### 4. The Show Me Pane
On the far right side of the screen is the Show Me pane. This is what is looks like before you have populated the Row and Column shelves.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/show-me-no-data.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 350px;"/>
</td></tr></table>
    </center>
</div>

Once you have populated the row and column shelves, you can use the Show Me Pane to:
* choose the type of visualization
* see the type of data needed for each visualization
* how many dimensions and measures are necessary to generate the visualization
* possible visualizations based on your data

<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/show-me-data.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 350px;"/>
</td></tr></table>
    </center>
</div>

### 5. The Menu Bar
At the top of your screen is the __Menu bar__. This menu bar contains many functions to help you in your creation of worksheets and dashboards. In the image below, we identify each component of the Menu bar. Read the descriptions under the image for a description of each component.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson2/menu-bar.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image."/>
</td></tr></table>
    </center>
</div>
<br>


<b>1. Tableau Icon</b><br>
> Will return you to the Start page where you can start a new workbook and connect to new data
<br>

<b>2. Undo and Redo</b><br>
> Will undo the last action and will do the last action that was undone
<br>

<b>4. Save</b><br>
> Will allow you to save your work either to Tableau Desktop or Tableau Public depending on which version you are using
<br>

<b>5. New Data Source</b><br>
> Will connect to a new data source
<br>

<b>6. New Sheet</b><br>
> Adds a new sheet to current workbook
<br>

<b>9. Swap</b><br>
>Moves the fields on the Rows shelf to the Columns shelf and vice versa.
<br>

<b>10. Sort Ascending/Descending</b><br>
>__Sort Ascending__ sorts values from smallest to largest and __Sort Descending__ will sort values from largest to smallest. 
<br>

<b>11. Highlight</b><br>
>Will turn on highlighting on the selected sheet, allowing you to accentuate important data points in your viz.
<br>

<b>12. Group Members</b><br>
>Combines selected values to create groups. Use the drop-down menu to specify whether to group on a specific dimension or across all dimensions if you are using multiple dimensions.
<br>

<b>13. Show Marks Labels</b><br>
> Reveal labels in visualization
<br>

<b>14. Fix Axis</b><br>
>Switches between a __locked axis__ (only shows a specific range) and a __dynamic axis__ that adjusts the range based on the minimum and maximum values in the view
<br>

<b>15. Fit</b><br>
> Will allow you to fit your visualization to the screen with the options of width, height, standard, and entire view
<br>

<b>16. Show/Hide Cards</b><br>
> Shows and hides specific cards in a worksheet. Just select the card you want to show or hide from the drop down menu. 
<br>

<b>17. Presentation Mode</b><br>
> Will allow you to hide all of the editing tools and present your worksheets or dashboards
<br>

## Summary
In this lesson, we populated the Data Source page with sample data from the Superstore Sales dataset. Then, we explored the components of the Data Source page and launched the Tableau workspace. Finally, we got familiar with the Tableau workspace to build a foundation for creating visualizations.

In the upcoming lesson, we will take a closer look at Measures and Dimensions and review some of the most useful visualizations you can create with Tableau. 
