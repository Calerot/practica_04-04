# practica_04-04
preparacio de la molecula UBQ

codi linux:
lscpu #veure quants cpus tens
nohup namd2 +p 12 equilibrationNVT.namd > equilibrationNVT.log & #fer la simulacio amb els cpus lokuu

more/tail MDequil.xst #veure com va la simulacio

grep "ns" *.log #bscar coses en l'archiu .log
