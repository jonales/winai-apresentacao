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
  próprio e histórico de operações.

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
| **Produtos e preços** | Consulta de produtos, política de preço fixo, emissão de etiquetas (impressoras Zebra) com oferta De/Por |
| **Consulta de preço** | Terminais nas lojas com leitor de código de barras, preço por loja e propagandas em tela cheia |
| **Relatórios** | Vendas e faturamento por filial, supervisor e vendedor; relatório de metas; PIX |
| **WhatsApp** | Conexão das contas e disparos automáticos de mensagens |
| **PIX** *(em elaboração)* | Cobrança PIX com QR Code e relatório das vendas pagas por PIX |
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

Modelos de etiqueta montados em editor visual e impressos em impressoras Zebra, com oferta De/Por.

![Etiquetas](telas/20-etiquetas.jpg)

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

---

## Em elaboração

### PIX

Cobrança PIX integrada ao banco (Santander), com os dados gravados no próprio banco do Winthor:

- emissão do QR Code de cobrança pela tela;
- confirmação do pagamento devolvida ao PDV;
- relatório das vendas recebidas por PIX.

As telas *Emitir PIX* e *Relatório PIX* já estão no menu e serão liberadas quando a integração estiver concluída.

### Hub de integração com marketplaces

Integração do Winthor com hubs e marketplaces de e-commerce, começando pela **Magis5**, configurada por filial dentro
do WINAI:

- envio de produtos, preços e estoque;
- recebimento dos pedidos dos marketplaces no Winthor;
- envio do XML da nota fiscal;
- chaves de acesso guardadas criptografadas e histórico de cada sincronização.

A comunicação com a Magis5 já foi validada de ponta a ponta. A tela de configuração está pronta e as rotinas de
sincronização estão em desenvolvimento.

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
