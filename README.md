# HENRIQUE TAVEIRA — Site Oficial & Ateliê Artsy Consolidado

> **Plataforma Web Unificada & Indexada no GitHub Pages**  
> Fusão do design minimalista/artsy de alta sofisticação (`HENRIQUETAVEIRA`) com o acervo e conteúdos completos (`HENRIQUETAVEIRAFERREIRA`).

---

## 🏛️ Arquitetura do Projeto

- **`index.html`**: Single Page Application (SPA) responsiva com design minimalista/editorial:
  - Cursor magnético personalizado (`VER`)
  - Tipografia de luxo `Jost` com tracking editorial
  - Filtro por categorias com barra sticky (Desktop) e barra arredondada flutuante (Mobile)
  - Visualizador detalhado de obras em alta resolução com gaveta retrátil de **Ficha Técnica** e **Lightbox**
  - Seções consolidadas: *Panorama Geral*, *Moda & Alfaiataria (Animale)*, *Artes Visuais & Têxtil*, *Pintura & Série Corpo*, *Projetos Especiais (CBF x Animale - Copa 2023)*, *Processo, Lab & Pesquisa (Veneza, Calder, Moulage)*, *Lab Dali.lido*, *Sobre / Biografia (IED / PUC)* e *Ateliê Concierge WhatsApp*.
- **`editor.html`**: Painel Studio 3.0 Pro para edição visual ao vivo com exportação de `content.json`.
- **`content.json`**: Fonte da verdade desacoplada com todas as categorias, obras, kickers, biografias e contatos.
- **`fotos/`**: Acervo local de 231 imagens em alta resolução otimizadas para carregamento rápido.
- **`sitemap.xml` & `robots.txt`**: Configuração completa para indexação no Google Search Console, Bing e redes sociais.
- **`.nojekyll`**: Garante compatibilidade direta com o GitHub Pages.
- **`404.html`**: Página de erro personalizada com a mesma identidade visual.

---

## 🚀 Como Visualizar e Testar Localmente

1. Basta abrir o arquivo `index.html` em qualquer navegador (Chrome, Edge, Safari, Firefox).
2. Para editar dados e fotos graficamente, abra `editor.html` no navegador e exporte o `content.json`.
3. Para validar a integridade da plataforma:
   ```bash
   python validate_platform.py
   ```

---

## 🌐 Publicação no GitHub Pages

Para publicar este site no seu repositório do GitHub (`fariatitan/HENRIQUETAVEIRA`):
1. Suba o conteúdo desta pasta `(010) SITE CONSOLIDADO ARTSY` para a raiz do repositório ou branch `main` / `gh-pages`.
2. No GitHub: **Settings -> Pages -> Deploy from a branch -> / (root)**.
3. O site estará disponível e indexado com SEO completo em:  
   👉 `https://fariatitan.github.io/HENRIQUETAVEIRA/`
