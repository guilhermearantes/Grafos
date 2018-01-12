# Trabalho Prático de Teoria dos Grafos



* Linguagem:  Java

* IDE:  Eclipse

* S.O: Windows 10

* Estrutura:  Lista

* Instruções:  
<p>Na classe Main, da linha 6 até a linha 56 estão as chamadas das funções para testar a Parte 01 do Trabalho, os exercícios 01 ao 15. Logo em seguida estão os algoritimos da Parte 02, o algoritmo DIJKSTRA e BELLMAN-FORD. </p>
<p>Na classe Grafos, na linha 334 e 335 estã comentado a parte da função que é responsável por mostrar a sequência de vértices a ser tomada com vértice de origem sendo 0 e vértice destino 100, conforme solicitado nas instruções do Trabalho.</p>


* Tabela com o tempo de execução e custo para as instâncias dadas executadas pelos algoritmos Dijkstra e Bellman-Ford.


| Grafos de Teste:      	| DIJKSTRA (Tempo em Segundos / Custo) 	| 
|-----------------------	|--------------------------------------	|
| rg300_4730.txt,       	| {0, 24}                              	| 
| rome99c.txt,          	| {6, 36037}                           	| 
| facebook_combined.txt 	| {11, 1}                              	| 
| USA-road-dt.DC.txt    	| {160, 28137}                         	| 



| Grafos de Teste:      	| BELLMAN-FORD (Tempo em Segundos / Custo)  | 
|-----------------------	|-----------------------------------------	|
| rg300_4730.txt,       	| {0, 24}                                 	| 
| rome99c.txt,          	| {0, 36037}                              	| 
| facebook_combined.txt 	| {10, 1}                                 	| 
| USA-road-dt.DC.txt    	| {3, 28137}                              	| 


* Sequência de vértices a ser tomada com o Vértice de Origem igual a 0 e Vértice de Destino igual a 100: 


rg300_4730.txt:  100 -> 282 -> 156 -> 188 -> 0


rome99c.txt:  100 -> 97 -> 87 -> 89 -> 90 -> 79 -> 85 -> 86 -> 72 -> 126 -> 127 -> 125 -> 124 -> 123 -> 119 -> 120 -> 65 -> 128 -> 129 -> 138 -> 181 -> 155 -> 171 -> 158 -> 159 -> 19 -> 14 -> 18 -> 17 -> 16 -> 20 -> 21 -> 0 -> 


facebook_combined.txt:  100 -> 0 


USA-road-dt.DC.txt:  100 -> 128 -> 163 -> 99 -> 168 -> 170 -> 104 -> 172 -> 119 -> 116 -> 184 -> 186 -> 127 -> 189 -> 190 -> 195 -> 976 -> 827 -> 977 -> 833 -> 831 -> 834 -> 840 -> 838 -> 839 -> 841 -> 848 -> 849 -> 846 -> 809 -> 9530 -> 896 -> 897 -> 891 -> 892 -> 873 -> 882 -> 899 -> 883 -> 880 -> 877 -> 521 -> 878 -> 519 -> 874 -> 530 -> 527 -> 522 -> 488 -> 486 -> 477 -> 474 -> 472 -> 332 -> 345 -> 346 -> 328 -> 299 -> 301 -> 336 -> 338 -> 308 -> 305 -> 290 -> 291 -> 24 -> 3 -> 1 -> 0


