Passos tomados




1 - Realizei os ajustes de pastas e organizações para que fique tudo mais clean possivel
2 - Instalei a biblioteca styled-components
3 - Com tudo instalado e configurado, iniciei a estilização da pagina e preparação de constantes no style.js
4 - Com o style.js feito, realizei algumas funçoes e montei um MAP no index.js
5 - Criei uma pasta de key.js para importar quando necessario minha key acess
6 - Apos importar todos os componetes e variaveis fiz a chamada da API e setando ele para que converse com o MAP criado anteriormente.
7 - Criei uma constante para pegar a url da imagem que a API fornece
8 - Ajsutei a img src com minha const que criei e para que consiga fornecer as imagens certas que a API envia
9 - Agora para lidar com as rotas preciso instalar react router para que consiga informaçoes especificas de cada filme 

Saindo da pasta pages, vamos para index.js para mexer com as rotas 

10 - Npm install react-router-dom@6
11 - importei BrowserRouter, Routes, Route e criei as Rotas
12 - Criei uma pasta Details, importei o useParams e criei a função com uma const id para cada id de filme
13 - Criei mais um state para consumir novamente a API para que eu possa puxar dessa vez informaçoes da sinospe do filme porem dessa vez com uma mudança no link para o ID e localizar o id do filme
14 - setei os dados que a const do ID tinha que pegar na API
15 - importei o Link e container
16 - Finalizei com algumas alterações no style.js da pasta details 



