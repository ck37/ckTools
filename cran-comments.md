## Resubmission
This is a resubmission. In this version I have:

* Converted the DESCRIPTION title to title case.

* Simplified the LICENSE file to reflect the copyright holder and year directly.
  
## Test environments

* Local
    * macOS 10.12.5: R release
    * Windows 10: R release
* Travis CI
    * Ubuntu precise (12.04.5): R devel, release, oldrel
    * macOS 10.11.6: R devel, release, oldrel
* AppVeyor CI
    * Windows Server 2012 R2: R devel, release, oldrel
* win-builder: R devel and release

## R CMD check results

There were no ERRORs or WARNINGs.

NOTEs (1):

1. Package suggested but not available for checking: 'doMC'

-- Windows-only; occurs because doMC is not available for Windows.