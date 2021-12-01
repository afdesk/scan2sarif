# scan2sarif
A Trivy plugin that scans and outputs the results to a sarif file.
## Install
```sh
$ trivy plugin install github.com/afdesk/scan2sarif

$ trivy scan2sarif -h

Usage: trivy scan2sarif [-h,--help] command target filename
 A Trivy plugin that scans and outputs the results to a sarif file.
Options:
  -h, --help    Show usage.
Examples:
  # Scan `alpine:latest` image
  trivy scan2sarif image alpine:latest result.sarif

  # Scan local folder
  trivy scan2sarif fs . result.sarif
```