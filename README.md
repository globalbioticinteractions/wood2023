[![GloBI Review by Elton](../../actions/workflows/review.yml/badge.svg)](../../actions/workflows/review.yml) [![GloBI](https://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:globalbioticinteractions/wood2023&refutes=true&refutes=false)](https://globalbioticinteractions.org/?accordingTo=globi:globalbioticinteractions/wood2023)

Configuration to help Global Biotic Interactions (GloBI, https://globalbioticinteractions.org) index: 

Wood, T.J., Müller, A., Praz, C. et al. Elevated rates of dietary generalization in eusocial lineages of the secondarily herbivorous bees. BMC Ecol Evo 23, 67 (2023). https://doi.org/10.1186/s12862-023-02175-1

## Provenance

Original dataset was transformed into tab-separated values using the following command:

```bash
preston track --algo md5 "https://static-content.springer.com/esm/art%3A10.1186%2Fs12862-023-02175-1/MediaObjects/12862_2023_2175_MOESM2_ESM.xlsx" \
 | preston dwc-stream --algo md5 \
 | mlr --ijsonl --otsv cat \
 > 12862_2023_2175_MOESM2_ESM.xlsx.tsv
```

with first record being (in xtab format), describing a _Actenosigynes mantiqueirensis_ (Colletidae) having a relation to Loasaceae plant family with value ```100```.  

```
http://www.w3.org/ns/prov#wasDerivedFrom line:xlsx:hash://md5/3d4a61547a8792d99a630317f1d8a9f8!/Sheet1!/L2
http://purl.org/dc/elements/1.1/format   application/vnd.openxmlformats-officedocument.spreadsheetml.sheet
Reference                                Siriani-Oliveira et al (2018)
Number (Appenidx I)                      80
Family                                   Colletidae
Species                                  Actenosigynes mantiqueirensis
Loads                                    null
Nest                                     null
Obs.                                     Obs.
M                                        10
Acanthaceae                              
Adoxaceae                                
Aizoaceae                                
Amaryllidaceae                           
Altingiaceae                             
Anacardiaceae                            
Apiaceae                                 
Apocynaceae                              
Aquifoliaceae                            
Araliaceae                               
Arecaceae                                
Asparagaceae                             
Asphodelaceae                            
Asteraceae                               
Balsaminaceae                            
Berberidaceae                            
Betulaceae                               
Bignoniaceae                             
Bixaceae                                 
Boraginaceae                             
Brassicaceae                             
Cactaceae                                
Calceolariaceae                          
Campanulaceae                            
Capparaceae                              
Caprifoliaceae                           
Caryophyllaceae                          
Chenopodiaceae                           
Cistaceae                                
Clusiaceae                               
Colchicaceae                             
Commelinaceae                            
Convolvulaceae                           
Cordiaceae                               
Cornaceae                                
Costaceae                                
Crassulaceae                             
Cucurbitaceae                            
Cunoniaceae                              
Ebenaceae                                
Elaeagnaceae                             
Ericaceae                                
Escalloniaceae                           
Euphorbiaceae                            
Fabaceae                                 
Fagaceae                                 
Frankeniaceae                            
Gentianaceae                             
Geraniaceae                              
Grossulariaceae                          
Heliconiaceae                            
Hippocastanaceae                         
Hydrangaceae                             
Hypericaceae                             
Iridaceae                                
Juglandaceae                             
Juncaceae                                
Krameriaceae                             
Lamiaceae                                
Limnocharitaceae                         
Lauraceae                                
Liliaceae s.l.                           
Linaceae                                 
Loasaceae                                100.0
Lythraceae                               
Malpighiaceae                            
Malvaceae                                
Melanthiaceae                            
Melastomataceae                          
Meliaceae                                
Mimosaceae                               
Molluginaceae                            
Monocots                                 
Muntingiaceae                            
Montiaceae                               
Myrtaceae                                
Nitrariaceae                             
Nyctaginaceae                            
Oleaceae                                 
Onagraceae                               
Orobanchaceae                            
Oxalidaceae                              
Papaveraceae                             
Parnassiaceae                            
Passifloraceae                           
Phytolaccaceae                           
Pinaceae                                 
Plantaginaceae                           
Plumbaginaceae                           
Poaceae                                  
Polemoniaceae                            
Polygonaceae                             
Pontederiaceae                           
Primulaceae                              
Protaceae                                
Pteridaceae                              
Ranunculaceae                            
Resedaceae                               
Rhamnaceae                               
Rosaceae                                 
Rubiaceae                                
Rutaceae                                 
Salicaceae                               
Santalaceae                              
Sapindaceae                              
Saxifragaceae                            
Scrophulariaceae                         
Solanaceae                               
Sterculiaceae                            
Tamaricaceae                             
Theaceae                                 
Turneraceae                              
Ulmaceae                                 
Urticaceae                               
Verbenaceae                              
Violaceae                                
Vitaceae                                 
Xanthorrhoaceae                          
Zygophyllaceae                           
Unknown                                  
``` 
