# How to use EERIE's facilities at JASMIN

[JASMIN](https://jasmin.ac.uk/) is the UK's data analysis facility for environmental science.  JASMIN is operated by [UK Research and Innovation](https://www.ukri.org/) who are EERIE partners.

EERIE users have access to the following facilities at JASMIN:

* 250 TB of [group workspace](https://help.jasmin.ac.uk/article/199-introduction-to-group-workspaces)
* 50 TB of [object store](https://help.jasmin.ac.uk/article/4847-using-the-jasmin-object-store)
* [interactive analysis servers](https://help.jasmin.ac.uk/article/121-sci-servers)
* [LOTUS batch cluster](https://help.jasmin.ac.uk/category/4889-slurm) - 19,000 core batch computing system
* [Jupyter Notebook service](https://help.jasmin.ac.uk/article/4851-jasmin-notebook-service)
* [transfer servers](https://help.jasmin.ac.uk/category/217-data-transfer)
* [scientific software](https://help.jasmin.ac.uk/category/270-software-on-jasmin)
* [CEDA Archive](https://help.jasmin.ac.uk/article/3838-ceda-archive)
* [Elastic Tape system](https://help.jasmin.ac.uk/article/3842-secondary-copy-using-elastic-tape)
* [Met Office MASS tape system client](https://help.jasmin.ac.uk/category/227-mass)

There is extensive help documentation available for all JASMIN systems at https://help.jasmin.ac.uk/

### Getting a JASMIN account

Please follow the instructions at http://help.jasmin.ac.uk/article/189-get-started-with-jasmin to get access to the JASMIN facilities:

* At step 4, applying for the jasmin-login role, you should include the email addresses of Malcolm Roberts and Jon Seddon who will provide you with a reference to support your application.
* At step 5 you should apply for access to the ["eerie" Group Workspace](https://accounts.jasmin.ac.uk/services/group_workspaces/eerie/) and ["eerie-o" object store](https://accounts.jasmin.ac.uk/services/object_store/eerie-o/). 
* To access data that has already been published to the ESGF, for example the EERIE simulations or CMIP6-HighResMIP data, you will also need to [register for a CEDA account](​http://www.ceda.ac.uk/) and link this to your [JASMIN account](​https://accounts.jasmin.ac.uk/account/profile/).

### Accessing your JASMIN account

Please follow the instructions at https://help.jasmin.ac.uk/article/187-login to login to your JASMIN account using SSH.

### Using JASMIN storage

The JASMIN storage is summarised in the [JASMIN help system](https://help.jasmin.ac.uk/article/176-storage). EERIE users will have access to the following forms of storage:

* 100 GB of [home directory](https://help.jasmin.ac.uk/article/176-storage#home) at `/home/users/<username>`, which is the only storage that is backed up.The home directory has snapshots enabled to allow for the quick recovery of deleted files. Important results should be stored in your home directory.

* [temporary scratch storage ](https://help.jasmin.ac.uk/article/176-storage#disktemp) for the storage of large files that are being actively analysed. Data on the scratch storage that is older than 28 is automatically deleted.

* there is a single 250 TB allocation of group workspace (GWS) for the EERIE project at `/gws/nopw/j04/eerie`. This GWS will be used to hold the model output data that is required for analysis. Data will be written to it using the Data Management Tool, a web based catalogue of EERIE model data. If this GWS becomes full then all EERIE users will be unable to work and so we must be very careful what data is written to the GWS.

* there is 100 GB of fast solid state disk (SSD) storage that is available at `/gws/smf/j04/eerie`. This SSD is ideal for storing software on. Please contact Jon Seddon if you would like some software to be installed here.

* the CEDA archive is available at `/badc`. The archive contains a range of observation and reanalysis datasets along with CMIP6 data that is available at CEDA's ESGF node. EERIE data that has been published to, or repliacted to, CEDA's ESGF node will be available at `/badc/cmip6`.

* EERIE has 50 TB of [object storage](https://help.jasmin.ac.uk/article/4847-using-the-jasmin-object-store). The object store is only available internally at JASMIN and is not available externally of JASMIN.

### Extra services

The [Jupyter Notebook service](https://help.jasmin.ac.uk/article/4851-jasmin-notebook-service) provides access to a Python environment through a web browser. The notebook service can read data from the EERIE GWS and the CEDA archive. The notebook service may be useful during hackathons.

Files can be made available for pubic download from the EERIE GWS via password protected [HTTP data sharing](https://help.jasmin.ac.uk/article/202-share-gws-data-via-http). Please contact Jon Seddon for more details on this facility.

### Data Transfer

JASMIN has fast network access to the UK's Janet network and from there to the GÉANT network. JASMIN supports many different methods for [fast and efficient data transfer](https://help.jasmin.ac.uk/category/217-data-transfer).


### Getting help

Initially, please check the existing documentation at https://help.jasmin.ac.uk/

If the documentation does not help then please either ask for informal help from another member of the EERIE project (Jon Seddon has much previous experience of using JASMIN) or contact JASMIN support by clicking on the big blue question mark (?) button at the bottom of https://help.jasmin.ac.uk/.
