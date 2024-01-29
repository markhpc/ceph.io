# To generate a pdf file, run:

pandoc --pdf-engine xelatex -s --highlight-style tango -V colorlinks=true -V linkcolor=OliveGreen -V urlcolor=OliveGreen -V geometry:"left=1.5in,right=1.5in,top=1.5in,bottom=1.5in" index.md -o ~/Documents/Clyso/Ceph-A-Journey-to-1TiBps.pdf
