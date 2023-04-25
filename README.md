# awx-migration
Base AWX artifacts migration scripts

The script exports artifacts from source and imports it into awx target instance.
This script will not work as expected if the source instance has Workdlow approval Template as its artifact can't be exported due to limitations from awx itself.
 
