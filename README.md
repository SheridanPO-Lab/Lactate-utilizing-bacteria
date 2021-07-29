# Lactate-utilizing-bacteria
This repository contains the profile hidden Markov models used in the identification of lactate utilization genes and the 3448 protein sequences (in fasta format) used as marker genes for the presence of butyrate and propionate production pathways.

## HMMER-based functional characterisation of lactate utilization genes
Lactate utilization loci were searched for using the Hidden Markov Model (HMM) profiles of conserved domains found in three-component L-lactate hydrogenase (PF02754, PF02589, PF13183, PF11870), FAD-dependent D-lactate dehydrogenase (PF01565, PF02913, PF09330, PF12838, PF02754), FMN-dependent L-lactate dehydrogenase (PF01070, PF00173), NAD-dependent D-lactate dehydrogenase (PF00389, PF02826), NAD-dependent L-lactate dehydrogenase (PF02866, PF00056), lactate permease (PF02652), lactate racemase (PF09861) and ETF (PF00766, PF01012) using hmmsearch in HMMER3. A threshold of 80 bit score was used.

## BLASTP-based functional characterisation of marker genes for short-chain fatty acid pathways
The presence of short-chain fatty acid pathways involved in the production of butyrate and propionate were predicted by querying genome sequences against a database of marker genes. Butyrate kinase and butyryl-CoA:acetate CoA-transferase were used as indicators of butyrate production, and propanediol utilization protein (PduP), lactoyl CoA dehydratase alpha-subunit (LcdA) and methyl-malonyl-CoA decarboxylase alpha-subunit (MmdA) as indicators of propionate production through the propanediol, acrylate and succinate pathways, respectively. A strict threshold of 60% identity was used.

## BLASTP-based functional characterisation of the Rnf complexes
The presence of Rnf complexes were predicted by querying genomes against the protein sequences (in fasta format) from the experimentally proven Rnf complexes of *Clostridium ljungdahlii* and *Acetobacterium woodii*.
