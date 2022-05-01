#### Avaliação Compass

# Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes 
#### 1. O que é um ataque DDoS e como posso me proteger?
O ataque DDoS é um ataque de negação, onde o invasor visa sobrecarregar o servidor com tráfego de internet falso, dessa forma o servidor sobrecarregado deixa de responder as conexões legitimas, ficando indisponível por um período de tempo.

Nesse tipo de ataque são usados terminais muitas vezes invadidos por malware, que infectam outros equipamentos conforme tenha acesso, tornando essas máquinas Bot zumbi, essa técnica dificulta ou inviabiliza a correta identificação de quem iniciou o ataque.

Para se proteger desse tipo de ataque é necessário implantar sistemas de mitigação de ataques DDoS, onde normalmente é utilizado os processos de Detecção, Desvio, Filtragem e Análise. 

* Nesse método a fase de detecção realiza a análise na mudança do tráfego, procurando identificar mudança que signifiquem a formação de um ataque DDoS. 
* O Desvio é onde o tráfego é redirecionado do alvo, seja para um IP inexistente ou mesmo descartado. 
* Na filtragem o tráfego é separado para analisar os pacotes e encontrar padrões que diferenciem tráfego legitimo do tráfego malicioso.
* Na última fase que é a análise, os registros são analisados com a intenção de identificar o atacante, assim como estudar o modo de ataque afim de criar novas formas de barrar esse tipo de ataque.

### 2. Por que o firewall é uma ferramenta muito importante de proteção?
O firewall é a principal ferramenta para controle de acesso malicioso em uma rede, cabe a ele analisar tudo o que sai e entra na rede, verificando todos os detalhes como procedência, se é uma resposta a uma solicitação legitima, no firewall ainda podemos estabelecer regras especificas, como por exemplo restringir IPs, quais sites podem ser acessados ou mesmo se o acesso a internet é liberado. Logo o firewall exerce um papel fundamental na segurança da rede.

# Tema: Git e GitHub 
### 3. Explique de forma sucinta, o fluxo e envio de um arquivo novo para o repositório do projeto. 
Para adicionar um arquivo novo ao repositório é necessário executar o comando git add NOME_DO ARQUIVO, ainda é possível usar apenas o ponto final (.) no local do nome para adicionar todos os arquivos da pasta. Já o envio do arquivo é feito utilizando o comando git commit -m “descrição do commit”.

### 4. Descreva sobre os ganhos de se utilizar a funcionalidade da branch do git. 
A utilização do sistema de branchs além de permitir o versionamento da aplicação, permite uma melhor distribuição do trabalho entre os desenvolvedores, permitindo que muitas pessoas trabalhem em um mesmo projeto, assim como testar uma funcionalidade nova, sem gerar qualquer dificuldade para os demais desenvolvedores ou ao projeto. Utilizando as branch é possível trabalhar na mesma branch ou mesmo dividir o trabalho em branchs separadas que são unidas através do merge para enfim gerar o projeto final.

### 5. Explique a diferença entre criar o repositório na nuvem e iniciar o repositório a partir de um código existente local.
A principal diferença entre uma repositório local e uma remoto é que no remoto várias pessoas podem se conectar e enviar suas alterações, já no repositório local somente o usuário daquele máquina pode atualizar o repositório com seus commits, para o trabalho em equipe o repositório remoto é muito mais vantajoso, pois o trabalho de cada um ou o avanço do projeto fica mais evidente, sem contar o fato de poder ter os histórico de mudanças de todos os desenvolvedores, facilitando muito em caso de falhas.
 
### 6. Qual a diferença entre Git e GitHub?
Git é um software livre de versionamento onde é possível salvar estados do projeto, ele permite que salve o arquivo por inteiro ou somente as modificações aplicadas ao arquivo original, ele guarda diversas informações sobre as modificações realizadas, facilitando muito em caso de possível falha e a necessidade de voltar o projeto a um estado anterior.

O GitHub por sua fez é uma plataforma que permite o salvamento e gerenciamento desses arquivos versionados, essa plataforma é muito utilizada pela sua facilidade em compartilhar seu código com outros desenvolvedores, permitindo que outras pessoas possam baixar, testar e até mesmo sugerir mudanças no projeto.

# Tema: Fundamentos de Agilidade: seus primeiros passos para a transformação ágil 
### 7. Quais as principais diferenças entre o modelo ágil e o waterfall (modelo em cascata)? 
O modelo em cascata segue uma sequência específica, só parando ao final da sequência, exige uma planejamento muito bem feito deste o início,  nomeada por W. W. Royce como metodologia estática fluida, essa metodologia tem apenas uma direção e não permite alterações ou correções durante seu fluxo o que para o desenvolvimento de software tornou-se um problema uma vez que essa metodologia independente do que o cliente deseja, uma vez iniciado o projeto ele segue até o fim sem alterações.

Já os modelos ágeis tem como principal objetivo criar valor para o cliente com a ferramenta produzida, no menor tempo possível, de modo geral produz pequenas porções do projeto e faz a entrega dessas partes durante o desenvolvimento para avaliação do cliente, dessa forma qualquer situação em que o cliente entenda que aquela ferramenta não esta como deveria, ela poderá sofrer modificações/correções antes do fim do projeto, nos modelos ágeis o feedback mais rápido do cliente auxilia no desenvolvimento de algo que realmente vai gerar valor, assim como economiza tempo e dinheiro comparado ao modelo em cascata.

### 8. Quais são as 3 perguntas que devem ser respondidas na Daily?
* O que você fez ontem?
* O que você fará hoje?
* Quais problemas enfrentou?

### 9. Qual o intuito das seguintes cerimônias? 
* Daily – É onde o time analisa o avanço na sprint, quais as dificuldades enfrentadas, a daily é uma forma de saber se a sprint está seguindo como planejado ou se esta havendo alguma dificuldade que poderá exigir um pouco mais de tempo.
* Planning – É a reunião inicial da sprint, onde o PO apresenta a lista priorizada do backlog para a equipe, e a partir dela é realizado o planejamento do que irá fazer parte daquela sprint.
* Refinamento – É o que o PO faz com o topo do backlog, para apresentar as histórias na Planning com uma granularidade que permita a equipe de desenvolvimento estimar os prazos para entrega.
* Review – A review é a reunião que em que a equipe apresenta as novas funcionalidades desenvolvidas durante a sprint, nela cliente e se possível o usuário final são convidados a testar as funcionalidades para analisarem se está tudo como deveria.
* Retrospectiva – A reunião de retrospectiva se destina a analisar a sprint que acabou, verificar o que funcionou e os problemas e buscar soluções para que essas questões não ocorram novamente na próxima sprint.

### 10. O que é a estimativa na metodologia ágil? 
A estimativa ágil pode ser usada para analisar a velocidade da equipe, desenvolver previsões, melhorar o refinamento do backlog. Ela serve para dar um valor aos itens do backlog, dessa forma o PO pode fazer uso dela para tomar melhores decisões.

# Tema: Fundamentos HTTP 
### 11. O que é o protocolo HTTP? Qual a diferença entre HTTP e HTTPS?
O HTTP significa protocolo de transferência de hypertexto, esse protocolo é usado para processar, renderizar e disponibilizar páginas web, ele funciona através de solicitações, onde a pessoa ao utilizar o navegador manda uma solicitação seja através de endereço do site como por exemplo digitando Goolge.com, como ao clicar em um link ou botão, ao realizar uma dessas ações essa solicitação é enviada ao servidor, ele recebe, analisa e responde com o recurso solicitado.

A diferença do HTTP para o HTTPS é que o protocolo HTTP por si só, trafega texto, isso quer dizer que ao fazer uma requisição de login em um site que utiliza apenas http seu usuário e senha serão enviados em texto simples, ficando completamente desprotegido para eventuais situações em que seus dados sejam interceptados. Já no HTTPS os dados sensíveis, ou seja, aqueles que não devem estar visíveis, são criptografados e enviados dessa maneira, o navegador e o servidor terão chaves de codificação, sendo a do servidor privada, para que outras pessoas não tenham acesso, dessa forma mesmo que sua conexão seja interceptada seus dados permanecerão em segurança, pois somente com a chave guardada no servidor a pessoa conseguiria quebrar a criptografia e ver os dados.
 
### 12. Cite 4 métodos HTTP. 
* POST
* PUT
* GET
* DELETE
