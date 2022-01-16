Comments on the mass sheet degeneracy in cosmography analyses
==============================

This repository hosts the programs needed to obtain some of the results showed in the paper
**Comments on the mass sheet degeneracy in cosmography analyses** by Luca Teodori, Kfir Blum, Emanuele Castorina, Marko Simonovic and Yotam Soreq.

Abstract
--------
We make a number of comments regarding modeling degeneracies in strong lensing measurements of the Hubble parameter H0. The first point concerns the impact of weak lensing associated with different segments of the line of sight. We show that external convergence terms associated with the lens-source
and observer-lens segments need to be included in cosmographic modeling, in addition to the usual
observer-source term, to avoid systematic bias in the inferred value of H0. Specifically, we show how an
incomplete account of some line of sight terms biases stellar kinematics as well as ray tracing simulation
methods to alleviate the mass sheet degeneracy. The second point concerns the use of imaging data for
multiple strongly-lensed sources in a given system. We show that the mass sheet degeneracy is not fully
resolved by the availability of multiple sources: some degeneracy remains because of differential external
convergence between the different sources. Similarly, differential external convergence also complicates
the use of multiple sources in addressing the approximate mass sheet degeneracy associated with a local ("internal")
core component in lens galaxies. This internal-external degeneracy is amplified by the non-
monotonicity of the angular diameter distance as a function of redshift. For a rough assessment of the
weak lensing effects, we provide estimates of external convergence using the nonlinear matter power
spectrum, paying attention to non-equal time correlators.

Notebooks
---------
For understanding on how we obtained our results,
we prepared dedicated jupyter notebooks:

* ``kappa_linear.ipynb``: Computing \kappa^s RMS just in linear theory
* ``delta_kappa_nonlinear.ipynb``: Showing the plots regarding the RMS of external convergences and related

Authors
-------
- Luca Teodori; luca.teodori@weizmann.ac.il
- Kfir Blum; kfir.blum@weizmann.ac.il
- Emanuele Castorina; emanuele.castorina@unimi.it
- Marko Simonovic; marko.simonovic@cern.ch
- Yotam Soreq; soreqy@physics.technion.ac.il

Citations
---------
To cite our work::

  @article{Teodori:2022ltt,
      author = "Teodori, Luca and Blum, Kfir and Castorina, Emanuele and Simonovi\'c, Marko and Soreq, Yotam",
      title = "{Comments on the mass sheet degeneracy in cosmography analyses}",
      eprint = "2201.05111",
      archivePrefix = "arXiv",
      primaryClass = "astro-ph.CO",
      month = "1",
      year = "2022"
  }

