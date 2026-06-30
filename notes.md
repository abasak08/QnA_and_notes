# Some questions form last collaboration meeting:

* NOvAsoft take $\Delta m^2_{32}$ as input?
  * What are the pros and cons of this in context of our analysis?
* What are the **Asimov samples** ?
* What is meant by **POT in spill**?
* What is meant by **spill in data**?
* when we plot $\nu_e$ appearance event spectra the events are normalized over POT equivalent events, what does this mean?
* What is the CAFAna's relation to Prod 5.1?
* What is meant by **Beam data base**?
* What is meant by **Signal injection to spectra/sample** in the calculation?


# Data fit in NOvA:

- There are two general techniques to fit MC samples. Those are 
    1. AsimoV Fake data sets
    2. Pseudo experiments
    3. Antoher option we can use it to use open box data set rather. ***BB** suggested this!*


## Asimov Fake data set:

- The thing is if we choose one AsimoV point to generate a predictions then how do we calculate $\chi^2$ with it.
	* Suggestion is that we extract one best fit point from best fit file as we do in the prdiction plot and use some other asimove point with it.
- What is nominal spectr? and can we call our generated spectra as **nominal spectra**?
- How can we write the code for systematic variation of Osc. Param to compare SNSI and 3Flavor case?
- When we are fitting the data which spectra should be taken into account?
- If I look into the code by **MARIO A.** and from that can we  extract some techniques for the analysis? 


# Normalization of event spectra:

* **Shivam** suggested to add cosmic events to the predictions. What can be done with this?

* Why different type of normalization technique is used for numu disappearance nue appearance spectra. most importantly in case of numu disappearance we use events/0.1 GeV whereas for  nue appearance we use events/POT equivalent, why so?
* **Shivam** is suggesting data POT should be normalize before using it.
  * How that can be done?
# Sensitivity:

* When we are starting to estimate sensitivity, should not we start from the $\nu_{\mu}$ disappearance rather than $\nu_e$ appearance? Because the  $\nu_{\mu}$ spectra is simpler than $\nu_e$( which is divided into three catagory).

* Have to look into how 3Flavor/Mario is doing the sensitivity estimation.

* Also, measuring the $\chi^2$ how BB sir suggesting i.e. using unblinded 3Flavor data\
 will also be helpful incase of $\nu_\mu$ sample. *Have to check!*
 
