# 💳 Upload e Validação de Cartões de Crédito com Azure Document Intelligence

Este projeto foi desenvolvido como parte do **Desafio 1 da DIO (Azure – Fake Docs)**.  
Ele permite que o usuário **faça upload de uma imagem (PNG, JPG, JPEG)** contendo informações de cartão de crédito.  
O arquivo é enviado para o **Azure Blob Storage**, e em seguida analisado pelo **Azure Document Intelligence** para verificar se o documento contém dados válidos de cartão.

---

## 🚀 Funcionalidades
- Upload de imagens de cartão de crédito.
- Envio automático para o **Azure Blob Storage**.
- Análise do documento com o modelo **prebuilt-creditCard** do Azure.
- Feedback visual indicando se o cartão é **válido** ou **inválido**.

---

## 🛠️ Tecnologias Utilizadas
- [Python 3.7+](https://www.python.org/)
- [Streamlit](https://streamlit.io/) – interface web
- [Azure Blob Storage](https://learn.microsoft.com/azure/storage/blobs/) – armazenamento dos arquivos
- [Azure Document Intelligence](https://learn.microsoft.com/azure/ai-services/document-intelligence/) – análise dos documentos




