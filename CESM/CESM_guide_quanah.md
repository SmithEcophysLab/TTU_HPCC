<!--
this file can be used to load and run
CESM on TTU quanah cluster
-->

# Background information

The Community Earth System Model (ESM) is a model for simulating coupled and
uncoupled Earth system components, such as land, atmosphere, and ocean.

Basic documentation about the CESM can be found at
[http://www.cesm.ucar.edu/models/cesm2/](http://www.cesm.ucar.edu/models/cesm2/).

This documentation will cover cloning and running the land component of the CESM,
that is the Community Land Model (CLM). Documentation on the CLM can be found at 
[http://www.cesm.ucar.edu/models/cesm2/land/](http://www.cesm.ucar.edu/models/cesm2/land/).
Documentation includes access information and 
the [CLM5.0 User Guide](https://escomp.github.io/ctsm-docs/doc/build/html/users_guide/index.html).

Steps outlined below were developed by [Nick Smith](mailto:nick.smith@ttu.edu) and 
[Dewang Shah](mailto:dewang.shah@ttu.edu). Please email one of them with questions
or create an issue on this GitHub repository.

# Branching CLM onto Quanah

1. Sign in to quanah:

	* ssh -x <em>your_ttu_user_id</em>@quanah.hpcc.ttu.edu


2. Run the following branch commands in your desired directory (copy/paste from here)
	* git clone -b release-clm5.0 https://github.com/ESCOMP/ctsm.git clm5.0
	* cd clm5.0
	* ./manage_externals/checkout_externals



