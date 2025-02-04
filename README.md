# Mastering Reinforcement Learning

Bem-vindo ao repositório **Mastering Reinforcement Learning**! Este repositório contém uma série de notebooks que abordam conceitos e implementações práticas de Aprendizado por Reforço (Reinforcement Learning). Ele é destinado a quem deseja aprender de forma prática como implementar e entender algoritmos clássicos de RL.

## Objetivo

O objetivo deste repositório é fornecer uma introdução sólida ao Aprendizado por Reforço, através de exemplos de código que utilizam o popular framework `gymnasium` para simulação de ambientes e treinamento de agentes. As três primeiras aulas abordarão conceitos essenciais e práticas fundamentais:

1. **Aula 1: Q-Learning no ambiente Taxi**  
   - Introdução ao algoritmo de Q-Learning.
   - Implementação do Q-Learning no ambiente `Taxi` do gymnasium, que envolve o aprendizado de um agente para transportar passageiros de uma localização para outra.

2. **Aula 2: FrozenLake e a Equação de Bellman**  
   - Abordagem da tomada de ação sequencial com base na Equação de Bellman.
   - Aplicação do algoritmo de Q-Learning no ambiente `FrozenLake`, onde o agente precisa navegar por um lago congelado evitando buracos e alcançando a meta.

3. **Aula 3: Deep Q-Learning**  
   - Introdução ao Deep Q-Learning, um método de aprendizado por reforço que utiliza redes neurais profundas.
   - Aplicação prática do algoritmo Deep Q-Learning em dois ambientes diferentes: `Breakout` e `LunarLander`.

## Estrutura do Repositório

```
Mastering-Reinforcement-Learning/
├── Aula1_Q_Learning_Taxi.ipynb
├── Aula2_Bellman.ipynb
├── Aula2_Grid_movements_RL.ipynb
├── Aula2_Q_Learning_FrozenLakev1.ipynb
├── Aula3_DQN_Breakout.ipynb
├── Aula3_DQN_LunarLander.ipynb
├── README.md
```

- **Aula1_Q_Learning_Taxi.ipynb**: Notebook que explora a implementação de Q-Learning no ambiente `Taxi` do gymnasium.
- **Aula2_Bellman.ipynb**: Explicação sobre a Equação de Bellman e sua relação com a tomada de decisão sequencial.
- **Aula2_Grid_movements_RL.ipynb**: Demonstração prática de movimentos em uma grade utilizando aprendizado por reforço.
- **Aula2_Q_Learning_FrozenLakev1.ipynb**: Implementação do algoritmo de Q-Learning no ambiente `FrozenLake`, explorando como o agente deve evitar buracos e alcançar a meta.
- **Aula3_DQN_Breakout.ipynb**: Implementação de Deep Q-Learning no ambiente `Breakout`, utilizando uma rede neural para aproximar a função de valor.
- **Aula3_DQN_LunarLander.ipynb**: Implementação de Deep Q-Learning no ambiente `LunarLander`, com uma rede neural que ajuda o agente a pousar com segurança.

## Como Rodar os Notebooks

1. Clone este repositório em seu ambiente local:

   ```bash
   git clone https://github.com/seu-usuario/Mastering-Reinforcement-Learning.git
   cd Mastering-Reinforcement-Learning
   ```

2. Instale as dependências necessárias (recomendamos o uso de um ambiente virtual).

3. Abra os notebooks utilizando Jupyter ou Google Colab e siga os passos descritos em cada aula.

## Dependências

Este repositório utiliza as seguintes bibliotecas:

- `gymnasium`: Para simulação de ambientes de aprendizado por reforço.
- `numpy`: Para manipulação de arrays e cálculos matemáticos.
- `matplotlib`: Para visualizações gráficas dos resultados.
- `tensorflow` ou `torch` (para Deep Q-Learning): Frameworks de deep learning para a implementação de redes neurais.

Você pode instalar todas as dependências com:

```bash
pip install gymnasium numpy matplotlib tensorflow
```

## Contribuições

Contribuições são bem-vindas! Se você deseja colaborar com melhorias no código ou sugestões de novos tópicos, por favor, abra uma *issue* ou envie um *pull request*.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
