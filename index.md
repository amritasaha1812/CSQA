---
layout: default
---


<div class="panel panel-default">
  <div class="panel-heading">Abstract</div>
<div class="panel-body">

  While conversing with chatbots, humans typically tend to ask many questions, a significant portion of which can be answered by referring to large-scale knowledge graphs (KG). While Question Answering (QA) and dialog systems have been studied independently, there is a need to study them closely to evaluate such real-world scenarios faced by bots involving both these tasks. Towards this end, we introduce the task of Complex Sequential QA which combines the two tasks of (i) answering factual questions through complex inferencing over a realistic-sized KG of millions of entities, and (ii) learning to converse through a series of coherently linked QA pairs. Through a labor intensive semi-automatic process, involving in-house and crowdsourced workers, we created a dataset containing around 200K dialogs with a total of 1.6M turns. Further, unlike existing large scale QA datasets which contain simple questions that can be answered from a single tuple, the questions in our dialogs require a larger subgraph of the KG. Specifically, our dataset has questions which require logical, quantitative, and comparative reasoning as well as their combinations. This calls for models which can: (i) parse complex natural language questions, (ii) use conversation context to resolve coreferences and ellipsis in utterances, (iii) ask for clarifications for ambiguous queries, and finally (iv) retrieve relevant subgraphs of the KG to answer such questions. However, our experiments with a combination of state of the art dialog and QA models show that they clearly do not achieve the above objectives and are inadequate for dealing with such complex real world settings. We believe that this new dataset coupled with the limitations of existing models as reported in this paper should encourage further research in Complex Sequential QA.
</div>
</div>

---
**CODE**
<div class='row section highlight'>
  <div class='col-xs-10 col-xs-offset-1'>
To be made available soon!
  </div>
</div>

---
---
**PAPER**

<!-- Put paper arxiv link here -->
Please download the paper here [paper link](https://arxiv.org/abs/1801.10314)

---
---
**BIBTEX**

@article{1801.10314, </br>
Author = {Amrita Saha and Vardaan Pahuja and Mitesh M. Khapra and Karthik Sankaranarayanan and Sarath Chandar},</br>
Title = {Complex Sequential Question Answering: Towards Learning to Converse Over Linked Question Answer Pairs with a Knowledge Graph},</br>
Year = {2018},</br>
Eprint = {arXiv:1801.10314},</br>
}</br>

---
---
**DATASET**

Please [Click here]({{site.baseurl}}/download/) to download the dataset.

---
### Two-Fold Challenges of this Dataset

<ul style="list-style-type:disc">
<li> <ul style="list-style-type:disc"><b> Complexities in KB-based Question Answering</b> 
        <li>&nbsp;&nbsp;&nbsp;Some categories of questions cannot be answered from a single KB-tuple and needs inferencing over a much larger subgraph</li>
	<li>&nbsp;&nbsp;&nbsp;Different kinds of inferencing required; logical, quantitative, comparative as well as their combinations</li>
	<li>&nbsp;&nbsp;&nbsp;Large Scale of the Knowledge Base (consisting of millions of entities)</li>
	</ul>
</li>	
<br/>
<li> <ul style="list-style-type:disc"><b> Complexities in handling sequential Question Answering</b>
	<li>&nbsp;&nbsp;&nbsp;Use conversation context to resolve co-references and ellipsis in utterances</li>
 	<li>&nbsp;&nbsp;&nbsp;Ask for clarifications for ambiguous queries</li>
	</ul>
</li>
</ul>	


