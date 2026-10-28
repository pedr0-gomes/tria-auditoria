# Tria

**Confira antes. Receba pelo que fez.**

Fotografe a prescrição, a anotação de enfermagem e a evolução com o celular, e o Tria mostra onde os registros não batem, antes de o plano de saúde conferir. Assim a instituição recebe pelo cuidado que já prestou.

[Página do projeto](https://tria-auditoria.vercel.app) · [Vídeo de demonstração](https://tria-auditoria.vercel.app/#video) · [O problema em detalhe](docs/problema.md) · [Testar o Tria pelo WhatsApp](https://wa.me/5588998659065?text=Ol%C3%A1%2C%20Pedro%21%20Vim%20pela%20p%C3%A1gina%20do%20Tria%20e%20quero%20testar.) · [LinkedIn do fundador](https://www.linkedin.com/in/pedro-gomes-sampaio-42539a409)

> Este repositório é a apresentação pública do Tria. O código do produto é privado.

[![Vídeo de demonstração do Tria: do documento fotografado ao relatório de achados](assets/video-capa.jpg)](https://tria-auditoria.vercel.app/#video)

## O problema

Glosa é quando o plano de saúde nega ou retém o pagamento de uma conta hospitalar. Em 2025, a glosa média inicial nos hospitais associados à Anahp foi de 15,93% do faturamento; depois da negociação, só 1,72% se sustenta. E o dinheiro demora: em média 77 dias para receber das operadoras contra 48 para pagar os fornecedores, 29 dias a mais.

Algumas glosas não questionam o cuidado, e sim o registro: o que foi prescrito, o que foi feito e o que foi anotado precisam contar a mesma história. Num estudo de 424 prontuários de um hospital universitário (dados de 2006–07), a anotação de enfermagem estava presente em 99,5% deles, mas completa em apenas 2,4%. Conferir esses documentos à mão não dá conta de tudo: as glosas grandes são vistas, os erros pequenos passam.

→ [Leia o problema em detalhe, com as fontes](docs/problema.md)

## Como funciona

<img src="assets/relatorio-exemplo.png" alt="Relatório de achados do Tria no celular, em um caso sintético" width="280" align="right">

1. **Dados soltos.** O Tria recebe o documento como ele já existe. Hoje o app lê por foto de celular, e basta abrir um link: não há nada para instalar. Outros formatos (PDF, planilha, scan) entram conforme a necessidade de cada instituição.
2. **Conferência precisa.** A inteligência artificial só lê o que está escrito, linha por linha. Regras fixas cruzam os documentos entre si e mostram ao auditor onde a história não fecha, com a razão de cada achado.
3. **Valor protegido.** O relatório aponta onde olhar, tudo antes de o plano de saúde conferir. O painel de gestão e a visão de receita em risco estão em construção.

Ao lado, o relatório real do app em um caso sintético, sem nenhum dado de paciente.

## Por que o Tria

- **Precisão.** A IA só lê; as regras decidem. Cada achado traz a razão, e a decisão final é sempre do auditor.
- **Qualquer documento.** Aceita o documento como ele já existe (foto, PDF, planilha ou papel escaneado). Hoje o app lê por foto e confere medicamentos; as demais frentes entram conforme a necessidade.
- **Sem integração.** Funciona com o que o hospital já tem. Não depende de prontuário eletrônico nem de equipe de TI.
- **Resultado medido.** A sua auditoria confirma cada achado. O valor do Tria é medido no seu hospital, não prometido.

## Como começar

Você testa de graça, vê o resultado e decide.

1. **Testa.** Uso gratuito por 30 dias, com limite de uso. Você recebe um link e começa com documentos do seu hospital, sem identificação do paciente.
2. **Mede.** A sua auditoria confere e confirma os achados. Você vê, no seu próprio hospital, o que o Tria encontra.
3. **Assina.** Se o resultado valer, a assinatura é por instituição, em faixas de porte. Sem prazo fixo para decidir.

## O que o Tria confere

A administração de medicamentos é a primeira frente: cruza prescrição, anotação de enfermagem e evolução. O que a instituição precisar e ainda não existir, o Tria implementa.

| Frente | Estado |
|---|---|
| Administração de medicamentos | no ar |
| Materiais cirúrgicos | próxima |
| Exames e laudos | depois |
| Conta × prontuário | depois |
| Painel de gestão | depois |
| A sua prioridade | o que a sua instituição precisar |

## Privacidade e limites

- O Tria não guarda os documentos. A imagem é enviada a um provedor de inteligência artificial só para a leitura.
- Use documentos sem identificação do paciente: antes da foto, cubra nome, leito e número do prontuário.
- Foto desfocada é recusada antes da leitura, e linha ilegível não vira chute: o Tria avisa para conferir no papel.
- O Tria aponta onde olhar. Corrigir, deixar de cobrar ou declarar continua sendo decisão de quem audita.

## Onde estamos

O Tria está pronto para testar e busca as primeiras instituições. O app está no ar, acessado por link, e lê os documentos por foto. Até agora foi testado só em casos sintéticos.

O que vem a seguir está na tabela acima: materiais cirúrgicos, exames e laudos, conta × prontuário e painel de gestão.

## Quem faz

**Pedro Gomes Sampaio**, fundador, responsável por produto e desenvolvimento. Estudante de Ciência da Computação.

## Quer testar?

O uso é gratuito e limitado para instituições que atendem planos de saúde. Se você trabalha com auditoria, faturamento ou gestão hospitalar, [fale comigo pelo WhatsApp](https://tria-auditoria.vercel.app/#contato) e eu envio o seu link de acesso.
