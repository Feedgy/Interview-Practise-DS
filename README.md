# Interview-Practice-DS

Welcome to this data science interview repository.

This repository is meant to be used with GitHub Codespaces. To start using this repository:

1. Connect to your GitHub account.
2. Click **Use this template**, then click **Open in a codespace**.
3. You should accept to download the Python extension for Visual Studio Code.
4. When choosing the kernel, you should choose `feedgy-ds-repo-template-NK18vZRh-py3.10`.

In this repository, you will find a dataset of 15-minute time series data from 3 solar plants. The columns of the dataset are as follows:

- `mpppt_id`: ID of the mpppt (a group of panels in the power plant)
- `date`: Date
- `power`: Power produced by the mpppt
- `voltage`: Voltage of the mpppt
- `current`: Current of the mpppt
- `poa_global`: Light received by the panels
- `temperature_ambiante`: Ambient temperature
- `pressure`: Ground pressure
- `wind_speed`: Ground wind speed
- `rainfall`: Amount of rain
- `snowfall`: Amount of snow
- `snow_depth`: Amount of snow on the ground
- `global_horizontal_irradiance`: Light received from above by a surface horizontal to the ground
- `clear_sky_global_horizontal_irradiance`: Light received from above by a surface horizontal to the ground if no clouds
- `farm`: Solar farm name
- `mppt_config`: Concatenation of tilt and azimuth of an mppt. For the same farm, if two mppts are in the same mppt_config, they should produce the same power

During the interview, you will be asked to access data, understand it, clean it, and build a regression model.
