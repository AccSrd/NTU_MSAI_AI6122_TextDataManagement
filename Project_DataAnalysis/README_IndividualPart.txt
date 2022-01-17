#####################################################################
@brief:	
	This is an explanatory file to illustrate how to use the 
	corresponding code snippets in the compressed package 
	to reproduce the effects in the report.

@author:
	Li Hantao		G2101725H  HLI038@e.ntu.edu.sg
	...Other group members.

@contributions:
	Hantao Li: Tokenization and Stemming; POS Tagging; Consolidated Report; 
		 Reformatted Report and README. 
	...Other group members.

@date:
	24/10/2021

@note:
	1. The text of the README.txt was finished by all team members with completing their own parts. 
	    Therefore, in terms of narration, it is described according to the order of report.
	2. Apologize in advance for possible duplicate library references.
	3. The root database for most of the code in this file is 'yelp_academic_dataset_Review.json file' 
	    Because it is very easy to download and the file size is large, it is not provided in the network disk shared file. 
                     Please download it by yourself. [1]

@source online:
[1] https://www.yelp.com/dataset/download
[2] https://entuedu-my.sharepoint.com/:f:/g/personal/hli038_e_ntu_edu_sg/EjHaPx0hB2ZApSUqAXew_oEBD-ubi0Mh9Uh3VAJ-aiYLFA?e=7mb5N3
[3] https://code.google.com/archive/p/json-simple/downloads



#####################################################################
1.1 	Tokenization and Stemming.
1.2	POS Tagging.
#####################################################################
@author:
	Li Hantao		G2101725H  HLI038@e.ntu.edu.sg

@code files:
	Assignment-DataAnalysis.ipynb

@online datasets:
	json_pdx.json	-> The dataset of reviews for B1
	json_chinese.json 	-> The dataset of reviews for B2
	yelp_academic_dataset_Review.json -> The whole dataset

@availability:
	code files   	-> ./SourceCode/1.1 - 1.2
	online datasets	-> OneDrive [2] -> ./Assignment_Data/1.1 - 1.2
	yelp_academic_dataset_Review.json -> [1]

@code library:
	NLTK 	https://pypi.org/project/nltk/

@usage method:
	1. This section includes the process of randomly extracting a business from the entire database. 
	    If you want to start with the initial extraction B1, you need to download the complete database. [1]
	2. Download the database in the '1.1-1.2' folder from [2]
	3. There are clear code comments in the code file. After specifying a data file, and applying each cell, 
	    the code will automatically process the text in the data to obtain the corresponding results in report.
	4. For the POS process of CoreNLP, please refer to the corresponding description in code file.

@output:
	1. The code file can save the word distribution curve as the same as in the report to the root.
	2. The code can show the POS results.

#####################################################################
...Other group members'
#####################################################################	
