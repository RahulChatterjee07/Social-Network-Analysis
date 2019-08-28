# Social-Network-Analysis

The Python script in this repository can be used to partition a social network into communities using the k-clique algorithm.
The network was formed using Facebook data, collected from survey participants using the Facebook app. The dataset includes node features (profiles), circles, and ego networks.
Structure of different communities are also attached in this repository in form of a '.png' file.

This script also does community ranking based on the following methods:
Method-1: No of social active nodes present in the community.
Method-2: On the basis the value of the function W(m)  of nodes present in the community. W(m)=0.5A1(m)+0.5A2(m), where A1(m) is the average number of posts posted per week by user m and A2(m) is the average number of shares plus the number of comments plus the number of likes for each of his posts. 
