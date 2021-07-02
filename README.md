# Labview-for-Scanning-and-Detection
This is customer-designed labview program for APD/PMT detecting &amp; Piezo stage scanning
The customer-designed Labview programms are for scanning PSFs of confocal and STED system. We update two programms for PMT and APD capturing, whose folder names begin with APD and PMT respectively.
These programms are designed and uploaded by Xinzhu Xu, Kun Zhao, Chaoyang Wu, Wei Ren, from Xipeng Lab, Department of Biomedical Engineering, College of Future Technology, Peking University. They are supplyment materials of “”, so, if use please cite this paper.

Operation illustrations:

①	Scan type: 

X &Y: Scanning lateral PSF 

X &Z: Scanning axial PSF

②	Offset position of the other axis:

Offset Z position to center PSF when on X &Y scan,

Offset Y position to center PSF when on X &Z scan.

③	Acquisition rate of APD/PMT
Setting acquisition rate of detector in both two programms and usually, it ranges from several hundreds to several thousands Hz in our experiments.

④	Scan range: Scan FOV in μm.

⑤	Scan step size: Piezo stage scanning step.

⑥	Zoom factor for view: When previewing, it will magnify the preview figure size but will not affect the size of saving figure. 

⑦	Number of images: The image number you want to capture or preview.

⑧	Date/time string: The date you do experiment which will become a part of your folder name.

⑨	Sample name: Please name your sample for saving data.

⑩	Saving path: Choose path to save your figure. If it doesn’t exsist, programm will create one. 

After setting all parameters, there are two modes for previewing or saving data

Preview Mode: Click “Saving Profiles?” off and “Start”, the programm will only display magnified figures and no data will be saved, but the folder will still be created.

Saving Mode: Click “Saving Profiles?” on and “Start”, the programm will automatically save data you capture.
