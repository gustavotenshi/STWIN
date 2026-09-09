# STWIN

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22676355-blue)](https://doi.org/10.5281/zenodo.22676355)
[![Zenodo](https://img.shields.io/badge/Zenodo-Publicação_oficial-blue)](https://zenodo.org/records/22676356)
[![Versão do manuscrito](https://img.shields.io/badge/Manuscrito-v1.0-green)](STWIN_Paper_EN.md)
[![Licença: CC BY 4.0](https://img.shields.io/badge/Licença-CC_BY_4.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)

**Subluminally Transported Wormhole Infrastructure Networks**

Uma proposta conceitual de infraestrutura interestelar baseada no transporte subluminal de bocas de buracos de minhoca atravessáveis.

O STWIN explora uma pergunta: **se buracos de minhoca atravessáveis e controláveis forem fisicamente possíveis, como poderiam funcionar como uma rede permanente de comunicação e transporte entre sistemas estelares?**

A ideia central é separar o **tempo necessário para instalar uma conexão** da **latência de uso depois da instalação**. Uma sonda faria a primeira viagem a uma velocidade inferior à da luz, levando uma das bocas de um buraco de minhoca. Se a conexão sobrevivesse ao percurso e permanecesse utilizável, as interações posteriores poderiam percorrer o caminho interno dessa conexão.

> **Status:** pesquisa conceitual e arquitetura teórica condicional. O artigo não apresenta uma tecnologia demonstrada nem um projeto de engenharia realizável com a física atual. A possibilidade física dos componentes necessários é uma hipótese fundamental do modelo.

**Publicação acadêmica oficial:** [acesse o registro no Zenodo](https://zenodo.org/records/22676356). **DOI:** [10.5281/zenodo.22676355](https://doi.org/10.5281/zenodo.22676355).

Para leitura no repositório, abra o [artigo completo em inglês](STWIN_Paper_EN.md) ou baixe a [versão em Word](STWIN_Paper_EN.docx). O manuscrito se identifica como **versão 1.0 — setembro de 2026**.

**Acompanhe a pesquisa:** consulte o [roadmap mestre em português](STWIN_Master_Research_Roadmap_PT-BR.docx) e a [primeira conclusão temporal — NER/SNT](<STWIN-T1 — Network Epoch Reset and Forward-Time Operational Principle.md>). A próxima etapa definida é **SRP-2.1 — modelo causal de duas bocas**.

## Sumário

- [Sobre o projeto](#sobre-o-projeto)
- [Conteúdo do repositório](#conteúdo-do-repositório)
- [Estado atual da pesquisa](#estado-atual-da-pesquisa)
- [Como acessar](#como-acessar)
- [Como a arquitetura funciona](#como-a-arquitetura-funciona)
- [Conceitos principais](#conceitos-principais)
- [Exemplo: Proxima Centauri](#exemplo-proxima-centauri)
- [Níveis de capacidade](#níveis-de-capacidade)
- [Hipóteses e limitações](#hipóteses-e-limitações)
- [Guia de leitura](#guia-de-leitura)
- [Agenda de pesquisa](#agenda-de-pesquisa)
- [Como contribuir](#como-contribuir)
- [Publicação e versionamento](#publicação-e-versionamento)
- [Referências e citação](#referências-e-citação)
- [Licença](#licença)

## Sobre o projeto

O STWIN trata conexões hipotéticas entre sistemas estelares como infraestrutura: estrelas são nós, conexões atravessáveis são arestas e sondas instalam novos pontos da rede.

A contribuição proposta pelo artigo é **arquitetural**. O transporte de uma boca de buraco de minhoca já aparece na literatura discutida no manuscrito; o STWIN organiza esse cenário em termos de implantação, latência, capacidade, redundância, segurança causal e expansão de redes.

O material se destina a leitores interessados em relatividade, gravitação, comunicação interestelar e teoria de redes. Familiaridade com relatividade especial e geral ajuda na leitura das seções técnicas, mas a introdução apresenta a proposta em linguagem conceitual.

## Conteúdo do repositório

| Arquivo | Conteúdo |
| --- | --- |
| [README.md](README.md) | Apresentação em português e orientação para leitura e contribuição. |
| [STWIN_Paper_EN.md](STWIN_Paper_EN.md) | Manuscrito em inglês, com 21 seções, equações, estudo de caso e referências. |
| [STWIN_Paper_EN.docx](STWIN_Paper_EN.docx) | Versão do artigo em formato Word. |
| [Roadmap mestre da pesquisa](STWIN_Master_Research_Roadmap_PT-BR.docx) | Programa em português, versão 1.0, com 30 domínios de pesquisa (SRP-0 a SRP-29), perguntas, dependências e estados de avanço. |
| [Conclusão temporal NER/SNT](<STWIN-T1 — Network Epoch Reset and Forward-Time Operational Principle.md>) | Nota em português sobre Network Epoch Reset, STWIN Network Time e o princípio de operação orientada para o futuro. Identificada no texto como STWIN-C3. |

O repositório é documental. Atualmente não contém software, simuladores, dados experimentais, dependências de execução ou uma suíte de testes automatizados.

## Estado atual da pesquisa

O [roadmap mestre](STWIN_Master_Research_Roadmap_PT-BR.docx) registra o seguinte estágio do programa:

| Frente | Estado |
| --- | --- |
| Artigo conceitual STWIN v1 | Publicado. |
| Questão inicial sobre diferenças de tempo próprio | Concluída no nível conceitual. |
| Network Epoch Reset e Forward-Time Operational Principle | Adotados conceitualmente. |
| STWIN Network Time | Arquitetura selecionada; formalização matemática pendente. |
| Realização física de NER/SNT | Em aberto. |
| SRP-2.1 — modelo causal de duas bocas | Próxima etapa definida. |
| Dinâmica de bocas móveis, energia, capacidade e redes | Investigações futuras. |

### Primeira conclusão temporal

A [nota NER/SNT](<STWIN-T1 — Network Epoch Reset and Forward-Time Operational Principle.md>) adota uma arquitetura em que cada boca conserva sua história relativística e seu tempo próprio. Não se exige que os tempos próprios acumulados pelas duas extremidades sejam iguais.

Na ativação, o **Network Epoch Reset (NER)** estabelece uma referência lógica de operação. O **STWIN Network Time (SNT)** organiza os eventos da infraestrutura sem substituir os relógios locais. O **Forward-Time Operational Principle** exige, para cada travessia admissível:

```text
T_out = T_in + δ_W, com δ_W > 0
```

A nota distingue **STWIN-COM**, voltado à comunicação, de **STWIN-TRANS**, voltado ao transporte de matéria. Segundos ou menos são uma meta arquitetural para comunicação; transporte poderia tolerar latências positivas maiores. Esses valores não são capacidades demonstradas.

**Alcance da conclusão:** NER/SNT define uma camada lógica e um requisito operacional. A correspondência dessa ordenação com a estrutura causal física ainda precisa ser demonstrada. Redefinir relógios não altera a geometria nem elimina, por si só, curvas temporais fechadas. A hipótese de compensação geométrica ativa (*Active Wormhole Compensation*) também permanece em aberto.

O arquivo dessa conclusão tem o prefixo **STWIN-T1**, enquanto seu título e o roadmap usam **STWIN-C3**. Ambos se referem à nota vinculada acima.

### Próxima pergunta — SRP-2.1

Com uma boca na Terra e outra em Proxima Centauri, qual condição física garante que uma travessia com `T_out > T_in` no SNT também seja orientada para o futuro na estrutura causal do espaço-tempo?

O escopo definido no roadmap é **duas bocas, uma mensagem e estrutura causal**. A etapa deverá modelar as trajetórias das bocas, os eventos de entrada e saída e a relação entre SNT e causalidade física. Redes com múltiplos nós e requisitos avançados de energia, transporte e segurança ficam para etapas posteriores.

## Como acessar

### Leitura pelo GitHub

Abra o [manuscrito em Markdown](STWIN_Paper_EN.md). Para ler ou editar em um processador de texto, baixe o [arquivo `.docx`](STWIN_Paper_EN.docx) e abra-o em um aplicativo compatível.

### Cópia local

Com o Git instalado:

```sh
git clone https://github.com/gustavotenshi/STWIN.git
cd STWIN
```

Também é possível baixar o repositório pelo menu **Code → Download ZIP** no GitHub, sem instalar o Git.

Abra `STWIN_Paper_EN.md` em um editor de texto ou visualizador de Markdown. As equações do manuscrito usam notação LaTeX; sua exibição depende do suporte do visualizador. Nenhuma instalação de pacotes, compilação ou configuração de variáveis de ambiente é necessária para consultar os documentos.

## Como a arquitetura funciona

1. **Preparação:** duas bocas conectadas, `W_A` e `W_B`, começam próximas no sistema de origem.
2. **Implantação:** `W_A` permanece na origem e uma sonda transporta `W_B` até outro sistema, com velocidade `v < c`.
3. **Instalação no destino:** a sonda desacelera e posiciona a boca remota em uma configuração operacional estável.
4. **Operação:** se a geometria permanecer atravessável e causalmente admissível, sinais — e, sob hipóteses adicionais, matéria — passam pela conexão.
5. **Expansão:** nós com capacidade industrial e de provisionamento de novas bocas poderiam enviar outras sondas e ampliar a rede.

O manuscrito também discute uma variante de **geração remota**, na qual a sonda criaria uma boca no destino. Essa variante exige hipóteses adicionais e não deve ser confundida com a arquitetura básica de transporte de uma boca já conectada.

## Conceitos principais

| Conceito | Significado no STWIN |
| --- | --- |
| Custo causal de instalação | Tempo necessário para levar fisicamente um novo ponto de conexão ao destino. |
| Amortização da distância | Reutilização da conexão instalada em sucessivas comunicações ou travessias. |
| Distância topológica de rede | Custo de percorrer conexões da rede, que pode diferir do percurso pelo espaço exterior. |
| Implantação com segurança cronológica | Restrições sobre trajetórias e conexões para evitar curvas temporais fechadas. |
| Expansão recursiva | Novos nós provisionam e enviam missões para instalar outras conexões. |

As relações simplificadas usadas no artigo são:

```text
Tempo de implantação:             T_deploy ≈ D / v
Tempo de propagação da luz:        T_light  = D / c
Condição de baixa latência:        τ_W ≪ D / c
```

Aqui, `D` é a distância exterior entre os sistemas, `v` é a velocidade de cruzeiro da sonda, `c` é a velocidade da luz e `τ_W` representa a latência efetiva de travessia da conexão. A estimativa de implantação desconsidera aceleração e frenagem.

**Latência e capacidade são grandezas distintas:** mesmo uma conexão hipotética de baixa latência poderia ter limites severos de largura de banda, energia ou fluxo de matéria.

## Exemplo: Proxima Centauri

O estudo de caso do manuscrito adota uma distância aproximada de **4,24 anos-luz**. Com velocidade de cruzeiro constante, os tempos de implantação no referencial da origem seriam:

| Velocidade de cruzeiro | Tempo aproximado de implantação |
| --- | ---: |
| `0,01c` | 424 anos |
| `0,10c` | 42,4 anos |
| `0,20c` | 21,2 anos |
| `0,50c` | 8,48 anos |

Nesse modelo, um sinal luminoso pelo espaço exterior continuaria levando aproximadamente **4,24 anos em um sentido**, ou **8,48 anos para uma troca de pergunta e resposta imediata**. A latência de uma conexão STWIN dependeria da geometria hipotética do buraco de minhoca; o projeto não estabelece um valor fisicamente realizável.

Esses números são estimativas ilustrativas reproduzidas do artigo. Não incluem aceleração, desaceleração ou os requisitos de estabilidade da boca transportada. O tempo próprio medido pela sonda também difere do tempo no referencial de origem em velocidades relativísticas.

## Níveis de capacidade

O artigo distingue cinco capacidades, cada uma com requisitos próprios:

| Nível | Capacidade hipotética |
| --- | --- |
| I | Transmissão de sinais clássicos. |
| II | Transferência de estados quânticos com preservação de coerência. |
| III | Passagem de matéria microscópica, como átomos e moléculas. |
| IV | Transporte de cargas macroscópicas, equipamentos e robôs. |
| V | Transporte biológico ou tripulado em condições toleráveis. |

A viabilidade de um nível não demonstra a dos seguintes. Uma conexão capaz de transmitir sinais pode ser inadequada para transportar matéria ou organismos.

## Hipóteses e limitações

As conclusões do STWIN dependem de que seja possível:

- Criar ou obter um buraco de minhoca macroscópico atravessável.
- Acomodar e transportar uma de suas bocas em uma sonda.
- Preservar a conexão durante aceleração, cruzeiro, frenagem e grande separação espacial.
- Controlar a energia de sustentação e a reação da geometria à passagem de sinais ou matéria.
- Manter uma configuração globalmente consistente com as restrições de causalidade.
- Obter taxas de transmissão ou transporte úteis.

O manuscrito identifica como obstáculos centrais a energia negativa e suas restrições quânticas, a estabilidade da garganta, a defasagem temporal entre bocas, a possível formação de curvas temporais fechadas e os limites impostos pela reação gravitacional ao tráfego.

Na formulação do artigo, **emaranhamento quântico comum não é um canal controlável de comunicação superluminal**. A discussão de ER=EPR e de modelos teóricos de atravessabilidade não fornece um método de construção de conexões macroscópicas entre estrelas.

A primeira implantação continua exigindo uma viagem subluminal no cenário básico. A baixa latência posterior é uma consequência condicional da conexão postulada, sem demonstração experimental no projeto.

## Guia de leitura

Para acompanhar o programa, a sequência sugerida é: **artigo conceitual → conclusão temporal NER/SNT → roadmap mestre**, com atenção à próxima pergunta SRP-2.1. Os três documentos estão vinculados em [Conteúdo do repositório](#conteúdo-do-repositório).

As seções abaixo pertencem ao [manuscrito completo](STWIN_Paper_EN.md):

| Interesse | Seções |
| --- | --- |
| Entender a proposta e seu escopo | Resumo e 1–3: introdução, hipóteses e arquitetura. |
| Acompanhar os cálculos ilustrativos | 4–5: amortização da distância e caso Proxima Centauri. |
| Examinar os obstáculos físicos | 6–9: cronologia, energia negativa, emaranhamento e capacidade. |
| Entender requisitos de transporte e implantação | 10–11: níveis de capacidade e requisitos da sonda. |
| Explorar redes e expansão | 12–15: topologias, falhas, expansão recursiva e primeira travessia. |
| Examinar implicações operacionais | 16–17: translocação, identidade, segurança e governança. |
| Avaliar questões em aberto | 18–19: falsificabilidade e marcos de pesquisa. |
| Ler a síntese conceitual | 20–21: discussão e conclusão. |

## Agenda de pesquisa

O [roadmap mestre](STWIN_Master_Research_Roadmap_PT-BR.docx) desdobra a agenda do artigo em 30 domínios. A tabela resume seu escopo; os estados de cada pergunta e suas dependências estão no documento completo.

| Domínios | Escopo |
| --- | --- |
| SRP-0–2 | Fundamentos, hipóteses mínimas, arquitetura temporal, causalidade e cronologia. |
| SRP-3–4 | Geometria do buraco de minhoca e dinâmica de uma boca em movimento. |
| SRP-5–6 | Missões de implantação, trajetórias, massa efetiva e energia de propulsão. |
| SRP-7–8 | Energia exótica, tensor energia-momento, estabilidade e reação da geometria ao tráfego. |
| SRP-9–10 | Comunicação, capacidade de canal e informação quântica. |
| SRP-11–13 | Teoria de redes, grafos causais e tempo distribuído. |
| SRP-14–16 | Controle autônomo, IA, prevenção de falhas e proteção contra ataques. |
| SRP-17–18 | Transporte de matéria e requisitos adicionais para transporte biológico. |
| SRP-19–20 | Expansão recursiva e consequências para uma civilização conectada. |
| SRP-21–22 | Condições que inviabilizam o modelo e arquiteturas alternativas. |
| SRP-23–27 | Simulações, formalização matemática, falsificabilidade, observação e experimentos análogos. |
| SRP-28–29 | Publicações incrementais, registros de pesquisa, hipóteses, decisões e versionamento. |

A sequência imediata parte de **SRP-2.1**, segue para diagramas de Minkowski e mapeamentos temporais (**SRP-2.2/2.3**) e então para margens de cronologia e condições de curvas temporais fechadas (**SRP-2.4/2.5**). O próximo alvo de publicação previsto é o **Paper II — arquitetura temporal e causalidade de duas bocas**.

O método do programa é trabalhar uma pergunta central por vez, buscar refutações e registrar a conclusão, o grau de confiança, as objeções e as questões abertas. As afirmações devem distinguir física estabelecida, resultados teóricos conhecidos, extrapolações condicionais, hipóteses STWIN e especulação de engenharia.

## Como contribuir

Contribuições úteis incluem correções matemáticas, identificação de hipóteses implícitas, revisão de terminologia, referências relevantes, traduções e melhorias na apresentação do argumento.

Para propor uma alteração:

1. Abra uma issue ou prepare uma pull request com a seção afetada e a mudança proposta.
2. Explique o problema e apresente a justificativa; para alterações científicas, inclua fontes e explicite as hipóteses adotadas.
3. Preserve a distinção entre resultados estabelecidos, resultados teóricos de domínio restrito e suposições do STWIN.
4. Confira equações, unidades, referências, links e renderização do Markdown.
5. Ao alterar o manuscrito, mantenha as versões `.md` e `.docx` consistentes ou informe na proposta qual delas ainda precisa ser atualizada.
6. Para avanços de pesquisa, indique o identificador SRP correspondente, as dependências e o que foi concluído ou permanece em aberto. Atualize o roadmap quando houver mudança de estado.

Não há um processo automatizado de sincronização dos documentos ou validação científica neste repositório. A revisão das alterações é documental e conceitual.

## Publicação e versionamento

O projeto utiliza dois espaços complementares:

| Espaço | Finalidade |
| --- | --- |
| [Zenodo](https://zenodo.org/records/22676356) | Publicação acadêmica arquivada, identificada por DOI e usada como referência para citação. |
| [GitHub](https://github.com/gustavotenshi/STWIN) | Documentação em evolução, manuscrito em Markdown, histórico de alterações, issues e discussão técnica. Pode também reunir futuras figuras, simulações e cálculos. |

O roadmap e as notas de conclusão acompanham a evolução da pesquisa no repositório. A presença desses documentos não implica uma nova versão do artigo arquivado; o badge do manuscrito permanece em `v1.0` até uma atualização formal correspondente.

Para futuras versões do artigo, como `v1.1` ou `v2.0`, o fluxo de publicação proposto é:

1. Atualizar e revisar os arquivos do manuscrito, registrando as mudanças em um changelog.
2. Criar uma release correspondente no GitHub, com a versão e as notas de alteração.
3. Publicar a nova versão no Zenodo e registrar seu DOI nas notas da release.
4. Atualizar os links e o badge de versão deste README para manter a correspondência entre os materiais.

No cadastro do Zenodo, o endereço `https://github.com/gustavotenshi/STWIN` deve constar como repositório relacionado. Este README já oferece o caminho do GitHub para a publicação acadêmica.

## Referências e citação

A bibliografia está ao final do [artigo em Markdown](STWIN_Paper_EN.md), com trabalhos sobre buracos de minhoca atravessáveis, proteção cronológica, restrições quânticas de energia, ER=EPR e geometrias com múltiplas bocas, além da fonte usada para a distância a Proxima Centauri.

Para citar a publicação acadêmica, consulte os metadados e as opções de exportação de citação no [registro do Zenodo](https://zenodo.org/records/22676356). O DOI informado para o projeto é **[10.5281/zenodo.22676355](https://doi.org/10.5281/zenodo.22676355)**.

O título do manuscrito é *STWIN: Subluminally Transported Wormhole Infrastructure Networks — A Conditional Framework for Persistent Interstellar Communication, Transport, and Topological Infrastructure*, versão **1.0 (setembro de 2026)**. Ao citar uma versão específica, use o DOI correspondente exibido no Zenodo. Ao discutir alterações ainda presentes apenas no GitHub, inclua também o hash do commit ou um permalink do arquivo.

O repositório não inclui atualmente um arquivo `CITATION.cff`.

## Licença

O artigo e a documentação do projeto são disponibilizados sob a licença **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.

Consulte o texto da licença no link acima para as condições aplicáveis à reutilização. Ao reutilizar o material, atribua o crédito à autoria, indique a licença e informe eventuais alterações.
