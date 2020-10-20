# Por favor, escreva seus entendimentos sobre os tópicos abaixo:

- Sobre ser melhor estudante
- Sobre cdd
- Sobre o conjunto de técnicas de código
- Sobre cada funcionalidade implementada

# Sobre nos tornar melhores estudantes
<p align="justify">
Quando falamos sobre estudo, devemos levar em consideração que cada indivíduo aprende dentro do seu próprio tempo e no seu próprio ritmo. Portanto, algo muito importante é que não se deve ficar se comparando uns aos outros quando se trata deste assunto. Tendo dito isto, existem alguns fatores que devemos levar em consideração quando estamos estudando. </p>

## Um atleta treina muito antes de competir
<p align="justify">
Vamos pegar um exemplo de um atleta que pratica natação. Pois bem, se é seu primeiro dia nadando, é evidente que ele não terá um bom desempenho caso participe de uma competição, afinal ele não está preparado, o falta treino. Desta mesma forma, podemos dizer que quando queremos utilizar algo em nossas vidas para fins profissionais ou competitivos, devemos antes treinar. Quanto mais nós treinamos, mais competente nos tornamos e conseguimos desempenhar de forma mais ágil.
</p>

## Se prepare para aprender
<p align="justify">
Tenha em mente que quando estamos aprendendo algo completamente novo, é natural que necessitemos de um tempo maior para começar a nos sentirmos confortáveis e familiarizados com aquilo que estamos estudando. Sendo assim, é uma boa ideia parar para refletir, antes mesmo de começar os estudos, sobre o que já sabemos sobre determinado conteúdo e no que iremos ter que gastar mais tempo para aprender, para evitar frustrações.
</p>

# Sobre CDD
<p align="justify">
O CDD (Cognitive Driven Design) é uma teoria de design de código que tem como objetivo estabelecer limites de complexidade nos códigos, baseado na psicologia da cognição.<br/>
Nessa teoria, conta-se pontos de complexidade de acordo com alguns elementos no código. Sendo assim, cada um desses elementos contam 1 ponto de complexidade: branches no código (if, else, case), exceptions (try, catch, finally), acoplamento e funções como argumento.<br/>
A ideia é que a carga intrínseca (soma dos pontos de complexidade) não passe de 7 pontos, uma vez que passado, o entendimento do código é muito afetado, sendo mais difícil refatorá-lo e exigindo muito mais custo e tempo para realizar manutenções.
</p>

# Sobre o conjunto de técnicas de código
<p align="justify">
Devemos dar prioridade máxima ao funcionamento do código. Sendo assim, devemos executá-lo o mais rápido possível para minimizar o acúmulo de erros e termos uma melhor percepção do que está acontecendo de errado.<br/>
A proteção das bordas é extremamente importante, principalmente as mais externas. Para isso, utilizamos validações e redobramos nossa atenção quando se trata das bordas mais externas.<br/>
É importante que o seu código seja entendível por outras pessoas, uma vez que todos devem estar na mesma página para mais agilidade no desenvolvimento, e melhor compreeensão.
Nossos controllers devem ser 100% coesos.<br/>
Uma boa arquitetura facilita o entendimento.<br/>
</p>

# Sobre cada funcionalidade implementada e entendimentos em geral

## Validadores personalizados
<p align="justify">
Com o Spring, podemos criar validadores personalizados para determinado input onde os validadores pré-definidos não satisfazem nossa necessidade de negócio. Para isso, criamos uma anotação e uma classe, que implementa a interface ConstraintValidator, com nossa regra dentro.
</p>

## Entidadeds anêmicas
<p align="justify">
Podemos ter uma ideia de que podemos melhorar nosso código quando percebemos que temos muitas entidades anêmicas, que são entidades que possuem somente um conjunto de atributos, deixando toda a regra de negócio na responsabilidade de outra camada. Portanto, devemos evitar ter entidades anêmicas, uma vez que quando adotamos o modelo anêmico, estamos deixando de lado todos os benefícios da orientação a objetos.
</p>
