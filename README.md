# cf-buildpack_testeR
A buildpack for Cloud-Foundary environment such as IBM BlueMix or Heroku

## Buildpack information
A custom buildpack for downloading and installing R in a CF environment. 
The script `compile` contains code for downloading and installing R binaries and installing R packages that are listed in the `init.r` file, required for the app.

## R binaries
The R-binaries are stored at a storage service location such as Amazon-AWS or Dropbox or even GitHub large files.

### R version
Currently the R version is **R-3.2.0**, and build is **20150719-0018**. 
The version or build of R binaries can be chnaged by compiling an R binary for the required version and providing the accessible link to this file in the `compile` script as a hard-coded link.
