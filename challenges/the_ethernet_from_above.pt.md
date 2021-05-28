A maioria das atividades obscuras do governo de Rhiza é realizada no continente, para ficar longe dos olhos da população comum da Ilha e evitar vazamento de informações. No entanto, os prédios da Ilha que abrigam material potencialmente comprometedor, como o centro de genética humana, contam com um rígido sistema de controle de acesso.

Laura conseguiu comprometer alguns computadores do laboratório do governo que desenvolve esse sistema. Ao analisar o projeto, ela constatou que o ponto mais fraco parece ser a placa eletrônica que verifica se o código de acesso aos prédios está correto. Não há nada de especial na placa em si: trata-se de uma Colorlight 5A-75B V7.0 que, aparentemente, podia ser encontrada muito facilmente antes da Guerra. O que é interessante é o bitfile gravado na placa, que é desenvolvido pelo laboratório do governo.

Laura conseguiu acesso ao bitfile que o laboratório está testando. De acordo com o documento de especificações que acompanhava esse bitfile, após ser conectada à rede, a placa pode ser acessada pelo endereço IP 200.18.104.100, na porta UDP 6000. Ao receber o código de acesso correto, ela retorna um datagrama iniciado por `OK`. Caso contrário, retorna `NOK`. O projeto aparentemente é baseado em uma versão customizada do LiteEth, mas Laura não conseguiu obter acesso ao código fonte completo.

Faça engenharia reversa no bitfile para descobrir qual código de acesso é aceito pela placa.

**Curiosidade**: Se você não possuir uma Colorlight e quiser ver o bitfile funcionando, pode submetê-lo para a [infraestrutura de testes de Rhiza](https://fpga.pwn2.win). Mas isso provavelmente não vai te ajudar a resolver o desafio. Você precisa realmente fazer engenharia reversa no bitfile.

**Autores**: [racerxdl](https://github.com/racerxdl), [thotypous](https://github.com/thotypous)

[Arquivos](https://static.pwn2win.party/the_ethernet_from_above_2d0cc1b5cf46f22db915d2cd11107f44b1914b5b598516a58ece25c97fcdc916.tar.gz)

[Mirror](https://drive.google.com/file/d/1SL62dGFCpsZ8vP-kVa-rVbSOrXYuke2F/view?usp=drivesdk)
