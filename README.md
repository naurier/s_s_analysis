# s_s_analysis
jupyter notebook codes for sentence similarity analysis 

<b>export_pearsonrs_and_pvalues.jpynb</b><br>
As a preliminary step, exclude from analysis any data where the p-values of the correlation in the double-pass section are below or at 0.05.

<b>Matrix_from_CSV_with_stimulus_pairs_and_similarity_avg.ipynb</b><br>
After creating a CSV that lists all pairs of stumulus sentences and their average similarity ratings used in the analysis.

### analysis_by_traits
Sort the sentence pairs in the CSV by list_sentencePairs_dissimilarityRatings_traits.ipynb so that identical sentence pairs and their ratings and scores are grouped together. Then, input the resulting CSV into calculate_pearsonrs_spearmanrs_p-values.ipynb.

<b>calculate_pearsonrs_spearmanrs_p-values.ipynb</b><br>
Please input one of the 5 traits into 'openness = group['Neuroticism']'.
