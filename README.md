# Registro de Atividade

Página web simples para registrar atividades e compartilhar o resumo no WhatsApp.

## Como usar

1. Abra o `index.html` no navegador do celular ou do computador.
2. Preencha os campos (data, horário, unidade, atividade, objetivo, público, participantes, responsável e resultados).
3. Adicione uma ou mais fotos do registro.
4. Toque em **Compartilhar** para enviar texto e fotos pelo compartilhamento do sistema, ou em **Copiar** para copiar a mensagem.

## Rascunho automático

O preenchimento é salvo automaticamente no próprio aparelho:

- os campos de texto ficam em `localStorage`;
- as fotos ficam em `IndexedDB`.

Se fechar ou recarregar a página sem querer, os dados voltam sozinhos ao abrir de novo. O botão **Limpar** apaga o rascunho.

## Estrutura

```
index.html   -> página única (formulário, prévia e compartilhamento)
logos/       -> imagens dos logos exibidos no topo
```

Não precisa de instalação nem build: é só abrir o `index.html`.
