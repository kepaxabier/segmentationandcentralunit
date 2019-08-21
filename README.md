# segmentationandcentralunit
Segmentation and Central Unit for Basque:


For Central Unit Task:

The corpus was randomly divided into 3 non-overlapping files: etrainuceduposwords.csv, edevuceduposwords.csv and etestuceduposwords.csv.

-etrainuceduposwords.csv: 84 texts as a training data-set.

-edevuceduposwords.csv: 28 texts as development data-set.

-etestuceduposwords.csv: 28 texts as test data-set.

The format is a csv file: 

-In the first column, if segment is CU segment its value is 1 else 0.

-In the second column we can find the EDU position in the text.

-And finally in the third column is the text of the segment.

Exclusively for segmentation training purposes, we added 335 new texts with 8,633 EDUs.The format of osorik.crfIn-SENT-LAB-BESTE-MEAN.csv file is a csv file:

Id:Identifier

WordForm:WordForm

Lemma:lemma

POS:POS

C-POS:More detailed POS

CASE:Case (ABS:ABSOLUTIVE, ERG: ERGATIVE,DAT: DATIVE etc)

FEAT1:Some Morpological Features (Subordinate type)

FEAT2:Some Morpological Features (such as nominalization, ADIZE)

FEA3:Some Morpological Features (aspect)

FEA4:Some Morpological Features (temporal markers in verbs, such as past,present)

FEA5:Some Morpological Features (sing/plural in nouns, determiners, nominalizations, S singular, P plural)

SINT: NP --> Noun Phrase, VP --> Verb Phrase etc

HEAD: In dependency analysis (MALT), the head

REL:In dependency analysis (MALT), the syntactic relation

RULES-SEG:Segmentation according to the rules

GOLD-SEG:Segmentation according to human taggers

Examples:

Id,WordForm,Lemma,POS,C-POS,CASE,FEAT1,FEAT2,FEAT3,FEAT4,-,-,SINT,-,-,HEAD,REL,RULES-SEG,GOLD-SEG

1,Zer,zer,DET,DET_NOLGAL,ABS,_,_,_,_,_,0,NP,_,_,2,ncpred,EDU{,B-SEG

2,da,izan,ADT,ADT,_,_,_,PNT,MDN:A1,_,0,VP,_,_,0,ROOT,_,I-SEG
