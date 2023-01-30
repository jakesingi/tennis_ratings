# Tennis Ratings
#### Author: [Jake Singleton](https://twitter.com/jakesingi)

## Version 1: January 2023 ATP Men's Singles Ratings and Rankings
* The ratings below are the work of my master's thesis and are based on a fully-[Bayesian](https://en.wikipedia.org/wiki/Bayesian_statistics) [Bradley-Terry model](https://en.wikipedia.org/wiki/Bradley%E2%80%93Terry_model). They are similar to [Elo ratings](https://en.wikipedia.org/wiki/Elo_rating_system), but I'd argue they resemble [Glicko ratings](https://en.wikipedia.org/wiki/Glicko_rating_system) even more closely. I show in my work that these ratings outperform Glicko (more to come on this later). 
* Only players with 5 or more ATP-level matches played in the last 365 days are listed.
* **Interpretation**: There are 3 "skill" columns, one for each surface. Unfortunately they are not sortable at the moment, but as a first step, I've sorted the table by "hard_skill" (players' skills on hard court), as this is the most popular surface.

### Updated through the end of the 2022 season. Updated monthly.

| rank | full_name                   | hard_skill  | clay_skill  | grass_skill |
| ---- | --------------------------- | ----------- | ----------- | ----------- |
| 1    | Novak Djokovic              | 0.67397587  | 0.63905555  | 0.62858388  |
| 2    | Daniil Medvedev             | 0.54910247  | 0.32049175  | 0.48930529  |
| 3    | Rafael Nadal                | 0.54647339  | 0.71383284  | 0.51232825  |
| 4    | Alexander Zverev            | 0.47170961  | 0.43802871  | 0.43391748  |
| 5    | Andrey Rublev               | 0.40093938  | 0.34631892  | 0.36159512  |
| 6    | Carlos Alcaraz              | 0.40082991  | 0.40254738  | 0.36134748  |
| 7    | Stefanos Tsitsipas          | 0.39859861  | 0.53994276  | 0.36183315  |
| 8    | Nick Kyrgios                | 0.3791998   | 0.24616287  | 0.35136772  |
| 9    | Dominic Thiem               | 0.35877315  | 0.16584906  | 0.32284136  |
| 10   | Matteo Berrettini           | 0.34959735  | 0.34843528  | 0.34675987  |
| 11   | Jannik Sinner               | 0.34331499  | 0.39126284  | 0.31980295  |
| 12   | Jack Draper                 | 0.33748285  | 0.28236686  | 0.30955854  |
| 13   | Roberto Bautista Agut       | 0.3312867   | 0.28622927  | 0.30641699  |
| 14   | Casper Ruud                 | 0.3232017   | 0.38679002  | 0.29110756  |
| 15   | Gael Monfils                | 0.31937016  | 0.05610718  | 0.27006593  |
| 16   | Felix Auger Aliassime       | 0.30859066  | 0.22602935  | 0.28593577  |
| 17   | Taylor Fritz                | 0.30431487  | 0.09448598  | 0.28074186  |
| 18   | Hubert Hurkacz              | 0.29763422  | 0.17287747  | 0.28006323  |
| 19   | Cameron Norrie              | 0.28956038  | 0.25146793  | 0.27811279  |
| 20   | Sebastian Korda             | 0.28485606  | 0.23876163  | 0.26124214  |
| 21   | Denis Shapovalov            | 0.26454794  | 0.22367841  | 0.2470306   |
| 22   | Holger Rune                 | 0.26434068  | 0.18260045  | 0.22925114  |
| 23   | Pablo Carreno Busta         | 0.26414113  | 0.31494345  | 0.23878827  |
| 24   | Jenson Brooksby             | 0.25887563  | 0.01749965  | 0.22259487  |
| 25   | Alex De Minaur              | 0.25389433  | 0.13869462  | 0.23449738  |
| 26   | Karen Khachanov             | 0.25231459  | 0.14161216  | 0.22971436  |
| 27   | Ilya Ivashka                | 0.25188816  | 0.17790556  | 0.22973684  |
| 28   | Grigor Dimitrov             | 0.24880822  | 0.29199888  | 0.23158283  |
| 29   | Diego Schwartzman           | 0.23794783  | 0.30263135  | 0.22007068  |
| 30   | Antoine Bellier             | 0.23012056  | 0.16863569  | 0.21717126  |
| 31   | Borna Coric                 | 0.22928572  | 0.07184859  | 0.20477975  |
| 32   | Marin Cilic                 | 0.22449606  | 0.26303006  | 0.21757598  |
| 33   | Roman Safiullin             | 0.218439    | 0.2373854   | 0.20308587  |
| 34   | Tommy Paul                  | 0.21532123  | 0.07402861  | 0.20356962  |
| 35   | Daniel Evans                | 0.21441544  | 0.09792909  | 0.18862536  |
| 36   | Maxime Cressy               | 0.21052833  | 0.021145    | 0.19723651  |
| 37   | Frances Tiafoe              | 0.20852663  | 0.09213059  | 0.18657666  |
| 38   | Brandon Nakashima           | 0.20715672  | 0.10531003  | 0.19155228  |
| 39   | Dominic Stricker            | 0.20357457  | 0.17462538  | 0.18572606  |
| 40   | Botic Van De Zandschulp     | 0.20165986  | 0.24090461  | 0.19065883  |
| 41   | Aslan Karatsev              | 0.19708826  | 0.1159007   | 0.16980611  |
| 42   | Stan Wawrinka               | 0.19004752  | 0.10287707  | 0.16679539  |
| 43   | Emil Ruusuvuori             | 0.18783172  | 0.00457045  | 0.16187177  |
| 44   | Benjamin Bonzi              | 0.18447838  | 0.04676076  | 0.17390773  |
| 45   | Mikael Ymer                 | 0.18433849  | 0.04332168  | 0.15679805  |
| 46   | Tim Van Rijthoven           | 0.1768302   | 0.13958834  | 0.18029761  |
| 47   | Reilly Opelka               | 0.16987797  | 0.13637256  | 0.14277309  |
| 48   | Andy Murray                 | 0.16769003  | 0.13433235  | 0.16859219  |
| 49   | Tomas Machac                | 0.16587358  | 0.16069169  | 0.15262931  |
| 50   | Vasek Pospisil              | 0.16582942  | 0.04724379  | 0.14028481  |
| 51   | Lorenzo Sonego              | 0.16101921  | 0.13979821  | 0.15491738  |
| 52   | Ugo Humbert                 | 0.15674316  | 0.01336897  | 0.14293102  |
| 53   | Gijs Brouwer                | 0.15598374  | 0.20467854  | 0.14584505  |
| 54   | Lloyd Harris                | 0.15547816  | 0.00030923  | 0.13244927  |
| 55   | John Isner                  | 0.15402668  | 0.16764088  | 0.14161963  |
| 56   | Alexander Bublik            | 0.15368476  | 0.01698685  | 0.15410976  |
| 57   | Alexander Ritschard         | 0.14994376  | 0.08482865  | 0.13941838  |
| 58   | Marton Fucsovics            | 0.14930685  | 0.1644493   | 0.14040065  |
| 59   | Arthur Rinderknech          | 0.14690823  | 0.12737313  | 0.12769016  |
| 60   | Pierre Hugues Herbert       | 0.14630756  | 0.11599745  | 0.13090506  |
| 61   | David Goffin                | 0.14609311  | 0.1600244   | 0.14665872  |
| 62   | Constant Lestienne          | 0.13746462  | 0.09854297  | 0.12439457  |
| 63   | Mackenzie Mcdonald          | 0.13648025  | 0.06813886  | 0.11577612  |
| 64   | Francisco Cerundolo         | 0.13160291  | 0.14123918  | 0.12214634  |
| 65   | Thanasi Kokkinakis          | 0.13112131  | 0.11047417  | 0.1208225   |
| 66   | J J Wolf                    | 0.13087521  | 0.03012314  | 0.1166763   |
| 67   | Marc Andrea Huesler         | 0.12743823  | 0.1120269   | 0.11320965  |
| 68   | Zizou Bergs                 | 0.12678025  | 0.07253856  | 0.11381904  |
| 69   | Filip Krajinovic            | 0.12589894  | 0.17552292  | 0.11591082  |
| 70   | Miomir Kecmanovic           | 0.12584558  | 0.12897709  | 0.11006296  |
| 71   | Richard Gasquet             | 0.1238586   | 0.06710748  | 0.11137217  |
| 72   | Jan Lennard Struff          | 0.12095928  | 0.08671203  | 0.11335325  |
| 73   | Kyle Edmund                 | 0.11788785  | 0.0523618   | 0.10638633  |
| 74   | Adrian Mannarino            | 0.11685798  | \-0.2064911 | 0.08756887  |
| 75   | Jason Kubler                | 0.11174584  | 0.08153985  | 0.11247552  |
| 76   | Corentin Moutet             | 0.11135178  | 0.01078153  | 0.09252965  |
| 77   | Franco Agamenone            | 0.10826352  | 0.14609932  | 0.10218194  |
| 78   | Lorenzo Musetti             | 0.10416345  | 0.2195109   | 0.09313776  |
| 79   | Soon Woo Kwon               | 0.10366101  | 0.02084947  | 0.09012238  |
| 80   | Alejandro Davidovich Fokina | 0.10116043  | 0.1689763   | 0.09638748  |
| 81   | Jack Sock                   | 0.09799605  | 0.06253757  | 0.09670129  |
| 82   | Ben Shelton                 | 0.0968203   | 0.06369769  | 0.08680613  |
| 83   | Juan Pablo Varillas         | 0.09386694  | 0.15506205  | 0.08963154  |
| 84   | Ryan Peniston               | 0.09360888  | 0.06787692  | 0.09291197  |
| 85   | Jiri Vesely                 | 0.08917473  | \-0.0159495 | 0.08421888  |
| 86   | Oscar Otte                  | 0.08621302  | 0.1446537   | 0.09005434  |
| 87   | Vit Kopriva                 | 0.08579244  | 0.11071592  | 0.08119901  |
| 88   | Christopher Oconnell        | 0.08533885  | \-0.0120012 | 0.07298712  |
| 89   | Kevin Anderson              | 0.08276835  | 0.10591399  | 0.08402213  |
| 90   | Kamil Majchrzak             | 0.08129442  | \-0.0302257 | 0.07109288  |
| 91   | Yosuke Watanuki             | 0.08081028  | 0.14191299  | 0.08141561  |
| 92   | Gilles Simon                | 0.07955725  | \-0.1408429 | 0.05901325  |
| 93   | Borna Gojo                  | 0.07586142  | 0.04874242  | 0.06771358  |
| 94   | Elias Ymer                  | 0.07471992  | 0.08131467  | 0.06543784  |
| 95   | Aljaz Bedene                | 0.07471842  | \-0.0211878 | 0.07020395  |
| 96   | Marcos Giron                | 0.07156618  | \-0.1005056 | 0.05971219  |
| 97   | John Millman                | 0.06939396  | \-0.057796  | 0.05438768  |
| 98   | Jurij Rodionov              | 0.06480852  | 0.09662872  | 0.0597152   |
| 99   | Pedro Cachin                | 0.06304449  | 0.09280967  | 0.058929    |
| 100  | Alexei Popyrin              | 0.06110127  | 0.01754585  | 0.04714692  |
| 101  | Filip Misolic               | 0.0598247   | 0.14655061  | 0.06010672  |
| 102  | Nuno Borges                 | 0.05868748  | 0.09622039  | 0.05354527  |
| 103  | Alejandro Tabilo            | 0.05849202  | 0.17370375  | 0.05337198  |
| 104  | Steve Johnson               | 0.0521728   | \-0.0233181 | 0.05104131  |
| 105  | Fabio Fognini               | 0.05158422  | 0.04823187  | 0.04606772  |
| 106  | Altug Celikbilek            | 0.0481294   | 0.01328036  | 0.03833331  |
| 107  | Aleksandar Vukic            | 0.04801785  | \-0.0069397 | 0.04277102  |
| 108  | Liam Broady                 | 0.04800521  | 0.00083421  | 0.0413962   |
| 109  | Jordan Thompson             | 0.04781457  | \-0.1575411 | 0.04563375  |
| 110  | Daniel Elahi Galan          | 0.04754936  | 0.11465072  | 0.04351558  |
| 111  | Egor Gerasimov              | 0.04729041  | \-0.0165212 | 0.03646993  |
| 112  | James Duckworth             | 0.0469185   | \-0.1078133 | 0.04092879  |
| 113  | Laslo Djere                 | 0.04319757  | 0.18715605  | 0.04924746  |
| 114  | Ricardas Berankis           | 0.04172667  | \-0.0403328 | 0.0345913   |
| 115  | Yoshihito Nishioka          | 0.04088081  | \-0.0519192 | 0.01754189  |
| 116  | Hugo Grenier                | 0.03989343  | 0.00262394  | 0.02951442  |
| 117  | Christopher Eubanks         | 0.03643888  | 0.03140202  | 0.03619811  |
| 118  | Alex Molcan                 | 0.02841269  | 0.25184631  | 0.0444251   |
| 119  | Thiago Monteiro             | 0.02781849  | 0.06808949  | 0.02302037  |
| 120  | Zhizhen Zhang               | 0.02466595  | 0.0720106   | 0.02100286  |
| 121  | Quentin Halys               | 0.02308892  | 0.03930407  | 0.02781771  |
| 122  | Tallon Griekspoor           | 0.01798512  | \-0.0092191 | 0.01718996  |
| 123  | Dusan Lajovic               | 0.01432943  | 0.02806743  | 0.00653931  |
| 124  | Hugo Gaston                 | 0.01156455  | 0.0898268   | 0.01830887  |
| 125  | Luca Nardi                  | 0.01013887  | \-0.0480916 | 0.006798    |
| 126  | Manuel Guinard              | 0.00679445  | \-0.0226081 | 0.00510142  |
| 127  | Pedro Martinez              | 0.00647139  | 0.12665458  | 0.00749034  |
| 128  | Jiri Lehecka                | 0.00169782  | 0.03121498  | 0.00329106  |
| 129  | Denis Kudla                 | 0.00140142  | \-0.0397868 | 0.01481066  |
| 130  | Dominik Koepfer             | \-0.0065054 | 0.04104872  | \-0.0050656 |
| 131  | Stefano Travaglia           | \-0.0097451 | \-0.029295  | \-0.0100408 |
| 132  | Giulio Zeppieri             | \-0.0100409 | 0.06771082  | \-0.0063842 |
| 133  | Carlos Taberner             | \-0.0111676 | 0.00424903  | \-0.011079  |
| 134  | Jaume Munar                 | \-0.0130102 | 0.11001229  | \-0.0077994 |
| 135  | Cristian Garin              | \-0.0183431 | 0.16696629  | 0.00573137  |
| 136  | Andreas Seppi               | \-0.0201115 | \-0.0295333 | \-0.0146433 |
| 137  | Maximilian Marterer         | \-0.0201774 | 0.01056999  | \-0.0154817 |
| 138  | Radu Albot                  | \-0.0215994 | \-0.1410924 | \-0.0315605 |
| 139  | Taro Daniel                 | \-0.0220334 | \-0.0012816 | \-0.0226884 |
| 140  | Nikoloz Basilashvili        | \-0.0228882 | \-0.0878349 | \-0.0173833 |
| 141  | Albert Ramos                | \-0.0244551 | 0.11614105  | \-0.0228091 |
| 142  | Max Purcell                 | \-0.0253642 | \-0.0292739 | \-0.0185495 |
| 143  | Sam Querrey                 | \-0.0271386 | \-0.0422696 | \-0.0085739 |
| 144  | Peter Gojowczyk             | \-0.0291452 | \-0.1016084 | \-0.0268699 |
| 145  | Juan Manuel Cerundolo       | \-0.0292115 | 0.06920952  | \-0.0229145 |
| 146  | Facundo Bagnis              | \-0.0294363 | 0.05573136  | \-0.0260817 |
| 147  | Lucas Pouille               | \-0.0297641 | \-0.1150716 | \-0.0291945 |
| 148  | Norbert Gombos              | \-0.032041  | \-0.0107362 | \-0.0356495 |
| 149  | Fernando Verdasco           | \-0.0430305 | \-0.0753251 | \-0.0442005 |
| 150  | Gregoire Barrere            | \-0.0475014 | \-0.1144118 | \-0.0498082 |
| 151  | Yannick Hanfmann            | \-0.0480902 | 0.13287054  | \-0.0400182 |
| 152  | Pablo Andujar               | \-0.0540834 | \-0.0215083 | \-0.0481196 |
| 153  | Stefan Kozlov               | \-0.0546904 | \-0.0449981 | \-0.0558613 |
| 154  | Benoit Paire                | \-0.060336  | \-0.1408104 | \-0.0735653 |
| 155  | Mitchell Krueger            | \-0.0627281 | \-0.0526192 | \-0.058237  |
| 156  | Feliciano Lopez             | \-0.068616  | \-0.1358078 | \-0.0675904 |
| 157  | Jo-Wilfried Tsonga          | \-0.0712827 | \-0.1325781 | \-0.0694737 |
| 158  | Roberto Carballes Baena     | \-0.0733374 | 0.05433245  | \-0.071469  |
| 159  | Michael Mmoh                | \-0.0741554 | \-0.0805279 | \-0.0691251 |
| 160  | Pavel Kotov                 | \-0.0802873 | \-0.0355464 | \-0.0724304 |
| 161  | Flavio Cobolli              | \-0.0803618 | \-0.0381512 | \-0.0718982 |
| 162  | Sebastian Baez              | \-0.0852373 | 0.21961001  | \-0.0642773 |
| 163  | Dennis Novak                | \-0.0881657 | \-0.17595   | \-0.0872688 |
| 164  | Emilio Gomez                | \-0.0910163 | \-0.0653641 | \-0.0840354 |
| 165  | Pablo Cuevas                | \-0.0951863 | 0.06599438  | \-0.0820594 |
| 166  | Bernabe Zapata Miralles     | \-0.1120488 | 0.02585944  | \-0.1034049 |
| 167  | Nicolas Jarry               | \-0.1131951 | 0.0039561   | \-0.0992687 |
| 168  | Joao Sousa                  | \-0.1183617 | \-0.1357044 | \-0.1175551 |
| 169  | Ramkumar Ramanathan         | \-0.1218345 | \-0.0808272 | \-0.1042494 |
| 170  | Henri Laaksonen             | \-0.1239161 | 0.00906103  | \-0.1114593 |
| 171  | Daniel Altmaier             | \-0.1256715 | 0.04071808  | \-0.108946  |
| 172  | Juan Ignacio Londero        | \-0.1277976 | \-0.0789064 | \-0.1199515 |
| 173  | Cem Ilkel                   | \-0.1323421 | \-0.1936506 | \-0.1250902 |
| 174  | Mikhail Kukushkin           | \-0.1388968 | \-0.1550763 | \-0.139453  |
| 175  | Damir Dzumhur               | \-0.141867  | \-0.0337071 | \-0.1263218 |
| 176  | Tomas Martin Etcheverry     | \-0.1623843 | \-0.1870674 | \-0.1491769 |
| 177  | Federico Coria              | \-0.1799658 | 0.04724824  | \-0.1586848 |
| 178  | Marco Cecchinato            | \-0.1960003 | 0.03414493  | \-0.1754515 |
| 179  | Emilio Nava                 | \-0.2003897 | \-0.1413694 | \-0.1818629 |
| 180  | Federico Delbonis           | \-0.2222174 | 0.08262094  | \-0.1959652 |
| 181  | Chun Hsin Tseng             | \-0.2319536 | \-0.1963103 | \-0.2162912 |
| 182  | Hugo Dellien                | \-0.2630141 | \-0.1275134 | \-0.2377017 |

## Images
* For brevity, here are visuals of the posterior distributions for each of the top 10 players listed
* If you want to see plots for other players, I've uploaded them all [here](https://drive.google.com/drive/folders/1FPIqMj5Dm8t5D6z58C4bLfM7g8dWGFbl?usp=sharing).
* **Interpretation**: Higher values of skill are good. The tighter the colorful blobs (aka distributions) are, the more confident we are about that player's skill on that particular surface. Note the blue blobs will tend to be tighter, since more matches are played on hard courts than clay and grass. 
* For example, we know Nadal is incredibly dominant on clay, and you can see his red blob is quite far to the right, reaffirming our belief he is uniquely good on clay courts.

<img src="./images/thruDec22/104925Novak_Djokovic.png" width="600" height="500" />
<img src="./images/thruDec22/106421Daniil_Medvedev.png" width="600" height="500" />
<img src="./images/thruDec22/104745Rafael_Nadal.png" width="600" height="500" />
<img src="./images/thruDec22/100644Alexander_Zverev.png" width="600" height="500" /> 
<img src="./images/thruDec22/126094Andrey_Rublev.png" width="600" height="500" />
<img src="./images/thruDec22/207989Carlos_Alcaraz.png" width="600" height="500" />
<img src="./images/thruDec22/126774Stefanos_Tsitsipas.png" width="600" height="500" />
<img src="./images/thruDec22/106401Nick_Kyrgios.png" width="600" height="500" />
<img src="./images/thruDec22/106233Dominic_Thiem.png" width="600" height="500" /> 
<img src="./images/thruDec22/126610Matteo_Berrettini.png" width="600" height="500" />

## Future additions
* Add master's paper with mathematical details and performance of ratings
* Add women's ratings and rankings later, and potentially doubles
* Move the site away from markdown and toward something cleaner and more aesthetically-pleasing
