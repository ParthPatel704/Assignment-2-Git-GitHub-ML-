Dataset Information
Additional Information

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image. A few of the images can be found at http://www.cs.wisc.edu/~street/images/

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree.  Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

The actual linear program used to obtain the separating plane in the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Has Missing Values?

No

Introductory Paper
Nuclear feature extraction for breast tumor diagnosis
By W. Street, W. Wolberg, O. Mangasarian. 1993

Published in Electronic imaging

Variables Table
Variable Name	Role	Type	Description	Units	Missing Values
ID	ID	Categorical			no
Diagnosis	Target	Categorical			no
radius1	Feature	Continuous			no
texture1	Feature	Continuous			no
perimeter1	Feature	Continuous			no
area1	Feature	Continuous			no
smoothness1	Feature	Continuous			no
compactness1	Feature	Continuous			no
concavity1	Feature	Continuous			no
concave_points1	Feature	Continuous			no
