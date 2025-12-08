# Physics 77: Final Project TESS Exoplanet

Group Members: Cyan Yee, Kiran John, Hana Zitnanska, Isaac Chan, Jonathan Pan

# Project Overview: 
The purpose of this project is to investigate whether computational techniques applied to TESS Full Frame Images (FFIs) can identify transit events with incomplete orbital information and use physical transit modeling (batman) combined with Markov Chain Monte Carlo (MCMC) sampling to recover or refine key parameters such as period, radius ratio, impact parameter, transit mid-time, and eccentricity. As TESS often produces incomplete or noisy data due to short observing windows, we aim to increase the accuracy of the orbital parameters that help understand the physical properties of given exoplanets. To do so, we extract light curves from TESS FFI using TLS to detect transit signals and estimate initial parameters. Instead of using a more frequent BLS method that allows more flexibility to missing parameters, we relied on the TLS method that provides more realistic transit shapes and, therefore, higher precision. Our project was limited to light curves dominated by a single host star. In conclusion, the missing parameters can be approximated without significantly biasing detections.

# Deliverables: 
- 3D animation of exoplanet orbits based on calculated orbital radii and planet radii  
- Light curve plots with best-fit models using least squares regression, including residuals and chi-squared analysis  

# Methods & Tools (this is also in the requirements.txt):
- Scientific Libaries used: NumPy, SciPy, Matplotlib, Pandas  
- Astronomy data analysis: Astropy, Lightkurve, batman 
- Interactive 3D visualization: Plotly (quick for data disualization), VPython, Tqdm (to see progress bar, will be useful for large data sets), Seaborn
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
