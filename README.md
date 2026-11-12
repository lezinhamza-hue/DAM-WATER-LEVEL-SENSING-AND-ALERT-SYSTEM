
# Sistema de Monitoramento do Nível de Água em Barragens

Este projeto é um sistema de monitoramento em tempo real do nível da água em barragens, desenvolvido para melhorar a segurança e prevenir possíveis acidentes.

Ele utiliza um Arduino Uno, um sensor ultrassônico HC-SR04 para medir a distância da água, uma tela LCD I2C 16x2 para mostrar as informações e um buzzer para emitir alertas.

## Problema

O monitoramento do nível da água é muito importante para evitar transbordamentos, enchentes e prejuízos à população. Métodos tradicionais dependem de verificações manuais, que podem demorar e apresentar falhas.

## Solução

O sistema utiliza um sensor ultrassônico para medir a distância até a superfície da água. O Arduino processa essas informações e calcula a porcentagem do nível da água.

A tela LCD mostra os resultados, enquanto o buzzer é acionado quando o nível atinge valores perigosos, a partir de 80%.

## Funcionalidades

- Monitoramento contínuo do nível da água.
- Medição sem contato físico usando sensor ultrassônico.
- Exibição da porcentagem em uma tela LCD.
- Representação do nível por meio de uma barra gráfica.
- Alarme sonoro automático em situações de perigo.
- Projeto de baixo custo e fácil reprodução.

## Objetivo

Ajudar no monitoramento de barragens, facilitando a identificação de níveis perigosos de água e contribuindo para a prevenção de enchentes.

## Classificação dos Níveis de Água

Para facilitar a identificação de possíveis situações de risco, podemos utilizar quatro níveis de classificação:

- **Normal (0% a 49%):** nível dentro da faixa considerada normal no exemplo.
- **Atenção (50% a 69%):** é necessário acompanhar o nível da água.
- **Alerta (70% a 79%):** o nível está elevado e exige maior atenção.
- **Emergência (80% a 100%):** o sistema aciona o alarme sonoro.

Essas porcentagens são exemplos didáticos e não representam limites oficiais de segurança. Os valores reais devem ser definidos por critérios técnicos.

## Referências

Projeto utilizado como referência: [Dam Water Level Sensing and Alert System](https://github.com/lezinhamza-hue/DAM-WATER-LEVEL-SENSING-AND-ALERT-SYSTEM).

Também utilizei minha cópia (Fork): [Meu Fork](https://github.com/sobre334/DAM-WATER-LEVEL-SENSING-AND-ALERT-SYSTEM).

A principal ideia aproveitada foi a classificação dos níveis de água em diferentes situações de risco: Normal, Atenção, Alerta e Emergência. Essa organização ajuda a identificar situações perigosas e apresentar avisos de forma mais clara.
