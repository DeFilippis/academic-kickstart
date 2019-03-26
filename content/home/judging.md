+++
widget = "blank"  # Do not modify this line!
active = true  # Activate this widget? true/false
weight = 17  # Order that this section will appear.

title = "Judging Criteria"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  #color = "navy"

  # Background gradient.
  #gradient_start = "DarkGreen"
  #gradient_end = "ForestGreen"

  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

[advanced]
 # Custom CSS.
 css_style = "padding-top: 20px; padding-bottom: 20px;"

 # CSS class.
 css_class = ""
+++

## Submission Criteria

- Participants may submit as many questions as they like, but note that not all questions will pass our initial review. (See below for details). Submitting a large number of low-quality questions will not increase your odds of winning a prize.

- Prizes will be awarded to the top two submissions for each of the following categories: Democrat "Knowledge Deserts", Republican "Knowledge Deserts", Democrat "Belief Biases" and Republican "Belief Biases" (see prizes tab for award amounts)

- The deadline for submitting questions is May 5th, 2019 at 11:59 p.m.

## Judging Criteria

To determine winners for each category of question, we will do the following:

* All questions will be subject to an initial review designed to screen out low-quality questions. (Given that we do not know how many questions we will receive, we cannot commit in advance to testing all submitted questions. It is our intention, however, to test all questions that could plausibly meet our criteria.

* We will take all of the questions that pass our initial review as contest entries and pose them to a large sample of real Republican and Democrat respondents.

* To qualify as a "belief bias", participants from a specific political party (e.g. Republicans) should, on average, get the answer wrong more often than a participant from the other political party (e.g. Democrat).  Furthermore, both participants should have a hunch that their answer is right.  To qualify as a "knowledge desert" a participant should register a low degree of confidence, while getting the answer wrong (and a corresponding participant from the other political party should be register high confidence and be correct).  The actual cut-off for what constitutes a "large degree of confidence" will be up to our discretion.  

* Quantitative questions should be submitted without answer choices. We expect that the majority of quantitative questions will involve the "False Belief" category, although you are free to submit quantitative questions to the "Knowledge Desert" category. We will determine the best quantitative question (e.g. what percent of climate change scientists believe in global warming?) by computing the absolute value of the difference between the average Democrat's answer and the average Republican's answer for a given question (and vice versa depending on the category). The top questions that maximize the appropriate difference for quantitative questions will receive a reward.  

For questions that are supposed to favor Republicans, we compute the following:

$$\mid \text{Average Dem. Answer - Correct Answer} \mid  - \mid\text{Average Rep. Answer - Correct Answer}\mid$$

Such that the larger this value, the greater the answer favors Republicans. For questions that are supposed to favor Democrats, we compute  the following:

$$\mid \text{Average Rep. Answer - Correct Answer} \mid  - \mid\text{Average Dem. Answer - Correct Answer}\mid$$

Such that the larger this value, the greater the answer favors Democrats. We award the questions that maximize the above quantities.   

* Qualitative questions should be submitted *with* four multiple-choice answers. We expect that the majority of qualitative questions will involve the "Knowledge Desert" category, although you are free to submit qualitative questions to the "False Belief" category. See the "rules tab" for examples.  To determine the best questions we will take the difference between the rate of Democrats/Republicans who got the answer right and the rate of Republicans/Democrats who got the answer right.

For Republican "Knowledge Desert" questions (questions Republicans are likely to get wrong), we compute the following:

$$\mid \text{Rate for Dems - Rate for Reps} \mid $$

For Democratic "Knowledge Desert" questions, we compute the following:

$$\mid \text{Rate for Reps - Rate for Dems} \mid $$

Again, we award the questions that maximize the above quantities.   

* We reserve the right to use our discretion to reward questions that are particularly unique or clever, over and above the strict quantitative criteria described above.  
