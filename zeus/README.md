This directory contains reports from a sampling of Zeus malware.

Each subdirectory (`anubis`, `threatexpert`) contains MAEC reports derived from the original [Anubis](https://anubis.iseclab.org/) and [ThreatExpert](http://threatexpert.com/) reports. The original reports are in the `originals` directory for each category. Conversions were performed by:

* Anubis to MAEC: https://github.com/MAECProject/anubis-to-maec
* ThreatExpert to MAEC: https://github.com/MAECProject/threatexpert-to-maec

Samples are named by the MD5 hash of the original malware, so reports named with the same hash were derived from the same malware sample. For example:

* `anubis/originals/0bab6936c4ac24257194472e1362d31e.xml` is an Anubis report
* `anubis/0bab6936c4ac24257194472e1362d31e_maec.xml` is the MAEC report devired from that Anubis report
* `threatexpert/originals/0bab6936c4ac24257194472e1362d31e_threatexpert.xml` is a ThreatExpert report
* `anubis/0bab6936c4ac24257194472e1362d31e_threatexpert_maec.xml` is the MAEC report devired from that ThreatExpert report
* Both the ThreatExpert and Anubis reports were created from some Zeus malware sample with the MD5 hash `0bab6936c4ac24257194472e1362d31e`