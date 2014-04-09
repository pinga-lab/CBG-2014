#Métodos Potenciais


[Oliveira Jr., V. C.$^1$](http://fatiando.org/people/oliveira-jr/), 
[Uieda, L. *#](http://www.leouieda.com/), 
[Barbosa, V. C. F. *](http://lattes.cnpq.br/0391036221142471)

$^1$*Observatório Nacional*; *Universidade do Estado do Rio de Janeiro*

##Resumo:

A magnetometria e a gravimetria são dois dos mais antigos métodos geofísicos 
e fazem parte do que se conhece como métodos potenciais. 

O uso da magnetometria para a exploração mineral remonta ao início do século 
XVII. Posteriormente, durante a segunda guerra mundial, a magnetometria foi 
fortemente impulsionada devido ao desenvolvimento de magnetômetros utilizados 
em aeronaves com o intuito de detectar submarinos inimigos.

Já o uso da gravimetria na solução de problemas geológicos remonta ao século 
XIX, contudo o uso na exploração mineral remonta ao início do século XX e foi 
impulsionado pelo interesse de empresas de petróleo na exploração de óleo e 
gás.

A aplicação dos métodos potenciais (magnetometria e gravimetria) na exploração 
mineral foi extremamente beneficiada pelo desenvolvimento de equipamentos 
(magnetômetros e gravímetros) próprios para a realização de medições em 
plataformas móveis tais como navios, helicópteros e aviões. 

Atualmente, os aerolevantamentos (predominantemente realizados por aviões) 
constituem a principal forma de aquisição de dados magnetométricos e 
gravimétricos, uma vez que possibilita a cobertura de extensas áreas em um 
tempo relativamente curto. A importância dos aerolevantamentos se deve ao 
desenvolvimento de equipamentos cada vez mais precisos. Somado a isso, o 
aprimoramento das técnicas de posicionamento por satélite possibilitou a 
determinação precisa da localização das aeronaves durante o vôo e resultou 
na melhora significativa da qualidade dos dados adquiridos em 
aerolevantamentos.

Dentre as principais técnicas utilizadas na interpretação de dados 
magnetométricos e gravimétricos, destacamos a Deconvolução de Euler, o Sinal 
Analítico e a Camada Equivalente.

A Deconvolução de Euler foi desenvolvida no final dos anos 80, é comumente 
aplicada a dados magnetométricos e ainda é objeto de estudo de vários grupos 
pesquisa no mundo. Essa técnica utiliza as primeiras derivadas espaciais dos 
dados para determinar a posição das fontes geológicas. Embora essa técnica 
seja amplamente utilizada na interpretação de ambientes geológicos diversos, 
ela foi desenvolvida para determinar a posição de determinadas fontes 
geológicas com formas simples. 

O Sinal Analítico é uma técnica comum no processamento de sinais. Sua 
aplicação a dados magnetométricos remonta aos anos 70 e, durante muito tempo, 
foi equivocadamente considerada uma técnica que não depende da direção de 
magnetização das fontes geológicas. Sua principal aplicação é a determinação 
dos limites horizontais das fontes geológicas. 

Por fim, a Camada Equivalente é uma técnica desenvolvida no final dos anos 60, 
pode ser aplicada tanto a dados magnetométricos como gravimétricos e é uma 
alternativa ao processamento de dados no domínio da frequência. O 
processamento de dados no domínio da frequência é, em geral, extremamente 
eficiente do ponto de vista computacional. Contudo, o uso eficiente de 
técnicas de processamento no domínio da frequência requer, em geral, que os 
dados estejam regularmente espaçados sobre um plano com coordenada vertical 
constante, o que não é possível na grande maioria dos levantamentos 
geofísicos. Por outro lado, a Camada Equivalente é relativamente mais custosa 
do ponto de vista computacional. Entretanto, essa técnica pode ser aplicada a 
dados irregularmente espaçados e evita grande parte dos problemas referentes 
a técnicas no domínio da frequência.

Neste trabalho, apresentamos uma série de exemplos da aplicação da 
Deconvolução de Euler, Sinal Analítico e Camada Equivalente na interpretação 
de dados magnetométricos e gravimétricos. Os exemplos incluem boas e 
más práticas no uso dessas técnicas tão difundidas na indústria e na 
academia.

Todos os códigos para a reprodução dos resultados estão disponibilizados 
em um repositório do grupo de 
[Problemas INversos em GeofísicA](https://github.com/pinga-lab/CBG-2014.git)
e são feitos utilizando-se o pacote de inversão e modelagem geofísica 
[Fatiando a Terra](http://fatiando.org/), que é um projeto de sofware livre 
distribuído gratuitamente na internet. 
