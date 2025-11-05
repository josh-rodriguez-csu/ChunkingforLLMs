# ChunkingforLLMs
This repository houses supplementary code and data for the project "Memory Chunking for Enhancing Deductive Coding for Urban System Management with Large Language Models"

File: output_data.csv
Context: Contains results from LLM execution consolidated into a single file. This contains the raw textual response from the LLM which is converted into Boolean values using the keywords described in the Methods.

Values: 
File - The file from which the data was extracted, primarily used to validate the data preprocessing script.
Sheet - The Excel sheet from which the data was extracted, primarily used to validate the data preprocessing script.
Model - The OpenAI LLM model which generated the result {GPT-4o-mini, GPT-4o, o1-mini}
Prompt - The prompting approach given to the LLM {Whole Paper, Chunking}
Iteration - The assigned repetition number for the execution of the prompt when searching for the dimension within the paper. {1:15}.
Paper - The text in which the dimension was searched for. See "LLMsForDeductiveCoding_Appendix.xlsx" for a complete list of citations.
Dimension - The Digital Twinning dimension searched for in the paper. See "LLMsForDeductiveCoding_Appendix.xlsx" for the complete codebook.
Value - The raw response from the LLM in searching for the dimension in the paper. 

---------------
File: manual_results.csv
Context: Contains the combined results from the three manual raters for each paper and dimension. 

Values: 
Dimension - The Digital Twinning dimension searched for in the paper. See "LLMsForDeductiveCoding_Appendix.xlsx" for the complete codebook.
Paper - The text in which the dimension was searched for. See "LLMsForDeductiveCoding_Appendix.xlsx" for a complete list of citations.
Rater 1-3 - The Boolean value assigned to the dimension based on the presence or absence of the dimension in the paper.

---------------
File: LLMsForDeductiveCoding_Appendix.xlsx
Context: Contains additional materials to aid in the understanding of the research process. 

Sheet:
DT Dimensions - Contains the codebook used for both manual and LLM raters, including the example statements used in single-shot prompting described in Appendix B.
Paper Citations - Contains the complete list of citations and links for the papers analyzed in this study. 
