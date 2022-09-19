# LMAS_DEMO_BMOCK12

The twelve bacterial replicons of the [BMock12 Community Standards](https://www.nature.com/articles/s41597-019-0287-z#Abs1)
were used as reference. It includes the following strains: 

| Species                        	| Sample ID  	| Depth of Coverage (x) 	|
|--------------------------------	|------------	|----------------------:	|
| Muricauda   sp. ES.050         	| 2615840527 	|               618,758 	|
| Thioclava sp. ES.032           	| 2615840533 	|                78,318 	|
| Cohaesibacter sp. ES.047       	| 2615840601 	|               170,586 	|
| Propionibacteriaceae bacterium 	| 2615840646 	|                31,902 	|
| Marinobacter sp. LV10R510-8    	| 2615840697 	|               447,834 	|
| Marinobacter sp. LV10MA510-1   	| 2616644829 	|                135,05 	|
| Psychrobacter sp. LV10R520-6   	| 2617270709 	|               425,472 	|
| Micromonospora echinaurantiaca 	| 2623620557 	|                14,912 	|
| Micromonospora echinofusca     	| 2623620567 	|                18,192 	|
| Micromonospora coxensis        	| 2623620609 	|                  0,02 	|
| Halomonas sp. HL-4             	| 2623620617 	|                507,08 	|
| Halomonas sp. HL-93            	| 2623620618 	|               579,874 	|

The raw sequence data of the mock communities, with an even distribution of species, is available at:

- [SRR8073716](https://www.ebi.ac.uk/ena/browser/view/SRR8073716?show=reads)

For the sake of a less resource-intense evaluation we downsampled to have 20% of the reads available in the original sample and further processed only these. The main challenges of this data set are possibly to assemble the genomes of the three *Micromonospora* spp. and the two *Halomonas* spp. strains, which have an ANIb >0.84 and 0.98, respectively. The two *Marinobacter* spp. have an ANIb of 0.78.