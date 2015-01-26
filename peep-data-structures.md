# peep-data-structures.md

# Design
- Conditions
    + Scripts:{1-3}:(s1-s3)
    + Emotions:{Angry, Happy, Neutral}:(ang,hap,neu)
    + Speaker:{Familiar, Novel}:(fam,nov)
        * If participant child is from family 003, then f003 is familiar (fam) and some _other_ family's recordings are the novel (nov) condition.
    + Runs:{1-?}:(r1,r2,r3,...)
    + Stim_Orders:{?}:(?)
    + Family_ID:{001...999}:(f001,f002,...)

# Scripts

# Other directories
- wav/
    + f001/
        * s1-ang.wav
        * s2-ang.wav
        * s3-ang.wav
        * s1-hap.wav
        * s2-hap.wav
        * s3-hap.wav
        * s1-neu.wav
        * s2-neu.wav
        * s3-neu.wav
    + f002/
    + f003/
- sessions
    + 2015-01-23-1507-f001/
        * log/
            - 2015-02-23-1507-f001-r1.log
            - 2015-01-23-1517-f001-r2.log
            - 2015-01-23-1527-f001-r3.log
        * data/
            - 2015-02-23-1507-f001-r1.{txt,csv}
            - 2015-02-23-1517-f001-r2.{txt,csv}
            - 2015-02-23-1527-f001-r3.{txt,csv}
    + 2015-01-24-0915-f002/