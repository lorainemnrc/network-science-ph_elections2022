![fig6](https://github.com/lorainemnrc/network-science-ph_elections2022/assets/23328647/ece2e4c7-f0ee-4d93-8aaf-0a33fdadf387)

# <center> Polarized Opinions and Echo Chambers: <br> A Network Analysis of 2022 PH Presidential Election Tweets </center>

<h1 style="color: #1048CB"><b>Overview</b></h1>

<p align="justify"> &emsp;
  With around 90% of Filipinos having internet access and 81% being on Facebook, the Philippines serves as an ideal site to study the mobilization power of these platforms and how they may contribute to the emergence of polarized opinions and potential “echo chambers”. Particularly, I explored the impact of polarized political positions on relationship formation, information dissemination, and the potential presence of echo chambers within political communication networks on Twitter during the 2022 Philippine Presidential campaign and election period. Despite having 10 candidates, I only focused on two prominent figures — “Leni” Robredo and Ferdinand “Bongbong” Marcos (BBM) Jr., who significantly divided the nation during that time.
</p>

<h1 style="color: #1048CB"><b>Data Source</b></h1>

<p align="justify"> &emsp;
  This project uses BKManabat's dataset for his sentiment analysis of the tweets during the 2022 Philippine Presidential Elections. This includes the username of the tweet’s author, the posting date and time, as well as its sentiment. The sentiment analysis was done using the XLM-RoBERTa base model, which was trained on approximately 198 million tweets and fine-tuned in 8 different languages.
</p>

  If you are interested in the results of this sentiment analysis, you can find them on his Github repository through this [`link`](https://github.com/BKManabat/2022-presidential-sentiment-analysis-ph/tree/main#results).

![image](https://github.com/lorainemnrc/network-science-ph_elections2022/assets/23328647/7884c7f8-3a88-4a47-b24f-f3134d8e540e)


<h1 style="color: #1048CB"><b>Highlights</b></h1>

<p align="justify"> &emsp; 
1. Influential nodes play a critical role in shaping opinions and facilitating information flow within the political communication network. Kingmakers have the power to sway opinions among those they interact with, and opinion leaders are essential “information hubs” capable of disseminating information more effectively by reaching other users through shorter paths.
</p>
<p align="justify"> &emsp; 
2. Studying the effect of homophily on information flow is crucial in understanding the dynamics of opinion formation and potential echo chambers in political discourse. We found that less active or popular users tend to mention more active or popular users. They also have the tendency to interact with others who share similar political positions which leads to increased polarization and reinforcement of existing viewpoints through selective exposure to like-minded individuals.
</p>
<p align="justify"> &emsp; 
3. Identifying communities based on their political affiliations and interactions can give an idea to the nature of political conversations. Analyzing these communities can reveal the ideological clustering of users, and the presence of influential nodes and opinion leaders. This would be beneficial for policymakers, researchers, and the public in promoting a healthier and more inclusive digital discourse, leading to a better-informed electorate and a more democratic society.
</p>
  
