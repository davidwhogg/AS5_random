# AS5_random
Short ideas for the After Sloan 5 Blue Skies process

## Instructions
Fork this repository, add a bullet point to the list of ideas below, and *add your name* to the author list, and generate a pull request.
If you add an idea, you must add your name, and *vice versa*.

## Style notes
Keep it brief, but specific. Boldface a phrase or sentence that serves as the "title" for your idea.

## Authors
- **Joel Brownstein** (University of Utah)
- **Andy Casey** (Monash University)
- **Carrie Filion** (Flatiron Institute)
- **David W. Hogg** (Flatiron Institute)
- **Ilija Medan** (Vanderbilt University)
- **Moire Prescott** (New Mexico State University)
- **Zach Way** (Georgia State University)
- **Andrew Saydjari** (Princeton)
- *[ADD YOUR NAME HERE]*

## Ideas

- Create a **live auction for spectra**. The interface is: Choose your instrument, your observing conditions, exposure time, time constraints, and so on, and a *maximum amount* you are willing to pay for one spectrum (the bid). At every interval (15 minutes, say), we find the telescope pointing and field configurations that maximize revenue. We charge a discounted rate to the bids, which is discounted because we bill a total amount to all the winning bids that delivers to us a total revenue that is halfway between the best field's total of bids and the second-best field's total of bids (I believe there is research about this structure). *&mdash; Hogg*

- **Follow the *LSST* footprint**, by some sparse sampling. Operate a time-domain survey that is always pointing at a field that was observed by *LSST* within the last *N* minutes. Permits all-sky survey targets and also *LSST*-triggered target-of-opportunity targets in the same program. Could be combined with the live auction idea above. *&mdash; Hogg*

- **Fill out the binary system parameter space**. There will be many binary systems where Gaia DR4 will be unable to solve the complete orbit. Some will be too faint, particularly for stars in the dusty disk. Other systems might be multi-modal: two or more likely regions of binary parameter space. In these situations, a (possibly) well-timed RV precise (~100 m/s) RV measurement from APOGEE will resolve the orbit. *&mdash; Casey*

- **A noisier expansion of Galactic Genesis**. APOGEE is the only current or planned spectrograph that can survey the Galactic plane at scale. GALAH, 4MOST, and WEAVE either avoid the plane entirely, or produce shallow samples. A low S/N spectrum (~20) for millions more Galactic Genesis targets would be sufficient to measure a radial velocity, to measure interstellar dust along the line of sight. *&mdash; Casey*

- **Narrow-band photometry yields abundance indicators for stellar litmus tests.** There are stellar astrophysics questions where competing physical explanations might be differentiated by the measurement of a single absorption line. For example, is this star lithium-rich? Is there also high berylium, or high chromospheric activity in the helium lines? Is the lead abundance in this star very high (indicating one nucleosynthetic process), or very low (indicating the other)? With good models of stellar spectra, an extremely narrow-band photometric filter can be sufficient to perform these litmus tests for large numbers of stars, where high-resolution spectroscopy would otherwise be too expensive. *&mdash; Casey*

- **Bridging the gap between low- and high-resolution spectroscopy for low-luminosity stars.** Low-luminosity stars are ubiquitous across the sky and are observed in large numbers in surveys like Gaia. Notably in Gaia DR3, a large number of these stars have low-resolution Gaia XP spectra. In SDSS however, 99% of APOGEE spectra are of targets with M<sub>G</sub> < 10.5 mag, meaning the vast majority of these low-luminosity objects haven't been systematically targeted in higher resolution spectroscopic surveys. We propose to make these targets a high priority in a future iteration of SDSS. This would require the creation of a new APOGEE observing mode with extended exposure times that achieve sufficient signal-to-noise for these fainter objects. Specifically, APOGEE fibers could be parked on low-luminosity (and other faint) objects for long exposure times, while BOSS fibers are reconfigured at the typical 15 minute exposure time cadence. This would be the first time a large number of these low-luminosity objects are systematically observed with high resolution spectroscopy, which would deepen our understanding of low-mass stars and expand our overlap with other surveys. *&mdash; Medan and Way*

- **LVM in the North for M31 and Friends** LVM is doing incredible work in the Southern hemisphere; why not add a second LVM and extend the footprint to include the Northern hemisphere, too? In addition to the Milky Way science that LVM can do in the North, it would also be able to provide exquisite observations of M31 and M33. LVM North data for the disks and haloes of M31 and M33 (and the bridge between them!) would allow us to create unique maps of the kinematics and chemistry of our nearest spiral galaxy neighbors, ultimately better contextualizing our own Galaxy. *&mdash; Filion*

- **A MaNGA-style approach to studying AGN with extended emission line regions** tracing outflows or ionization echoes. This would presumably have to be restricted to lower z cases (e.g., the Voorwerpje) due to the typical angular sizes and surface brightnesses, but it would allow for detailed studies of AGN outflows and would also probe extremely long time-baselines in the case of ionization echoes (i.e., 10,000-50,000 years). One would need to think about the available sample sizes, whether this would be feasible in terms of sensitivities, and what we could learn beyond what was done using AGN hosts in the original MaNGA sample. *&mdash; Moire*

- **Mapping Spiral Arms in Dust** APOGEE is now achieving velocity resolution with DIBs comparable to CO gas studies of Galactic structure. This capability is unrivaled and provides a unique opportunity to SEE the spiral arm structure of our own Milky Way, because DIBs have the advantage of partial distance information that admits a 4D reconstruction of Galactic structure. Observations in the Galactic Plane, targeted off of DECaPS2, VVV, and Roman GPS will provide a denser spectroscopic sampling of lines-of-sight necessary to constrain these reconstructions. This project can be carried out synergistically with other stellar proposals in the plane, but its optimization benefits from volume, uniformity, + dustiness of the targets. Additional fibers, increasing the multiplexing of APOGEE, would be a benefit, but this can be carried out with current software and hardware.  *&mdash; Saydjari*
  
- **A comprehensive scan of the sky for signatures of strong gravitational lenses.**  In the AS5 era, the availability of advanced instruments for followup confirmation make the SDSS BOSS spectograph, at redshifts between 0.3 -- 1.0, and MaNGA IFU instrument, at resdhifts less than 0.3, ideal tools to scan the sky for multiple redshifts in the same line-of-sight.  This type of spectrographic detection has provided the most successful method of detecting strong galaxy-galaxy gravitational lenses (e.g. SLACS and SWELLS for SDSS-II, BELLS for SDSS-III, and SILO for SDSS-IV with CASIGLO providing machine learning deep-learning neural network).  The extension of the search for strong gravitational lenses into the FPS era for AS5 would allow multiple visits, or long exposure times, in order to generate sufficient S/N to better resolve the emission-lines and velocity dispersion measurements used by the detection algorithms that have been steadily improved since the original Burles and Bolton code.  In addition the extension to include QSO lenses would enable the transient detections related to the (second-order) time-delay effect, which has not been spectroscopically observed.  A comprehensive scan of the sky for gravitational lenses including followup imaging to allow lens models is extremely valuable, because gravitational lenses provide a direct probe into the effect of dark matter at the galaxy's Einstein radius, in principle allowing the mathematical dissection into luminous and dark components.  The opportunity to create a collaboration of many non-SDSS folks from the gravitational lensing community could also provide individual "slots" for the AS5 budget, if such a proposal were to be made attractive to faculty and postdocs that strongly depend on these rare (approximately one in a thousand) astronomical targets, with significant research impact following 2 years of AS5 observing time, or 4 more years to include transient phenomena, such as the time delay effect. *&mdash; Brownstein*
