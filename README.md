# projeto-azure-zonas-disponibilidade
# O que são as zonas de disponibilidade.

Várias regiões do Azure fornecem zonas de disponibilidade, que são grupos separados de datacenters em uma região. Cada zona de disponibilidade tem energia, resfriamento e infraestrutura de rede independentes, para que, se uma zona sofrer uma interrupção, os serviços regionais, a capacidade e a alta disponibilidade sejam compatíveis com as zonas restantes.

As zonas de disponibilidade normalmente são separadas por vários quilômetros e geralmente estão dentro de uma distância de 100 quilômetros. Essa distância significa que eles estão próximos o suficiente para ter conexões de baixa latência com outras zonas de disponibilidade por meio de uma rede de alto desempenho. No entanto, elas estão longe o suficiente para reduzir a probabilidade de que mais de uma será afetada por interrupções ou condições climáticas locais.

Os locais de datacenter são selecionados usando critérios rigorosos de avaliação de riscos de vulnerabilidade. Esse processo identifica todos os riscos significativos específicos do datacenter e considera os riscos compartilhados entre as zonas de disponibilidade.

O diagrama a seguir mostra vários exemplos de regiões do Azure. As regiões 1 e 2 dão suporte a zonas de disponibilidade e as regiões 3 e 4 não têm zonas de disponibilidade.

[](https://github.com/ThiagoPereiraFunayama/projeto-azure-zonas-disponibilidade/blob/main/Captura%20de%20tela%20de%202025-07-23%2008-40-35.png)