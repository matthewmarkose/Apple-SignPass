# Apple-SignPass
Apple SignPass executable
used to create .pkpass files


### Running signpass:
usage:    signpass -p <rawpass> [-o <path>] [-c <certSuffix>]
    signpass -v <signedpass>

     -p Sign and zip a raw pass directory
     -v Unzip and verify a signed pass's signature and manifest. This DOES NOT validate pass content.

ex: `./signpass -p mypasscontents.pass`


### Additional Documentation
[Getting started](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/PassKit_PG/index.html#//apple_ref/doc/uid/TP40012195-CH1-SW1)\
[Json Hierarchy Naming](https://developer.apple.com/library/archive/documentation/UserExperience/Reference/PassKit_Bundle/Chapters/Introduction.html#//apple_ref/doc/uid/TP40012026-CH0-SW1)\
[User's Pass Types Ids](https://developer.apple.com/account/resources/identifiers/list/passTypeId)\
[PK Pass validator](https://pkpassvalidator.com/)
