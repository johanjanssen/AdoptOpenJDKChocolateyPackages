# Chocolatey packages 
This repo contains the source for the AdoptOpenJDK packages. These packages are deprecated as AdoptOpenJDK [moved](https://blog.adoptopenjdk.net/2021/03/transition-to-eclipse-an-update/) to the Eclipse foundation and the new Chocolatey packages are now available under the name Temurin.

The old JDK 8/11/latest and JRE 8/11/latest AdoptOpenJDK will now automatically install Temurin.

# Changing the packages
* Build all packages: buildpackages.ps1
* Test the package (as administrator): choco install [packageName] -dv -source "'.;https://community.chocolatey.org/api/v2/'"
* Push all packages pushpackages.ps1
