# intelicondos-docs
Documentação Técnica Intelicondos

InteliCondos - Plataforma de Análise Inteligente para Condomínios

InteliCondos é uma plataforma SaaS que realiza análise econômico-financeira preditiva, preventiva e corretiva para condomínios, a partir da leitura automatizada de documentos como balancetes, extratos bancários, orçamentos, atas, contratos e regulamentos internos. Seu objetivo é gerar diagnósticos, relatórios e dashboards mais completos que qualquer consultoria tradicional.

📄 Documentos processados

A plataforma reconhece e interpreta automaticamente os seguintes tipos de documentos:

Balancete mensal (estrutura tipo DRE gerencial)

Extrato bancário

Orçamento anual

Ata de assembleia

Contrato de prestação de serviço

Regulamento interno / Convenção condominial

⚙️ Tecnologias e Componentes

Supabase: banco de dados, autenticação, storage e edge functions

Lovable: plataforma low-code para prototipagem da interface (multi-tenant)

Google Document AI: OCR inteligente com fallback

OpenAI (GPT-4o): interpretação de texto, análises e recomendações

pdf-parse: leitura local de PDFs como primeira opção

🔍 Diagnóstico automático

A IA extrai dados de forma estruturada e cruza as informações entre os documentos. Exemplos:

Receita prevista (orçamento) vs realizada (balancete + extrato)

Projeção de inadimplência

Forecast de caixa mensal

Incompatibilidades entre contrato e valores pagos

Análise SWOT (mini) baseada em contexto

✨ Diferenciais

Integração com a API da Superlógica (em andamento)

OCR + PDF parser + LLM combinados para maior acurácia

Visualização em dashboard financeiro interativo

Upload direto de documentos ou via API

Multi-tenant (por condomínio e por usuário)

🔑 Licença

Este repositório contém apenas a documentação pública. O código-fonte principal da plataforma é fechado. O uso das ideias e arquitetura aqui descritas está sujeito à licença Creative Commons BY-NC-ND 4.0:

❌ Não permite uso comercial sem autorização.
✅ Permite leitura, estudo, referência e citação com crédito.
❌ Não permite obras derivadas nem cópia direta da estrutura de produto.

📊 Roadmap



🚀 Para desenvolvedores

A documentação de integração, uso de parsers customizados, edge functions e configurações do Supabase está sendo montada nesta Wiki/README.

Caso queira colaborar, entre em contato via https://intelicondos.com.br ou abra uma issue com sugestões de melhoria.

🏠 Projeto desenvolvido por Alex Bahr - CEO da InteliCondos

