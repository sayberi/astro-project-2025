# Astro-project-2025
My astrophysics projects from 2025



# Workplan
1. Literature review and familiarization with the research topic.
2. Selection of planet-host stars to be analyzed, prioritizing stars with archival data from ground-based facilities, namely ESO’s HARPS and ESPRESSO, that were observed also by NASA’s TESS space mission.
3. Familiarization with readily available tools for the retrieval of rotation and magnetic activity. Alternatively, the student can write their own algorithm.
4. Computation of rotation periods and magnetic activity for the target sample selected in task 2.
5. Comparison between the obtained parameters with values in the literature and validation of the methodology.
6. Expansion of the target sample to planet-hosts without archival data and computation of their rotation periods and magnetic activity.
7. Implementation into SWEET-cat.



# Literature Review:
Hathaway, D. 2015, Living Rev. Sol. Phys., 12, 4, https://ui.adsabs.harvard.edu/abs/2015LRSP...12....4H
(Sections 1 & 2)

Santos, A. R. G., García, R. A., Mathur, S., et al. 2019, ApJS, 244, 21, https://ui.adsabs.harvard.edu/abs/2021ApJS..255...17S/abstract
Santos, A. R. G., Breton, S. N., Mathur, S., García, R. A., et al. 2021, ApJS, 255, 17, https://ui.adsabs.harvard.edu/abs/2021ApJS..255...17S

Star-privateer: https://pypi.org/project/star-privateer/
SWEET-Cat: https://sweetcat.iastro.pt/
QLP light curves: https://archive.stsci.edu/hlsp/qlp (at the moment, thought to be the best calibration/correction for TESS)
Another tool for light curves: Lightkurve - https://lightkurve.github.io/lightkurve/ 
ID crossmatch: it should be possible to do it in the MAST portal, but for a small number of targets SIMBAD can be used.



# References:
Aigrain, S., Llama, J., Ceillier, T., et al. 2015, MNRAS, 450, 3211, https://ui.adsabs.harvard.edu/abs/2015MNRAS.450.3211A/abstract
Brun, A. S., & Browning, M. K. 2017, LRSP, 14, 4, http://adsabs.harvard.edu/abs/2017LRSP...14....4B
Hathaway, D. 2015, Living Rev. Sol. Phys., 12, 4, https://ui.adsabs.harvard.edu/abs/2015LRSP...12....4H
Mathur, S., Salabert, D., García, R. A. 2014, JSWSC, 4, A15, https://ui.adsabs.harvard.edu/abs/2014JSWSC...4A..15M/abstract
Santos, A. R. G., & Mathur, S. 2020, Science, 368, 466, https://ui.adsabs.harvard.edu/abs/2020Sci...368..466S



# File identification 
Caixa de Ferramentas.ipynb - store basic python/jupiter notebook commands and functions for me to get started
practice.ipynb - allow me to get a grip on the many new python packages