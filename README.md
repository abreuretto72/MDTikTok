# MultiversoDigital - TikTok Direct Post Manager

O **MultiversoDigital** é uma ferramenta administrativa robusta desenvolvida em Flutter para Windows, projetada para a gestão de ativos de média e publicação direta (**Direct Post**) no TikTok.

## 🚀 Propósito do Projeto
Este aplicativo foi criado como uma ferramenta privada para permitir que o proprietário do app publique vídeos curados diretamente em perfis autorizados do TikTok, garantindo total controle sobre o fluxo de conteúdo e integridade da marca.

## 🛠️ Especificações Técnicas e Robustez
Seguindo a nossa "Lei de Ferro" de desenvolvimento, o projeto prioriza:
- **Estabilidade Total:** Código imune a travamentos (crashes) e erros silenciosos.
- **Persistência Segura:** Utilização de Hive para armazenamento local de tokens com reconstrução automática de boxes em caso de corrupção.
- **Interface Otimizada:** Telas com rolagem protegida e visibilidade total, adaptadas para evitar overflow.
- **Internacionalização:** Todas as mensagens, títulos e botões utilizam chaves de tradução (l10n), sem strings hardcoded.

## 🔐 Integração com TikTok API
O app utiliza os seguintes módulos da TikTok for Developers:
- **Login Kit:** Autenticação segura via OAuth 2.0.
- **Content Posting API:** Para upload binário e publicação direta (scopes `video.upload` e `video.publish`).

## ⚖️ Documentos Legais
Para transparência e conformidade com as políticas da ByteDance, os documentos oficiais podem ser acedidos aqui:
- [Termos de Serviço](terms.html)
- [Política de Privacidade](privacy.html)

---
*Desenvolvido por Belisario Retto de Abreu.*
