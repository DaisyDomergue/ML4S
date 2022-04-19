# ML4S

# uses brainspeech for training speect-to-text engine

the prepare.ipynb is used to prepare the ICNALE data to be fed to the training of the stt engine
there must be a the following folder in the same folder for the prepare to work and installed version of speechbrain

!pip install speechbrain
mkdir data

the extracted data of ICNALE

ICNALE_SM_2.0_A
ICNALE_SM_2.0_T

and all the contents of the following directories must be copied
"\ML4S\ICNALE_SM_2.0_T\ICNALE_Spoken_Monologue_2.0_Transcripts\Unmerged_classified\ICNALE_SM_ENS_XX3_N100"
"\ML4S\ICNALE_SM_2.0_T\ICNALE_Spoken_Monologue_2.0_Transcripts\Unmerged_classified\ICNALE_SM_ENS_XX1_N200"
"\ML4S\ICNALE_SM_2.0_T\ICNALE_Spoken_Monologue_2.0_Transcripts\Unmerged_classified\ICNALE_SM_ENS_XX2_N300"

destination dir

"C:\Users\Gaia\Documents\Schoolwork\ML4S\ICNALE_SM_2.0_T\ICNALE_Spoken_Monologue_2.0_Transcripts\Unmerged_classified\ICNALE_SM_ENS_XXX_NX00"
