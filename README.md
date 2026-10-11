<h1 align="center">Joberth Firmino Gambati</h1>

<p align="center">
  <strong>Engenheiro Sanitarista e Ambiental · Geoprocessamento, Sensoriamento Remoto e Automação com Python</strong><br>
  Cuiabá, Mato Grosso, Brasil
</p>

<p align="center">
  <a href="https://yiuky.github.io"><img src="https://img.shields.io/badge/🌐%20Website-yiuky.github.io-0F172A?style=for-the-badge" alt="Website"></a>
  <a href="https://github.com/Yiuky/ArcMagery-releases"><img src="https://img.shields.io/badge/Projeto%20principal-ArcMagery%20%26%20QMagery-1B4F72?style=for-the-badge" alt="ArcMagery & QMagery"></a>
  <a href="https://github.com/Yiuky/PrivioSentry"><img src="https://img.shields.io/badge/IA%20local-PrivioSentry-6941C6?style=for-the-badge" alt="PrivioSentry"></a>
  <a href="https://doi.org/10.5380/raega.v63i2.99969"><img src="https://img.shields.io/badge/Artigo-RA'E%20GA%202025-0B5345?style=for-the-badge" alt="Artigo RA'E GA 2025"></a>
  <a href="https://www.linkedin.com/in/joberth-firmino-gambati-57248a94"><img src="https://img.shields.io/badge/in%20LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="#-doe-um-café-para-o-dev"><img src="https://img.shields.io/badge/%E2%98%95%20Doe%20um%20caf%C3%A9-Pix-E67E22?style=for-the-badge" alt="Doe um café"></a>
</p>

---

## 🌎 Sobre mim

Trabalho na Secretaria de Estado de Meio Ambiente de Mato Grosso (SEMA-MT), na Coordenadoria de
Geoprocessamento e Monitoramento Ambiental (CGMA). Mato Grosso tem mais de 2,5 vezes a área da Alemanha e
abriga Amazônia, Cerrado e Pantanal: trabalhar com dados geoespaciais aqui é trabalhar em escala.

Fora do expediente, desenvolvo ferramentas próprias desde 2020: **imagens de satélite, processamento
geoespacial, automação com Python** e, mais recentemente, **inteligência artificial rodando localmente**.

> Os projetos publicados aqui são **pessoais e independentes**. Não são produtos de nenhuma instituição nem
> falam em nome dela.

## 🚀 Projetos públicos

<p>
  <a href="https://github.com/Yiuky/ArcMagery"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Yiuky&repo=ArcMagery&locale=pt-br&description_lines_count=3" alt="ArcMagery" height="140"></a>
  <a href="https://github.com/Yiuky/PrivioSentry"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Yiuky&repo=PrivioSentry&locale=pt-br&description_lines_count=3" alt="PrivioSentry" height="140"></a>
  <a href="https://github.com/Yiuky/ReperIO"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Yiuky&repo=ReperIO&locale=pt-br&description_lines_count=3" alt="ReperIO" height="140"></a>
  <a href="https://github.com/Yiuky/CODES"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Yiuky&repo=CODES&locale=pt-br&description_lines_count=3" alt="CODES" height="140"></a>
</p>

- **[ArcMagery & QMagery](https://github.com/Yiuky/ArcMagery-releases)** (Python 2.7 + 3, open source,
  MIT): Ferramenta para ArcGIS Desktop (ArcMap 10.8) e QGIS (3.18+) que busca, recorta e carrega imagens de
  satélite direto no mapa na resolução nativa, de seis fontes: Google Earth Engine, CBERS-2/4/Amazônia-1 (INPE),
  SPOT 1–5 (CNES, com alinhamento por correlação de fase), Google Earth histórico, Esri Wayback e XYZ.
  Motor portátil independente, instalador automatizado, verificação SHA-256 e repositório próprio de plugins do QGIS.
- **[PrivioSentry](https://github.com/Yiuky/PrivioSentry)** (Python, open source, AGPL-3.0): encontra CPFs e
  endereços pessoais em PDFs com IA que roda na própria máquina (Tesseract OCR + detector YOLO de assinaturas +
  LLM de visão via Ollama), sugere as tarjas e leva tudo para revisão humana num editor web, com verificação
  pós-tarja que **falha fechado**: na dúvida, o documento vai para revisão. Apoia práticas alinhadas à LGPD,
  sem prometer anonimização garantida.
- **[ReperIO](https://github.com/Yiuky/ReperIO)** (Python, open source, MIT): encontra, indexa, exporta
  (Excel/CSV/TXT) e copia arquivos em servidores de arquivos grandes e lentos (SMB/DFS), sem instalar nada.
  Executável único para Windows e Linux, que não trava com pastas que congelam a conexão.
- **[CODES](https://github.com/Yiuky/CODES)**: scripts para metadados EXIF de fotos de campo (carimbo de
  data, hora e coordenadas; gravação de GPS).

## 🛠️ Áreas de atuação

| Área | Experiência |
|---|---|
| 🛰️ **Sensoriamento remoto** | Google Earth Engine, catálogos STAC, mosaicos e índices espectrais, georreferenciamento e corregistro de imagens |
| 🗺️ **Geoprocessamento** | ArcGIS/arcpy, QGIS/PyQGIS, GDAL/OGR, GeoPandas; análises topológicas entre camadas; bancos espaciais (PostGIS, Oracle Spatial) |
| 🤖 **Automação e ETL** | Rotinas que baixam e atualizam bases públicas, com fallback entre fontes, multiprocessamento e publicação em GeoServer via REST |
| 🧠 **IA local** | Visão computacional (YOLO + OCR) e LLMs rodando na própria máquina (Ollama) para processar documentos sem enviar dados para fora, como no [PrivioSentry](https://github.com/Yiuky/PrivioSentry) |
| 🧰 **Ferramentas para não programadores** | Interfaces gráficas, instaladores com diagnóstico e atualização automática, executáveis únicos sem instalação ([ReperIO](https://github.com/Yiuky/ReperIO)) |

## 💻 Tecnologias

**Geo:**
<img src="https://img.shields.io/badge/ArcGIS%20%2F%20arcpy-2C7AC3?logo=arcgis&logoColor=white" alt="ArcGIS">
<img src="https://img.shields.io/badge/QGIS%20%2F%20PyQGIS-589632?logo=qgis&logoColor=white" alt="QGIS">
<img src="https://img.shields.io/badge/GDAL%20%2F%20OGR-5CAE58?logo=gdal&logoColor=white" alt="GDAL">
<img src="https://img.shields.io/badge/GeoPandas%20%2F%20Shapely-139C5A?logo=geopandas&logoColor=white" alt="GeoPandas">
<img src="https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?logo=googleearthengine&logoColor=white" alt="Google Earth Engine">
<img src="https://img.shields.io/badge/GeoServer-0088A9" alt="GeoServer">
<img src="https://img.shields.io/badge/PostGIS-336791?logo=postgresql&logoColor=white" alt="PostGIS">
<img src="https://img.shields.io/badge/Oracle%20Spatial-F80000" alt="Oracle Spatial">

**Linguagem e aplicações:**
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white" alt="Streamlit">
<img src="https://img.shields.io/badge/Apache%20Superset-20A6C9?logo=apachesuperset&logoColor=white" alt="Superset">
<img src="https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white" alt="Selenium">

**IA:**
<img src="https://img.shields.io/badge/Ollama%20%2F%20LLMs%20locais-000000?logo=ollama&logoColor=white" alt="Ollama">
<img src="https://img.shields.io/badge/YOLO%20%2F%20OCR-5C3EE8?logo=opencv&logoColor=white" alt="YOLO OCR">
<img src="https://img.shields.io/badge/Claude%20Code-D97757?logo=claude&logoColor=white" alt="Claude Code">

## 📚 Formação e pesquisa

- 🎓 **Engenharia Sanitária e Ambiental**, Universidade Federal de Mato Grosso (UFMT).
- 📄 **Artigo:** *Aplicação integrada de TGI e NDMI para identificação de desmatamento químico no Pantanal,
  Brasil.* Revista RA'E GA (UFPR), v. 63, n. 2, 2025. Ferreira, J. C.; Dias, A. P.; **Gambati, J. F.**
  [DOI 10.5380/raega.v63i2.99969](https://doi.org/10.5380/raega.v63i2.99969)
  ([versão em inglês](https://revistas.ufpr.br/raega/article/view/99972)).
- 🤖 **Em curso (ago–nov/2026):** Formação Institucional em Claude Code (SEMA-MT, 100 h): governança, engenharia de contexto,
  agentes e uso seguro de IA no desenvolvimento de software.
- 🏗️ Coordenador do **Crea Júnior-MT**, Núcleo Centro Sul (2018).

## ☕ Doe um café para o dev

Se algum projeto meu economizou o seu tempo, considere pagar um café: ajuda a manter os projetos abertos e
evoluindo.

<table>
  <tr>
    <td align="center"><img src="pix_qrcode.png" alt="QR Code Pix" width="170" /></td>
    <td>
      <strong>Pix</strong> (qualquer valor)<br><br>
      Chave aleatória:<br>
      <code>fcf8071f-416d-49f1-b4b9-3188d3d03c4b</code><br><br>
      Pix copia e cola:<br>
      <code>00020101021126580014br.gov.bcb.pix0136fcf8071f-416d-49f1-b4b9-3188d3d03c4b5204000053039865802BR5917JOBERTH F GAMBATI6006CUIABA62070503***63048088</code><br><br>
      <em>Favorecido: Joberth Firmino Gambati</em>
    </td>
  </tr>
</table>

## 📫 Contato

Sugestões, dúvidas e problemas com os projetos: abra uma *issue* no repositório correspondente.
Para contato profissional, use o [LinkedIn](https://www.linkedin.com/in/joberth-firmino-gambati-57248a94).
