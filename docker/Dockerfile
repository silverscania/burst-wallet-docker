# version 2+ with the h2 database which doesn't require a separate database container
FROM pocconsortium/burstcoin:2-h2

# Setup reward address
#CMD sed -i 's/P2P.myPlatform = PC/P2P.myPlatform = BURST-KBEX-RF89-ANRL-89PAG/g' /conf/brs-default.properties
COPY brs.properties /conf/brs.properties

