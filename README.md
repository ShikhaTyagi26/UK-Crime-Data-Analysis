<h1>UK Crime Hotspot Analysis</h1>
<h3>Crime Hotspot Detection Using Geospatial Visualisation and Unsupervised Clustering</h3>

<hr>

<h2>Overview</h2>
<p>
This project investigates the spatial and temporal dynamics of crime in the United Kingdom using
<b>unsupervised machine learning</b> and <b>geospatial visual analytics</b>.
Python-based clustering techniques (DBSCAN and HDBSCAN) are applied to UK open police data to
identify statistically significant crime hotspots, while <b>Tableau dashboards</b> are used to
visualise hotspot distribution, persistence, and risk characteristics.
</p>

<p>
The analysis supports <b>evidence-based crime analysis</b> by revealing where crime concentrates,
how hotspots evolve over time, and how crime types and investigative outcomes vary across locations.
</p>

<hr>

<h2>Objectives</h2>
<ul>
  <li>Identify spatial crime hotspots using density-based clustering</li>
  <li>Analyse temporal persistence and change in hotspot locations</li>
  <li>Profile high-risk areas by crime type and outcome effectiveness</li>
  <li>Demonstrate how unsupervised learning supports geospatial decision-making</li>
</ul>

<hr>

<h2>Data Sources</h2>
<ul>
  <li>UK Open Police Data (Street-Level Crime and Outcomes)</li>
  <li>Time period: January – September 2025</li>
  <li>Original dataset size: ~3.67 million records</li>
  <li>Analytical sample: 50,000 records (validated against full dataset)</li>
</ul>

<p>
Due to GitHub file size limitations, large datasets are hosted externally and linked below.
</p>

<hr>

<h2>Project Structure</h2>
<pre>
UK-Crime-Data-Analysis/
│
├── notebooks/        Python notebooks for data cleaning, sampling, clustering,
│                     hotspot classification, and dataset generation
│
├── data/             Sample datasets used for analysis (excluding large raw files)
│
├── dashboards/       Tableau dashboard screenshots and supporting files
│
├── dissertation/     Dissertation document (PDF)
│
└── README.md         Project documentation
</pre>

<hr>

<h2>Methodology and Techniques</h2>
<ul>
  <li><b>Data Cleaning &amp; Preprocessing:</b> Pandas, NumPy</li>
  <li><b>Sampling Strategy:</b> Random sampling with statistical validation</li>
  <li><b>Clustering Algorithms:</b> DBSCAN and HDBSCAN</li>
  <li><b>Hotspot Classification:</b> Emerging, Stable, and Disappearing hotspots</li>
  <li><b>Spatial Analysis:</b> Latitude–longitude based clustering</li>
  <li><b>Temporal Analysis:</b> Month-wise crime trend evaluation</li>
  <li><b>Visual Analytics:</b> Tableau dashboards</li>
</ul>

<hr>

<h2>Tableau Dashboards</h2>
<p>Three interactive dashboards were developed in Tableau:</p>

<ol>
  <li><b>UK Crime Hotspot Overview</b><br>
      Spatial distribution of crime clusters across the UK</li>
  <li><b>Hotspot Dynamics: Emerging, Stable, and Disappearing</b><br>
      Temporal evolution and persistence of hotspots</li>
  <li><b>High-Risk Area Profiling</b><br>
      Crime type composition, outcome effectiveness, and LSOA-level interpretation</li>
</ol>

<p>
Dashboard screenshots are included in the <code>/dashboards</code> folder.
The full interactive Tableau workbook is available via Google Drive.
</p>

<hr>

<h2>Large Files and External Resources</h2>
<p>
Due to GitHub’s 100 MB file size limit, the following files are hosted externally:
</p>

<ul>
  <li>Cleaned Crime Dataset (3.67M records)</li>
  <li>Sample_50K dataset</li>
  <li>Tableau Workbook (.twbx)</li>
  <li>Clustering output files</li>
  <li>Raw UK police crime and outcome data</li>
</ul>

<p>
<b>Google Drive Repository:</b><br>
<a href="https://drive.google.com/drive/folders/1wO0OB9xg1nK5EHgHco3WNBdkM9NiHc5S?usp=sharing" target="_blank">
Access datasets and analytical artefacts
</a>
</p>

<hr>

<h2>How to Run the Project</h2>

<ol>
  <li>Clone this repository:
    <pre>git clone https://github.com/ShikhaTyagi26/UK-Crime-Data-Analysis.git</pre>
  </li>

  <li>Install required Python libraries:
    <pre>pip install pandas numpy scikit-learn hdbscan matplotlib seaborn</pre>
  </li>

  <li>Open the notebooks in the <code>/notebooks</code> directory to:
    <ul>
      <li>Clean and preprocess data</li>
      <li>Perform clustering</li>
      <li>Generate Tableau-ready datasets</li>
    </ul>
  </li>

  <li>Download the Tableau workbook from Google Drive and open it in Tableau Desktop.</li>
</ol>

<hr>

<h2>Key Outcomes</h2>
<ul>
  <li>Crime in the UK is highly concentrated in identifiable micro-locations</li>
  <li>Many hotspots show temporal persistence rather than random fluctuation</li>
  <li>Hotspots differ significantly in crime composition and outcome effectiveness</li>
  <li>Combining unsupervised learning with visual analytics provides deeper insight than traditional mapping</li>
</ul>

<hr>

<h2>Author</h2>
<p>
<b>Shikha Tyagi</b><br>
MSc Business Analytics<br>
Crime Analytics | Geospatial Analysis | Machine Learning
</p>
Email: shikhat26@gmail.com
