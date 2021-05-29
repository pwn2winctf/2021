Encontramos esse servidor do governo de Rhiza, que é muito esquisito, e precisamos muito acessá-lo! Ele roda um emulador de Apple II e aceita códigos em Applesoft BASIC. Se o resultado do seu código gerar um QR Code padrão válido (não um micro QR), ele será lido e o conteúdo será executado como um comando shell no sistema Linux. Um jeito muito interessante de interagir com um servidor, você não acha?

Siga as diretrizes abaixo:

* Tamanho máximo do payload: 268 chars (ele será truncado aí)
* Envie em somente uma linha (somente caracteres printáveis). Se houver quebra de linha, substitua pelo símbolo § (é permitido apenas um deles)
* Apenas QR Code tradicional é aceito, **não micro QR**
* Seu código pode demorar até 50 segundos pra ser desenhado, antes da verificação do QR Code ocorrer
* Em caso de dúvidas, consulte o código fonte do server dentro do container

Estamos disponibilizando duas opções para você poder **rodar localmente e fazer seus testes**.

**Docker:**

    $ docker-compose up
    $ nc localhost 1337

[Docker Files](https://static.pwn2win.party/oldschool_adventures_appleii_0cd428eea828e4712ef92a1075a2c6718b6032f75bb0ce0fcaa514049fcb1b57_docker.tar.gz)

**Container LXC:**

    $ lxd init e alguns <Enters> (se você nunca usou isso antes)
    $ lxc image import <name>.tar.gz --alias oldschool
    $ lxc launch oldschool oldschool
    $ lxc list (pra pegar o IP)
    $ nc IP 1337
    
[LXC Files](https://static.pwn2win.party/oldschool_adventures_appleii_079445b87c7d73778b8c149d5ecf16aea09b3cd0282ce0dbc91ab3dd1891771a_lxc.tar.gz)

[LXC Mirror](https://drive.google.com/file/d/1kIRwf_H6d9eKZ7pwvVjl5ThK9mt4xUYG/view?usp=drivesdk)

**Server:** nc oldschool.pwn2win.party 1337

