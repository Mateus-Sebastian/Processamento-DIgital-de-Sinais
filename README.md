<h1 align="center">Processamento Digital de Sinais - Atividade Prática</h1>

<p>
Este repositório contém a atividade prática da disciplina de <strong>Processamento Digital de Sinais</strong>, abordando conceitos avançados com base no livro texto <em>Digital Signal Processing using MatLab</em>.
</p>

### **Capítulo 4: A Transformada-z**
A transformada-z representa um método matemático essencial para examinar e desenvolver sistemas de processamento digital de sinais. Considerada o equivalente discreto da transformada de Laplace, esta ferramenta permite estudar sistemas LTI (Lineares e Invariantes no Tempo) analisando seu comportamento frequencial.

#### **Definição da Transformada-z** 
Para uma sequência discreta x[n], a transformada-z é expressa matematicamente como:

<img src="https://github.com/user-attachments/assets/de2535be-07b5-40af-abfb-75711d890811" alt="Transformada Z" width="400"/>

sendo 𝑧 uma variável complexa.

#### **Propriedades Fundamentais**
- **Linearidade:** Se aplicada a uma combinação de sequências, a transformada-z resulta na mesma combinação das transformadas individuais.
- **Deslocamento Temporal:** Ao deslocar uma sequência no tempo, sua transformada-z é multiplicada por uma potência de 𝑧.
- **Convolução:** Uma operação de convolução temporal se traduz em multiplicação no domínio z.

#### **Região de Convergência (ROC)**
Define-se como ROC o conjunto de pontos no plano complexo onde a série da transformada-z apresenta convergência. Esta região é essencial na avaliação da estabilidade e causalidade dos sistemas.

#### **Usos Práticos**
A transformada-z encontra aplicação em:
- **Verificação da estabilidade em sistemas digitais.**
- **Desenvolvimento e implementação de filtros digitais.**
- **Estudo do comportamento frequencial de sistemas.**

#### **Anexos**
<table>
  <tr>
    <td align="center">
      <a href="https://colab.research.google.com/drive/15LLKP70mI4uQdBgdRD-PIKjTUPuk68zU?usp=sharing">
        <b>Colab</b>
      </a>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=_cwMggmruPw">
        <b>Vídeo</b>
      </a>
    </td>
  </tr>
</table>

### **Capítulo 5: Transformada Discreta de Fourier**
A DFT (Transformada Discreta de Fourier) representa um método fundamental para processar sinais digitais, possibilitando examinar sinais através de seus componentes frequenciais. Esta transformada realiza a conversão de uma série temporal discreta para uma representação em frequências discretas.

#### **Como Funciona a DFT**
Para uma sequência 𝑥[𝑛] com 𝑁 elementos, a transformada é calculada por:

<img src="https://github.com/user-attachments/assets/314c124d-e0e1-4408-b5a6-5d4301d91f3d" alt="Transformada Z" width="400"/>

sendo 𝑘 um valor entre 0 e 𝑁-1.

#### **Características Fundamentais**
- **Periodicidade:** Os resultados se repetem a cada 𝑁 pontos.
- **Simetria:** Quando os dados são reais, existe uma simetria conjugada nos resultados.
- **Linearidade:** Ao somar sinais, podemos somar suas transformadas individuais.

#### **Onde é Utilizada**
A DFT encontra uso em:
- **Investigação do espectro de frequências.**
- **Processamento de sinais no domínio frequencial.**
- **Técnicas de compactação de informações.**

#### **Anexos**
<table>
  <tr>
    <td align="center">
      <a href="https://colab.research.google.com/drive/1Ifc7uLiO3z2CWeZNPe90yAk5zuPg_bvH?usp=sharing">
        <b>Colab</b>
      </a>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=B7OVlVCyJPc">
        <b>Vídeo</b>
      </a>
    </td>
  </tr>
</table>
