# MODIS Re-LWP kernels
These files are the shortwave (SW) cloud radiative kernels for liquid-topped clouds that can be used with joint histograms partitioned by cloud-droplet effective radius (Re) and liquid water path (LWP) from the Moderate Resolution Imaging Spectroradiometer (MODIS) satellite instrument. Information about the kernels can be found in Wall et al. (2023), and information about the MODIS data can be found in Pincus et al. (2023). Two kernels are included:
(1) SW_kernel_liquid_lat_alb.nc: kernel with dimensions of Re, LWP, latitude, surface albedo, and calendar month. This kernel can be transformed from latitude-surface-albedo space to latitude-longitude space with linear interpolation.
(2) SW_kernel_liquid_lat_lon.nc: kernel with dimensions of Re, LWP, latitude, longitude, and calendar month. Surface albedo is taken from the Clouds and the Earth's Radiant Energy System (CERES) Energy Balanced and Filled (EBAF) ed. 4.1 satellite dataset.

Please cite Wall et al. (2023) when using these kernels in publications.

References:
Wall, C. J., Storelvmo, T., and Possner, A.: Global Observations of Aerosol Indirect Effects from Marine Liquid Clouds, EGUsphere (preprint), https://doi.org/10.5194/egusphere-2023-1436, 2023.
Pincus, R., Hubanks, P. A., Platnick, S., Meyer, K., Holz, R. E., Botambekov, D., and Wall, C. J.: Updated observations of clouds by MODIS for global model assessment, Earth Syst. Sci. Data, 15, 2483–2497, https://doi.org/10.5194/essd-15-2483-2023, 2023.
