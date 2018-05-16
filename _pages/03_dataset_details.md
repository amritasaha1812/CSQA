---
layout: page
title: Dataset Details
permalink: /dataset/
---
### Question Nomenclature

<!-- <dt>ques_type_id=1
Simple Question (subject-based)
<dt>ques_type_id=2
Secondary question 
sec_ques_type=1: Subject based question 
sec_ques_type=2: Object based question 
 sec_ques_sub_type=1: Direct (Singular) 
 sec_ques_sub_type=2: Indirect (Singular) 
 sec_ques_sub_type=3: Indirect (Plural) 
 sec_ques_sub_type=4: Direct (Plural) 
<dt>ques_type_id=3
Clarification (for secondary) question 
<dt>ques_type_id=4
Set-based question 
set_op_choice=1: OR 
set_op_choice=2: AND 
set_op_choice=3: Difference 
<dt>ques_type_id=5
Boolean (Factual Verification) question 
bool_ques_type = 1
Verification | 2 entities, both direct 
bool_ques_type = 2
Verification | 2 entities, one direct and one indirect, subject is indirect 
bool_ques_type = 3
Verification | 2 entities, one direct and one indirect, object is indirect 
bool_ques_type = 4
Verification | 3 entities, all direct, 2 are query entities 
bool_ques_type = 5
Verification | 3 entities, 2 direct, 2(direct) are query entities, subject is indirect 
bool_ques_type = 6
Verification | one entity, multiple entities (as object) referred indirectly 
<dt>ques_type_id=6
Incomplete question (for secondary) 
inc_ques_type=1
Incomplete | object parent is changed, subject and predicate remain same 
inc_ques_type=2
Only subject is changed, parent and predicate remains same 
inc_ques_type=3
Incomplete count-based ques 
<dt>ques_type_id=7
Comparative and Quantitative questions (involving single entity) 
 count_ques_sub_type=1
Quantitative (count) single entity 
 count_ques_sub_type=2
Quantitative (min/max) single entity 
 count_ques_sub_type=3
Quantitative (atleast/atmost) single entity (which) 
 count_ques_sub_type=4
Comparative (more/less) single entity (count) 
 count_ques_sub_type=5
Quantitative (atleast/atmost) single entity (count) 
 count_ques_sub_type=6
Comparative (more/less) single entity (which) 
 count_ques_sub_type=7
Quantitative Indirect (count) single entity 
 count_ques_sub_type=8
Comparative Indirect (more/less) single entity (count) 
 count_ques_sub_type=9
Comparative Indirect (more/less) single entity (which) 
  is_incomplete=1: Incomplete form (of the category of question) 
<dt>ques_type_id=8
Comparative and Quantitative questions (involving multiple(2) entities) 
 count_ques_sub_type=1
Quantitative with Logical Operators 
 count_ques_sub_type=2
Quantitative (count) multiple entity 
 count_ques_sub_type=3
Quantitative (min/max) multiple entity 
 count_ques_sub_type=4
Quantitative (atleast/atmost) multiple entity (which) 
 count_ques_sub_type=5
Comparative (more/less) multiple entity (count) 
 count_ques_sub_type=6
Quantitative (atleast/atmost) multiple entity (count) 
 count_ques_sub_type=7
Comparative (more/less) multiple entity (which) 
 count_ques_sub_type=8
 Quantitative Indirect (count) multiple entity 
 count_ques_sub_type=9
Comparative Indirect (more/less) single entity (count) 
 count_ques_sub_type=10
Comparative Indirect (more/less) multiple entity (which) 
  is_incomplete=1: Incomplete form (of the category of question)  -->

<!-- <dl>
<dt style="color: #A43720">ques_type_id=1</dt> 
<dd>Simple Question (subject-based)</dd>

<dt style="color: #A43720">ques_type_id=2</dt>
<dd>Secondary question
<dl>
<dt>sec_ques_type=1</dt>
<dd>Subject based question

<dl>
<dt style="color: #B26216">sec_ques_sub_type=1</dt>
<dd>Direct (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=2</dt>
<dd>Indirect (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=3</dt>
<dd>Indirect (Plural) </dd>
<dt style="color: #B26216">sec_ques_sub_type=4</dt>
<dd>Direct (Plural) </dd>
</dl>
</dd>

<dt>sec_ques_type=2</dt>
<dd>Object based question

<dl>
<dt style="color: #B26216">sec_ques_sub_type=1</dt>
<dd>Direct (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=2</dt>
<dd>Indirect (Singular) </dd>
<dt style="color: #B26216">sec_ques_sub_type=3</dt>
<dd>Indirect (Plural) </dd>
<dt style="color: #B26216">sec_ques_sub_type=4</dt>
<dd>Direct (Plural) </dd>
</dl>
</dd>

</dl>
</dd>

<dt style="color: #A43720">ques_type_id=3</dt>
<dd>Clarification (for secondary) question </dd>
<dt style="color: #A43720">ques_type_id=4</dt>
<dd>Set-based question
<dl>
<dt>set_op_choice=1</dt>
	<dd>OR</dd> 
<dt>set_op_choice=2</dt>
	<dd>AND</dd>
<dt>set_op_choice=3</dt>
	<dd>Difference</dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=5</dt>
<dd>Boolean (Factual Verification) question
<dl>
<dt>bool_ques_type = 1</dt>
<dd>Verification | 2 entities, both direct </dd>
<dt>bool_ques_type = 2</dt>
<dd>Verification | 2 entities, one direct and one indirect, subject is indirect </dd>
<dt>bool_ques_type = 3</dt>
<dd>Verification | 2 entities, one direct and one indirect, object is indirect </dd>
<dt>bool_ques_type = 4</dt>
<dd>Verification | 3 entities, all direct, 2 are query entities </dd>
<dt>bool_ques_type = 5</dt>
<dd>Verification | 3 entities, 2 direct, 2(direct) are query entities, subject is indirect </dd>
<dt>bool_ques_type = 6</dt>
<dd>Verification | one entity, multiple entities (as object) referred indirectly </dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=6</dt>
<dd>Incomplete question (for secondary)

<dl>
<dt>inc_ques_type=1</dt>
<dd>Incomplete | object parent is changed, subject and predicate remain same </dd>
<dt>inc_ques_type=2</dt>
<dd>Only subject is changed, parent and predicate remains same </dd>
<dt>inc_ques_type=3</dt>
<dd>Incomplete count-based ques </dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=7</dt>
<dd>Comparative and Quantitative questions (involving single entity)
<dl>
<dt>count_ques_sub_type=1</dt>
<dd>Quantitative (count) single entity
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=2</dt>
<dd>Quantitative (min/max) single entity </dd>
<dt>count_ques_sub_type=3</dt>
<dd>Quantitative (atleast/atmost) single entity (which) </dd>
<dt>count_ques_sub_type=4</dt>
<dd>Comparative (more/less) single entity (count)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=5</dt>
<dd>Quantitative (atleast/atmost) single entity (count) </dd>
<dt>count_ques_sub_type=6</dt>
<dd>Comparative (more/less) single entity (which)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=7</dt>
<dd>Quantitative Indirect (count) single entity </dd>
<dt>count_ques_sub_type=8</dt>
<dd>Comparative Indirect (more/less) single entity (count) </dd>
<dt>count_ques_sub_type=9</dt>
<dd>Comparative Indirect (more/less) single entity (which) </dd>
</dl>
</dd>

<dt style="color: #A43720">ques_type_id=8</dt>
<dd>Comparative and Quantitative questions (involving multiple(2) entities) </dd>
<dt>count_ques_sub_type=1</dt>
<dd>Quantitative with Logical Operators </dd>
<dt>count_ques_sub_type=2</dt>
<dd>Quantitative (count) multiple entity
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=3</dt>
<dd>Quantitative (min/max) multiple entity </dd>
<dt>count_ques_sub_type=4</dt>
<dd>Quantitative (atleast/atmost) multiple entity (which) </dd>
<dt>count_ques_sub_type=5</dt>
<dd>Comparative (more/less) multiple entity (count)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=6</dt>
<dd>Quantitative (atleast/atmost) multiple entity (count) </dd>
<dt>count_ques_sub_type=7</dt>
<dd>Comparative (more/less) multiple entity (which)
<dl>
<dt style="color: #B26216">is_incomplete=1</dt>
<dd>Incomplete form (of the category of question) </dd>
</dl>
</dd>
<dt>count_ques_sub_type=8</dt>
<dd>Quantitative Indirect (count) multiple entity </dd>
<dt>count_ques_sub_type=9</dt>
<dd>Comparative Indirect (more/less) single entity (count) </dd>
<dt>count_ques_sub_type=10</dt>
<dd>Comparative Indirect (more/less) multiple entity (which) </dd>

</dl> -->

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg .tg-yw4l{vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-031e">Question type</th>
    <th class="tg-031e">Question sub-type</th>
    <th class="tg-031e">Question sub-sub-type</th>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=1<br>Simple Question (subject-based)</td>
    <td class="tg-031e"></td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">ques_type_id=2<br>Secondary question</td>
    <td class="tg-031e">sec_ques_type=1<br>Subject based question</td>
    <td class="tg-031e" rowspan="2">sec_ques_sub_type=1<br>Direct (Singular)<br><br>sec_ques_sub_type=2<br>Indirect (Singular)<br><br>sec_ques_sub_type=3<br>Indirect (Plural)<br><br>sec_ques_sub_type=4<br>Direct (Plural)</td>
  </tr>
  <tr>
    <td class="tg-yw4l">sec_ques_type=2<br>Object based question</td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=3<br>Clarification (for secondary) question</td>
    <td class="tg-031e"></td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=4<br>Set-based question</td>
    <td class="tg-031e">set_op_choice=1<br>OR<br><br>set_op_choice=2<br>AND<br><br>set_op_choice=3<br>Difference</td>
    <td class="tg-031e">is_inc=1<br>Incomplete version of set-based ques.</td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=5<br>Boolean (Factual Verification) question</td>
    <td class="tg-031e">bool_ques_type = 1<br>Verification | 2 entities, both direct<br><br>bool_ques_type = 2<br>Verification | 2 entities, one direct and one indirect, subject is indirect<br><br>bool_ques_type = 3<br>Verification | 2 entities, one direct and one indirect, object is indirect<br><br>bool_ques_type = 4<br>Verification | 3 entities, all direct, 2 are query entities<br><br>bool_ques_type = 5<br>Verification | 3 entities, 2 direct, 2(direct) are query entities, subject is indirect<br><br>bool_ques_type = 6<br>Verification | one entity, multiple entities (as object) referred indirectly</td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e">ques_type_id=6<br>Incomplete question (for secondary)</td>
    <td class="tg-031e">inc_ques_type=1<br>Incomplete | object parent is changed, subject and predicate remain same<br><br>inc_ques_type=2<br>Only subject is changed, parent and predicate remains same<br><br>inc_ques_type=3<br>Incomplete count-based ques</td>
    <td class="tg-031e"></td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">ques_type_id=7<br>Comparative and Quantitative questions (involving single entity)</td>
    <td class="tg-031e">count_ques_sub_type=1<br>Quantitative (count) single entity<br><br>count_ques_sub_type=2<br>Quantitative (min/max) single entity<br><br>count_ques_sub_type=3<br>Quantitative (atleast/atmost) single entity (which)<br><br>count_ques_sub_type=5<br>Quantitative (atleast/atmost) single entity (count)<br><br>count_ques_sub_type=7<br>Quantitative Indirect (count) single entity<br><br></td>
    <td class="tg-031e" rowspan="2">is_incomplete=1<br>Incomplete form (of the category of question)</td>
  </tr>
  <tr>
    <td class="tg-yw4l">count_ques_sub_type=4<br>Comparative (more/less) single entity (count)<br><br>count_ques_sub_type=6<br>Comparative(more/less) single entity (which)<br><br>count_ques_sub_type=8<br>Comparative Indirect (more/less) single entity (count)<br><br>count_ques_sub_type=9<br>Comparative Indirect (more/less) single entity (which)</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">ques_type_id=8<br>Comparative and Quantitative questions (involving multiple(2) entities)</td>
    <td class="tg-031e">count_ques_sub_type=1<br>Quantitative with Logical Operators<br><br>count_ques_sub_type=2<br>Quantitative (count) multiple entity<br><br>count_ques_sub_type=3<br>Quantitative (min/max) multiple entity<br><br>count_ques_sub_type=4<br>Quantitative (atleast/atmost) multiple entity (which)<br><br>count_ques_sub_type=6<br>Quantitative (atleast/atmost) multiple entity (count)<br><br>count_ques_sub_type=8<br>Quantitative Indirect (count) multiple entity<br><br></td>
    <td class="tg-031e" rowspan="2">is_incomplete=1<br>Incomplete form (of the category of question)</td>
  </tr>
  <tr>
    <td class="tg-yw4l">count_ques_sub_type=5<br>Comparative (more/less) multiple entity (count)<br><br>count_ques_sub_type=7<br>Comparative(more/less) multiple entity (which)<br><br>count_ques_sub_type=9<br>Comparative Indirect (more/less) single entity(count)<br><br>count_ques_sub_type=10<br>Comparative Indirect (more/less) multiple entity (which)</td>
  </tr>
</table>

### Dataset statistics (Number of QA pairs for each question type)

<!--  |  ﻿Question Type                                                                                             |  Train   |  Valid  |  Test   |  
 | ---------------------------------------------------------------------------------------------------------- | -------- | ------- | ------- | 
 |  Simple&#124;Direct                                                                                        |  446,927  |  47,868  |  74,800  |  
 |  Simple&#124;Indirect                                                                                      |  285,825  |  30,397  |  49,993  |  
 |  Simple&#124;Incomplete                                                                                    |  54,711   |  5,913   |  8,664   |  
 |  Comparative&#124;Count over More/Less&#124;Mult. entity type&#124;Direct                                  |  37,090   |  4,199   |  6,591   | 
 |  Comparative&#124;Count over More/Less&#124;Mult. entity type&#124;Indirect                                |  8,090    |  858    |  1,427  | 
 |  Comparative&#124;Count over More/Less&#124;Mult. entity type&#124;Incomplete                              |  15,260   |  1,747   |  2,448   | 
 |  Comparative&#124;Count over More/Less&#124;Single entity type&#124;Direct                                 |  42,930   |  4,629   |  4,472   | 
 |  Comparative&#124;Count over More/Less&#124;Single entity type&#124;Indirect                               |  9,793    |  1,020   |  1,222   |  
 |  Comparative&#124;Count over More/Less&#124;Single entity type&#124;Incomplete                             |  17450   |  1885   |  1277   |  
 |  Comparative&#124;More/Less&#124;Mult. entity type&#124;Direct                                             |  37784   |  3995   |  6677   |  
 |  Comparative&#124;More/Less&#124;Mult. entity type&#124;Indirect                                           |  8161    |  899    |  1340   |  
 |  Comparative&#124;More/Less&#124;Mult. entity type&#124;Incomplete                                         |  15598   |  1626   |  2449   |  
 |  Comparative&#124;More/Less&#124;Single entity type&#124;Direct                                            |  43529   |  4639   |  4376   | 
 |  Comparative&#124;More/Less&#124;Single entity type&#124;Indirect                                          |  9786    |  1082   |  1286   | 
 |  Comparative&#124;More/Less&#124;Single entity type&#124;Incomplete                                        |  17781   |  1887   |  1228   |  
 |  Logical&#124;Union&#124;Direct                                                                            |  30267   |  3347   |  5656   |  
 |  Logical&#124;Intersection&#124;Direct                                                                     |  21151   |  2293   |  4086   | 
 |  Logical&#124;Difference&#124;Direct                                                                       |  1497    |  166    |  298    | 
 |  Logical&#124;Incomplete                                                                                   |  4909    |  533    |  1083   | 
 |  Quantitative&#124;Atleast/ Atmost/ Approx. the same/Equal&#124;Mult. entity type&#124;Direct              |  25484   |  2674   |  4409   |  
 |  Quantitative&#124;Atleast/ Atmost/ Approx. the same/Equal&#124;Single entity type&#124;Direct             |  31668   |  3439   |  2395   |  
 |  Quantitative&#124;Count over Atleast/ Atmost/ Approx. the same/Equal&#124;Mult. entity type&#124;Direct   |  25210   |  2693   |  4367   |  
 |  Quantitative&#124;Count over Atleast/ Atmost/ Approx. the same/Equal&#124;Single entity type&#124;Direct  |  31121   |  3366   |  2323   |  
 |  Quantitative&#124;Count&#124;Logical operators&#124;Direct                                                |  25731   |  2661   |  4001   | 
 |  Quantitative&#124;Count&#124;Logical operators&#124;Indirect                                              |  9350    |  998    |  1621   |  
 |  Quantitative&#124;Count&#124;Mult. entity type&#124;Direct                                                |  29420   |  3150   |  4925   | 
 |  Quantitative&#124;Count&#124;Single entity type&#124;Direct                                               |  64225   |  6761   |  8318   |  
 |  Quantitative&#124;Count&#124;Single entity type&#124;Indirect                                             |  15690   |  1645   |  2194   | 
 |  Quantitative&#124;Count&#124;Single entity type&#124;Incomplete                                           |  26472   |  2752   |  3348   | 
 |  Verification&#124;Single/Multiple Entity&#124;Direct                                                      |  66550   |  7101   |  13879  | 
 |  Verification&#124;Single/Multiple Entity&#124;Indirect                                                    |  91061   |  9965   |  17003  | 
 |  Clarification (All)                                                                                       |  62825   |  6761   |  9348   | 
 |  Indirect (All)                                                                                            |  412716  |  44221  |  72271  | 
 |  Incomplete (All)                                                                                          |  176284  |  18926  |  23453  | 
 |  Logical&#124;Multiple Relations&#124;Direct                                                               |  29537   |  3209   |  5463   | 
 |  Quantitative&#124;Min/Max&#124;Single entity type                                                         |  33580   |  3664   |  304    | 
 |  Quantitative&#124;Min/Max&#124;Mult. entity type                                                          |  25363   |  2725   |  2813   | 
 -->

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-us36{border-color:inherit;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-us36">Question Type</th>
    <th class="tg-us36">Train</th>
    <th class="tg-us36">Valid</th>
    <th class="tg-us36">Test</th>
  </tr>
  <tr>
    <td class="tg-us36">Simple|Direct</td>
    <td class="tg-us36">465184</td>
    <td class="tg-us36">52189</td>
    <td class="tg-us36">81994</td>
  </tr>
  <tr>
    <td class="tg-us36">Simple|Indirect</td>
    <td class="tg-us36">293692</td>
    <td class="tg-us36">32877</td>
    <td class="tg-us36">54854</td>
  </tr>
  <tr>
    <td class="tg-us36">Simple|Incomplete</td>
    <td class="tg-us36">58627</td>
    <td class="tg-us36">6658</td>
    <td class="tg-us36">10045</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|Count over More/Less|Mult. entity type|Direct</td>
    <td class="tg-us36">36658</td>
    <td class="tg-us36">3791</td>
    <td class="tg-us36">7711</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|Count over More/Less|Mult. entity type|Indirect</td>
    <td class="tg-us36">7783</td>
    <td class="tg-us36">808</td>
    <td class="tg-us36">1177</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|Count over More/Less|Mult. entity type|Incomplete</td>
    <td class="tg-us36">15137</td>
    <td class="tg-us36">1564</td>
    <td class="tg-us36">3249</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|Count over More/Less|Single entity type|Direct</td>
    <td class="tg-us36">47682</td>
    <td class="tg-us36">4738</td>
    <td class="tg-us36">5224</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|Count over More/Less|Single entity type|Indirect</td>
    <td class="tg-us36">9100</td>
    <td class="tg-us36">932</td>
    <td class="tg-us36">922</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|Count over More/Less|Single entity type|Incomplete</td>
    <td class="tg-us36">19324</td>
    <td class="tg-us36">1929</td>
    <td class="tg-us36">1972</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|More/Less|Mult. entity type|Direct</td>
    <td class="tg-us36">36538</td>
    <td class="tg-us36">3711</td>
    <td class="tg-us36">7655</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|More/Less|Mult. entity type|Indirect</td>
    <td class="tg-us36">6797</td>
    <td class="tg-us36">645</td>
    <td class="tg-us36">1184</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|More/Less|Mult. entity type|Incomplete</td>
    <td class="tg-us36">15086</td>
    <td class="tg-us36">1546</td>
    <td class="tg-us36">3209</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|More/Less|Single entity type|Direct</td>
    <td class="tg-us36">47149</td>
    <td class="tg-us36">4725</td>
    <td class="tg-us36">5520</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|More/Less|Single entity type|Indirect</td>
    <td class="tg-us36">7087</td>
    <td class="tg-us36">736</td>
    <td class="tg-us36">925</td>
  </tr>
  <tr>
    <td class="tg-us36">Comparative|More/Less|Single entity type|Incomplete</td>
    <td class="tg-us36">19107</td>
    <td class="tg-us36">1910</td>
    <td class="tg-us36">2064</td>
  </tr>
  <tr>
    <td class="tg-us36">Logical|Union|Direct</td>
    <td class="tg-us36">70694</td>
    <td class="tg-us36">7345</td>
    <td class="tg-us36">14418</td>
  </tr>
  <tr>
    <td class="tg-us36">Logical|Intersection|Direct</td>
    <td class="tg-us36">31205</td>
    <td class="tg-us36">3278</td>
    <td class="tg-us36">5708</td>
  </tr>
  <tr>
    <td class="tg-us36">Logical|Difference|Direct</td>
    <td class="tg-us36">3726</td>
    <td class="tg-us36">373</td>
    <td class="tg-us36">661</td>
  </tr>
  <tr>
    <td class="tg-us36">Logical|Incomplete</td>
    <td class="tg-us36">6372</td>
    <td class="tg-us36">765</td>
    <td class="tg-us36">1679</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Atleast/ Atmost/ Approx. the same/Equal|Mult. entity type|Direct</td>
    <td class="tg-us36">21110</td>
    <td class="tg-us36">2161</td>
    <td class="tg-us36">3910</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Atleast/ Atmost/ Approx. the same/Equal|Single entity type|Direct</td>
    <td class="tg-us36">27613</td>
    <td class="tg-us36">2790</td>
    <td class="tg-us36">2306</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count over Atleast/ Atmost/ Approx. the same/Equal|Mult. entity type|Direct</td>
    <td class="tg-us36">21257</td>
    <td class="tg-us36">2272</td>
    <td class="tg-us36">3850</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count over Atleast/ Atmost/ Approx. the same/Equal|Single entity type|Direct</td>
    <td class="tg-us36">27507</td>
    <td class="tg-us36">2801</td>
    <td class="tg-us36">2288</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count|Logical operators|Direct</td>
    <td class="tg-us36">21734</td>
    <td class="tg-us36">2089</td>
    <td class="tg-us36">3753</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count|Logical operators|Indirect</td>
    <td class="tg-us36">10802</td>
    <td class="tg-us36">991</td>
    <td class="tg-us36">2035</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count|Mult. entity type|Direct</td>
    <td class="tg-us36">24561</td>
    <td class="tg-us36">2472</td>
    <td class="tg-us36">4329</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count|Single entity type|Direct</td>
    <td class="tg-us36">51584</td>
    <td class="tg-us36">5125</td>
    <td class="tg-us36">4477</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count|Single entity type|Indirect</td>
    <td class="tg-us36">15995</td>
    <td class="tg-us36">1519</td>
    <td class="tg-us36">2547</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Count|Single entity type|Incomplete</td>
    <td class="tg-us36">20050</td>
    <td class="tg-us36">1990</td>
    <td class="tg-us36"> - </td>
  </tr>
  <tr>
    <td class="tg-us36">Verification|Single/Multiple Entity|Direct</td>
    <td class="tg-us36">47505</td>
    <td class="tg-us36">5376</td>
    <td class="tg-us36">10150</td>
  </tr>
  <tr>
    <td class="tg-us36">Verification|Single/Multiple Entity|Indirect</td>
    <td class="tg-us36">83325</td>
    <td class="tg-us36">9218</td>
    <td class="tg-us36">16578</td>
  </tr>
  <tr>
    <td class="tg-us36">Clarification (All)</td>
    <td class="tg-us36">77835</td>
    <td class="tg-us36">8164</td>
    <td class="tg-us36">12121</td>
  </tr>
  <tr>
    <td class="tg-us36">Indirect (All)</td>
    <td class="tg-us36">407784</td>
    <td class="tg-us36">45216</td>
    <td class="tg-us36">75640</td>
  </tr>
  <tr>
    <td class="tg-us36">Incomplete (All)</td>
    <td class="tg-us36">172957</td>
    <td class="tg-us36">18341</td>
    <td class="tg-us36">23220</td>
  </tr>
  <tr>
    <td class="tg-us36">Logical|Multiple Relations|Direct</td>
    <td class="tg-us36">49970</td>
    <td class="tg-us36">5164</td>
    <td class="tg-us36">9598</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Min/Max|Single entity type</td>
    <td class="tg-us36">29409</td>
    <td class="tg-us36">2942</td>
    <td class="tg-us36">342</td>
  </tr>
  <tr>
    <td class="tg-us36">Quantitative|Min/Max|Mult. entity type</td>
    <td class="tg-us36">21098</td>
    <td class="tg-us36">2133</td>
    <td class="tg-us36">2695</td>
  </tr>
</table>

### Overall Dataset Statistics

 |  Dataset Statistics                              |  Train   |  Valid  |  Test   | 
 | ------------------------------------------------ | -------- | ------- | ------- | 
 |  Total No. of Dialogs(chat sessions)             |  152391  |  16813  |  27797  | 
 |  Avg. No. of Utterances per dialog               |  15.9    |  15.65  |  19.44  | 
 |  Total No. of Utterances having Question/Answer  |  1.2M    |  .13M   |  .27M   | 
 |  Length of user’s question (in words)            |  9.7     |  9.68   |  10.28  | 
 |  Length of system’s response (in words)          |  4.74    |  4.67   |  4.37   | 
 |  Avg. No. of Dialog states per dialog            |  3.89    |  3.84   |  4.53   | 
 |  Vocab size (freq>=10)                           |  0.1M    |  -      |  -      | 
