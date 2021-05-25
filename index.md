---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<img alt="Accelerating Autonomy Workshop Logo" style="float: right; margin: 1em" src="{{site.logos}}/acceleratingautonomylogo.png">

The Accelerating the Use of Autonomy on Robotic Space Missions Workshop will focus on the following questions:

- What are the impediments to making more use of autonomy on robotic space missions?

- Which of those impediments apply to which kinds of space missions?

- In order to overcome those impediments,

	- What has been done in the past that has proven successful?

	- What approaches show promise, and what needs to be done to prove their worth?

	- What further ideas can be proposed?

Those interested in participating are encouraged to suggest answers to any of the above questions and email them in advance to Martin.S.Feather@jpl.nasa.gov.

Answers are also welcomed from those not planning to participate in the workshop.

We provide a detailed list of potential impediments and ways they might be addressed below to give participants an idea of where the discussion may lead. 

## Registration
  {% include registration.html%}

## Organisers


The Accelerating the Use of Autonomy on Robotic Space Missions Workshop is organised by:

  {% include chairs.html %}

## Potential Impediments
To start your thinking, here is a draft list of possible impediments. Are there more? To which kinds of missions do they apply? How can they be addressed?

1. Verification and Validation challenges:

  - a. Testing autonomy when it is to function in a large variety of situations

  - b. Assessing risk when autonomy in involved

  - c. Developing simulation environments of adequate fidelity

  - d. Reviewing / inspecting autonomy software

  - e. Unknown what coding standards are appropriate for autonomy software

2. Engineering gaps – lack of knowledge of:

  - a. The appropriate development process (waterfall, spiral, agile, …)

  - b. How to estimate the cost and schedule of developing an autonomy capability

  - c. What metrics to use to track the progress of autonomy development

  - d. How to decompose requirements to the point where they can be implemented

  - e. How to develop models for model-based autonomy

  - f. Autonomy isn’t compatible (or we don’t know how to make it compatible) with the traditional parts of spacecraft software

  - g. How hard it will be to debug autonomy software

3. Concerns

  - a. Operations teams will not know how to control autonomy

  - b. Operations teams will not know why autonomy behaved the way it did

  - c. Autonomy will achieve its goals in an unintended, unacceptable manner

  - d. Autonomy cannot be relied upon to take the correct actions

  - e. Some forms of autonomy have very varied and unpredictable runtime performance and/or resource usage

  - f. Autonomy developers will be lured away by terrestrial autonomy applications

4. Infusion barriers

  - a. Proposers of missions avoid considering autonomy because they don’t understand it

  - b. Reviewers of missions that use autonomy don’t understand it, so rate it as too risky

  - c. There is a lack of metrics to support the argument that autonomy is cost effective

  - d. Small missions cannot afford autonomy

  - e. Large missions will not accept the risk of using autonomy

  - f. Autonomy is made to be too mission-specific, meaning it will not be reusable

  - g. Autonomy fails to advance from research into practice

  - h. Autonomy is hard to describe, so does not attract the funding it needs to mature

  - i. Space missions are too infrequent to allow for the continuous advancement of autonomy, leading to talent drain

  - j. Autonomy is not developed in-house because of the expectation that it can be bought from elsewhere

  - k. Autonomy is never the first priority for research and development funding

And here are a few examples of how some of those impediments might be addressed – a goal of the workshop is provide improvements to, and many more of, these answers!

1 a) Guide testing towards scenarios where the system is getting closer to the edge of failure

1 a) Use formal methods to check the correctness of decision algorithms

2 b) Gather together from as many places as possible information on the effort it has taken to develop kinds of autonomy

3 a) Involve operations teams from the start of an autonomy development

3 c) Direct autonomy (e.g., an autonomous planner) to exclude common solutions to see what unusual solutions it discovers

4 f) Insist that autonomy developments be design and made to be reusable

4 i) Collaborate with other areas where autonomy can be infused and operated more frequently and more quickly, e.g., underwater vehicles, maritime automation 
