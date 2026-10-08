# PlayStation Subscription Dashboard 🎮

Projeto de análise e visualização de dados desenvolvido no **Excel para a Web**, com uma base demonstrativa de assinaturas inspirada no ecossistema PlayStation. O objetivo é organizar informações de assinantes, resumir indicadores por plano e tipo de assinatura e apresentá-los em um dashboard visual.

> **Nota:** os dados deste arquivo devem ser tratados como dados demonstrativos. Antes de publicar ou reutilizar a planilha em outro contexto, confira se todos os registros e nomes podem ser divulgados.

## 📊 Visão geral

A pasta de trabalho está organizada em quatro abas:

- **Assets** — reúne a paleta de cores e recursos visuais utilizados no projeto, como logos e ícones.
- **Bases** — contém a tabela principal de assinaturas, com **293 registros** e 13 colunas.
- **Cálculos** — concentra tabelas-resumo usadas para analisar a quantidade de assinaturas e os valores por plano.
- **Dashboard** — apresenta gráficos e indicadores resumidos para facilitar a leitura dos resultados.

## 🧾 Dados da base

A tabela principal contém os seguintes campos:

| Campo | Descrição |
|---|---|
| `Subscriber ID` | Identificador do assinante |
| `Name` | Nome associado ao registro |
| `Plan` | Plano contratado: Essential, Extra ou Premium |
| `Start Date` | Data de início da assinatura |
| `Auto Renewal` | Indica se a renovação automática está ativada |
| `Subscription Price` | Preço informado para a assinatura |
| `Subscription Type` | Periodicidade: Monthly, Quarterly ou Annual |
| `EA Play Season Pass` | Indica a presença do adicional EA Play |
| `EA Play Season Pass Price` | Preço associado ao adicional EA Play |
| `Minecraft Season Pass` | Indica a presença do adicional Minecraft |
| `Minecraft Season Pass Price` | Preço associado ao adicional Minecraft |
| `Coupon Value` | Valor de cupom informado |
| `Total Value` | Valor total calculado para o registro |

Os resumos permitem comparar a quantidade de assinaturas por plano e periodicidade, além dos valores agrupados por plano e tipo de assinatura.

## 📈 O dashboard

O dashboard foi criado para oferecer uma visão rápida dos dados, incluindo:

- comparação entre planos;
- distribuição das assinaturas por periodicidade;
- totais consolidados;
- gráficos para apoiar a interpretação dos indicadores.

Os números exibidos representam os dados presentes na própria planilha e não devem ser interpretados como estatísticas oficiais da PlayStation.

## 🎨 Identidade visual e uso de IA

A aba **Assets** registra cores e elementos gráficos usados na composição visual. A paleta foi organizada para manter uma aparência inspirada na identidade visual PlayStation.

**O ícone da personagem utilizado no projeto foi criado com inteligência artificial (IA).** Ele é um recurso visual do projeto e não representa uma personagem oficial da PlayStation, salvo indicação explícita em contrário. Marcas e referências visuais de terceiros pertencem aos seus respectivos titulares.

## 🛠️ Ferramenta utilizada

O projeto foi elaborado no **Microsoft Excel para a Web**, acessado pelo navegador. A versão web facilita a edição e o compartilhamento sem exigir a instalação do aplicativo desktop, mas possui diferenças em relação ao Excel para computador.

### Limitações e cuidados do Excel para a Web

- **Diferenças de recursos:** alguns recursos avançados e opções de configuração podem estar disponíveis apenas no aplicativo desktop ou funcionar de forma diferente na versão web.
- **Macros e VBA:** macros VBA não podem ser criadas, executadas ou editadas diretamente no Excel para a Web. Portanto, o funcionamento do projeto não deve depender de macros.
- **Tabelas dinâmicas e gráficos:** a disponibilidade de criação, edição e configuração de determinados recursos pode variar. Após abrir ou modificar o arquivo em outra versão do Excel, é recomendável verificar se tabelas dinâmicas, gráficos e formatações continuam corretos.
- **Atualização dos dados:** tabelas-resumo e indicadores podem precisar ser atualizados após a inclusão ou alteração de registros. Confira os resultados antes de utilizar o dashboard para tomar decisões.
- **Compatibilidade visual:** fontes, alinhamentos, imagens, dimensões de linhas e colunas e outros detalhes de layout podem ser exibidos de maneira diferente conforme navegador, resolução e versão do Excel.
- **Automação e integrações:** recursos avançados de importação, transformação, conexão com fontes externas ou automação podem ter limitações na versão web, dependendo do recurso e da conta utilizada.

Essas observações são gerais sobre o Excel para a Web; a disponibilidade exata de cada recurso pode variar conforme a atualização do produto, a licença e as configurações da organização.

## ▶️ Como visualizar

1. Baixe o arquivo `.xlsx` disponibilizado neste repositório.
2. Abra-o no Excel para a Web ou em uma versão compatível do Microsoft Excel.
3. Acesse a aba **Dashboard** para visualizar os indicadores.
4. Consulte **Bases** para conferir os registros e **Cálculos** para examinar as tabelas-resumo.
5. Se alterar os dados, confira e atualize os resumos e gráficos, quando necessário.

## 🔎 Possíveis melhorias futuras

- adicionar filtros interativos para plano e periodicidade;
- incluir indicadores de renovação automática e adesão aos adicionais;
- padronizar os nomes dos campos e a linguagem do dashboard;
- documentar de forma explícita a regra de cálculo de `Total Value`;
- validar a atualização dos resumos após a inclusão de novos registros;
- melhorar a acessibilidade, incluindo títulos claros e descrições dos gráficos.

## ⚠️ Aviso

Este é um projeto demonstrativo de análise de dados e construção de dashboard. Não é um produto oficial da PlayStation e não possui vínculo oficial com a Sony Interactive Entertainment. Os dados não devem ser considerados dados reais ou oficiais da empresa.

## 👤 Créditos

- **Ferramenta:** Microsoft Excel para a Web.
- **Ícone da personagem:** criado com auxílio de inteligência artificial.
- **Objetivo:** prática de organização de dados, análise e visualização em dashboard.
