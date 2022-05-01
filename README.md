# Avaliação Compass

# Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes 
1. 
O que é um ataque DDoS e como posso me proteger? 
O ataque DDoS é um ataque de negação, onde o invasor visa sobrecarregar o servidor com tráfego de internet falso, dessa forma o servidor sobrecarregado deixa de responder as conexões legitimas, ficando indisponível por um período de tempo.

Nesse tipo de ataque são usados terminais muitas vezes invadidos por malware, que infectam outros equipamentos conforme tenha acesso, tornando essas máquinas Bot zumbi, essa técnica dificulta ou inviabiliza a correta identificação de quem iniciou o ataque.

Para se proteger desse tipo de ataque é necessário implantar sistemas de mitigação de ataques DDoS, onde normalmente é utilizado os processos de Detecção, Desvio, Filtragem e Análise. 

* Nesse método a fase de detecção realiza a análise na mudança do tráfego, procurando identificar mudança que signifiquem a formação de um ataque DDoS. 
* O Desvio é onde o tráfego é redirecionado do alvo, seja para um IP inexistente ou mesmo descartado. 
* Na filtragem o tráfego é separado para analisar os pacotes e encontrar padrões que diferenciem tráfego legitimo do tráfego malicioso.
* Na última fase que é a análise, os registros são analisados com a intenção de identificar o atacante, assim como estudar o modo de ataque afim de criar novas formas de barrar esse tipo de ataque.

2. 
Por que o firewall é uma ferramenta muito importante de proteção?
O firewall é a principal ferramenta para controle de acesso malicioso em uma rede, cabe a ele analisar tudo o que sai e entra na rede, verificando todos os detalhes como procedência, se é uma resposta a uma solicitação legitima, no firewall ainda podemos estabelecer regras especificas, como por exemplo restringir IPs, quais sites podem ser acessados ou mesmo se o acesso a internet é liberado. Logo o firewall exerce um papel fundamental na segurança da rede.