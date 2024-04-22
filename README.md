# Unsupervised-Learniong
TOPIC: Analysis is to find inherent clusters in sites (locations) and Plant Species

OBJECTIVE: The objective of the analysis is to find relationships / inherent clusters in sites (locations) and/or plant species. The counts of various species at multiple quadrats at multiple locations are provided in various sheets in the excel file.

Data Importing and understanding:
Originally we are considering the data in the file named All sites All quadrats tree list final.xlsx which contains information of approx 682 plants species at different locations. The loactions present are:
Malshej_Ghat,Naneghat,Bhimashankar,Malegaon_Budruk,Dahuli,Lonavala,Tailbaila, Mulshi,Tamhini_Ghat,Gunjavane_dam,Abhepuri,Mahabaleshwar.

Data Preprocessing:
1) The missing values in the data-There are some missing values in the data after importing.we can replace NA values by Zero value,this is because plant species count loaction wise is given.
2) After that,we are joining totals of plants species of all the locations that gives us total variables equals to 12;
3) Finally,from plant species column we are finding unique species corresponding to different locations and clubbing them all that gives us total plant sepecies for consideration is equal to 214.

CONCLUSION:
By applying various clustering methods we found out that-
1) In locations , “MAHABALESHWAR” lies in one cluster “BHIMASHANKAR” lies in second cluster “Malshej_Ghat”,“Naneghat”,“Malegaon_Budruk”,“Dahuli”, “Lonavala”,“Tailbaila”,“Mulshi”,“Tamhini_Ghat”, “Gunjavane_dam”,“Abhepuri”lies in third cluster.
2) In Plant Species,33rd plant species i.e,“Memecylon umbellatum Burm.f” is in one cluster(differ significantly from other plant sepcies) ,rest all the 213 species are in other 2 clusters.
