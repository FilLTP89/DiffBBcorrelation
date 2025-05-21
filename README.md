# Interfrequency-conditioned diffusion model for earthquake signal super-resolution

The project is forked from [STEAD_diffusion project](https://github.com/HugoGabrielidis16/STEAD_Diffusion.git) which develops a [Denoising Diffusion Probabilistic Model [1]](https://proceedings.neurips.cc/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html) to generate broadband (0-30 Hz) earthquake accelerograms based on low-frequency signals obtained by numerical simulations of earthquake scenarios. 

This project conditions the generation of broadband signals by penalizing the inter-frequency correlation with an empirical model obtained from [[2]](https://doi.org/10.1785/0120170081).


## References

[1] Ho, J.; Jain, A.; Abbeel, P. Denoising Diffusion Probabilistic Models. arXiv December 16, 2020. [https://doi.org/10.48550/arXiv.2006.11239](https://doi.org/10.48550/arXiv.2006.11239).

[2] Stafford, P. J. Interfrequency Correlations among Fourier Spectral Ordinates and Implications for Stochastic Ground‐Motion Simulation. Bulletin of the Seismological Society of America 2017, 107 (6), 2774-2791. [https://doi.org/10.1785/0120170081](https://doi.org/10.1785/0120170081).

