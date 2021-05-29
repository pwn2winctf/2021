Nos anos que antecederam a Guerra, radioamadores construíram transmissores do tipo *beacon* extremamente sólidos e duráveis. Esses transmissores podem ser ouvidos até hoje nas ondas de rádio que chegam a Rhiza, e estão documentados até mesmo nos livros didáticos do ensino médio!

Estudando os arquivos contidos na cápsula do tempo colocada na ilha pela Telefonica e outras empresas na década de 2020, Laura deparou-se recentemente com uma implementação um tanto curiosa de um transmissor WSPR.

Esse transmissor insere uma segunda modulação por cima do WSPR, quase imperceptível ao olho nu. O indicativo de chamada do autor do código corresponde justamente a uma das estações *beacon* que podem ser ouvidas até hoje. Essa estação está na área onde um dia esteve localizada a Universidade Federal de São Carlos.

Será que esses transmissores podem revelar algo que não é contado pela história oficial do governo? Talvez eles estejam ligados a algum movimento de resistência das pessoas do continente!

Infelizmente, a cápsula do tempo contém apenas o código fonte do codificador. Você consegue implementar o decodificador correspondente? Grave as transmissões de rádio que são emitidas a cada 10 min e forneça-as ao seu decodificador, recuperando o conteúdo do arquivo `flag.txt` do transmissor.

**Nota importante aos competidores de 2021**

Aproveite que o planeta ainda não foi devastado! Existem muitos receptores KiwiSDR, OpenWebRX e WebSDR públicos na internet. Utilize esses receptores para gravar o áudio da transmissão. Você também pode consultar o [histórico da WSPRNet](https://wsprnet.org/olddb?mode=html&band=all&limit=10000&findcall=PU2UID&findreporter=&sort=date) para verificar quais regiões do planeta estão recebendo o sinal em um dado momento, ou programar-se sabendo quais regiões costumam recebê-lo em determinado horário.

Ou simplesmente use um receptor próximo, que deve ser capaz de receber o sinal **a todo momento**: [https://pu2uid.duckdns.org](https://pu2uid.duckdns.org).

Recomendamos que você faça, o mais cedo possível, **pelo menos** 4 gravações do sinal com boa relação sinal ruído (SNR) e com pouco *fading*. Comece a gravar as transmissões mesmo antes de implementar o seu decodificador.

**Autores**: [thotypous](https://github.com/thotypous), [racerxdl](https://github.com/racerxdl)

**Agradecimentos especiais**: [marcoslaerte](https://github.com/marcoslaerte), [nutc4k3](https://github.com/nutc4k3)

[Arquivos](https://static.pwn2win.party/wspr_decoy_0cb92fe3e0a9c2ad6686a06064ceaaacf8884c117ca9d75462f76cb5c0208c6b.tar.gz)

[Mirror](https://drive.google.com/file/d/1mfwQ-grs9AVSQpepBl21Y3EOdb-7fpMC/view?usp=drivesdk)
