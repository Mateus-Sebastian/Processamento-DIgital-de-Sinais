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
