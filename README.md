# Tria

**Conferência de documentação clínica para hospitais de interior.**
O Tria mostra onde a documentação do hospital vai falhar, antes de o convênio auditar.

[Página do projeto](https://tria-auditoria.vercel.app) · [O problema em detalhe](docs/problema.md) · [LinkedIn do fundador](https://www.linkedin.com/in/pedro-gomes-sampaio-42539a409)

> Este repositório é a apresentação pública do Tria. O código do produto é privado.

## O problema

Glosa é quando o convênio nega ou retém o pagamento de uma conta hospitalar. Em 2024, a glosa média nos hospitais privados associados à Anahp chegou a 15,89%, com mais de R$ 5,8 bilhões em serviços prestados e não pagos. Mesmo quando a glosa cai no recurso, o dinheiro fica parado de 4 a 24 meses.

Muitas glosas não questionam o cuidado, e sim o registro. Em dois hospitais privados estudados, a glosa administrativa respondeu por 68,7% e 78,2% do valor glosado. No hospital de interior, que trabalha no papel, a conferência é manual e contra o relógio: as glosas grandes são vistas, os erros pequenos passam.

→ [Leia o problema em detalhe, com as fontes](docs/problema.md)

## Como funciona

<img src="assets/relatorio-exemplo.png" alt="Relatório de achados do Tria no celular, em um caso sintético" width="280" align="right">

1. **Foto.** Prescrição, anotação de enfermagem e evolução, fotografadas no celular. Basta abrir um link: não há nada para instalar.
2. **A IA lê.** A inteligência artificial só lê: transforma o papel em fatos, como medicamento e horário.
3. **O código cruza.** Regras fixas comparam os três documentos e mostram ao auditor onde eles não batem, com a razão de cada achado.

Ao lado, o relatório real do app em um caso sintético, sem nenhum dado de paciente.

## Por que o Tria

- **A IA só lê; o código decide.** A leitura é separada da regra, e cada achado traz a razão para o auditor conferir.
- **Confere tudo, não uma amostra.** Todos os documentos enviados passam pela conferência, inclusive os erros pequenos que a revisão manual não alcança.
- **Sem sistema, sem TI.** Funciona com foto de celular e com o papel que o hospital já tem. Não depende de prontuário eletrônico.
- **A decisão é do auditor.** O Tria aponta onde olhar. Corrigir, deixar de cobrar ou declarar continua sendo decisão de quem audita.

## Privacidade e limites

- O Tria não guarda os documentos. A imagem é enviada a um provedor de inteligência artificial só para a leitura.
- Use documentos sem identificação do paciente: antes da foto, cubra nome, leito e número do prontuário.
- Linha ilegível não vira chute: o Tria avisa para conferir no papel.
- Hoje o Tria confere medicação. Outros itens da conta vêm depois.

## Onde estamos

O Tria está em validação. O app está no ar, acessado por link, e funciona com o papel que o hospital já tem. Até agora foi testado só em casos sintéticos.

Próximos passos:

1. Testes reais com gestores e auditoria.
2. Validação técnica com um profissional auditor.
3. Primeiras instituições no uso gratuito e limitado.

## Quem faz

**Pedro Gomes Sampaio**, fundador, responsável por produto e desenvolvimento. Estudante de Ciência da Computação.

## Quer testar?

O uso é gratuito e limitado para hospitais que atendem convênio. Se você trabalha com auditoria, faturamento ou gestão hospitalar, [fale comigo pela página do projeto](https://tria-auditoria.vercel.app/#contato).
