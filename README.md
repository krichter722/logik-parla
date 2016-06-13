## logik-parla
A data mining experiment for the course "Die Logik parlamentarischer Demokratie: eine historisch-vergleichende Analyse der Entwicklung von Exekutiv-Legislativen Beziehungen" of Humboldt University Berlin 2016. It aims at identifying newspaper articles related to the PATRIOT act of 2001 and the French emergency state laws of 2015/16 for comparison and statistical analysis.

## Setup
    ############################################
    # Crawler                                  #
    # (Apache Nutch, Heritrix, dataparksearch) #
    ############################################
                           |
                           v
    #################################################
    # Identification of relevant newspaper articles #
    # (Weka)                                        #
    #################################################
               |
               v
    ########################
    # Analysis             #
    # (R, sagemath, Stata) #
    ########################
