# MODIS Re-LWP cloud radiative kernel
This file contains a shortwave (SW) cloud radiative kernel for liquid-topped clouds that can be used with joint histograms from the Moderate Resolution Imaging Spectroradiometer (MODIS) satellite instrument. The kernel and histograms are partitioned by cloud-droplet effective radius (Re) and liquid water path (LWP). Information about the kernel can be found in Wall et al. (2023), and information about the MODIS observations can be found in Pincus et al. (2023). The kernel has dimensions of clear-sky surfae albedo, latitude, Re, LWP, and calendar month. This kernel can be transformed from surface-albedo-latitude space to longitude-latitude space with linear interpolation. Wall et al. (2023) transformed this kernel to longitude-latitude space using observations of clear-sky surface albedo from the Clouds and the Earth's Radiant Energy System (CERES) Energy Balanced and Filled ed. 4.1 satellite dataset. The file size for the transformed kernel is too large to post on GitHub, but it can be obtained by emailing Casey Wall at: casey (dot) wall (at) geo (dot) uio (dot) no

Please cite Wall et al. (2023) when using the kernel in publications.

References:

Wall, C. J., Storelvmo, T., and Possner, A.: Global Observations of Aerosol Indirect Effects from Marine Liquid Clouds, EGUsphere (preprint), https://doi.org/10.5194/egusphere-2023-1436, 2023.

Pincus, R., Hubanks, P. A., Platnick, S., Meyer, K., Holz, R. E., Botambekov, D., and Wall, C. J.: Updated observations of clouds by MODIS for global model assessment, Earth Syst. Sci. Data, 15, 2483–2497, https://doi.org/10.5194/essd-15-2483-2023, 2023.
