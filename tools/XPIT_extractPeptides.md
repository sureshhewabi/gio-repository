**Name:** PIT:Extract hits

**Description:**
Extract peptide information from various file formats for PIT analysis

**Input files:**

**Parameters:**
* Conditional element: Input name: type_selection
  * mzid
  * mzq
  * maxquant

**Outputs:**
* output in tabular format

**Details:**

	    The proteomics data can come in various formats, including but not limited to PSI standards (mzQuantML and mzIdentML) and widely-used TSV(tab-separated-value) formats which is used by MaxQuant. This tools converts the information in different formats to a fixed-header tsv which will be used in the PIT:Integrate tool. The headers are in the order of Peptide, Protein, Reverse, Contamination, Score, Quantitation and unlimited optional columns. Of course it can be used standard-alone to extract the essential information from those more-complex formats.
	