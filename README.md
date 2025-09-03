# CS 4170: Data Mining With Applications in the Life Sciences
## Activity 1: Familiarize with the file's contents and perform an exploratory analysis of the data.

### Dataset Description
Data file mutationc.csv is taken from The Cancer Genome Atlas (TCGA): is the datafile
Some individuals who participated in the research study have cancer, and some individuals do not have cancer. Each row of the file contains the binary mutation vector for one individual. The first element in each row is a unique identifier, which consists of 
1.	a class identifier: 
- ‘C’ if the individual has cancer, 
- ‘NC’ if the individual does not have cancer 
2.	a numeric patient identifier (patients in each class are assigned a unique number).
Each remaining element in a row contains a ‘1’ or a ‘0’, indicating the presence or absence of a specific mutation in a particular gene. 
The first row of the matrix lists the names of the specific genetic mutations considered in the study.

### Requirement:
Get the followings:
- Number of unique mutations contained in the data file (each column represents a unique mutation)
- Number of individual samples contained in the data file (each row represents a patient sample)
- Number of mutations for individual C1
- Number of mutations for individual NC1
- The average number of mutations per individual
- The minimum and maximum number of mutations per individual
- Number of individuals who have a mutation in the ‘BRAF’ gene
- Number of individuals who have a mutation in the ‘KRAS’ gene
- The average number of individuals per mutation (i.e., the number of individuals expected to have a randomly selected mutation). This can be computed as follows:
    - For each mutation i, compute mi, the number of individuals who have mutation i
    - Compute m_sum = the sum of mi for all i
    - The average number of individuals per mutation = m_sum / number of mutations
- The minimum and maximum number of individuals per mutation

## Data Preprocessing
### Outlier detection
Use scatterplots to determine if there are (1) any outlier samples and (2) if there are any outlier genetic mutations.
### Understand data better
Explore how the individual genetic mutations relate to the two categories of samples

