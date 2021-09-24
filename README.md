# Script para configuração e instalação do CentOS Web Panel

Este script instala e configura o CentOS Web Panel de acordo com as boas práticas recomendadas por **WNPower**

#### Modo de uso:

```sh
wget https://raw.githubusercontent.com/wnpower/CWP-config/master/install_cwp.sh && bash install_cwp.sh
```

###### NOTA: Instale apenas no CentOS 7 Minimal

#### Tarefas que realiza:

- Otimização de configuração de rede
- Configura DNS
- Instala o pacote "Base" e outros mais recomendados
- Instala e configura o Firewall CSF com as configurações recomendadas
- Configura o php.ini com os valores recomendados
- Configura os valores recomendados do MySQL
- Sincroniza a hora do servidor com um servidor NTP
