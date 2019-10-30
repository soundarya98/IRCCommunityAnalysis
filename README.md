# IRCCommunityAnalysis
The following contains codes as part of the analysis of the community structure of the IRC logs channel. 

The steps in this are summarised in the photo given below:

![Steps for creation of chat-bot](https://github.com/soundarya98/IRCCommunityAnalysis/blob/master/Images/Project_Flow.png)

We have attached codes for:
1. Web Scraping
2. Classifications into users and experts
3. Testing on a custom WhatsApp chat.

The codes are organised as follows:
IRC_NAMES.ipynb contains code that extracts top experts and their active timings for each keyword.
Dashboard.txt contains this output, which will be displayed on the chat-bot interface.
QSTP_Competitive.ipynb contains code that extracts the usernames and timings for a university group chat on WhatsApp.


Here is a snippet of the directed graph for various users in 2013:

![Directed Graph](https://github.com/soundarya98/IRCCommunityAnalysis/blob/master/Images/DirectedGraph.png)

Following is the directed graph obtained by all users/experts in 2013 Jan:

![GephiGraph1](https://github.com/soundarya98/IRCCommunityAnalysis/blob/master/Images/GephiGraph1.png)

And following is the graph for users/experts with colour denoting the various communities, and nodes ranked by betweenness centrality:

![GephiGraph2](https://github.com/soundarya98/IRCCommunityAnalysis/blob/master/Images/GephiGraph2.png)
