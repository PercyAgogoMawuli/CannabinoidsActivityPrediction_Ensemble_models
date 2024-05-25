
# Predicting the bioactivities of Cannabinoid receptor 1 (CN1R) compounds using Ensemble models

In this project, different ensemble models were built to help predict the bioactivity of a CN1R compound.
CN1R is a G protein-coupled receptor that plays a crucial role in regulating various physiological processes such as hunger, memory, gastrointestinal activity, and pain management. Cannabinoid 1 receptor (CN1R) compounds have been extensively studied for their bioactivity, particularly in the context of obesity and metabolic disorders. 


## Dataset
The data consists of information on 22,886 CN1R compounds and other information related to the drug compounds including their bioactivities, cid, compound name,sid, aid and geneid, which were obtained from the PubChem database. In this project, the first 100 CN1R compounds were used in model building.The dataset can be downloaded here: https://pubchem.ncbi.nlm.nih.gov/gene/1268#section=Chemicals-and-Bioactivities

Features of these compounds were extracted from Pubchem database with the use of webscrapers. 
The features use include: MolecularWeight,XLogP, ExactMass, MonoisotopicMass, TPSA, Complexity, Charge,HBondDonorCount, HBondAcceptorCount, RotatableBondCount,HeavyAtomCount, IsotopeAtomCount, AtomStereoCount,DefinedAtomStereoCount, UndefinedAtomStereoCount, BondStereoCount,DefinedBondStereoCount, UndefinedBondStereoCount, CovalentUnitCount,Volume3D, XStericQuadrupole3D, YStericQuadrupole3D,ZStericQuadrupole3D, FeatureCount3D, FeatureAcceptorCount3D,FeatureDonorCount3D, FeatureAnionCount3D,FeatureCationCount3D,FeatureRingCount3D', FeatureHydrophobeCount3D, ConformerModelRMSD3D,EffectiveRotorCount3D, ConformerCount3D

In addition to these chemical features, Morgan fingerprints were also generated for each compound to introduce structural information in the model
## Tools/Skills Used
-Google colab

-Pubchempy

-Pandas

-RDKit

-Numpy

-Scikit-learn

-Data wrangling