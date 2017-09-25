=======
History
=======

0.1.2 (2016-10-29)
------------------

* Curate Ammonia assimilation such that GS/GOGAT and NADP-GDH are the only
options as reported for U. maydis.
* Move the glyoxylate shunt to the Mitochondrion since the Glyoxysome is not
represented in the model
* Fix GPR for MDH and Malic Enzyme and distinguish between the cytosolic and
mitochondrial enzymes.
* Remove parallel Glycolysis reactions which use glucose isoforms (alpha, beta)
instead of one metabolite form that represents a racemate.
* Set correct IDs for ubiquinone and ubiquinol metabolites
* Map gene IDs to the newer representation (from um**** to UMAG_****)
* Implement the erythritol biosynthesis pathway.
* Implement the MEL biosynthesis pathway.
* Implement the Ustilagic acid biosynthesis pathway.
* Clean up and map IDs for the fatty acid biosynthesis.
* Start building a metabolic map in Escher.
* Curate BiGG IDs, reaction direction and bounds in the central carbon
metabolism
* Balance respiratory chain

0.1.1 (2016-08-11)
------------------

* Partially map reaction and metabolite IDs from metacyc to MNX to BiGG
* Implement the growth conditions from the matlab script in the thesis to python
* Move notes field contents to annotation attribute
* Create json-formatted representation of the model

0.1.0 (2015-09-11)
------------------

* Curate automated draft from master's thesis (Lieven, C., & Blank, P. L. M.
(2015). Generation of a genome-scale metabolic model of Ustilago maydis ,
causative agent of corn smut)
