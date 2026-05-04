### Esse código cria um gráfico que mostra o aumento gradual da "força do ruído" ao longo do tempo. Embora o título mencione "Previsão do Vento", a lógica matemática por trás dele é o alicerce de modelos de IA generativa, como os que criam imagens (Stable Diffusion).

### Entendendo o que cada parte faz:



### 1. Configurações Iniciais:
- timesteps = 1000: Define que teremos 1000 passos de tempo (como se fossem segundos ou etapas).
- beta_start e beta_end: Definem o valor inicial (quase zero) e o valor final da intensidade desse "vento" ou ruído.

### 2. Criação da Progressão (np.linspace):
- O beta_schedule_linear cria uma linha reta que começa em 0.0001 e termina em 0.02, espalhando esses valores - igualmente pelos 1000 passos. Isso é chamado de Linear Schedule.

### 3. Visualização (matplotlib):
- O gráfico resultante é uma linha diagonal ascendente. No contexto de IA, isso representa o processo onde você começa com uma imagem nítida e vai adicionando "ruído" (vento/poeira) aos poucos até que a imagem original suma completamente.


### Em resumo: O código simula um aumento constante e linear na intensidade de uma variável (Beta) ao longo de 1000 etapas.

**Atividade 1** - Exemplo de criação de imagem  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erik-oliveira-leao/tempestade/blob/main/tempestade.ipynb)<br>