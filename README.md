Plotly: Data Visualization

Plotly is known as an interactive Python library for creating charts, graphs, maps and multidimensional models. It is most commonly used for data analysis, dashboard development and integration with other web applications. It also works well for web-based rendering including HTML, CSS and JavaScript. Plotly is similar, in its use, to Matplotlib. However, the key differences are that Plotly has interactivty capability and can generate 3D models and map visuals, whereas Matplotlib focuses on static images. Plotly also integrates with other libraries and environments included Pandas, NumPY, Dash and Jupyter Notebooks.

Installation Instructions
1. Clone GitHub Repository: https://github.com/cdeperro1/Plotly
2. Open Jupyter Notebook from Anaconda 
3. Ensure Jupyter notebook is running at the latest version. If necessary, use pip and upgrade to install:
   pip install --upgrade notebook
4. Install plotly using the pip command:
   pip install plotly
5. The focus for the tutorial will be the application of Plotly Express. To allow interactivity between Plotly and Jupyter Notebook, ensure Jupyer's widgets are installed. (This will make it easier to create and engagew with the plots. Use both pip and ipywidgets to complete installation):
   pip install ipywidgets

As a recap, Plotly is a Python-based library. However, even if Python is already installed, Plotly is not by default included in the standard package. Therefore, installing Plotly separately is required. 

There are mutliple Plotly Modules available to use:
A. Plotly Express: Used to create quick and simple plots, requiring minimal code
B. Plotly Graph Objects: Adds extra layer of customization and detail to further interact with plots
C. Plotly Subplots: Generating multiple plots within a single figure
D. Dash: Developing web apps using Plotly
E. Plotly Figure Factory: Used for more advanced plotting (such as heat maps, and diagrams)
F. Plotly IO: Used for modifying figures

For the purpose of today's exercise we will focus on creating plots using Plotly Express. 
We will review various plots based on 2020-2024 tornado csv data reported by the National Oceanic and Atmospheric Assocation.
Reference "Plotly_Tornado.ipynb" file to view the code for the line graphs, bar charts and choropleth map presented in the deck. 
Our final step will be to complete a quick tutorial on creating pie charts using the Plotly Express module. 
For the tutorial, please reference the "Tornado_Pie_Shell.ipynb" - this is an incomplete template we will populate during class.   
Solutions can be found in the "Tornado_Pie_Solutions.ipynb" file. 
