# simulated_stimulation_on_VERTEX
This is a tutorial on how to use a computational model of cortical tissue with explicit neuron morphologies and distinct layers that can be used to simulate the impact of electric field stimulation on VERTEX. 
The model exists within the VERTEX toolbox [1] in MATLAB that is freely available for download online. 
It is important to have a computational model that can simulate transcranial direct current stimulation (tDCS) as there is a lot of variability in real world results due to multiple factors as well as the fact that sample sizes are usually too small to give statistically significant results. However, there is some evidence to show that tDCS can be used to treat major depression [2, 3], chronic pain [4] and also assist in stroke recovery [5]. Being able to run tests in silico using programs like VERTEX can allow us to better understand the effects of the confounding variables that lead to the variability in the results of the previous studies [6], allowing us to learn more from the results of these studies and get closer to potential clinical application of tDCS. 

 This model was designed using data from a cat visual cortex, which is shown to be similar to that of a ferret [7] and compared to data obtained by Fröhlich et al [8] of in vitro studies done to demonstrate the effect that electric current stimulation has on a ferret visual cortex. 
 
References：
[1] Tomsett RJ, Ainsworth M, Thiele A, Sanayei M, Chen X, Gieselmann MA, Whittington MA, Cunningham MO, Kaiser M. Virtual Electrode Recording Tool for EXtracellular potentials (VERTEX): comparing multi-electrode recordings from simulated and biological mammalian cortical tissue. Brain Structure and Function. 2015 Jul 1;220(4):2333-53.

[2] Ferrucci R, Bortolomasi M, Brunoni AR, Vergares M, Tadini L, Giacopuzzi M, Priori A. Comparative benefits of transcranial direct current stimulation (tDCS) treatment in patients with mild/moderate vs. severe depression. Clin Neuropsychiatry. 2009 Dec;6(6):246-51.

[3] Shiozawa P, Fregni F, Benseñor IM, Lotufo PA, Berlim MT, Daskalakis JZ, Cordeiro Q, Brunoni AR. Transcranial direct current stimulation for major depression: an updated systematic review and meta-analysis. International Journal of Neuropsychopharmacology. 2014 Sep 1;17(9):1443-52.

[4] Vaseghi B, Zoghi M, Jaberzadeh S. Does anodal transcranial direct current stimulation modulate sensory perception and pain? A meta-analysis study. Clinical Neurophysiology. 2014 Sep 1;125(9):1847-58.
