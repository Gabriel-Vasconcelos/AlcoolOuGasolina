# :car: Álcool Ou Gasolina 
Este repositório foi criado para submissão de um trabalho da disciplina de _Programação para Dispositivos Móveis_, parte do curso de _Sistemas e Mídias Digitais na UFC_, ministrado pelo Professor Windson Viana.

A tarefa envolve o desenvolvimento de um aplicativo Android que auxilia os usuários na escolha entre Álcool e Gasolina como combustível, com base nos valores fornecidos nos campos de entrada.

[Atualização] A tarefa envolve a atualização desse aplicativo para melhorar sua acessibilidade utilizando o <a href="https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.auditor&hl=pt_BR&gl=US">Scanner de Acessibilidade</a>

![posto_gasolina](https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/c6a74a14-8b2d-460a-878e-0cb280104752)

## :notebook: Atividade para nota - AT03 - Álcool ou Gasolina? - Apps Acessíveis 

Você deve fazer um aplicativo que facilite a vida de quem vai decidir se vai usar Álcool ou Gasolina no carro. Ele pode ter apenas uma única tela conforme mostrado ao lado. Você pode usar o código base fornecido pelo professor ou construir o seu. 

Mdifique as aplicações Vamos Rachar! e Álcool ou Gasolina para que elementos da sua interface tenham uma melhor acessibilidade de acordo com o *Scanner de Acessibilidade*

Repositório Vamos Rachar: https://github.com/Gabriel-Vasconcelos/LetsShare

Repositório Álcool ou Gasolina_: https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/

### :hammer: As features principais são:

1. (3 pontos): Descreva os erros apontados pelo Accessibility Scanner nas versões iniciais ilustrando com as capturas de tela feitas pelo app e um resumo das violações. :white_check_mark:
2. (5 pontos): Indique o repositório dos novos códigos, ilustrando as novas telas e as modificações de descrição realizadas para reduzir os problemas de acessibilidade. :white_check_mark:
3. (2 pontos): Com printscreens, compare os resultados do novo relatório do Accessibility Scanner e o da Parte 1 feito nas versões iniciais. :white_check_mark:

## 📋 Relatório

> Ao contrário do aplicativo *Vamos Rachar*, este apresentou um número significativamente maior de pontos assinalados pelo Scanner de Acessibilidade, no entanto, continuam sendo bem simples de se resolver. Os problemas apontados foram mais voltados ao textos, principalmente contraste da sua cor com a cor de background e em relação ao tamanho, também foi apontado problemas nos *Edit Text* envolvendo a cor e o tamanho. Por fim, o Scanner também apontou problemas envolvendo a imagem.


### A lista a seguir contém oportunidades de melhoria na acessibilidade de Com qual combustível?

#### Área de toque
*com.example.alcoolougasolina:id/edGasolina*
A altura deste item é 46dp. Considere definir a altura desta área de toque como 48dp ou maior.

#### Área de toque
*com.example.alcoolougasolina:id/edAlcool*
A altura deste item é 46dp. Considere definir a altura desta área de toque como 48dp ou maior.

#### Área de toque
*com.example.alcoolougasolina:id/swPercentual*
A altura deste item é 27dp. Considere definir a altura desta área de toque como 48dp ou maior.

#### Contraste da imagem
*com.example.alcoolougasolina:id/imageView*
A taxa de contraste da imagem é 2,46. Essa taxa baseia-se em uma estimativa da cor do primeiro plano #B19D9D e da cor de fundo #FAFAFA. Considere aumentar essa taxa para 3,00 ou mais.

#### Contraste do texto
*[32,125][461,179]*
A taxa de contraste do texto no item é 2,53. Ela é determinada com base na estimativa da cor do primeiro plano #FFFFFF e da cor de fundo #F7842D. Aumente esse valor para 3,00 ou mais.

#### Contraste do texto
*com.example.alcoolougasolina:id/titulo*
A taxa de contraste do texto no item é 1,86. Ela é determinada com base na estimativa da cor do primeiro plano #87C4CB e da cor de fundo #FAFAFA. Aumente esse valor para 3,00 ou mais.

#### Contraste do texto
*com.example.alcoolougasolina:id/edGasolina*
A taxa de contraste do texto no item é 2,23. Ela é determinada com base na estimativa da cor do primeiro plano #AAAAAA e da cor de fundo #FAFAFA. Aumente esse valor para 3,00 ou mais.

#### Contraste do texto
*com.example.alcoolougasolina:id/edAlcool*
A taxa de contraste do texto no item é 2,23. Ela é determinada com base na estimativa da cor do primeiro plano #AAAAAA e da cor de fundo #FAFAFA. Aumente esse valor para 3,00 ou mais.

#### Contraste do texto
*com.example.alcoolougasolina:id/btCalcular*
A taxa de contraste do texto no item é 2,53. Ela é determinada com base na estimativa da cor do primeiro plano #FFFFFF e da cor de fundo #F7842D. Aumente esse valor para 4,50 ou mais.

#### Contraste do texto
*[144,1320][576,1385]*
A taxa de contraste do texto no item é 2,73. Ela é determinada com base na estimativa da cor do primeiro plano #999999 e da cor de fundo #FAFAFA. Aumente esse valor para 3,00 ou mais.

#### Contraste do texto
*com.example.alcoolougasolina:id/tvResultado*
A taxa de contraste do texto no item é 1,86. Ela é determinada com base na estimativa da cor do primeiro plano #87C4CB e da cor de fundo #FAFAFA. Aumente esse valor para 3,00 ou mais.

#### Tamanho do texto
*[144,1320][576,1385]*
Especifique o texto em escala de pixels (sp).

#### Tamanho do texto
*com.example.alcoolougasolina:id/tvResultado*
Especifique o texto em escala de pixels (sp).

#### Tamanho do texto
*com.example.alcoolougasolina:id/edGasolina*
Modifique LayoutParams para permitir a expansão de texto.

#### Tamanho do texto
*com.example.alcoolougasolina:id/edAlcool*
Modifique LayoutParams para permitir a expansão de texto.

#### Tamanho do texto
*com.example.alcoolougasolina:id/btCalcular*
Modifique LayoutParams para permitir a expansão de texto.

#### Tamanho do texto
*com.example.alcoolougasolina:id/action_bar*
Modifique LayoutParams para permitir a expansão de texto.

### :camera: Prints do Scanner de Acessibilidade

<div>
  <img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/71fe4d7e-4e41-4f7a-acd8-569fca593147" width="500" height="auto" />
  <img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/5a8e3dd2-ee28-424d-ad9b-ffd7dc123adf" width="500" height="auto" />
  
  **Observação: Como pode ser visto acima, ainda há duas sugestões de melhoria pendentes. No entanto, elas estão relacionadas à cor da imagem. Para corrigir isso, seria necessário fazer edições no Photoshop ou no Illustrator (que foi a ferramenta utilizada inicialmente na edição dessa imagem).**
  
</div>

### Antes 
<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/9bd302ef-3421-403d-a86a-dcad64bce04a" width="500" height="auto" />

### Depois
<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/ee2920e6-8814-4281-9976-1dc869566045" width="500" height="auto" />

## :iphone: Demonstração do Aplicativo
https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/b544af6c-9d4f-439c-9d40-a4648c2f7914

### :camera: Prints

<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/a639cf92-b8f7-434f-acc0-fda8ebfaeac3" alt="posto_gasolina" width="auto" height="660">
<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/caf857d5-0423-48a0-b9be-b33f22b8aaf6" alt="posto_gasolina" width="auto" height="660">
<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/b8ba7b2a-d87f-46b1-a45e-e003bbc497c6" alt="posto_gasolina" width="auto" height="660">

<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/7a2034b6-2781-499c-be52-27c544e17151" alt="posto_gasolina" width="auto" height="660">
<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/38730bee-a24a-4853-956c-752b08a775ac" alt="posto_gasolina" width="auto" height="660">
<img src="https://github.com/Gabriel-Vasconcelos/AlcoolOuGasolina/assets/62850565/2452d9d0-1c2c-4712-b5bd-27dbc3d7205c" alt="posto_gasolina" width="auto" height="660">
