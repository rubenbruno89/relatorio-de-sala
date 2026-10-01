# Relatório de Salas sem Uso

Site simples para registrar as salas sem uso de uma faculdade, gerar um relatório com data e hora e enviá-lo pelo WhatsApp.

## Acesse o site

**https://rubenbruno89.github.io/relatorio-de-sala/**

Funciona no celular e no computador, direto no navegador. Não precisa instalar nada nem fazer login.

## O que dá para fazer

- Informar a **data** e a **hora** do relatório (já vêm preenchidas com o momento atual).
- Adicionar o **número das salas** sem uso, uma a uma ou várias de uma vez, separadas por vírgula (ex.: `101, 102, 205`).
- Remover uma sala da lista com um toque.
- Incluir, se quiser, o bloco ou unidade, o responsável e observações.
- Ver o relatório pronto em texto antes de enviar.
- **Enviar pelo WhatsApp** com o texto já preenchido, para um número específico ou para o contato que você escolher.
- **Copiar** o relatório para colar em outro lugar.
- Limpar a lista de salas para começar um novo relatório.

Os últimos dados digitados ficam salvos no navegador do próprio aparelho.

## Como usar

1. Abra o site.
2. Confira a data e a hora, ou toque em **Usar data e hora atuais**.
3. Digite o número de cada sala sem uso e toque em **Adicionar**.
4. Preencha os campos opcionais, se precisar.
5. (Opcional) Informe o número de WhatsApp de destino, com DDD.
6. Toque em **Enviar pelo WhatsApp**.

## Exemplo de relatório

```
*RELATÓRIO DE SALAS SEM USO*
Data: 01/10/2026
Hora: 14:30
Local: Bloco B

Salas sem uso (3): 101, 102, 205

Obs.: luzes e ar-condicionado ligados

Responsável: Nome do responsável
```

## Tecnologias

HTML, CSS e JavaScript puros, em um único arquivo (`index.html`). Sem dependências e sem servidor.

## Publicação no GitHub Pages

1. Envie o arquivo `index.html` e este `README.md` para o repositório `relatorio-de-sala`.
2. No GitHub, abra **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`.
4. Salve. Em alguns minutos o site fica disponível no endereço acima.

## Licença

Uso livre. Adapte como precisar.
