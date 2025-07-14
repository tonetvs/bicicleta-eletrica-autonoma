# Simulação Dinâmica De Uma Bicicleta Elétrica Autônoma

Este projeto apresenta a modelagem e simulação completa de uma bicicleta elétrica autônoma em ambientes com subidas, descidas e curvas suaves. O sistema foi construído do zero com foco em aplicações reais de mobilidade elétrica, controle inteligente e otimização energética.

## Objetivo

- Simular o comportamento dinâmico de uma bicicleta elétrica sob diferentes condições
- Implementar controladores autônomos de velocidade e trajetória
- Monitorar o consumo energético da bateria em tempo real
- Analisar o desempenho físico e energético por setor da pista

## Componentes do Projeto

### Modelos Físicos

- **Modelo Longitudinal Realista:** considera tração, arrasto, rolamento, gravidade e regeneração de energia.
- **Modelo Cinemático de Bicicleta:** atualiza a pose (posição e orientação) ao longo da pista.

### Controle

- **PID:** para controle suave da velocidade alvo.
- **Stanley Controller:** para controle de trajetória preciso e estável.

### Visualizações

- Gráficos de posição, orientação, velocidade, torque e consumo de energia
- Logs e análise por setor do circuito
- Pista com elevação baseada em seno e trechos variados

## Bibliotecas Utilizadas

numpy  
pandas  
matplotlib  
seaborn  
plotly  
IPython.display (HTML)  

## Execução

O notebook está pronto para ser executado em Google Colab ou Jupyter Notebook. Todos os modelos estão encapsulados e simulam a física real da bicicleta elétrica com base nos parâmetros fornecidos. Para acessar a versão completa com todos os gráficos, tabelas e análises rodadas, acesse:

https://drive.google.com/file/d/1CUF5UIek2F2t5kC4Xt1BVwTa2tPPtiwO/view?usp=drive_link

## Estrutura

bicicleta_eletrica_autonoma/  
├── notebooks/  
│   └── Bicicleta_Elétrica_Autônoma.ipynb  
├── README.md    
└── LICENSE

## Autor

Heitor Tonet  
Engenheiro de Controle e Automação e Cientista de Dados, com foco em aplicações industriais, mobilidade inteligente e modelagem preditiva aplicada ao mundo físico.

## Licença

Distribuído sob a licença MIT.
