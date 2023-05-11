# Source Code Plagiarism Dataset

The dataset can be used to evaluate the effectiveness of source code plagiarism detection. It consists of 467 Java source code files, covering seven introductory programming assessment tasks. Unique to this dataset, both intention to plagiarise and advanced plagiarism attacks are considered in its construction. The detail of the dataset can be seen in [the corresponding paper](https://doi.org/10.15388/infedu.2019.15) published in Informatics in Education.

# How to use
Each task contains three directories. 'Original' contains the original code for the task. 'non-plagiarized' contains N sub-directories in which each of them represents one code file, created independently from the original one. 'plagiarized' contains six sub-directories representing plagiarism levels from Faidhi and Robinson (1987). For each of those, it has N deeper sub-directories containing code files created by plagiarising the original one.

For further details how to use the dataset, please refer to the aforementioned publication.

# Important remarks
If you use this dataset, please cite the publication instead of this link. 

[@manuel-freire](https://github.com/manuel-freire) noted that submission 13 and 15 on the non-plagiarized submissions are alike in case-02, case-03, case-04, case-06, and case-07. Although we ensured that these students wrote the code independently, we acknowledge that there is a possibility that these students copied one another. Readers can choose to exclude one of the submissions if needed. See the details [here](https://github.com/oscarkarnalim/sourcecodeplagiarismdataset/issues/3).
