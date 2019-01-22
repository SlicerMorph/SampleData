# SampleData
Sample Datasets to be used by the SlicerMorph toolkit

<h2>Description of Datasets </H2>
<li><b>Gorilla_Skull_LMs.zip:</b> 41 cranial LMs annotated on 23 adult Gorilla skulls from the skeletal collection of National Museum of Natural History. Landmarks for each specimen was saved as .fcsv file (comma-separated fiducial file) readable by 3D-Slicer. All samples follow the same landmark sequence. Coordinate values are in millimeters.
<li><b>Gorilla_reference_mrb:</B> A synthetic gorilla skull derived from microCT scans of 38 adult Gorilla using deformable image registration as described in <a href = "http://meeting.physanth.org/program/2018/session23/maga-2018-image-registration-and-template-based-annotation-of-great-ape-skulls.html"> Davis and Maga, 2018</a>. The scene file is readble by 3D-Slicer, and contains a low-resolution 3D model, as well as associated 41 cranial landmarks. The full-resolution volumetric image can be obtain from https://github.com/muratmaga/Hominoid_Skulls. 
<li> <b>Mouse_skull_LMs.zip:</b> 55 cranial LMs annotated on 126 adult mice. Landmarks for each specimen was saved as .fcsv file (comma-separated fiducial file) readable by 3D-Slicer. All samples follow the same landmark sequence. Note that coordinate values are in IJK space. To convert them to mm's, they need to be scaled by 0.01734.
<li><b>mouse_skull_reference.mrb:</b> The 3D model of the sample closest to the mean from the Mouse skulls dataset, and its associated cranial LM dataset. The scene file is directly readble by 3D-Slicer.
