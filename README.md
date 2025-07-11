# 📄 pdfView

Este repositório contém uma versão **personalizada do PDF.js** (https://github.com/mozilla/pdf.js), mantida e adaptada pela equipe **Open Soluções Tributárias** para atender a requisitos específicos de visualização de documentos PDF em aplicações web.

---

## 🚀 Objetivo do Repositório

O objetivo principal deste repositório é fornecer um **visualizador de PDF seguro e simplificado**, com algumas funcionalidades **desativadas** para atender às necessidades internas da empresa e de seus clientes, especialmente em contextos onde:

- A exibição do PDF deve ocorrer sem permitir **download direto** ou **impressão**.
- O visualizador precisa ser **integrado a links temporários e seguros (Signed URLs)** gerados por sistemas como o **Supabase**.
- A experiência do usuário deve ser **controlada e personalizada**, respeitando o design e as políticas da Open Soluções Tributárias.

---

## 🛠️ Modificações Realizadas

Com base no projeto original do **Mozilla PDF.js**, as seguintes alterações foram aplicadas:

- 🔒 **Remoção dos botões de download e impressão**.
- 🎨 **Ajustes visuais no layout e na interface** para adequação a sistemas internos.
- 🔗 **Integração planejada com sistemas de armazenamento seguro**, como Supabase Storage.

Essas modificações visam **reduzir riscos de cópia não autorizada** e garantir que a leitura de documentos seja feita exclusivamente no ambiente controlado.

---

## 📜 Licenciamento

Este repositório continua licenciado sob a **Apache License 2.0**, conforme o projeto original.

- O arquivo `LICENSE` contém a licença oficial.
- O arquivo `NOTICE` documenta as modificações específicas feitas por **Open Soluções Tributárias**.

Você pode utilizar, modificar e distribuir este visualizador conforme os termos da Apache 2.0, respeitando as devidas atribuições e responsabilidades.

---

## 📌 Importante

Este repositório **não possui vínculo com a Mozilla Foundation**. A base do código vem do projeto **PDF.js** e foi apenas **adaptada para uso próprio e personalizado** pela **Open Soluções Tributárias**.

Repositório original:  
👉 https://github.com/mozilla/pdf.js

---

## 📥 Deploy e Uso

Para uso interno ou em sistemas da empresa:

1. Hospedar o conteúdo da pasta `/web` (já modificado) em qualquer ambiente web: GitHub Pages, Vercel, Netlify, servidor próprio.
2. Usar o `viewer.html` passando como parâmetro o link do arquivo PDF seguro:

