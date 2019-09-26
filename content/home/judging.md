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

- Prizes will be awarded to the top two submissions for each of the following categories: Democrat "False Beliefs" and Republican "False Beliefs" (see prizes tab for award amounts)

- The deadline for submitting questions is October 15th, 2019 at 11:59 p.m.

## Judging Criteria

To determine winners for each category of question, we will do the following:

* All questions will be subject to an initial review designed to screen out low-quality questions. (Given that we do not know how many questions we will receive, we cannot commit in advance to testing all submitted questions. It is our intention, however, to test all questions that could plausibly meet our criteria.

* We will take all of the questions that pass our initial review as contest entries and pose them to a large sample of real Republican and Democrat respondents.

* To qualify as a "False Belief", participants from a specific political party (e.g. Republicans) should, on average, get the answer wrong more often than a participant from the other political party (e.g. Democrat).  Furthermore, both participants should have a hunch that their answer is right.  The actual cut-off for what constitutes a reasonable hunch will be up to the judges' discretion.  

* All questions should be submitted with exactly four answer choices.  

For Republican "False Belief" questions (questions Republicans are likely to get wrong), we compute the following:

$$\mid \text{Rate for Dems - Rate for Reps} \mid $$

For Democratic "False Belief" questions, we compute the following:

$$\mid \text{Rate for Reps - Rate for Dems} \mid $$

We award prizes to the submissions that maximize the above quantities, giving at least two prizes in each category.  However, we will reward any question that is submitted that we consider to be "high quality."

* We reserve the right to use our discretion to reward questions that are particularly unique or clever, over and above the strict quantitative criteria described above.  

* To give some context as to what constitutes a "high-quality" submission, the best questions we have designed so far are able to generate an accuracy differential of 50% between Republicans and Democrats on a large sample of online participants.  That is, on average a Republican or a Democrat is 50% more likely to get these questions correct than their political counterpart.  It is likely that questions that achieve similar results will be rewarded at least $100.00 (depending on the total number of high-quality submissions).    
