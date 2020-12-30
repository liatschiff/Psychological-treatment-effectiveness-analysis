# Psychological treatment effectiveness analysis

## Introduction
  Over the past few years, transcripts of psychological treatments on patients have been collected in various laboratories in the country.
  The overarching goal of the project is to develop a system that will analyze the differences between transcripts of patients suffering 
  from post-traumaat the beginning of psychological treatment and the transcripts of those patients at the end of treatment.
	The future purpose of the system is to diagnose whether patients suffer from post-trauma even before contacting the clinic through 
  writing, and in the distant future even to prevent it.

## Methods
- Grouping all the words in the transcripts together and tagging them into groups that we assumed would constitute potential differences between transcripts before psychological treatment and transcripts after psychological treatment.

- Calculating the mean ratio for all patients for each group and examining which one of the groups had the most significant ratio (confirmed the reliability of our results using a T-TEST).

- Examining the most common words in all pre-treatment transcripts compared to post-treatment transcripts and vice versa.

- Constructing a representative vector for each transcript by using all the data we accumulated.

- Using classification algorithms and the GridSearchCV method, we classified the transcripts before psychological treatment and transcripts after psychological treatment.

## Results
The findings of the project show that a patient who suffers from post-trauma and is before psychological treatment often uses adjectives and future tenses compared to a patient after treatment, moreover a patient after treatment tends to use more pronouns-nickname and words expressing emotion and conscious than a pre-treatment patient.
All of this can indicate that a person suffering from post-trauma has difficulty focusing on the present, has difficulty expressing their feelings, and is less aware of himself and his environment. Unlike a recovered patient who recognizes his feelings, expresses his feelings, and notices the people around him.

![image](https://user-images.githubusercontent.com/49638679/95485689-c5053b00-099a-11eb-9a6d-c87dc93634d5.png)

## Conclusions
The objectives of the project were achieved, we found differences between patients suffering from post-trauma before psychological treatment and patients after psychological treatment.
We found a good way to represent each patient's transcript.
We classified the transcripts into transcripts before treatment and transcripts after treatment with an accuracy of 90%.

![image](https://user-images.githubusercontent.com/49638927/92263610-900e5000-eee5-11ea-84c9-374cc7a3bb7d.png)

## Discussions
- Increase the database and verify the differences we found.
- Distinguish between different levels of post-trauma
- Tag the words of each transcript to groups that we found relevant in an automatic way so that later will build a system that through writing the patient will know if he suffers from post-trauma before going to the clinic.
- Estimate which of the patients will suffer from post-trauma ahead of time and which of them will not, and whether this can be prevented in advance, i.e. find preventive treatment.

## Acknowledgments
This Research conducted by Liat Schiff & Aviv Shimoni, under the guidance of Dr. Jonathan Schler in collaboration between Holon Institute of Technology and Bar-Ilan University.
