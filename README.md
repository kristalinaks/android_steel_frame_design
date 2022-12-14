# Development of Design and Analysis Software of 3D Steel Frame Based on Android

App Demo: http://tiny.cc/demoAndroid

In general, the design and analysis of 3-dimensional frame structures is carried out with the help of software because it requires a complex calculation process. Nowadays, a software that works on more portable devices, such as Android smartphones, is also needed. In addition, the developed software needs to facilitate constructions in Indonesia by accommodating commonly used steel profiles in Indonesia and earthquake resistance analysis in accordance with SNI.

Author develops a software capable of analyzing and designing 3D steel frame structures. The structural analysis method used is the stiffness matrix method with the banded matrix storage method to save computer memory. The earthquake resistance analysis method used is the static equivalent method. Inputs processed by this software are frame dimensions, material and cross-sections properties, and loads: joint loads, frame loads, area loads, and earthquake loads.

Analysis and structural design of 3D steel frame software named CEMApp Steel Frame was successfully developed. CEMApp Steel Frame is able to produce outputs such as displacement, base reaction, internal forces, safety ratio to the axial-moment and shear combination, and the best steel profile safe to use. Output validation of CEMApp Steel Frame is done by comparing it to SAP2000 software. The comparison results in deviation of 2.04% in the Z-axis moment reaction. This deviation is still below the tolerance limit so the output of CEMApp Steel Frame can be accepted. However, CEMApp Steel Frame still has some shortcomings, such as the limitation of the frame shape in the form of quadrilateral prism, idealization of perfect stiffness in joints, lack of stiffness reduction in structures, lack of load combinations, and limited steel profile databases. The next researcher is expected to consider this limitation and develop the application.

Keywords: mobile software, Android, steel design, 3D framel, earthquake resistance
