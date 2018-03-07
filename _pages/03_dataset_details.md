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
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg .tg-yw4l{vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-yw4l">Question Type</th>
    <th class="tg-yw4l">Train</th>
    <th class="tg-yw4l">Valid</th>
    <th class="tg-yw4l">Test</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Simple | Direct</td>
    <td class="tg-yw4l">459393</td>
    <td class="tg-yw4l">49565</td>
    <td class="tg-yw4l">77569</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Simple | Indirect</td>
    <td class="tg-yw4l">295416</td>
    <td class="tg-yw4l">31719</td>
    <td class="tg-yw4l">52225</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Simple | Incomplete</td>
    <td class="tg-yw4l">58209</td>
    <td class="tg-yw4l">6408</td>
    <td class="tg-yw4l">9418</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | Count over More/Less | Mult. entity type | Direct</td>
    <td class="tg-yw4l">34868</td>
    <td class="tg-yw4l">3860</td>
    <td class="tg-yw4l">6569</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | Count over More/Less | Mult. entity type | Indirect</td>
    <td class="tg-yw4l">7399</td>
    <td class="tg-yw4l">840</td>
    <td class="tg-yw4l">1267</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | Count over More/Less | Mult. entity type | Incomplete</td>
    <td class="tg-yw4l">14288</td>
    <td class="tg-yw4l">1573</td>
    <td class="tg-yw4l">2724</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | Count over More/Less | Single entity type | Direct</td>
    <td class="tg-yw4l">45266</td>
    <td class="tg-yw4l">4785</td>
    <td class="tg-yw4l">4495</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | Count over More/Less | Single entity type | Indirect</td>
    <td class="tg-yw4l">8793</td>
    <td class="tg-yw4l">950</td>
    <td class="tg-yw4l">950</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | Count over More/Less | Single entity type | Incomplete</td>
    <td class="tg-yw4l">18238</td>
    <td class="tg-yw4l">1939</td>
    <td class="tg-yw4l">1624</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | More/Less | Mult. entity type | Direct</td>
    <td class="tg-yw4l">34978</td>
    <td class="tg-yw4l">3787</td>
    <td class="tg-yw4l">6659</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | More/Less | Mult. entity type | Indirect</td>
    <td class="tg-yw4l">7416</td>
    <td class="tg-yw4l">783</td>
    <td class="tg-yw4l">1247</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | More/Less | Mult. entity type | Incomplete</td>
    <td class="tg-yw4l">14368</td>
    <td class="tg-yw4l">1564</td>
    <td class="tg-yw4l">2717</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | More/Less | Single entity type | Direct</td>
    <td class="tg-yw4l">44408</td>
    <td class="tg-yw4l">4871</td>
    <td class="tg-yw4l">4654</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | More/Less | Single entity type | Indirect</td>
    <td class="tg-yw4l">8778</td>
    <td class="tg-yw4l">996</td>
    <td class="tg-yw4l">977</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Comparative | More/Less | Single entity type | Incomplete</td>
    <td class="tg-yw4l">17904</td>
    <td class="tg-yw4l">1959</td>
    <td class="tg-yw4l">1703</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Logical | Union | Direct</td>
    <td class="tg-yw4l">69805</td>
    <td class="tg-yw4l">7437</td>
    <td class="tg-yw4l">13805</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Logical | Intersection | Direct</td>
    <td class="tg-yw4l">45507</td>
    <td class="tg-yw4l">4798</td>
    <td class="tg-yw4l">8110</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Logical | Difference | Direct</td>
    <td class="tg-yw4l">4885</td>
    <td class="tg-yw4l">466</td>
    <td class="tg-yw4l">853</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Logical | Incomplete</td>
    <td class="tg-yw4l">7805</td>
    <td class="tg-yw4l">863</td>
    <td class="tg-yw4l">2045</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Atleast/ Atmost/ Approx. the same/Equal | Mult. entity type | Direct</td>
    <td class="tg-yw4l">20434</td>
    <td class="tg-yw4l">2218</td>
    <td class="tg-yw4l">3504</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Atleast/ Atmost/ Approx. the same/Equal | Single entity type | Direct</td>
    <td class="tg-yw4l">26409</td>
    <td class="tg-yw4l">2836</td>
    <td class="tg-yw4l">2046</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count over Atleast/ Atmost/ Approx. the same/Equal | Mult. entity type | Direct</td>
    <td class="tg-yw4l">20433</td>
    <td class="tg-yw4l">2272</td>
    <td class="tg-yw4l">3450</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count over Atleast/ Atmost/ Approx. the same/Equal | Single entity type | Direct</td>
    <td class="tg-yw4l">26511</td>
    <td class="tg-yw4l">2864</td>
    <td class="tg-yw4l">1973</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count | Logical operators | Direct</td>
    <td class="tg-yw4l">20789</td>
    <td class="tg-yw4l">2233</td>
    <td class="tg-yw4l">3241</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count | Logical operators | Indirect</td>
    <td class="tg-yw4l">9890</td>
    <td class="tg-yw4l">1002</td>
    <td class="tg-yw4l">1687</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count | Mult. entity type | Direct</td>
    <td class="tg-yw4l">23727</td>
    <td class="tg-yw4l">2465</td>
    <td class="tg-yw4l">4050</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count | Single entity type | Direct</td>
    <td class="tg-yw4l">51443</td>
    <td class="tg-yw4l">5426</td>
    <td class="tg-yw4l">7220</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count | Single entity type | Indirect</td>
    <td class="tg-yw4l">14815</td>
    <td class="tg-yw4l">1527</td>
    <td class="tg-yw4l">2129</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Count | Single entity type | Incomplete</td>
    <td class="tg-yw4l">21153</td>
    <td class="tg-yw4l">2217</td>
    <td class="tg-yw4l">2919</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Verification | Single/Multiple Entity | Direct</td>
    <td class="tg-yw4l">47175</td>
    <td class="tg-yw4l">5095</td>
    <td class="tg-yw4l">9889</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Verification | Single/Multiple Entity | Indirect</td>
    <td class="tg-yw4l">82332</td>
    <td class="tg-yw4l">8755</td>
    <td class="tg-yw4l">16094</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Clarification (All)</td>
    <td class="tg-yw4l">75944</td>
    <td class="tg-yw4l">8122</td>
    <td class="tg-yw4l">11029</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Indirect (All)</td>
    <td class="tg-yw4l">410134</td>
    <td class="tg-yw4l">44043</td>
    <td class="tg-yw4l">72760</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Incomplete (All)</td>
    <td class="tg-yw4l">171566</td>
    <td class="tg-yw4l">18646</td>
    <td class="tg-yw4l">25794</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Logical | Multiple Relations | Direct</td>
    <td class="tg-yw4l">49075</td>
    <td class="tg-yw4l">5179</td>
    <td class="tg-yw4l">9029</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Min/Max | Single entity type</td>
    <td class="tg-yw4l">28180</td>
    <td class="tg-yw4l">3008</td>
    <td class="tg-yw4l">302</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Quantitative | Min/Max | Mult. entity type</td>
    <td class="tg-yw4l">20451</td>
    <td class="tg-yw4l">2195</td>
    <td class="tg-yw4l">2358</td>
  </tr>
</table>
### Types of questions in the dataset

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
</style>
<table class="tg">
  <tr>
    <th class="tg-031e">Reasoning</th>
    <th class="tg-031e">Type</th>
    <th class="tg-031e">Containing</th>
    <th class="tg-031e">Example</th>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="4">Logical</td>
    <td class="tg-031e">Union</td>
    <td class="tg-031e" rowspan="3">Single Relation</td>
    <td class="tg-031e">Which rivers flow through India or China?</td>
  </tr>
  <tr>
    <td class="tg-031e">Intersection</td>
    <td class="tg-031e">Which rivers flow through India and China?</td>
  </tr>
  <tr>
    <td class="tg-031e">Difference</td>
    <td class="tg-031e">Which rivers flow through India but not China?</td>
  </tr>
  <tr>
    <td class="tg-031e">Any of above</td>
    <td class="tg-031e">Multiple Relations</td>
    <td class="tg-031e">Which river flows through India but does not originate in Himalayas?</td>
  </tr>
  <tr>
    <td class="tg-031e">Verification</td>
    <td class="tg-031e">Boolean</td>
    <td class="tg-031e">Single/Multiple<br> Entities</td>
    <td class="tg-031e">Does Ganga flow through India ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="9">Quantitative</td>
    <td class="tg-031e" rowspan="3">Count</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">How many rivers flow through India ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">How many rivers and lakes does India have ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Logical Operators</td>
    <td class="tg-031e">How many rivers flow through India and/or/but not China?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Min/Max</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">Which river flows through maximum number of countries ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">Which country has maximum number of rivers and lakes combined ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Atleast/Atmost/<br>Approx/Equal</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">Which rivers flow through at least N countries ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">Which country has at least N rivers and lakes combined ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Count over <br>Atleast/Atmost/<br>Approx/Equal</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">How many rivers flow through at least N countries?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">How many countries have at least N rivers and lakes combined ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="4">Comparative</td>
    <td class="tg-031e" rowspan="2">More/Less</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">Which countries have more number of rivers than India ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">Which countries have more rivers and lakes than India ?</td>
  </tr>
  <tr>
    <td class="tg-031e" rowspan="2">Count over<br>More/Less</td>
    <td class="tg-031e">Single Entity Type</td>
    <td class="tg-031e">How many countries have more number of rivers than India ?</td>
  </tr>
  <tr>
    <td class="tg-031e">Mult. Entity Type</td>
    <td class="tg-031e">How many countries have more rivers and lakes than India ?</td>
  </tr>
</table>

### Overall Dataset Statistics

 |  Dataset Statistics                              |  Train   |  Valid  |  Test   | 
 | ------------------------------------------------ | -------- | ------- | ------- | 
 |  Total No. of Dialogs(chat sessions)             |  152391  |  16413  |  27797  | 
 |  Avg. No. of Utterances per dialog               |  15.9    |  15.65  |  19.44  | 
 |  Total No. of Utterances having Question/Answer  |  1.2M    |  .13M   |  .27M   | 
 |  Length of user’s question (in words)            |  9.7     |  9.68   |  10.28  | 
 |  Length of system’s response (in words)          |  4.74    |  4.67   |  4.37   | 
 |  Avg. No. of Dialog states per dialog            |  3.89    |  3.84   |  4.53   | 
 |  Vocab size (freq>=10)                           |  0.1M    |  -      |  -      | 
