# Açougue 500 Classe A — Site Informativo

Site estático e responsivo, pronto para publicar no GitHub Pages.

## Estrutura
```
acougue-500-classe-a/
├─ index.html
├─ assets/
│  ├─ css/styles.css
│  ├─ js/data.js
│  ├─ js/main.js
│  ├─ img/… (imagens de exemplo)
│  └─ icons/logo.svg, favicon.png
└─ README.md
```

## Como usar
1. Substitua textos, telefones, endereço e imagens na pasta `assets/img`.
2. Ajuste os dados em `assets/js/data.js` (produtos, ofertas, galeria e depoimentos).
3. Publique no GitHub:
   - Crie um repositório e faça upload de todos os arquivos.
   - Vá em **Settings › Pages** e selecione a branch `main` e a pasta `/ (root)`.
   - O site ficará disponível em `https://seu-usuario.github.io/nome-do-repo`.

## Observações
- O formulário usa `mailto:` como fallback. Para receber mensagens sem abrir e-mail, use um serviço como Formspree/EmailJS e troque a lógica em `main.js`.
- O mapa é um *embed* do Google Maps genérico — troque a URL pelo seu endereço real.
- As imagens são *placeholders*; substitua por fotos reais do açougue.
