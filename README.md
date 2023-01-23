# Computational-Statistics
Computation Statistics Project for the course (Applied Mathematics and Computer Science)

### Description
Many of the wells used for drinking water in Bangladesh and other South Asian countries are contaminated with natural arsenic, affecting an estimated 100 million people. Arsenic is a cumulative poison, and exposure increases the risk of cancer and other diseases, with risks estimated to be proportional to exposure.

Any locality can include wells with a range of arsenic levels. The bad news is that even if your neighbor’s well is safe, it does not mean that yours is safe. However, the corresponding good news is that, if your well has a high arsenic level, you can probably find a safe well nearby to get your water from – if you are willing to walk the distance and your neighbor is willing to share. (The amount of water needed for drinking is low enough that adding users to a well would not exhaust its capacity, and the surface water in this area is subject to contamination by microbes, hence the desire to use water from deep wells.)

A research team from the United States and Bangladesh measured all the wells in a small area of Bangladesh and labeled them with their arsenic level as well as a characterization as “safe” (below 0.5 in units of hundreds of micrograms per liter, the Bangladesh standard for arsenic in drinking water) or “unsafe” (above 0.5). People with unsafe wells were encouraged to switch to nearby private or community wells or to new wells of their own construction. A few years later, the researchers returned to find out who had switched wells.

switch: whether the household switched to a new well

arsenic: the arsenic level of respondent’s well (hundreds of micrograms per liter)

dist: the distance (in meters) to the closest known safe well

assoc: whether any members of the household are active in community organizations

educ: the education level of the head of household (years of education)


You shall perform a logistic regression Bayesian analysis to understand the factors predictive of well switching among the users of unsafe wells.
The outcome variable is:

 

            1, if household i switched to a new well
Y_i=            
            0, if household i continued using its own well


1. Start with a single predictor (dist) and consider the possibility to rescale the distance to 100-meter units.

2. Fit a logistic regression model including all predictors.
