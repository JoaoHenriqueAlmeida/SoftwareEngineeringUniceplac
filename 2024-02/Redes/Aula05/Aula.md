# Redes aula 05

- Endereço IP é uma identificação numérica atribuída a cada dispositivo conectado em uma rede que utiliza o protocolo IP.

- Existem dois tipos de endereços IP em uso atualmente: IPv4 e IPv6.

## IPv4

- Um endereço IPv4 é composto por 32 bits, divididos em quatro partes chamadas octetos, separadas por pontos.
- Cada octeto contém 8 bits, totalizando 32 bits ou 4 bytes.
- O formato do IPv4 é representado na forma decimal, onde cada número no endereço é a conversão de um conjunto de 8 bits (um byte) em decimal.

- Cada octeto tem 8 bits, e um endereço IPv4 completo tem 4 octetos ou 32 bits. Cada octeto tem 8 bits, e um endereço IPv4 completo tem 4 octetos ou 32 bits.

### Classes IPv4

- Classe A: Endereços de 0.0.0.0 a 127.255.255.255 (grandes redes).
- Classe B: Endereços de 128.0.0.0 a 191.255.255.255 (redes de médio porte).
- Classe C: Endereços de 192.0.0.0 a 223.255.255.255 (pequenas redes).

- Endereços Privados: Faixas de IP reservadas para redes internas (não roteáveis na Internet):
  - Classe A: 10.0.0.0 a 10.255.255.255
  - Classe B: 172.16.0.0 a 172.31.255.255
  - Classe C: 192.168.0.0 a 192.168.255.255

### Quatro tipos de endereços de IP

**Publica** - Tem que ser visível para todos na rede. Ele é atribuído pelo ISP (provedor de Internet). Permite que dispositivos se comuniquem diretamente com outros dispositivos.Usado para identificar um dispositivo de forma única.

**Privada** - Utilizado dentro de uma LAN e não visível na Internet.
Faixas de IP privado - Classe A: 10.0.0.0 a 10.255.255.255 - Classe B: 172.16.0.0 a 172.31.255.255 - Classe C: 192.168.0.0 a 192.168.255.255

Uso: Dispositivos em uma rede local, como computadores,
impressoras e telefones, recebem IPs privados. Um roteador
pode ter um IP público e atribuir IPs privados aos dispositivos
internos.

**Estático** - Um endereço IP estático é um endereço IP que não muda.
Ele é atribuído manualmente a um dispositivo e permanece
o mesmo até que seja alterado.

É comum em servidores, impressoras e outros dispositivos
que precisam de um endereço IP fixo para funcionar
corretamente. Por exemplo, servidores de web precisam de
um IP estático para que possam ser acessados
consistentemente na Internet.

**Dinâmica** - Um endereço IP dinâmico é atribuído automaticamente a
um dispositivo por um servidor DHCP (geralmente um
roteador ou um servidor de provedor de Internet). Ele muda
sempre que o dispositivo se conecta ou após um
determinado período de tempo.

Uso: A maioria dos dispositivos conectados à Internet ou a
redes locais usa endereços IP dinâmicos, que são
temporários e reutilizados por outros dispositivos quando
não estão mais em uso.

### IPv6
