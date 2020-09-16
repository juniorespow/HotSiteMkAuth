# HotSiteMkAuth
Template hotsite MK-Auth para o nosso sistema de Ponto e Acesso.

A implantação desse layout é para quem usa o MK Auth não para mostrar planos e algo tipo, é para uma central de atendimento, meu segmento é controle de ponto e acesso, e o MK Auth 
me atende muito bem, por isso resolvi fazer um HotSite moderno e leve usando a técnica OnePage, tem o link para central do assinante e algumas outras informações.

Para implantar ele no Mk Auth é bem simples, você só precisa dentro da pasta /var/www/layout colocar uma nova pasta com o seu nome de preferencia, e dentro dessa pasta vai apenas o
arquivo index.html;
Dentro da pasta /var/www vc coloca a pasta assets contendo apenas a pasta img;
Continando em /var/www você coloca o arquivo de styles.css na pasta css;
E o arquivo scripts.js na pasta js.

Sim para o Mk Auth reconhecer um HotSite precisa ser fragmentado dessa forma, se não, não roda.

Dentro do seu Mk AUth, você navega até o menu HOTSITE, e em seguida para layout do HotSite;
Va para o opção de escolha um tema, e selecione o nome do seu Hotsite, nome esse que será o da pasta que você criou dentro do diretório /var/www/layout.

Por fim clique em gravar e pode testar seu novo HotSite.

Muito cuidado ao editar o arquivo index.html, existem algumas variaveis obrigatórias para o Back-end poder reconhece-lo, sugiro ler bem sobre isso no forum do Mk-Auth.
