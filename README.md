# Installation

Pull the image from the docker index. 

    docker pull msarti/activemq

# Quick Start
You can start the image using the docker command line:

    docker run -d  \
    --name activemq -p 8161:8161 -p 61616:61616 -p 61613:61613 \
    -p 61617:61617 msarti/activemq




