Earthquake Project: Team 9
=============================
###Collaborators
<table border="0">
<tr>
<th>Name</th>
<th>Role</th>
<th>GitHub Id</th>
</tr>
<tr>
<td>Joy Chen</td>
<td>Visualizer</td>
<td>@joyyqchen</td>
</tr>
<tr>
<td>Sam Kirschner</td>
<td>Visualizer</td>
<td>@</td>
</tr>
<tr>
<td>Brian Liou</td>
<td>Presenter</td>
<td>@brianliou</td>
</tr>
<tr>
<td>Eric Tsai</td>
<td>Analyzer</td>
<td>@</td>
</tr>
</table>



###Task at Hand: Task 2
-------------------------------------------------------------------
<i>From the task list in the Issue Tracker of the Presenters Repository</i>
<br><br>
<b>Researching and Negotiating on Data Formats:</b>
- Curator: Construct interface for Curators and Visualizers to to utilize 
- what is the most common one
- JSON versus CSV versus XML
- Data Frame versus 2-D Array versus List of Dictionaries
- Analyzers/Visualizers: research sufficient/functional data formats in terms of ease-of-use and ability to produce visuals~~
- Presenters: decide on how to present the data
- iPython notebook, HTML, etc.
- what are the pro’s and con’s of each method
- which format could be used to make the graph dynamic?




###SMART Goals
-------------------------------------------------------------------
1. Determine which data format would be most appropriate for data curators to export/analyzers to use as inputs
2. Understand what data parameters come out of an ETAS Model
3. Create a standardized data format/structure for the outputs from the ETAS Model
4. Test to see if the formatted data can be imported into a visualization tool to be visualized* <br>
<i>*Since the actual data is currently unavailable, create proxy "fake" data in the same structure and format that we expect the real data to be in and test (4) using that data</i>

###Results
-------------------------------------------------------------------
1. Our group has determined that the CSV format would be most appropriate for data curators to export for analyzers to use in the models. CSV has the most efficient and simple structure and can be easily imported/disected by the analyzers. We have also determined that it would be helpful for the data curators to also publish the same data in JSON format for the visualizers. If some visualizers want to create graphs in D3, the JSON format would be most adaptable.
2. 
