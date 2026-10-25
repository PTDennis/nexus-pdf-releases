# Nexus PDF — versões

Instaladores do **Nexus PDF**, editor de PDF nativo para macOS (Apple Silicon, macOS 13 ou posterior): ler, anotar, assinar, preencher formulários, editar texto e imagens, comprimir, OCR. Sem conta nem subscrição. Uso interno.

## Instalar

1. Descarrega o `Nexus-PDF-x.y.zip` da [versão mais recente](../../releases/latest) e abre-o.
2. Arrasta o **Nexus PDF** para **Aplicações**.
3. Na primeira abertura o macOS mostra um aviso (a app não está notarizada pela Apple): em **Definições do Sistema → Privacidade e Segurança**, carrega em **Abrir mesmo assim**.

Depois disso, a app atualiza-se sozinha: procura uma vez por semana e propõe a atualização, ou usa **Nexus PDF → Procurar atualizações…**.

## Segurança das atualizações

Cada versão inclui `Nexus-PDF-x.y.zip` e uma assinatura `Nexus-PDF-x.y.zip.sig` (Ed25519). A app só instala pacotes cuja assinatura corresponde à chave pública que traz consigo, e nunca recua para uma versão mais antiga.

## Componentes de terceiros

Inclui o PDFium (licença BSD-3-Clause) e o qpdf (licença Apache-2.0). Os textos das licenças vão dentro da app.
