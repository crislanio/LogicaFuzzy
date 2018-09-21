### Sistema de Controle Fuzzy
Vamos criar um sistema de controle fuzzy que modela como você pode escolher dar gorjeta em um restaurante. Ao dar gorjeta, você considera o serviço e a qualidade da comida, classificados entre 0 e 10. Você usa isso para deixar uma gorjeta entre 0 e 25%.

Nós formularíamos este problema como:
Antecedanças (Entradas)

#### serviço

Universo (ou seja, faixa de valores nítidos): Como foi bom o serviço da equipe de garçons, em uma escala de 0 a 10?
Conjunto fuzzy (ou seja, intervalo de valores difusos): fraco, aceitável, incrível

#### qualidade dos alimentos

Universo: Quão saborosa era a comida, numa escala de 0 a 10?
Conjunto fuzzy: ruim, decente, ótimo

Consequentes (Saídas)

#### gorjeta

Universo: quanto devemos dar gorjeta, numa escala de 0% a 25%
Conjunto fuzzy: baixo, médio, alto

Regras Se o serviço foi bom ou a qualidade da comida era boa, então a gorjeta será alta. Se o serviço foi médio, então a gorjeta será médio. Se o serviço foi ruim ea qualidade dos alimentos foi ruim, então a gorjeta será baixa

#### Uso 
Se eu disser a este controlador que eu avaliei:

#### o serviço como 9.8

#### a qualidade como 6.5,

#### recomendação de saída:

#### uma gorjeta de 20,2%.
