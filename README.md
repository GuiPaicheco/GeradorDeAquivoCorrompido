# Gerador de arquivos para testes

Utilitário web de geração de arquivos inválidos para testes de upload, validação e tratamento de erros.

**Contexto:** Utilitário experimental.  
**Tecnologias:** HTML e JavaScript.

## Visão do projeto

Use os arquivos gerados em ambientes de teste para verificar mensagens de erro, validação de formato e comportamento de importadores.

## Executar localmente

Clone o repositório e sirva os arquivos localmente. Com Python instalado:

```bash
git clone https://github.com/GuiPaicheco/GeradorDeAquivoCorrompido.git
cd GeradorDeAquivoCorrompido
python -m http.server 8000 --bind 127.0.0.1
```

Abra [http://127.0.0.1:8000/index.html](http://127.0.0.1:8000/index.html). Preserve as pastas de imagens, estilos e scripts. Recursos externos, quando usados pela página, podem exigir conexão com a internet.

## Estrutura

- `index.html`

## Desenvolvimento

O repositório reúne o código e os materiais do projeto. Para avaliar mudanças, consulte o histórico de commits e diferencie recursos implementados de evoluções previstas.

Esta revisão documenta os arquivos disponíveis; não executou testes funcionais nem certificou o funcionamento das integrações.
