---
theme: penguin
colorSchema: 'auto'
layout: intro2
# https://sli.dev/custom/highlighters.html
highlighter: shiki
themeConfig:
  logoHeader: '/bit_nucleotideo/logo_lanbin_color.svg'
  eventLogo: '/bit_nucleotideo/cipmec_logo.png'
  eventUrl: 'https://beacons.ai/CIPMEC'

css: unocss
---


# Computação na genética
<p>
 Do <simple-icons-bit mr-1/> ao nucleotídeo <simple-icons-microgenetics mr-1/>
</p>
<div class="pt-12">
  <span @click="next" class="px-2 p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10">
    Luiz Pedro Petroski
  </span>
</div>

---
layout: presenter
eventLogo: '/bit_nucleotideo/logo_lanbin_color.svg'

presenterImage: '/bit_nucleotideo/lpp.jpg'
---

# Luiz Pedro Petroski



## Formação
- Doutorando em  Ciências da Saúde - PUC PR 
- Engenharia de Computação - UEPG
- Mestrado em Computação Aplicada - UEPG

## Profissional
- Desenvolvedor
- Analista de Sistemas
- Professor
<div class="inline-block">
<img src ="/uepg.png" class="w-30 h-30 object-contain relative"/> 
</div>
<div class="inline-block">
<img src ="/logo-pucpr-vermelha.svg" class="w-30 h-30 object-contain relative"/> 
</div>

---
layout: text-image

media: '/bit_nucleotideo/audience.jpg'
caption: Image by upklyak on Freepik
---
# Quem é você?

<div v-click>

- ## Curso?

</div>
<div v-click>

- ## Ano/período?

</div>
<div v-click>

- ## Qual/quais linguagens sabe?

</div>

---
layout: text-image

media: '/bit_nucleotideo/think.jpg'
caption: Image by storyset on Freepik
---
# Vamos abstrair

<ul>
  <li> <h3>Níveis de abstração</h3></li>
  <ul>
    <li v-click>Do físico (BIT) ao conceitual (Esquema)</li>
  </ul>
  
  <li v-click><h3>Analogias</h3></li>
  <ul v-click>
    <li>Árvore</li>
    <li>Fila/Pilha</li>
    <li>Processo</li>
    <li>Memória</li>
    <li>Banco de dados</li>
    <li>Rede Neural</li>
  </ul>
  
</ul>



---
layout: text-image

media: '/bit_nucleotideo/bioinfo.png'
---




# O que é a bio+informática

Aplicação de estatística e Ferramentas de computação em dados biológicos

- Sistemas de informação
- Dados das Multi-ômicas
  - Genoma
  - Transcriptoma
  - Proteoma
  - Metaboloma

---
layout: default

media: '/bit_nucleotideo/bioinfo.png'
---

# O que é a informática?



<ul>
  <li> <h3>Qual é a menor unidade da computação</h3></li>
  <ul>
    <li v-click>bit, 0/1, ligado/desligado, sim/não, true/false</li>
  </ul>
  
  <li v-click><h3>Com 8 bits temos?</h3></li>
  <ul v-click>
    <li>Um Byte(B) 2^8=256 combinações</li>
  </ul>
  <li v-click><h3>Instruções</h3></li>
  <ul v-click>
    <li>Opcode: add, sub, mul, inc, and, nor, ld1, st1</li>
  </ul>
  <li v-click><h3>Linguagens de alto nível</h3></li>
  <ul v-click>
    <li>C, Java, Python, PHP, TypeScript, R, C#</li>
    <li>Compiladores, transpiladores, interpretadores</li>
  </ul>
  <li v-click><h3>Modelos lógicos e conceituais</h3></li>
  <ul v-click>
    <li>Diagramas (Casos de uso (UML), histórias de usuário, diagramas de bloco</li>
    <li>Programa completo, Sistema de Informação</li>
  </ul>
  
</ul>


---
layout: text-image
reverse: true
media: '/bit_nucleotideo/reinos-0.jpg'
---

# E a bio?

Biologia: Ciência que estuda a vida (organismos vivos)!

<h3>Exemplo: você!</h3>

<div v-click>
<h4>Do que você é formado?</h4>
</div>

---
layout: text-image
reverse: true
media: '/bit_nucleotideo/comp-humano.png'
---

# Conseguimos fazer alguma relação com a computação?

---
layout: text-image
reverse: true
media: '/bit_nucleotideo/code.png'
---

# Seria possível fazer um DEBUG de um ser vivo?
<div v-click>
<h4>Calma, calma!!</h4>
</div>

<div v-click>
<h4>Quais são os dados que conseguimos coletar de um ser vivo?</h4>

- DNA
- RNA
- Proteína

</div>

---
layout: text-image
reverse: true
media: '/bit_nucleotideo/basenitrogenada.webp'
---

# Menor unidade de dados dos seres vivos
<div v-click>
<h4>O nucleotídeo</h4>
</div>

- <b>Base nitrogenada:</b> Purinas -> adenina (A) e guanina (G) e Pirimidinas -> citosina ( C), uracila (U) e timina (T).
- <b>Grupo fosfato (HPO4):</b> Derivado do ácido fosfórico.
- <b>Pentose:</b> Um açúcar de 5 carbonos. No DNA temos a desoxirribose e no RNA temos a ribose.

---
layout: text-image
media: '/bit_nucleotideo/magnet.gif'
---
# Estrutura

O DNA pode formar uma dupla hélice, constituída por duas
fileiras de polinucleotídeos, unidas entre si por ligações de
hidrogênio.

A ligação de hidrogênio promove a forma e a estabilidade
do DNA para proteger o código genético, mas também prevê
a fácil ruptura das ligações (“Unzip”) através da ação de
enzimas para a replicação do DNA.

---
layout: image
image: '/bit_nucleotideo/dna.jpg'
---



---

# Pareamento das bases

Cada tipo	de	base	nitrogenada	pode	interagir	com	uma	outra	base complementar,	formando	ligações	de	hidrogênio.

- Guanina pareia com Citosina
- Adenina pareia com Timina

<br>
<br>
<h3>Processo de replicação semiconservativo</h3>


---
layout: text-image
media: '/bit_nucleotideo/sequence.jpg'
---

# Os nucleotídeos são o alfabeto do código da vida

- Como funciona o código no corpo humano?
- Como o código é compilado?
- Podemos copiar esse código para o computador?
- Podemos editar esse código?
- Podemos simular/emular um organismo?


---
layout: text-image
media: '/bit_nucleotideo/cromossomo.webp'
---

# Como funciona o código no corpo humano?

- O DNA fica empacotado no núcleo de cada célula
  - Segmento responsável pelas características herdadas: gene
  - Forma os cromossomos (Cromatina)
  - Cada célula tem uma cópia
  - É como um repositório de código descentralizado
---
layout: text-image
media: '/bit_nucleotideo/transcricao.png'
---

# O DNA é compilado?

<div v-click>

- Sim!! (analogia)
  - Esse processo é chamado de transcrição e tradução
  - O processo de transcrição pode ser entendido como uma espécie de compilação do código-fonte (DNA) em código objeto (RNA).
  - A tradução pode ser entendido como a transformação do código objeto (RNA) em executável (proteína).

</div>

---
layout: text-image
media: '/bit_nucleotideo/proteina.webp'
---

# A proteína é o executável de um sistema biológico

  - A maioria das funcões biológicas é executada por proteínas


  - Caso ocorra algum problema com a proteina (ou com o processo de formação da proteína) pode problemas no organismo (doenças)

---
layout: text-image
media: '/bit_nucleotideo/debug.png'
---

# Conseguimos copiar esse código?

Assim poderíamos analisar e procurar onde estão ocorrendo os erros nos executáveis (proteínas)


<div v-click>

- Mais uma vez sim!!
  - Podemos fazer o sequenciamento do DNA (genoma)
  - Também podemos fazer o sequenciamento do RNA (transcriptoma)


Qual a diferença?

</div>

---
layout: default
media: '/bit_nucleotideo/debug.png'
---

# Qual a diferença entre DNA e RNA?


<div v-click>

- O DNA é estático!!
  - O mesmo em todas as células
  - Não sofre alteração
  - Nem todo o código é executado em todos os lugares

- O RNA é dinâmico!!
  - É variável por cada tecido
  - Regulado por outros genes e fatores externos (ex medicamentos)
  - Mostra qual é o código está sendo executado naquele momento e lugar (monitor de processos)



</div>

---
layout: text-image
media: '/bit_nucleotideo/crispr.webp'
---

# É possível editar o DNA?


<div v-click>

- Sim!!
  - CRISPR/Cas9
  - Promissor para diversas doenças como HIV e cancer
  - Mas é necessário um alvo bem definido e preciso


Então precisamos conhecer a função de cada gene. Qual a dificuldade?
- Alguma vez você mudou uma variável e nada mais funcionou?

</div>

---
layout: default
---

# Qual o papel de cada gene?


<div v-click>

- Temos 2 cópias da maioria dos genes (pai e mãe)
- Os genes são ativados ou não de acordo com a necessidade (célula especializada)
  - Isso pode ser visto pelo RNA diferente em cada tecido
  - É chamado de regulação da expressão gênica
  
- Por isso pode ocorrer de possuir um gene relacionado a alguma doença, mas nunca manifestar
- Ou por uma regulação inadequada (super expressão ou inibição) apresentar uma condição sindrômica



</div>

---
layout: default
---

# Tipos de amostras

- ## Retirada de tecido/biopsia
- ## Modelos animais
- ## Amostras post mortem
- ## Modelos in vitro


---
layout: center
---

# Modelo de organóide

<img src ="/organoid.jpg" class="w-150 "/> 

---
layout: default
---

# Sequenciamento RNA-seq

- Coletar uma amostra
  - Ler as bases A, T, C, G
  - O primeiro método foi criado por Frederick Sanger (década de 70)
  - Hoje é utilizado as técnicas de NGS (Sequenciadores de Nova Geração)

- Fazer uma análise da qualidade das leituras
  - Arquivos chamados .fastq
  - O resultado do sequenciamento são  de 20 a 50 milhões de "reads" com 50 a 150 bp cada
  - Cada bp tem um score de qualidade de leitura do equipamento


---
layout: center
---

# FASTA format

<img src ="/fastqPic.png" class="w-150 "/> 

---
layout: default
---

# Processamento RNA-seq

- Alinhamento
  - Alinhar os reads contra um genoma de referência
  - Há diversas bases de genomas de referência
    - Por exemplo o genoma humano mais utilizado é o GRC38 e o T2T
  - O resultado é o arquivo SAM (Sequence Alignment/Map)


---
layout: center
---

# SAM format

<img src ="/sam.webp" class="w-150 "/> 

---
layout: center
---

# Alinhamento das reads

<img src ="/igv.png" class="w-150 "/> 

---
layout: center
---

# Quantificação da expressão de cada gene

<img src ="/count_modes.png" class="w-150 "/> 


---
layout: center
---

# Quantificação da expressão de cada gene

<img src ="/quant.png" class="w-150 "/> 


---
layout: default
---

# Problemas em comparar quantificação entre amostras
<h3>
1. Diferença no tamanho da biblioteca de sequenciamento (número de reads)


2. Diferença na composição da biblioteca (comparação entre diferentes tecidos ou mesmo tecido com fator de transcrição com knock out)
</h3>

---
layout: center
---

# Normalização

<img src ="/norm.png" class="w-150 "/> 

---
layout: default
---

# Normalização

- TPM (transcripts per kilobase million): Contagem pelo tamanho do transcrito (kb) por milhão de reads mapeados
- RPKM/FPKM (reads/fragments per kilobase of exon per million reads/fragments mapped): Similar ao TPM
- DESeq2’s median of ratios: usa uma média ponderada das razões de expressão logarítmica entre as amostras
- Z-score: Normalização do valor de TPM



---
layout: center
---

# Estudos Caso/Controle

<img src ="/sequencyng.svg" class="w-150 "/> 

---
layout: center
---

# Estudos Caso/Controle

<img src ="/aligncount.png" class="w-150 "/> 

---
layout: center
---

# Análise de expressão diferencial de genes (DGE)

<img src ="/sample_qc.png" class="w-150 "/> 


---
layout: center
---

# Análise de expressão diferencial de genes (DGE)

<img src ="/volcanoplot.png" class="h-100 "/> 

---
layout: intro
---

# Uso de Machine Learning em Sequenciamento

---
layout: center
---

# Correção de erro de sequenciamento

<img src ="/consensus-approach-overview.jpg" class="h-100 "/> 
<a href="https://google.github.io/deepvariant/posts/2019-01-31-using-nucleus-and-tensorflow-for-dna-sequencing-error-correction/">https://google.github.io/deepvariant/posts/2019-01-31-using-nucleus-and-tensorflow-for-dna-sequencing-error-correction/</a>

---
layout: center
---

# Predição de condição por expressão gênica

<img src ="/pred_neural.png" class="h-100 "/> 

---
layout: center
---

# Predição de condição por expressão gênica

<img src ="/tree.png" class="h-100 "/> 

---
layout: center
---

# Performance de predição

<img src ="/perform.png" class="h-100 "/> 

---
layout: default
---

# Perspectivas

- ## Determinar relações complexas de regulação dos genes
- ## Determinar genes alvos para diagnóstico e tratamento
- ## Validar com experimentos PCR (RNA) e Western Blotting (Proteína)
- ## Experimentos com knockout de genes
- ## Modelos experimental com organóides

---
layout: center
---

# Perguntas?

<img src ="/logo_lanbin_color.svg" class="w-50 "/> 
<a href="mailto:petroskilp@gmail.com" target="_blank">petroskilp@gmail.com</a>