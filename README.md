# 🧠 Miniguia de Estudos com NotebookLM: A Primeira Guerra Mundial e seus Impactos Multidimensionais

Repositório criado para o desafio de projeto da DIO, explorando o uso do Google NotebookLM como ferramenta de aprendizagem ativa, curadoria de conhecimento e engenharia de prompts.

---

## 🎯 Contexto e Objetivos

**Tema Central:** A Primeira Guerra Mundial (1914-1918) e seus impactos multidimensionais. O estudo explora o conflito sob a ótica militar e geopolítica, mas aprofunda-se em áreas como arqueologia de trincheiras, transformações na indústria brasileira, papel da propaganda política/semiótica e as revoluções estéticas da literatura de vanguarda.

**Objetivos de Estudo:**
* **Análise Socioeconômica Transnacional:** Compreender como a retração do comércio global impactou a industrialização periférica, com foco na capacidade produtiva e substituição de importações no Brasil.
* **Evolução Sociocultural e Literária:** Investigar como o trauma do combate impulsionou as vanguardas artísticas e reestruturou gêneros literários (como ficção policial) como crítica social.
* **Tecnologia, Comunicação e Saúde Pública:** Avaliar as inovações bélicas, as epidemias resultantes (Gripe Espanhola) e as estratégias de semiótica e persuasão em cartazes de propaganda de Estado.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM e garantir embasamento técnico e multidisciplinar, utilizei um acervo de mais de 30 documentos. Abaixo, destaco as 5 fontes principais que fundamentaram este caderno:

1. **A PRIMEIRA GUERRA MUNDIAL E A INDÚSTRIA BRASILEIRA...** (Artigo / PDF USP)
   * *Motivo:* Essencial para entender os impactos econômicos periféricos e o uso da capacidade industrial instalada.
2. **A vida nas trincheiras durante a Primeira Guerra** (Artigo Mundo Educação)
   * *Motivo:* Base para a análise arqueológica e do cotidiano material/psicológico dos soldados no front.
3. **“I Want You for the US Army”: Um estudo sobre a construção ideológica do cartaz e sua análise semiótica** (Artigo / PDF)
   * *Motivo:* Fundamental para o estudo de comunicação de massa, discurso fundador e persuasão do Estado.
4. **A Vida Lançada nos Dados: Vanguarda e Guerra em Le Cornet à Dés** (Artigo / PDF)
   * *Motivo:* Conecta os horrores da guerra com a ruptura dos padrões estéticos e literários clássicos.
5. **Gripe espanhola: onde surgiu, como se difundiu, mortes** (Artigo Brasil Escola)
   * *Motivo:* Adiciona a camada de saúde pública e o impacto demográfico das pandemias no pós-guerra.

---

## ⚙️ Engenharia de Prompts e "Cicatrizes"

Nesta seção, documento o processo de raciocínio lógico e o refinamento de prompts (troubleshooting) utilizado para extrair os melhores resultados do NotebookLM.

### Tentativa 1: A Armadilha da Generalização
* **Prompt Inicial:** *"Faça um resumo sobre a Primeira Guerra Mundial com base nos documentos."*
* **Cicatriz (Problema):** A IA gerou um texto de nível escolar, focando apenas em datas e no assassinato de Francisco Ferdinando, ignorando completamente os PDFs densos sobre economia brasileira e semiótica que eu havia anexado.
* **Solução:** Percebi que a IA precisa ser forçada a olhar para os nichos.

### Tentativa 2: O Excesso de Verborragia no Glossário
* **Prompt Intermediário:** *"Crie um glossário com os termos técnicos de todos os documentos."*
* **Cicatriz (Problema):** A ferramenta trouxe verbetes enormes, parecendo artigos da Wikipedia, o que inviabiliza uma revisão rápida.
* **Solução:** Era necessário impor restrições de formatação e tamanho.

### Tentativa 3: O "Mega-Prompt" Estruturado (Sucesso)
* **Prompt Final:** *"Atue como um curador de conhecimento sênior. Analise todos os documentos anexados neste caderno e gere um relatório de exportação em formato Markdown, contendo rigorosamente as seções: Contexto, Resumo Estruturado em bullet points, Glossário extraindo 5 a 10 termos com no máximo 2 linhas cada, e 3 Prompts avançados focados em personas específicas (historiador, economista, etc)."*
* **Resultado:** A IA assumiu o papel de especialista, integrou os diferentes temas (economia, literatura, arqueologia) e obedeceu às restrições de tamanho, gerando o material consolidado abaixo.

---

## 📖 Miniguia de Estudo

### 1. Resumo Estruturado

* **Causas e Características Militares:** Conflito resultante de disputas imperialistas e econômicas. Marcado pelo uso inédito de gases tóxicos e pela longa fase das "guerras de trincheiras", redefinindo o trauma humano e as funções tecnológicas em combate.
* **Arqueologia da Guerra:** Escavações modernas revelam a complexidade das trincheiras (linhas de abastecimento, camas, assistência odontológica) e a personalização histórica dos túmulos, alterando a visão sobre os rituais fúnebres sob fogo.
* **Impacto na Economia Brasileira:** Forçou um processo incipiente de substituição de importações. O crescimento, no entanto, baseou-se majoritariamente no uso da *capacidade industrial já instalada* antes de 1914, devido à queda na importação de maquinário.
* **A Virada na Literatura e nas Artes:** O pessimismo resultou no fim da linguagem romântica e ascensão do vanguardismo. Na cultura de massa, autoras como Patrícia Galvão usaram a ficção policial (*whodunit* e *noir*) para tecer críticas sutis ao sistema capitalista.
* **Saúde e Sociedade:** A guerra alterou a demografia laboral, ampliando o papel da mulher. Paralelamente, a letal pandemia de Gripe Espanhola (1918) vitimou milhões, evidenciando vulnerabilidades médicas. O conflito também amadureceu juridicamente o conceito de proteção a refugiados.
* **Semiótica e Comunicação Ideológica:** Massificação da propaganda política (ex: cartaz do "Tio Sam"). O uso da semiótica de redundância fechou o discurso de objeção, compelindo cidadãos ao recrutamento imediato através de gatilhos visuais incontestáveis.

### 2. Glossário

* **Substituição de Importações:** Estratégia e processo econômico forçado, comum no Brasil da Primeira Guerra, onde o país passa a fabricar bens industrializados internamente devido ao isolamento externo.
* **Guerra de Trincheiras:** Fase predominante e letal da guerra (1915-1918) caracterizada por redes intrincadas de valas subterrâneas para proteção, habitação e logística.
* **Ficção Whodunit:** Modalidade de romance policial baseada em um mistério ("quem fez isso?") resolvido por dedução científica, subvertida na era das vanguardas.
* **Vanguarda (Avant-garde):** Movimentos artísticos que romperam com métricas clássicas, impulsionados pela incerteza e pessimismo causados pela destruição do início do século XX.
* **Semiótica da Imagem:** Ciência que analisa linguagens visuais e comunicação não-verbal, utilizada para destrinchar ferramentas de persuasão (cores, redundância) em cartazes militares.
* **Geração Transnacional Historiográfica:** Fase atual dos estudos sobre a Grande Guerra, adotando uma visão global e comparativa das práticas e sofrimentos dos soldados, abandonando narrativas estritamente nacionalistas.
* **Discurso Fundador:** Conceito linguístico que liga a formação de um ideal de nação a uma ordem discursiva que não permite réplica, criando ações inquestionáveis de patriotismo.

### 3. Prompts Reutilizáveis (Para Revisão Futura)

Caso eu deseje aprofundar estes estudos usando outras IAs no futuro, deixo registrados prompts de alta complexidade:

1. **Historiografia e Arqueologia:** *"Atue como um historiador especializado no século XX e mestre em arqueologia militar. A partir de achados arqueológicos em linhas de frente antigas (como as escavações de trincheiras francesas e alemãs), elabore uma análise de 4 parágrafos focada no cotidiano material dos soldados: detalhe a organização arquitetônica dos abrigos, a assistência médica nos postos avançados e o surgimento da personalização do luto em contraposição às valas comuns."*
2. **Economia e Estrutura Industrial:** *"Como um economista histórico focado nos impactos de choques globais nas periferias, desenvolva um relatório técnico comparando as teorias de 'estímulo pela proteção tarifária' e 'barreira por falta de insumos' sobre a indústria brasileira na Primeira Guerra. Embase sua tese utilizando o conceito de uso da 'capacidade instalada ociosa'."*
3. **Literatura, Semiótica e Sociedade:** *"Atuando como um curador acadêmico especializado em comunicação de massa do Entreguerras, explique a conexão entre a fragmentação das vanguardas literárias europeias e o crescimento das 'pulp fictions' na América do Sul. Disserte sobre como o trauma coletivo alterou as exigências estéticas e permitiu o uso de artefatos visuais (como o cartaz do Tio Sam) como ferramentas de persuasão."*
