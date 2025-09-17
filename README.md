# carlosmantillaneto.github.io

# Gerador de XML vmPing

#link

https://carlosmantillaneto.github.io/

Uma aplicação web simples para gerar arquivos de configuração vmPing personalizados.

## Como usar

1. Acesse a página web
2. Preencha os campos:
   - **Segundo Octeto**: Valor entre 0-255 (zeros à esquerda serão removidos)
   - **Terceiro Octeto**: Valor entre 0-255 (zeros à esquerda serão removidos)
   - **Número Java**: Exatamente 4 dígitos (zeros à esquerda mantidos)
3. Clique em "Gerar Pacote ZIP"
4. Baixe o arquivo ZIP contendo:
   - `vmPing.exe` - Executável do vmPing
   - `vmPing.xml` - Arquivo de configuração personalizado

## Funcionalidades

- ✅ Interface web responsiva em português
- ✅ Validação de entrada em tempo real
- ✅ Normalização automática de octetos (remove zeros à esquerda)
- ✅ Preservação de zeros à esquerda no número Java
- ✅ Geração automática de pacote ZIP
- ✅ Download direto pelo navegador

## Tecnologias

- HTML5 + CSS3 (Bootstrap)
- JavaScript (JSZip para criação de arquivos ZIP)
- Hospedagem estática (GitHub Pages)

## Deploy no GitHub Pages

1. Faça fork/clone deste repositório
2. Adicione o arquivo `vmPing.exe` na raiz do repositório
3. Ative o GitHub Pages nas configurações do repositório
4. Acesse via: `https://seu-usuario.github.io/nome-do-repositorio`

## Estrutura de arquivos
