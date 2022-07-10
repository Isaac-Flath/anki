# Anki

This repo is to hold stuff for my Anki repetitive spaced learning decks.  Currently I only have decks created for Dyalog APL, though it may or may not host other stuff in the future.

# Fastai APL Study Group Instructions

If you are following the [fastai apl-study group](https://forums.fast.ai/t/apl-array-programming/97188) (either live or pre-recorded) follow these instructions.  These will allow cards to be added as you follow along in the course.

1. Load the `AplStudyGroup_CodeCards_Week1.csv` deck.  This has all the cards covered in week 1 of the fastai apl study group.  Unfortunately I do not have week 1 broken out.
1. After watching each study group session check back to load any new decks.  They will be named `AplStudyGroup_CodeCards_Session<num>diff.csv`.  This will create a deck with any cards that have either changed or created based on the latest changes.  For example `AplStudyGroup_CodeCards_Session5diff.csv` will have only cards modified or added during Session 5 of the study group.

# Files

+ **DyalogAnki.ipynb:** Creates several importable anki decks for dyalog APL
    + **AplStudyGroup_CodeCards_all.csv:** This is an Anki importable deck
        + Contains cards auto generated from notebooks created as part of the [fastai apl study group](https://fastai.github.io/apl-study).  These cards give a simple code snippet and your job is to predict the output
     + **DyalogDocs_AllCards.csv:** This is an Anki importable deck
        + Contains cards auto generated by scraping the Dyalog Docs.
        + Symbol -> Symbol Name, Symbol Name -> Symbol, Symbol Name -> What it does, What is does -> Symbol, etc.
  
