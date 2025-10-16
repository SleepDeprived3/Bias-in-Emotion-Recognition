# Exploring the Data

## Outcome Variables
Our outcome variable for this research project will be the emotions identified by our Crema-D-trained emotion classifier. In particular, we hope to examine the how emotional classification vary when applied to a non-emotionally-focused speech accent archive dataset. Since we expect Crema-D emotion classifiers to respond with negative biases towards certain accents over others, we predict that more negative emotional classifications will be present in some accents in when compared to others.

## Explanatory Variables
Explantory variable we plan to investigate in the Speech Accent Archive Dataset are as follows:
1. Accent 
2. Age
3. Sex

-----

# Data Preparation and Cleaning

## Data manipulations
Ultimately, our exploratory analyses did not require an extensive manipulation of the data as most of the provided csv files were tidy datasets to begin with. While the accent archive required a dropping of null values and a stripping of country names, the Crema-D csv required little to no manipulations. 

We have decided to include all of the data from these datasets. While we initially considered excluding Crema-D data that did not include a marked emotion strength, we determined that all emotion examples (regardless of strength) were necessary in order to create a strong emotion classifier. 

While we have not created any new variable yet, a variable we expect to make in the future is the 

-----

# Codebook

a description of all variables you are using, including ones you are creating for this project

|  var label  |  var name  |  type    |  description
--------------------------------------------------
|  emotion    |  emotion   |  string  |  Emotions provided by an emotional classifier 
|             |            |          |  (trained on Crema-D) when applied to the speech accent archive
|  accent     |  accent    |  string  |  Accent of a singular recording from the speech accent archive
|  age        |  age       |  int     |  Age of the speaker attached to a singular recording in the speech accent archive
|  sex        |  sex       |  string  |  Sex of the speaker attached to a singular recording in the speech accent archive