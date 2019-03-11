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

## Submission and Judging Criteria

Prizes will be awarded to the top two submissions for each of the following categories: Democrat "Knowledge Desert", Republican "Knowledge Desert", Democrat "False Belief", Republican "False Belief" (see prizes tab for award amounts)

To determine winners for each category of question, we will do the following:

- We will take all of the questions submitted as contest entries and ask them to real Republican and Democrat respondents sampled via Amazon's Mechanical Turk survey pool.  This will be a large sample to ensure adequate statistical power to detect effects. We will only examine the results from respondents who identify explicitly as either Republican or Democrat (we exclude moderates, independents, and third parties).  

- Quantitative questions should be submitted without answer choices. We expect that the majority of quantitative questions will involve the "False Belief" category. We will determine the best quantitative question (e.g. what percent of climate change scientists believe in global warming?) by computing computing two distances: (1)  the distance from the average Republican answer to the correct answer; (2) the distance from the average Democratic answer to the correct answer.  We then take the difference between these two distances.  The top two questions that maximize the appropriate difference for quantitative questions will receive a reward.  

For Republican "False Belief" questions, we perform the following:

$$\mid{\text{Average Democrat Answer} - \text{Correct Answer}} - \mid{\text{Average Republican Answer} - \text{Correct Answer}}$$




-
