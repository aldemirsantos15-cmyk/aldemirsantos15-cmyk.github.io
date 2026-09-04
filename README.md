# Inspeção 3D — versão de teste para GitHub Pages

Versão estática de demonstração da plataforma Inspeção 3D, preparada para publicação direta no GitHub Pages.

## Recursos disponíveis

- Dashboard e indicadores
- Inventário de extintores e mangueiras
- Gêmeo digital 3D simplificado
- Inspeções
- Evidências fotográficas/documentais
- Não conformidades e pendências
- Manutenção e ensaios
- Plano de substituição
- Relatório técnico com impressão/PDF
- Importação XLSX/CSV no navegador
- Trilha de auditoria
- Configuração do condomínio
- Persistência local com `localStorage`

## Publicar no GitHub Pages

1. Crie um repositório, por exemplo `inspecao3d`.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **GitHub Actions**.
5. O workflow `.github/workflows/pages.yml` fará a publicação.
6. Após a publicação, o endereço será semelhante a:
   `https://SEU-USUARIO.github.io/inspecao3d/`

## Limitações da versão de teste

Esta versão não possui backend, banco de dados compartilhado, autenticação, armazenamento remoto de fotos ou motor normativo conectado a fontes oficiais. Os dados ficam no navegador do usuário.

O conteúdo técnico deve ser tratado como apoio à inspeção. O sistema não deve transformar inferências visuais em conclusões normativas definitivas.
