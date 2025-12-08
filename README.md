<h1> Data-Driven Site Selection Project</h1>


<h2>Description</h2>
Duluth (MN) experienced a population and economic growth between 2010 and 2024 which provides push for new commercial activities and constructions. However, the hilly topography of the city exerts constraints. Creating a pipeline to identify suitable locations within a certain budget was the primary motivation behind this 2-member group project, completed to satisfy the requirements of my Geograghic Information System course in December 2025. We utilized spatial data science techniques (primarily Cost Surfaces) considering two important parameters: Slope and Distance from Roads. We succesfuly delivered the end product- demarcating about 260 square km of area within the city as potentially suitable. 
<br />


<h2>Languages and Platforms Used</h2>

- <b>ArcGIS Pro</b> 
- <b>Python</b>
- <b>SQL</b>

<h2>Project walk-through:</h2>

<p align="center">
Data Extraction from Multiple Sources: <br/>
<img src="https://i.imgur.com/7jHplNa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/TGLpfA2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visualizing Road Network across Duluth in ArcGIS Pro (post SQL querying within the platform):  <br/>
<img src="https://i.imgur.com/sUyinmx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visualizing Digital Elevation Model (DEM): <br/>
<img src="https://i.imgur.com/97hAolE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Python Commands for creating Slope Cost Surface using DEM:  <br/>
<img src="https://i.imgur.com/vX6js90.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/0bCFc86.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visualizing Slope Cost Surface:  <br/>
<img src="https://i.imgur.com/RSZeK2E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visualizing Road Cost Surface (post Python processing):  <br/>
<img src="https://i.imgur.com/uDAeo9V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Combining Slope and Road Cost Surfaces to get Total Cost Surface:  <br/>
<img src="https://i.imgur.com/lCYRhS9.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visualizing Total Cost Surface:  <br/>
<img src="https://i.imgur.com/1mjlahw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Eliminating Pixels that Exceed the Budget using a Mask:  <br/>
<img src="https://i.imgur.com/pLLdGjR.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Final Cost Surface (Downtown zoomed in on inset map):  <br/>
<img src="https://i.imgur.com/xFUJIlT.jpeg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
