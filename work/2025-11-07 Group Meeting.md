# 1 Results!

Question: how to model the **entire ODMR** spectrum, as they do in the other works:
- Udvarhelyi, P., Clua-Provost, T., Durand, A., Li, J., Edgar, J. H., Gil, B., Cassabois, G., Jacques, V., & Gali, A. (2023). A planar defect spin sensor in a two-dimensional material susceptible to strain and electric fields. Npj Computational Materials, 9(1), 150. https://doi.org/10.1038/s41524-023-01111-7
  ![[Pasted image 20251107092749.png|center|300]]
- Gong, R., He, G., Gao, X., Ju, P., Liu, Z., Ye, B., Henriksen, E. A., Li, T., & Zu, C. (2023). Coherent dynamics of strongly interacting electronic spin defects in hexagonal boron nitride. Nature Communications, 14(1), 3299. https://doi.org/10.1038/s41467-023-39115-y
  ![[Pasted image 20251107093207.png|center]]
- Durand, A., Clua-Provost, T., Fabre, F., Kumar, P., Li, J., Edgar, J. H., Udvarhelyi, P., Gali, A., Marie, X., Robert, C., Gérard, J. M., Gil, B., Cassabois, G., & Jacques, V. (2023). Optically Active Spin Defects in Few-Layer Thick Hexagonal Boron Nitride. Physical Review Letters, 131(11), 116902. https://doi.org/10.1103/PhysRevLett.131.116902  
  ![[Pasted image 20251107093249.png|center]]

> No one gives complete information on how to do that! (Suspicious eh?!)

Then I checked: Mittiga, T., Hsieh, S., Zu, C., Kobrin, B., Machado, F., Bhattacharyya, P., Rui, N. Z., Jarmola, A., Choi, S., Budker, D., & Yao, N. Y. (2018). Imaging the Local Charge Environment of Nitrogen-Vacancy Centers in Diamond. Physical Review Letters, 121(24), 1–6. https://doi.org/10.1103/PhysRevLett.121.246402

Discovered that people in the previous papers invented NOTHING, because everything had been already developed in the NV centers community, and the paper above is describing in an excellent way the steps to use the microscopical charge model to model the entire ODMR spectrum.

Here an extract:
>  The spectrum exhibits ==heavy tails which cannot be reproduced by either a double Lorentzian or a Gaussian== (orange fit) profile. The blue theory curve is obtained via our microscopic charge model.
>![[Pasted image 20251107093919.png|center|400]]

An here again from the SI:
> we simulate the high-field spectra by sampling over the positions $\{\vec{r}_i\}$ and spins $\{p_i\}$ of the magnetic impurities. For each configuration, we calculate the NV’s resonance frequencies using the full Hamiltonian of the system, Eq. (1) of the main text. Repeating this procedure for ∼ 5000 realizations, ==we obtain a histogram of resonance energies, which corresponds to an ensemble-averaged spectrum==. We generate such spectra for a range of $ρ_s$ and fit each to the high-field measurement. The free parameters for these fits are the center frequency, vertical offset, and overall amplitude. We characterize $ρ_s$ by calculating the least-square residuals between our simulated spectra and the experimental data (Figs. 5 and 6, left column). In particular, we identify $ρ_s$ that minimizes the residual as the best-fit parameter and estimate the error on this value as the range of ρs whose residuals lie within 10% of the minimum.

At this point I reminded myself that the physical process of measuring ODMR on an ensemble of spins (as in the case of $\mathrm{V}_\mathrm{B}^-$!), which implies sampling a population where the resonance of each individual emitter changes in population and time, so that the ODMR is a statistical sampling of such population (there comes the broadening of the resonances!).

And then I realized that (thanks Christoph!) checking the statistical distribution of the eigenvalues (for a fixed charge density $\rho_c$) is exactly what we did in the paper!

>[!My paper 🥹|right|300]
>![[Pasted image 20251107095010.png|center|400]]
> My paper 🥹

Two things:
- in the fitting of the ODMR resonances we adopted two exponentially modified Gaussians functions (thanks Christoph!), because these are the ones which resemble the closest to the actual ODMR linewidth!
- in the microscopical charge model simulation, when checking the statistical distribution of the eigenvalues for a fixed charge density, we apply a gaussian filter to the histograms to smoothen them and then find the actual eigenvalues as the maxima of such distributions (thanks Christoph!).

With all these things in the pocket, it becomes all of a sudden clear that the histograms are actually the ODMR spectrum!

Therefore, I took as an example the histograms for a charge density the closest as possible to the one we estimated for the highest irradiation fluence, tweaked a bit the offset and amplitudes and this is the result...

> [!My results 🥹|right|300]
> ![[Pasted image 20251107100926.png|center|450]]
> The linewidth match almost perfectly...

Man I wish I realized this way earlier...

# 2 Defense!
Battulga: his first PhD defense
Tobias Vogl: after 16th of Feb
Vladimir Dyakonov: before 28th of Feb
DPG: from 9th of March
