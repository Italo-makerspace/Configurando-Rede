# Configurando a Rede no Archer AX6000

Configurar corretamente o roteador Archer AX6000 é fundamental para garantir uma internet rápida, segura e eficiente. A seguir, estão os passos que qualquer pessoa pode seguir para realizar essa configuração com segurança, mesmo sem experiência técnica.

---

## Passo 1 – Acesso ao Painel de Configuração

A primeira ação que a pessoa realiza é conectar o computador ou celular ao roteador, usando cabo ou Wi-Fi. Em seguida, ela abre um navegador e digita o endereço IP padrão do Archer AX6000: `192.168.0.1`.

Na primeira vez que acessa, o roteador pede para criar uma nova senha de administrador. A pessoa escolhe uma senha forte, como `Italo2025!@`, para impedir acessos indesejados ao painel.

Depois de criar a senha, o sistema pergunta o tipo de conexão com a internet. A maioria das operadoras brasileiras usa **IP Dinâmico (Dynamic IP)**, então essa opção é mantida.

---

## Passo 2 – Configuração da Rede Wireless

Com o painel aberto, a pessoa acessa o menu `Wireless > Wireless Settings`. A função **Smart Connect** (que une as redes 2.4GHz e 5GHz em uma só) é desativada para que cada banda seja configurada separadamente.

No campo **SSID** (nome da rede), ela define nomes simples e fáceis de identificar:

- Para 2.4GHz: `Casa_Italo_2G`
- Para 5GHz: `Casa_Italo_5G`

No campo **Password**, ela define uma senha segura para ambas as redes, por exemplo: `SenhaForte2025#`.

Na opção de **segurança (Security)**, seleciona `WPA2-PSK` e criptografia `AES`, a combinação mais segura disponível atualmente.

---

## Passo 3 – Ajustes Avançados de Wireless

A pessoa segue até `Advanced > Wireless > Wireless Advanced` para otimizar o sinal:

- **Modo da rede (Mode)**:
  - 2.4GHz: `802.11ax/n/b/g mixed`
  - 5GHz: `802.11ax/ac/n mixed`

- **Canal (Channel)**:
  - 2.4GHz: seleciona manualmente o canal **3**, para evitar interferência de vizinhos.
  - 5GHz: deixa em **Auto (com DFS ativado)**, permitindo que o roteador escolha os melhores canais automaticamente.

- **Largura de canal (Channel Width)**:
  - 2.4GHz: ajusta para **40 MHz**
  - 5GHz: ajusta para **80 MHz**

- **Potência de transmissão (Transmit Power)**: define como **High**, para garantir o alcance máximo da rede.

> Para exemplificar: canais como 1, 6 e 11 são frequentemente usados, por isso o canal 3 pode reduzir interferências em apartamentos. Já os 80 MHz no 5GHz são ideais para streaming e jogos online, pois permitem maior transferência de dados simultaneamente.

---

## Passo 4 – Proteção Contra Acessos Não Autorizados

A pessoa acessa `Advanced > System Tools > Administration` para garantir a segurança do painel. Ali, ela verifica se a senha de administrador está atualizada e difícil de ser adivinhada.

Em seguida, vai em `Advanced > Wireless > WPS` e **desativa o WPS**, um recurso que facilita conexões mas representa risco de invasão.

Depois, acessa `Security > Remote Management` e garante que a opção **Disable** esteja marcada. Isso bloqueia tentativas de configuração remota não autorizada.

---

## Passo 5 – Atualização e Backup

No menu `System Tools > Firmware Upgrade`, a pessoa clica em **Check for Upgrade Online**. Se houver uma versão mais nova do firmware, a atualização é realizada. Isso garante mais segurança e estabilidade.

Em `System Tools > Backup & Restore`, ela clica em **Backup** e salva o arquivo de configuração. Esse arquivo pode ser restaurado caso o roteador seja resetado no futuro.

---

## Passo 6 – Qualidade de Conexão e Prioridade

Por fim, a pessoa acessa `Advanced > QoS (Qualidade de Serviço)`. Ela ativa o modo **By Device** e seleciona quais dispositivos devem ter prioridade — como o notebook usado para estudos e o console de videogame. Assim, mesmo com outras pessoas assistindo vídeos, esses aparelhos terão a melhor conexão.

Também ativa a função **Airtime Fairness**, que impede que aparelhos lentos prejudiquem o desempenho dos outros dispositivos.

---

> Com essas etapas, a rede foi configurada com segurança, eficiência e estabilidade. Os canais e larguras foram ajustados para reduzir interferências, e a proteção contra acessos indevidos foi reforçada.
