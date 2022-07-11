# NAM_Proj
YOUTUBE  SOCIAL NETWORK ANALYSIS

 We know that Youtube is a video-sharing web site that includes a social network. In the Youtube social network,
 users form friendship each other and users can create groups which other users can join. 

In this how well the users/ nodes are connected using different models like K-Core , and also  finding the communities using  SBM(Stochastic Block Mode)

The Dataset is taken from Stanford ( SNAP )
The Two Main attributes in the dataset are the User ID and the edges between them. 
The Dataset consists of more than 10 lakh nodes    (Different users ID’s), with more than 25 lakh edges ( Connections between users) 


Dataset link : https://snap.stanford.edu/data/com-Youtube.html

![image](https://user-images.githubusercontent.com/55807862/178270313-aa88390f-90e9-403b-bfc2-105c375d099d.png)


Analysis & Considerations:
The k-core decomposition on the original network generates graphs that seem to follow a preferential attachment behavior.
There are nodes with very high degree and very few with low degree. This is compatible with the starting network, which is a natural.
The decomposition of the Random and Small world graphs is not easily observable but surely for ER the subgraphs are random because
the original distribution is normal and consequentially the sub graph distribution are normal and thus random.
The same evaluation applies to SW. Degraded graphs also follow how it is possible to observe a power law.

