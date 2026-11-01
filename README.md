# yuriportelaturismo

Site de divulgação dos passeios guiados em Santos e dos roteiros de viagem sob medida do Yuri Portela.

## O que tem aqui

```
index.html          a página inteira (HTML, CSS e um pouco de JS no mesmo arquivo)
img/hero.jpg        foto do topo
img/yuri.jpg        foto da seção "Quem guia"
img/manual-capa.jpg capa do Manual Anti-Perrengue
img/og.jpg          imagem que aparece quando o link é compartilhado
```

Não há build, dependência nem framework. É um arquivo estático: abrir o `index.html` no navegador já mostra o site como ele é.

## Como publicar

**Vercel** — importe este repositório, deixe o framework como "Other" e publique. Não configure build.

**GitHub Pages** — em Settings → Pages, escolha a branch `main` e a pasta `/ (root)`.

Nos dois casos, cada `git push` publica a nova versão.

## Ao registrar o domínio

Três linhas do `<head>` do `index.html` ainda apontam para `yuriportelaturismo.com.br`, que ainda não existe. Se o domínio final for outro, troque:

- `<link rel="canonical">`
- `<meta property="og:url">`
- `<meta property="og:image">`

Elas definem o endereço oficial da página no Google e a imagem que aparece quando alguém manda o link no WhatsApp.

## Pontos em aberto

- **Preço dos passeios.** Hoje a página diz "Eu passo no WhatsApp". Mostrar um valor, mesmo "a partir de", costuma aumentar os agendamentos.
- **Avaliações.** A página não tem nenhuma prova social. É o que mais falta.
- **Título profissional.** A página se apresenta como "guia de turismo" no topo e "monitor de turismo" nas credenciais. São categorias diferentes no Cadastur; vale deixar as duas iguais.

## Regras de atendimento publicadas

Estão na seção "Antes de agendar" e valem como combinado com o cliente:

- Cancelamento com mais de 24h devolve o valor; depois disso, uma remarcação sem custo.
- Sem mínimo nem máximo de pessoas.
- Crianças com responsável; até 6 anos não paga.
- Terreno plano; avisar antes para ajustar ritmo e paradas.
