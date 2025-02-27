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

### **Capítulo 6: Implementação de Filtros Discretos no Tempo**
No processamento digital de sinais, os filtros em tempo discreto são elementos fundamentais para manipulação e análise de sinais. Existem dois tipos principais de filtros: os Filtros com Resposta Finita ao Impulso (FIR) e os Filtros com Resposta Infinita ao Impulso (IIR).

#### **Filtros FIR**
Os Filtros FIR caracterizam-se por produzirem uma resposta limitada no tempo quando recebem um impulso como entrada. Isso significa que sua saída eventualmente retorna a zero após um determinado número de amostras. Uma das grandes vantagens desses filtros é sua estabilidade garantida e fase linear, características que os tornam excelentes escolhas para diversos cenários.

#### **Filtros IIR**
Os Filtros IIR apresentam uma resposta que teoricamente continua indefinidamente quando estimulados por um impulso. Embora possam oferecer maior eficiência computacional comparados aos FIR, apresentam algumas limitações: podem se tornar instáveis em certas condições e não mantêm a linearidade da fase em sua resposta.

#### **Anexos**
<table>
  <tr>
    <td align="center">
      <a href="https://colab.research.google.com/drive/1ZNQJ1ZDZMkpKjWw6CSYY0ptt1jtA388h?usp=sharing">
        <b>Colab</b>
      </a>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=W6Tlq2YrXGk">
        <b>Vídeo</b>
      </a>
    </td>
  </tr>
</table>

### **Capítulo 7: Projeto de Filtros FIR**
No processamento de sinais digitais, os filtros de Resposta Finita ao Impulso (FIR) destacam-se por suas características de estabilidade e fase linear. Para implementar um filtro FIR, é necessário calcular seus coeficientes de modo a alcançar determinadas características desejadas na resposta em frequência.

#### **Técnicas de Desenvolvimento de Filtros FIR**
Diversas abordagens podem ser utilizadas para criar filtros FIR, entre elas:
- **Técnica de Janelamento:** Utiliza funções de janela temporal, como Hamming ou Blackman, para multiplicar a resposta impulsiva ideal.
- **Método de Chebyshev:** Busca reduzir ao máximo a diferença entre a resposta em frequência obtida e a resposta desejada.
- **Técnica de Otimização por Mínimos Quadrados:** Reduz o valor médio quadrático do erro entre a resposta em frequência real e a ideal.

#### **Características Fundamentais dos Filtros FIR**
- **Garantia de Estabilidade:** Por não apresentarem pólos externos ao círculo unitário, os filtros FIR são inerentemente estáveis.
- **Linearidade de Fase:** Esta característica é essencial em sistemas onde alterações na fase do sinal devem ser evitadas.

#### **Anexos**
<table>
  <tr>
    <td align="center">
      <a href="https://colab.research.google.com/drive/1d_6C8wV7YLuYZDHyNu7SGN3TjVifN9VY?usp=sharing">
        <b>Colab</b>
      </a>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=u_tFWolPZY0">
        <b>Vídeo</b>
      </a>
    </td>
  </tr>
</table>
