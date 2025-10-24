# Physics 77: Final Project TESS Exoplanet

# Group Members: Cyan Yee, Kiran John, Hana Zitnanska, Isaac Chan, Jonathan Pan

# Project Overview: 
Our research question is: "Can we show the tidal orbital decay of hot Jupiters through 3D simulations?" Using measured data from the Transiting Exoplanets Survey Satellites (TESS), we process light curves to remove background noise and calculate orbital parameters for selected exoplanets. We aim to produce two 3D models: one for an exoplanet known to exhibit orbital decay, and one for an exoplanet that does not. By comparing these models, we investigate the dynamics of tidal orbital decay.

# Deliverables: 
- -3D animation of exoplanet orbits based on calculated orbital radii and planet radii  
- Light curve plots with best-fit models using least squares regression, including residuals and chi-squared analysis  

# Methods & Tools:
# (this is also in the requirements.txt)
- Scientific Libaries used: NumPy, SciPy, Matplotlib, Pandas  
- Astronomy data analysis: Astropy, Lightkurve  
- Interactive 3D visualization: Plotly (quick for data disualization), VPython
- Regression and model fitting: curve_fit  
- Analysis: Jupyter notebooks

Resources:
- [TESS beginner light curve tutorial](https://spacetelescope.github.io/mast_notebooks/notebooks/TESS/beginner_how_to_use_lc/beginner_how_to_use_lc.html)  
- [TESS data validation tutorial](https://spacetelescope.github.io/mast_notebooks/notebooks/TESS/beginner_how_to_use_dvt/beginner_how_to_use_dvt.html)  
- [TESS Introduction](https://heasarc.gsfc.nasa.gov/docs/tess/TESS-Intro.html)  
- [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)  

-------------------------------------
To do (for group members):

1. Clone repository, use:
- https://github.com/cyan-yee/Physics-77-Final-Project---TESS-Exoplanet.git
1b. Then in your terminal, run:
- cd Physics-77-Final-Project---TESS-Exoplanet

2. Create Virtual Environment, use:
- python -m venv venv --> For Windows

3. Activate Virtual Environment, use:
- venv\Scripts\activate

4. Install Dependencies, use:
- pip install -r requirements.txt

5. Create your own branch to work on, use:
- git checkout -b (branch name)

6. Making changes + committing them, use:
- git add .
- git commit -m "Updates on what you did"

7. Push your changes back to main branch, so we can all see it:
- git push origin (branch name)

 -------------------------------------
# General Notes:

pull latest changes using:
- git checkout main
- git pull origin main
