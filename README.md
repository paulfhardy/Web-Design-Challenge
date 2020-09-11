## Web-Design-Challenge

The application URL is [here](https://paulfhardy.github.io/Web-Design-Challenge/)

#### Please note:

All components and requirements of this challenge have been met including some of the bonus items as described below:
<br>
1)  The __Landing__ Page contains:
    * An explanation of the project.
    * Links to each visualization page. 
    * The Sidebar contains preview images of each plot, and clicking an image takes the user to that visualization.
    
2) Four __Visualization__ pages, each with:
   * A descriptive title and heading tag.
   * The plot for the selected comparison.
   * A paragraph describing the plot and its significance.
   * I have also made the primary image on each visualization clickable so that the user can choose to view it in a separate browser page, zoom in, etc.
   
3) A __Comparisons__ page that:
   * Contains all of the visualizations on the same page to enable easy visual comparison.
   * Each visualization is clickable and navigates to the detailed visualization page for that plot.
   * Uses a Bootstrap grid for the visualizations.
   * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
   
4) A __Data__ page that:
   * Displays a responsive table containing the data used in the visualizations. (2 tables)
   * The table is a bootstrap table component.
   * It is responsive.
   * The data came from importing the original .csv files into Pandas and exporting them back out as HTML files. The code for this is in
     a Jupyter Notebook named "convert_csv_to_html.ipynb" in the "assets" subfolder.
   
5) All __Navbar__ requirements for the application were met including:
   * When screen sizes change from large to small the menu collapses to a sandwich menu.
   * The Navbar utilizes the "navbar" component of bootstrap.
   * The navbar has a "Home button on the left" and the other 3 buttons (one with a dropdown menu) on the right.

   For the components mentioned as __Bonus__ work:
   1) A different dataset was used - based on NBA team wins data for the past 5 seasons.
   2) I enabled visualization navigation on every visualization page with an active state - a redorange box indicates the active visualization.
   3) Menu items are highlighted when the user hovers over them.
   
