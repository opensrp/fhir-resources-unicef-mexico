# FHIR Resources for the UNICEF Mexico App

To load into the OpenSRP FHIR Core app on demand, for debug and development, you can create a symbolic link using:

```sh
git clone git@github.com:opensrp/hisp-wdf-fhir-resources.git
# assuming you have checked out fhircore in the same directory
mkdir -p fhircore/android/quest/src/unicef_mexico/assets/configs
ln -s `pwd`/hisp-wdf-fhir-resources/app fhircore/android/quest/src/unicef_mexico/assets/configs
```
