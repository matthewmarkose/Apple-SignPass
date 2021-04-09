# Apple-SignPass
Apple SignPass executable
used to create .pkpass files


Running signpass:
usage:    signpass -p <rawpass> [-o <path>] [-c <certSuffix>]
    signpass -v <signedpass>

     -p Sign and zip a raw pass directory
     -v Unzip and verify a signed pass's signature and manifest. This DOES NOT validate pass content.

ex: `./signpass -p mypasscontents.pass`
