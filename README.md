# SmartPlace
## Projeto acadêmico
 > Disciplina Arquitetura de Software 2022.2 BTI-UFRN. 
 
 O projeto é um sistema para controle de ambientes (SmartPlace) tem como objetivo monitorar arcondicionados e lâmpadas de um ambiente e liga-los quando houver pessoas no ambiente e desliga-los quando não tiver mais ninguém. Além disso, deve aumentar e diminuir a temperatura do arcondicionado de acordo com a temperatura desejada pelo usuário, estabelecida em um leitor na entrada da sala.


## Componentes
- Sensores de temperatura;
- Sensor de presença;
- Câmera para confirmar a presença de pessoas, contando o número de pessoas que tem na sala;
- Leitor da temperatura desejada.

### Cenários que descrevem o uso
1. Ao entrar alguém na sala, o arcondionado deve ser ligado, com temperatura estabelecida no leitor, e as luzes devem ser acesas;
2. Se o usuário alterar a temperatura, o sistema deve aumentar ou diminuir a temperatura do arcondicionado;
3. O sistema deve exibir, em sua interface web, o status dos arcondicionados das salas, bem como a presença de pessoas.
