Production study
================

Last update: 2021-03-24

This directory contains the files of the production study, which was
designed to elicit spoken utterances that contain referential phrases
like *blue banana*.

# Overview

There are 2 subdirectories:

-   `audio/` contains `.wav` and `.TextGrid` files from the production
    experiment.
-   `trial-lists/` contains `.csv` files with info on the trials from
    the production experiment.

# TextGrids

# Trial lists

Trial lists contain the following columns:

-   `speaker`: The speaker id.
-   `trial`: The position of the trial within the experiment (numeric).
-   `condition`: The focus condition (`NF` = noun focus, `AF` =
    adjective focus, `ANF` = double focus on adjective and noun; `NF`s
    are the critical conditions).
-   `typicality`: Typicality category (`typical`, `medium`, `atypical`;
    `NA` for AF and ANF).
-   `target_object`: Target object.
-   `target_colour`: Colour of the target object.
-   `competitor_name`: Competitor object.
-   `competitor_colour`: Colour of the competitor object.
-   `distractror1_name`: Distractor-1 object.
-   `distractror1_colour`: Colour of the distractor-1 object.
-   `distractror2_name`: Distractor-2 object.
-   `distractror2_colour`: Colour of the distractor-2 object.
-   `object_en`: The English translation of `target_object`.
-   `colour_en`: The English translation of `target_colour`.
-   `typ_sd`: The standard deviation of the typicality ratings .
-   `typ_median`: The median typicality rating.
-   `typ_median`: The median typicality rating.
