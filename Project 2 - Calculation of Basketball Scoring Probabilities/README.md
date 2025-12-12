# Project Instructions

There are four sections of this project to complete. Below are directions to assist with each portion of this project. Note "Made/Make" means "Was successful with."

## Overall Shooting Statistics

On this slide, calculate and report the:

- Overall probability of a make (result = TRUE)
- Overall probability of a miss (result = FALSE)
- Overall proportion of three-pointers (shot_type = 3)
- Overall proportion of two-pointers (shot_type = 2)

## Probabilities

Given the results you found on the previous slide:

- What is the probability of Steph making 3 of the next 4 shots?
- What is the probability that 4 of the next 5 shots are three-pointers?

Also, what assumptions are you making?

## Conditional Probabilities - Future

On this slide, use previously calculated probabilities to calculate and report the following conditional probabilities, which will require Bayes Theorem:

- If the next shot Steph shoots is a three-pointer...
    - What is the probability he makes it?
    - What is the probability it was taken while his team had the lead (lead = True)?
- If the next shot Steph shoots is a two-pointer...
    - What is the probability he makes it?
    - What is the probability it was taken while his team had the lead (lead = True)?

## Conditional Probabilities - Past

On this slide, calculate the following conditional probabilities. If Steph just made a shot...

- What is the probability that it was a three-pointer?
- What is the probability that it was a two-pointer?

Note: For these retrospective (past-conditional) probabilities, you could obtain the answers by direct counting, but please compute them using Bayes' theorem and show your steps.

Hint: First map each verbal description to notation. For example:

- "made three-pointer": P(Made,3)
- "three-pointer given a make": P(3∣Made)
- "make": P(Made)

Once labeled, it’s clear which terms to plug into Bayes' theorem.

