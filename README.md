# Jardim de Tesouros Vivos · IV Edição

Site do **Festival Jardim de Tesouros Vivos da Cultura do Bom Jardim**, IV edição — 2026.
Uma realização do **Centro Cultural Bom Jardim (CCBJ)**, gerido pelo **Instituto Dragão do Mar (IDM)** em parceria com a **Secretaria da Cultura do Estado do Ceará (Secult CE)**.

---

## Sobre o Festival

O Festival Jardim de Tesouros Vivos é um festival cultural e educativo realizado no território do **Grande Bom Jardim**, periferia sudoeste de Fortaleza (CE). Sua IV edição, em 2026, elege como eixo central a relação entre **cultura e educação**, articulando Mestras e Mestres da Cultura com estudantes de três instituições públicas de ensino.

O festival se desenvolve em duas fases:

1. **Vivências no território** — estudantes visitam os próprios espaços dos mestres: academias de capoeira, terreiros, casas de cultura e pontos de memória do Grande Bom Jardim.
2. **Seminário de culminância no CCBJ** — *"Jardim de Tesouros Vivos: Mestres da Cultura na Escola"*, encontro com secretarias de educação, gestores escolares, universidades e instituições públicas, em busca de caminhos concretos para inserir os saberes tradicionais nas práticas pedagógicas das redes públicas.

**Escolas participantes da edição 2026:**
- Escola Municipal Professora Lireda Facó
- EMEIF José Alcides Pinto
- IFCE — Instituto Federal de Educação, Ciência e Tecnologia do Ceará

---

## Os Tesouros Vivos do Bom Jardim

Os quatro mestres e mestras homenageados nesta edição são reconhecidos pelo **Programa Tesouros Vivos da Cultura do Ceará** (Lei estadual 13.842/2006), política pública da Secult CE que concede subsídio mensal a detentores de saberes tradicionais. O Grande Bom Jardim é o território de Fortaleza com a maior concentração de mestres e mestras reconhecidos pelo Estado.

| # | Mestra / Mestre | Área | Local |
|---|---|---|---|
| I | **Mestra Carla Mara** | Capoeira | Associação Zumbi Capoeira · Grande Bom Jardim |
| II | **Mestra Mãe Zimá** | Medicina de terreiro | Casa de Ogum Megê · Granja Lisboa |
| III | **Mestre Lula** | Capoeira | Conselho de Mestres de Capoeira do CE |
| IV | **Pai Neto Tranca Rua** | Umbanda · Tambor de mina de caboclo | Maranguape, CE |

---

## Estrutura do projeto

```
jardim-de-tesouros/
│
├── index.html              # Landing page — hero, sobre o festival, cards dos mestres
├── catálogo.html           # Página de entrada do catálogo (índice das seções)
│
├── catalogo/               # Seções do catálogo (edição ampliada 2026)
│   ├── estilo.css          # Estilos compartilhados do catálogo
│   ├── apresentacao.html   # Apresentação e Carta do Superintendente do CCBJ
│   ├── especiais.html      # 20 anos do CCBJ · 60 anos da Secult CE
│   ├── carla-mara.html     # Perfil · Mestra Carla Mara
│   ├── mae-zima.html       # Perfil · Mestra Mãe Zimá
│   ├── mestre-lula.html    # Perfil · Mestre Lula
│   ├── pai-neto.html       # Perfil · Pai Neto Tranca Rua
│   ├── cartografia.html    # Cartografia afetiva do Grande Bom Jardim
│   ├── ponto-de-memoria.html # Ponto de Memória do Grande Bom Jardim
│   ├── festival.html       # O Festival e a Política dos Tesouros Vivos
│   └── arquivo.html        # Vozes · Glossário · Notas · Expediente · Colofão
│
└── image/                  # Assets de imagem
    ├── logo-bar.png              # Barra de logos institucionais (hero)
    ├── logos-institucionais.png  # Logos para o rodapé
    ├── mestra-carla.png          # Retrato · Mestra Carla Mara
    ├── mestra-zima.png           # Retrato · Mestra Mãe Zimá
    ├── mestre-lula.png           # Retrato · Mestre Lula
    ├── mestre-pai-neto.png       # Retrato · Pai Neto Tranca Rua
    └── tesouros-vivos.png        # Logomarca do Programa Tesouros Vivos (Secult CE)
```

---

## Tecnologia

Projeto em **HTML e CSS puro**, sem dependências de build ou frameworks.

- **Tipografia (Google Fonts):**
  - `Playfair Display` — títulos e destaques
  - `Cormorant Garamond` — corpo de texto
  - `DM Mono` — labels, metadados e numeração
  - `Source Serif 4` e `JetBrains Mono` — catálogo interno
- **JavaScript:** apenas a Intersection Observer API nativa para animações de scroll reveal
- **CSS:** variáveis customizadas, grid layout, animações com `@keyframes`
- **Responsivo:** breakpoint principal em `800px`

Para visualizar, basta abrir `index.html` diretamente no navegador — não há servidor necessário.

---

## Instituições realizadoras

| Instituição | Papel |
|---|---|
| **Centro Cultural Bom Jardim (CCBJ)** | Realizador do Festival |
| **Instituto Dragão do Mar (IDM)** | Gestão do CCBJ |
| **Secretaria da Cultura do Ceará (Secult CE)** | Parceiro institucional e mantenedor do Programa Tesouros Vivos |
| **Governo do Estado do Ceará** | Apoio institucional |

---

*Grande Bom Jardim · Fortaleza · Ceará · Brasil*
