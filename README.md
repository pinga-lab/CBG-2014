Métodos Potenciais
==================

Autores
-------

[Oliveira Jr., V. C.](http://fatiando.org/people/oliveira-jr/)<sup>1</sup>, 
[Uieda, L.](http://www.leouieda.com/)<sup>12</sup>,
[Barbosa, V. C. F.](http://lattes.cnpq.br/0391036221142471)<sup>1</sup>

<sup>1</sup>[*Observatório Nacional*](http://www.on.br/) ; <sup>2</sup>
[*Universidade do Estado do Rio de Janeiro*](http://www.uerj.br/)

Evento
------

[*47<sup>o</sup> Congresso Brasileiro de Geologia*](http://www.47cbg.com.br/), 
21 a 26 de setembro de 2014, 
Salvador, Bahia

Resumo
------

A magnetometria e a gravimetria são dois dos mais antigos métodos geofísicos e
fazem parte do que se conhece como métodos potenciais. O uso da magnetometria 
na exploração mineral remonta ao início do século XVII. Posteriormente, 
durante a segunda guerra mundial, a magnetometria foi fortemente impulsionada 
pelo desenvolvimento de magnetômetros utilizados em aeronaves. Já o uso da 
gravimetria na exploração mineral remonta ao início do século XX e foi 
impulsionado pelo interesse de empresas de petróleo na 
exploração de óleo e gás. A aplicação dos métodos potenciais na exploração 
mineral foi extremamente beneficiada pelo desenvolvimento de equipamentos 
(magnetômetros e gravímetros) próprios para aquisições aéreas 
(aerolevantamentos). Atualmente, os aerolevantamentos constituem a principal 
forma de aquisição de dados magnetométricos e gravimétricos, uma vez que 
possibilita a cobertura de extensas áreas em um tempo relativamente curto. 
Além disso, o aprimoramento das técnicas de posicionamento por satélite 
possibilitou a determinação precisa da localização das aeronaves e resultou 
na melhora significativa da qualidade dos dados. Dentre as principais 
técnicas utilizadas em métodos potenciais, destacamos a Deconvolução de Euler 
e o Sinal Analítico. A Deconvolução de Euler foi desenvolvida no final dos 
anos 80 para determinar a posição, em geral, do topo ou centro 
de fontes geológicas simples. O Sinal Analítico foi utilizado na 
interpretação de dados potenciais nos anos 70 para a determinação dos limites 
horizontais de fontes geológicas. Estas duas técnicas usam derivadas 
espaciais dos dados que são geralmente
calculadas numericamente no domínio da frequência. Estes cálculos são
extremamente eficientes computacionalmente graças ao uso da transformada rápida
de Fourier (FFT). No entanto, esse tipo de cálculo tem as desvantagens de ser
numericamente instável, pois amplifica ruídos de alta frequência, e requerer
dados regularmente espaçados sobre um plano horizontal.
Por outro lado, o cálculo das derivadas pode ser feito no domínio do espaço via
a técnica da Camada Equivalente, que permite o controle da amplificação de
ruídos e não impõe restrições na distribuição espacial dos dados.
De fato, a camada equivalente pode ser utilizada para uma gama de
processamentos como continuação para cima, interpolação, redução ao pólo,
e nivelamento, dentre outros. Estes fatos viabilizam o uso da camada 
equivalente na grande maioria dos levantamentos geofísicos. No entanto, a 
utilização da camada equivalente é, em geral, computacionalmente mais custosa. 
Neste trabalho, apresentamos uma série de aplicações da Deconvolução de Euler,
Sinal Analítico e Camada Equivalente na interpretação e processamento de dados 
magnetométricos e gravimétricos. Os exemplos incluem boas e más práticas no uso 
dessas técnicas tão difundidas na indústria e na academia. Todos os códigos e 
dados sintéticos para a reprodução dos resultados foram gerados com o sofware 
livre Fatiando a Terra (http://www.fatiando.org)
e estarão disponíveis em https://github.com/pinga-lab/CBG-2014.
