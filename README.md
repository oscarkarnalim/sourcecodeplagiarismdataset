# Source Code Plagiarism Dataset

The dataset can be used to evaluate the effectiveness of source code plagiarism detection. It consists of 467 Java source code files, covering seven introductory programming assessment tasks. Unique to this dataset, both intention to plagiarise and advanced plagiarism attacks are considered in its construction. The detail of the dataset can be seen in https://www.mii.lt/informatics_in_education/htm/infedu.2019.15.htm.

# How to use
Each task contains three directories. 'Original' contains the original code for the task. 'non-plagiarized' contains N sub-directories in which each of them represents one code file, created remotely to the original one. 'plagiarized' contains six sub-directories representing plagiarism levels from Faidhi and Robinson. For each of those, it has N deeper sub-directories containing code files created by plagiarising the original one.

For further details how to use the dataset, please refer to the aforementioned publication.

# Important remarks
1. The plagiarism level taxonomy provided by Faidhi & Robinson (1987) may not be strictly followed due to different interpretations by the authors and the plagiarists of the taxonomy. However, we can guarantee that the plagiarism attacks become more advanced as the plagiarism level is increased.
2. Some code files may not solve their respective task perfectly due to the contributors' carelessness (e.g., some code files may have minor output errors), but each one compiles. These code files are still included to keep the naturalness of our dataset, and in real conditions, not all submitted code files get a perfect score. 
3. The dataset may not cover all types of plagiarism attacks on introductory programming, since the tasks used to form the dataset are only a subset of introductory programming tasks and the plagiarism attacks are purely defined by the plagiarists.
4. If you use this dataset, please cite the publication instead of this link.
