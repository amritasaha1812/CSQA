---
layout: page
title: Download
permalink: /download_CQA/
---
CQA i.e. subset of the CSQA dataset where the questions are directly answerable. The train, validation and test splits of the dataset are extracted from the respective data-splits in the CSQA dataset. The CQA dataset can be downloaded in .zip format at the link: 
[Dialog zip link](https://drive.google.com/file/d/1cHSIwUqcZPGP9fZoA46xLRL22kUqqvlo/view?usp=sharing) <br>

CQA-12K a smaller subset of the above CQA dataset, consisting of 10K QA pairs for training and 1K for validation and test split respectively. The train, validation and test splits of the dataset are extracted from the respective data-splits in the CQA dataset. The CQA-12K dataset can be downloaded in the preprocessed .zip format at the link:
[Dialog zip link](https://drive.google.com/file/d/1QcQyDcPxuFSQ7HTO03EffAEC-HSSq0MR/view?usp=sharing) <br>


The wikidata jsons (in pre-processed format) can be downloaded [here](https://drive.google.com/drive/folders/1ITcgvp4vZo1Wlb66d_SnHvVmLKIqqYbR?usp=sharing)

### **Information About Different Json Files Used In CQA/CQA-12K Pre-processing**
The preprocessed_data_*.zip contains the following zips, train_*.zip, valid_*.zip and test_*.zip. Each of these zips contain a list of folders, each named as QA_* (like QA_100, QA_10, etc.). Each of these QA_* folders  contains the following files, where each line corresponds to a single QA pair.

1. **QA_*_state.txt**  
where each line corresponds to one of the seven Query-Types 

2. **QA_*_context_utterance.txt** 
where each line corresponds to the natural language question

3. **QA_*_context.txt** 
where each line corresponds to a tokenized version of the natural language question, with the entity mention replaced by their corresponding QID from wikidata (using oracle entity linker)

4. **QA_*_context_entities.txt** 
where each line corresponds to a pipe-delimited list of QIDs of KB-entities in the query (from oracle entity linker)

5. **QA_*_context_relations.txt** 
where each line corresponds to a pipe-delimited list of PIDs of KB-relations  in the query (from oracle relation linker)

6. **QA_*_context_types.txt** 
where each line corresponds to a pipe-delimited list of QIDs of KB-types in the query (from oracle type linker)

7. **QA_*_context_ints.txt** 
where each line corresponds to a pipe-delimited list of integers in the query

8. **QA_*_orig_response.txt** 
where each line corresponds to the natural language response

9. **QA_*_response_entities.txt** 
where each line corresponds to the pipe-delimited list of QIDs of the KB-entities in the response (from the oracle entity linker). The natural language response may have a subsampled list of of entities from this list, that is simply done to keep the conversation realistic. If the response has more than 4-5 entities, the dialog agent usually answers saying, "... X, Y, Z are some of the answers. Do you want to see more?"

10. **QA_*_response_ints.txt** 
where each line corresponds to the pipe-delimited list of integers in the response

11. **QA_*_response_bools.txt**  
where each line corresponds to the pipe-delimited list of booleans (yes or no) in the response






### **Information About Different Json Files Used In WikiData Pre-processing**

1. **wikidata_short_1.json**
The outermost index indexes the ‘subject entities’. The value of each wikidata_short_1[key] is a dict. with keys as pid’s (id’s corresponding to the relations/predicates). The value of each wikidata_short_1[key][pid] is a list of object entities with the outer key as the subject entity.
The (key, pid, object entity) is a usual KB triple.
(Similarly for wikidata_short_2.json)

2. **comp_wikidata_rev.json**
The outermost index indexes the ‘object entities’. The value of each comp_wikidata_rev[key] is a dict. with keys as pid’s (id’s corresponding to the relations/predicates). The value of each comp_wikidata_rev[key][pid] is a list of subject entities with outer key as the object entity.
The (key, inverse(pid), subject entity) is a usual KB triple.

3. **wikidata_type_dict.json**
The outermost index indexes the entity types of ‘subject entities’. The value of each wikidata_type_dict[key] is a dict. with keys as pid’s (id’s corresponding to the relations/predicates). The value of each wikidata_type_dict[key][pid] is a list of object entity types with the outer key as the subject entity type.
The (child(key), pid, child(object entity)) is a usual KB triple.

4. **wikidata_rev_type_dict.json**
The outermost index indexes the entity types of ‘object entities’. The value of each wikidata_rev_type_dict[key] is a dict. with keys as pid’s (id’s corresponding to the relations/predicates). The value of each wikidata_rev_type_dict[key][pid] is a list of subject entity types with the outer key as the object entity type.
The (child(key), inverse(pid), child(subject entity)) is a usual KB triple.

5. **filtered_property_wikidata4.json**
This json contains a dict with keys as the ids of relations/predicates and values as the string labels of the corresponding predicates. Note: The list of predicates is filtered and undesirable/superficial predicates were removed.

6. **child_par_dict_immed.json**
This json contains a dict with keys as all the entities present in wikidata and the values as the corresponding immediate parent of the particular entity in wikidata hierarchy.

7. **child_par_dict_save.json**
This json contains a dict with keys as all the entities present in wikidata and the values as the corresponding parent entity (which may be the 1-hop or 2-hop parent of the entity).


8. **child_all_parents_till_5_levels.json**
This json contains a dict with keys as all the entities present in wikidata and the value is a list of all parents of the particular entity (till 5 levels).

9. **wikidata_fanout_dict.json**
The value corresponding to each entity in this dict contains the count of number of triples in which the particular entity participates.

10. **items_wikidata_n.json**
This json contains a dict with keys as the ids of wikidata entities and values as their string labels.

11. **prop_sub_90_map5.json**
This dict contains, corresponding to each key (predicate id), the list of subject parents which fall in top 90 percentile of all subject parents associated with that predicate (in form of triples).

12. **prop_obj_90_map5.json**
This dict contains, corresponding to each key (predicate id), the list of object parents which fall in top 90 percentile of all object parents associated with that predicate (in form of triples).

13. **par_child_dict.json**
This dict contains, corresponding to each key (entity id of a parent entity), the list of its children entities (in no particular order).

14. **child_par_dict_name_2_corr.json**
This dict contains, corresponding to each key (entity id of a parent entity), the label corresponding to that parent entity. Note: This overrides the labels obtained from item_wikidata_n.json.













