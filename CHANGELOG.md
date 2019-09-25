0.8.3 - September 24 2019
* Fixed #5 - UriFormatExceptionSystem thrown when calling UploadAsync
* Fixed several know issues
* Added caching for ListBuckets, ListFileNames, ListFileVersions, ListKeys and ListParts methods
* Added iterator adapters for ListBuckets(), ListFileNames(), ListFileVersions(), ListKeys() and ListParts() methods
* Added code comments for all interfaces
* Added configuration support for AddBackblazeAgent()
* Added error checking support for several models

0.8.2 - August 18 2019
* General code cleanup and documentation
* Added caching for upload_url and upload_part_url
* Added option configuration support using setting.json
* Fixed several know issues

0.8.1 - August 3 2019
* Added additional error checking and trace logging
* Added http retry for expired tokens
* Added BucketInfo, Fileinfo, CorsRules and LifecycleRules validation objects
* Added console progress bar for Iprogress<> upload/download status
* Fixed several know issues

0.8.0 - Jul 31 2019
* First public preview