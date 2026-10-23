<p align="center">
  <img src="winai-logo.png" alt="WINAI" width="140">
</p>

<h1 align="center">WINAI Gestão Integrada</h1>

<p align="center">
  Plataforma web de gestão para redes de lojas integrada ao ERP <b>Winthor</b>:
  pedidos, devoluções, transferências, inventário, metas, preços, etiquetas, faturamento automático e WhatsApp
  em um só sistema, para todas as filiais.
</p>

---

## Por que o WINAI

- **Tudo em um lugar**: as rotinas do dia a dia da loja e da gestão ficam em uma única tela web, sem instalar nada
  nas máquinas. Funciona no computador, no tablet e no celular (pode ser instalado como aplicativo).
- **Direto no Winthor**: lê e grava nas mesmas tabelas do ERP, seguindo as regras das rotinas originais
  (pedido 316, devolução 1360, transferência 1124, política de preço 357...). Não há base paralela nem
  sincronização.
- **Mesmo acesso do Winthor**: o login é o usuário e a senha do Winthor e cada tela respeita as permissões de rotina
  já cadastradas para o usuário.
- **Automação**: faturamento de pedidos, ajuste de estoque e avisos por WhatsApp rodam sozinhos, configurados por
  filial.
- **Seguro**: sessão com expiração por inatividade, acesso por perfil e por rotina, terminais públicos com link
  próprio, histórico de operações, auditoria dos logins e bloqueio de IP.

---

## Módulos

| Módulo | O que faz |
| ------ | --------- |
| **Pedidos** | Pedido de venda completo (com leitor de código de barras), orçamentos, desconto em pedido, pesquisa com exportação em PDF, Excel e CSV |
| **Devolução** | Devolução de cupom fiscal com nota de entrada, estoque, estorno de comissão e crédito do cliente, como na rotina 1360 |
| **Faturamento automático** | Fatura os pedidos liberados das filiais configuradas, confere a nota, ajusta estoque quando falta saldo e avisa no WhatsApp |
| **Transferências** | Transferência entre filiais, conferência da transferência e do bônus |
| **Inventário** | Contagem e gestão do inventário |
| **Metas** | Cadastro e configuração de metas por vendedor, supervisor, gerente e comprador, com relatório de acompanhamento |
| **Produtos e preços** | Consulta de produtos, política de preço fixo, emissão de etiquetas (impressoras Zebra ou a impressora do navegador) com oferta De/Por |
| **Consulta de preço** | Terminais nas lojas com leitor de código de barras, preço por loja e propagandas em tela cheia |
| **Relatórios** | Vendas e faturamento por filial, supervisor e vendedor; relatório de metas; PIX |
| **WhatsApp** | Conexão das contas e disparos automáticos de mensagens |
| **PIX** | Cobrança PIX com QR Code, baixa automática de títulos, devolução com aprovação e integração com o caixa |
| **Integrações** | OTO CRM: envio diário das vendas e cadastros ao CRM, com histórico e recuperação de dias perdidos |
| **Hub de integração** *(em elaboração)* | Integração do Winthor com marketplaces e hubs de e-commerce |

---

## Telas

> Capturas feitas em ambiente de homologação. Os dados de clientes e valores aparecem desfocados de propósito.

### Acesso

Login com o usuário e a senha do Winthor.

![Login](telas/27-login.jpg)

### Painel inicial

![Dashboard](telas/01-dashboard.jpg)

### Pedidos

**Novo pedido**: vendedor, cliente com limite de crédito, itens por código, leitor de código de barras ou câmera, e
fechamento como pedido ou orçamento na mesma tela.

![Novo Pedido](telas/04-novo-pedido.jpg)

<table>
  <tr>
    <td width="50%"><b>Pesquisar pedidos</b><br><img src="telas/06-pesquisar-pedidos.jpg" alt="Pesquisar Pedidos"></td>
    <td width="50%"><b>Pesquisar orçamentos</b><br><img src="telas/07-pesquisar-orcamentos.jpg" alt="Pesquisar Orçamentos"></td>
  </tr>
  <tr>
    <td><b>Lançar desconto em pedido</b><br><img src="telas/05-desconto-pedido.jpg" alt="Lançar Desconto em Pedido"></td>
    <td><b>Devolução de cupom fiscal</b><br><img src="telas/08-devolucao-cupom.jpg" alt="Devolução de Cupom Fiscal"></td>
  </tr>
</table>

### Faturamento automático

Configuração por filial, situação do agendador, histórico, ajustes de estoque e faturamento manual de um pedido.

![Faturamento Automático](telas/09-faturamento-automatico.jpg)

### Clientes e produtos

<table>
  <tr>
    <td width="50%"><b>Cadastro de cliente</b><br><img src="telas/02-clientes.jpg" alt="Clientes"></td>
    <td width="50%"><b>Pesquisar produtos</b><br><img src="telas/19-pesquisar-produtos.jpg" alt="Pesquisar Produtos"></td>
  </tr>
  <tr>
    <td colspan="2"><b>Política de preço fixo</b><br><img src="telas/21-politica-preco-fixo.jpg" alt="Política de Preço Fixo"></td>
  </tr>
</table>

### Etiquetas

Modelos de etiqueta montados em editor visual e impressos em impressoras Zebra, com oferta De/Por. Sem a Zebra, as
mesmas etiquetas saem na impressora comum pelo navegador, uma página do tamanho do modelo para cada etiqueta, com o
código de barras de verdade.

![Etiquetas](telas/20-etiquetas.jpg)

<table>
  <tr>
    <td width="50%"><b>Impressora do navegador</b>: destino da impressão na aba F7<br><img src="telas/52-etiquetas-impressao-navegador.jpg" alt="Etiquetas pela impressora do navegador"></td>
    <td width="50%"><b>Pré-visualização</b>: as etiquetas antes de imprimir<br><img src="telas/53-etiquetas-previa.jpg" alt="Pré-visualização das etiquetas"></td>
  </tr>
</table>

### Consulta de preço nas lojas

Um computador, TV ou tablet com leitor de código de barras vira terminal de consulta: abre um link próprio da loja,
sem login, e mostra as propagandas da loja em tela cheia. Ao passar um produto no leitor, aparecem a foto e os preços
para empresa (CNPJ) e para consumidor (CPF), e depois a tela volta às propagandas.

<table>
  <tr>
    <td width="50%"><b>Terminal aguardando leitura (propagandas)</b><br><img src="telas/29-terminal-consulta-preco.jpg" alt="Terminal de consulta de preço com propaganda"></td>
    <td width="50%"><b>Produto consultado</b><br><img src="telas/30-terminal-consulta-preco-produto.jpg" alt="Terminal de consulta de preço com produto"></td>
  </tr>
  <tr>
    <td colspan="2"><b>Gestão dos terminais e das propagandas</b>: cadastro por loja, link de acesso e envio das imagens<br><img src="telas/22-terminais-consulta-preco.jpg" alt="Terminais de Consulta de Preço"></td>
  </tr>
</table>

### Transferências

<table>
  <tr>
    <td width="50%"><b>Nova transferência</b><br><img src="telas/10-nova-transferencia.jpg" alt="Nova Transferência"></td>
    <td width="50%"><b>Pesquisar transferências</b><br><img src="telas/11-pesquisar-transferencia.jpg" alt="Pesquisar Transferência"></td>
  </tr>
  <tr>
    <td><b>Conferência de transferência</b><br><img src="telas/12-conferencia-transferencia.jpg" alt="Conferência de Transferência"></td>
    <td><b>Conferência de bônus</b><br><img src="telas/13-conferencia-bonus.jpg" alt="Conferência de Bônus"></td>
  </tr>
</table>

### Inventário

<table>
  <tr>
    <td width="50%"><b>Inventário</b><br><img src="telas/14-inventario.jpg" alt="Inventário"></td>
    <td width="50%"><b>Gestão do inventário</b><br><img src="telas/15-gestao-inventario.jpg" alt="Gestão do Inventário"></td>
  </tr>
</table>

### Metas

<table>
  <tr>
    <td width="50%"><b>Cadastrar meta</b><br><img src="telas/16-cadastrar-meta.jpg" alt="Cadastrar Meta"></td>
    <td width="50%"><b>Pesquisar metas</b><br><img src="telas/17-pesquisar-meta.jpg" alt="Pesquisar Meta"></td>
  </tr>
  <tr>
    <td><b>Configuração de metas</b><br><img src="telas/18-configuracao-metas.jpg" alt="Configuração de Metas"></td>
    <td><b>Relatório de metas</b><br><img src="telas/24-relatorio-metas.jpg" alt="Relatório de Metas"></td>
  </tr>
</table>

### Vendas

![Vendas](telas/23-vendas.jpg)

### WhatsApp

<table>
  <tr>
    <td width="50%"><b>Conexão das contas</b><br><img src="telas/25-whatsapp-conexao.jpg" alt="Conexão WhatsApp"></td>
    <td width="50%"><b>Disparos automáticos</b><br><img src="telas/26-whatsapp-disparos.jpg" alt="Disparos Automáticos"></td>
  </tr>
</table>

### PIX

Cobrança PIX integrada ao banco (Santander; preparado para outros bancos), com os dados gravados no próprio banco do
Winthor e o certificado digital que a filial já usa na nota fiscal. Validado com pagamento e devolução reais no banco.

- **Configuração por filial**: banco, chave PIX e credenciais; o aviso de pagamento do banco (webhook) é cadastrado
  sozinho, com um endereço próprio para cada filial.
- **Emitir PIX**: QR Code para pedido do balcão, título a receber ou valor avulso; pago, o título é baixado no Winthor.
- **Relatório PIX**: cobranças, recebimentos e devoluções, com exportação para o Excel; devolução só com aprovação de
  um responsável, e o estorno da baixa do título quando a devolução é total.
- **Caixa**: o frente de caixa do Winthor cobra PIX pelo WINAI, que confirma o pagamento e emite os comprovantes.
- **Ajuda na tela**: o botão **?** de cada tela explica, em poucos passos, como a funcionalidade funciona.

**Emitir PIX**: QR Code e copia-e-cola na hora; a tela confere o pagamento sozinha.

![Emitir PIX](telas/32-emitir-pix.jpg)

<table>
  <tr>
    <td width="50%"><b>Cobrança de título a receber</b>: busca pelo cliente ou pela duplicata<br><img src="telas/36-emitir-pix-titulo.jpg" alt="Emitir PIX de título"></td>
    <td width="50%"><b>PIX recebido</b>: confirmado na tela; título pago é baixado no Winthor<br><img src="telas/37-emitir-pix-paga.jpg" alt="PIX pago"></td>
  </tr>
  <tr>
    <td><b>Relatório PIX</b>: totais, devoluções aguardando aprovação e exportação<br><img src="telas/33-relatorio-pix.jpg" alt="Relatório PIX"></td>
    <td><b>Detalhe da cobrança</b>: situação, devoluções e histórico<br><img src="telas/38-relatorio-pix-detalhe.jpg" alt="Detalhe da cobrança PIX"></td>
  </tr>
  <tr>
    <td><b>Pedido de devolução</b>: vai ao banco só depois da aprovação<br><img src="telas/39-relatorio-pix-devolucao.jpg" alt="Pedir devolução do PIX"></td>
    <td><b>Devolvida</b>: histórico com o pedido, a aprovação e a confirmação do banco<br><img src="telas/40-relatorio-pix-detalhe-devolvida.jpg" alt="Cobrança PIX devolvida"></td>
  </tr>
  <tr>
    <td><b>Configuração PIX</b>: banco, chave, certificado e webhook por filial<br><img src="telas/31-configuracao-pix.jpg" alt="Configuração PIX"></td>
    <td><b>PIX da filial</b>: credenciais, validade do QR, webhook e conta da baixa<br><img src="telas/35-configuracao-pix-filial.jpg" alt="Configuração PIX da filial"></td>
  </tr>
  <tr>
    <td colspan="2"><b>Botão "?"</b>: explicação da tela em poucos passos<br><img src="telas/34-ajuda-pix.jpg" alt="Ajuda da Emissão de PIX"></td>
  </tr>
</table>

### Integração OTO CRM

Todo dia o WINAI manda ao OTO CRM as vendas do dia anterior das filiais ligadas, com os cadastros que elas usam
(lojas, vendedores, produtos, clientes, pedidos e itens), substituindo os fluxos do n8n:

- **Configuração na tela**: token guardado criptografado, janela do envio automático, filiais com o código da loja no
  OTO e resumo no WhatsApp.
- **Nada se perde**: cada dia e entidade fica no histórico com o retorno do OTO; o que falhou é tentado de novo e os
  dias que ficaram para trás são recuperados.
- **Dados completos**: notas canceladas depois da venda e devoluções também vão ao OTO.
- **Prévia e envio de um dia**: quantos registros iriam, sem enviar, e o envio à mão de qualquer dia.

Validada em produção com a carga de 01 a 09/10/2026: 54 envios, 9.519 registros aceitos pelo OTO.

<table>
  <tr>
    <td width="50%"><b>OTO CRM</b>: conexão, filiais e histórico dos envios<br><img src="telas/41-oto-crm.jpg" alt="OTO CRM"></td>
    <td width="50%"><b>Botão "?"</b>: como funciona a integração<br><img src="telas/42-oto-crm-ajuda.jpg" alt="Ajuda do OTO CRM"></td>
  </tr>
</table>

### Controle de acesso

Quem entra, de onde e quanto cada loja usa o sistema, numa tela só (Auditoria):

- **Tentativas de login** com IP, país e a intenção provável (erro de digitação, usuário inexistente, força bruta,
  robôs), além dos logins com sucesso.
- **Bloqueio de IP**: 10 falhas do mesmo IP em 15 minutos bloqueiam o IP por 60 minutos; IPs ou faixas bloqueados ou
  liberados à mão, com prazo e motivo; rede interna nunca é bloqueada.
- **Fora do Brasil**: o país vem da lista pública de faixas da LACNIC; primeiro só registra e, depois de conferidos os
  IPs das lojas, passa a barrar acessos de fora do país.
- **Uso por loja ou por usuário**: acessos, orçamentos, pedidos e pedidos completos no período, com o valor.

<table>
  <tr>
    <td width="50%"><b>Auditoria</b>: uso por loja, tentativas de login e IPs<br><img src="telas/63-auditoria.jpg" alt="Auditoria"></td>
    <td width="50%"><b>Bloqueio de IP</b>: IP ou faixa bloqueado com prazo e motivo<br><img src="telas/65-auditoria-ip-bloqueado.jpg" alt="Auditoria - IP bloqueado"></td>
  </tr>
</table>

---

## Em elaboração

### Frente de caixa

Caixa no navegador com a mesma lógica da rotina 2075 do Winthor, para o operador que já conhece o PDV:

- **Movimento do caixa e do operador**, suprimento, sangria e fechamento (cego conforme o parâmetro da filial),
  gravados nas mesmas tabelas da 2075, para o acerto da rotina 410 enxergar o caixa web como os PDVs. Um movimento por
  dia, um operador por vez: queda de energia ou aba fechada retomam o turno; o operador reabre o próprio turno no mesmo
  dia; o que ficar aberto na virada do dia é encerrado sozinho para o acerto na 410.
- **Venda pelas teclas da 2075**: A inicia (cliente e vendedor), leitor de código de barras ou R para consultar,
  F2 cancela item, F5 cancela a venda (com o caixa livre, o último cupom, pelo fiscal), T mostra as teclas — e clicar na
  tecla executa o atalho.
- **Fechamento (F1)** pelas finalizadoras da filial: dinheiro com troco, cartão com a bandeira, PIX loja; F salva e a
  venda vira pedido no Winthor.
- **NFC-e emitida pelo próprio WINAI** (validada na homologação em GO e no DF, pela SEFAZ da UF da filial): mesma montagem do PDV a partir do
  cadastro do Winthor (tributação, IBS/CBS da reforma), número na série do caixa, DANFE de 80 mm, cancelamento pelo
  fiscal com motivo (cancela também a venda e o pedido), contingência offline quando a SEFAZ não responde e catálogo
  das rejeições com a orientação de correção.

Em andamento: piloto da NFC-e em produção, PIX com QR Code no caixa, importação de orçamentos e envio do cupom por
e-mail e WhatsApp.

<table>
  <tr>
    <td width="50%"><b>Venda</b>: descrição, código, cupom e totais<br><img src="telas/46-frente-caixa-venda.jpg" alt="Frente de caixa - venda"></td>
    <td width="50%"><b>Fechamento (F1)</b>: pagamentos, troco e falta<br><img src="telas/48-frente-caixa-fechamento.jpg" alt="Frente de caixa - fechamento"></td>
  </tr>
  <tr>
    <td><b>Manutenção do caixa</b>: movimento do caixa e do operador<br><img src="telas/45-frente-caixa-manutencao.jpg" alt="Frente de caixa - manutenção"></td>
    <td><b>Consulta de produto (R)</b>: preço da região e estoque<br><img src="telas/47-frente-caixa-consulta-produto.jpg" alt="Frente de caixa - consulta de produto"></td>
  </tr>
  <tr>
    <td><b>Fechamento cego</b>: valor contado de cada cobrança<br><img src="telas/49-frente-caixa-fechamento-cego.jpg" alt="Frente de caixa - fechamento cego"></td>
    <td><b>Teclas de acesso (T)</b>: o padrão da 2075; clicar na tecla executa o atalho<br><img src="telas/50-frente-caixa-teclas.jpg" alt="Frente de caixa - teclas"></td>
  </tr>
  <tr>
    <td><b>Pedidos do caixa (P)</b>: pedido de cada venda, reimpressão e cupons cancelados<br><img src="telas/55-frente-caixa-pedidos-turno.jpg" alt="Frente de caixa - pedidos do caixa"></td>
    <td><b>NFC-e da filial</b>: ambiente, CSC, teste da SEFAZ e catálogo de rejeições<br><img src="telas/60-configuracao-caixa-nfce.jpg" alt="NFC-e da filial"></td>
  </tr>
  <tr>
    <td><b>Cancelar cupom (F5)</b>: com o caixa livre, o último cupom, com senha do fiscal e motivo<br><img src="telas/57-frente-caixa-cancelar-cupom.jpg" alt="Frente de caixa - cancelar cupom"></td>
    <td></td>
  </tr>
  <tr>
    <td><b>DANFE NFC-e</b> (homologação): cupom de 80 mm com QR Code<br><img src="telas/61-danfe-nfce.jpg" alt="DANFE NFC-e" width="260"></td>
    <td><b>DANFE em contingência</b>: emitido sem a SEFAZ e transmitido depois<br><img src="telas/62-danfe-nfce-contingencia.jpg" alt="DANFE NFC-e em contingência" width="260"></td>
  </tr>
  <tr>
    <td colspan="2"><b>Configuração do caixa</b>: caixa web na PCCAIXA, série da NFC-e, região e banco da sangria<br><img src="telas/51-configuracao-caixa.jpg" alt="Configuração do caixa"></td>
  </tr>
</table>

### Hub de integração com marketplaces

Integração do Winthor com hubs e marketplaces de e-commerce, começando pela **Magis5**, configurada por filial dentro
do WINAI:

- envio de produtos, preços e estoque;
- recebimento dos pedidos dos marketplaces no Winthor;
- envio do XML da nota fiscal;
- chaves de acesso guardadas criptografadas e histórico de cada sincronização.

A comunicação com a Magis5 já foi validada de ponta a ponta. A tela de configuração está pronta (menu Integrações,
ao lado do OTO CRM) e as rotinas de sincronização estão em desenvolvimento.

<table>
  <tr>
    <td width="50%"><b>Hub de Integração</b>: situação do servidor, filiais e histórico<br><img src="telas/43-hub-integracao.jpg" alt="Hub de Integração"></td>
    <td width="50%"><b>Filial no hub</b>: chave da API, modo teste, fluxos e regras<br><img src="telas/44-hub-integracao-filial.jpg" alt="Filial no Hub de Integração"></td>
  </tr>
</table>

---

## Tecnologia

Aplicação web em **Java 21** com **Spring Boot**, telas em **Jakarta Faces** com **PrimeFaces**, banco **Oracle**
(o mesmo do Winthor) e implantação em **Apache Tomcat**. A estrutura do banco é versionada com **Flyway** e a
aplicação tem testes automatizados que rodam a cada versão gerada.

---

## Sobre este repositório

Este repositório apresenta o projeto: descrição e telas. O código-fonte é privado.

Interesse em conhecer ou implantar o WINAI? Abra uma
[issue](https://github.com/jonales/winai-apresentacao/issues) neste repositório.

---

<p align="center">
  <b>WINAI Gestão Integrada</b> — desenvolvido por <b>4C3RT0 Sistemas</b><br>
  © 2025-2026 — Todos os direitos reservados
</p>
