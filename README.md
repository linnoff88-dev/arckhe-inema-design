ï»¿# ê°Å¸Å½Â¨ INEMA Design

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![INEMA Design](guia/assets/banner.jpg)](https://inematds.github.io/inema-design/guia/)

**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

## O que êÂ©

O INEMA Design êÂ© uma pasta de arquivos de texto com as regras visuais do ecossistema INEMA: cores, fontes, jeito de escrever, cêÂ¢mera de vêÂ­deo e a lista do que o Nei jêÂ¡ reprovou. Serve para quem cria pêÂ¡ginas, guias, cursos, banners, explicavideos, shorts e reels com agentes como Claude Code e Codex. O agente lêÂª a pasta antes de comeêÂ§ar e a peêÂ§a sai no padrêÂ£o da marca, sem repetir erro antigo. Para usar, basta copiar a pasta e pedir ao agente que leia o CLAUDE.md dela primeiro.

## ê°Å¸ââ Guia de uso

Guia completo (landing + passo a passo): **https://inematds.github.io/inema-design/guia/**

## Estrutura

```
inema-design/
  CLAUDE.md                 ordem de leitura e jeito de trabalhar
  DESIGN.md                 a marca: nêÂºcleo comum + uma seêÂ§êÂ£o por linha (guia, curso v2/v5/v6, banner, thumb, vêÂ­deo)
  DECISOES.md               conflitos entre fontes e lacunas ê¢â¬â o dono escolhe
  MAPA-PROJETOS.md          onde cada recurso entra em cada projeto
  regras/
    pagina-20.md            20 pontos antes de publicar pêÂ¡gina + pontos INEMA
    texto.md                texto com cara de gente (PT)
    bar.md                  modelo "o que a referêÂªncia faz bem" + loop de crêÂ­ticos
  video/
    style.md                padrêÂ£o INEMA 16:9 e 9:16 + modelo para extrair de uma referêÂªncia
    camera.md               palavras de cêÂ¢mera com nêÂºmero e limites INEMA
    revisao-5-quadros.md    quadros 0/25/50/75/100% com nota de 0 a 10
  memoria/correcoes.md      tudo o que jêÂ¡ foi reprovado, uma linha por regra
  checks/preship.py         checagem estêÂ¡tica de HTML
  fonte/blueprint/          os arquivos originais do Claude Design Blueprint (EN)
  guia/                     esta pêÂ¡gina (PT/EN/ES)
```

## Uso rêÂ¡pido

```bash
git clone https://github.com/inematds/inema-design ~/projetos/inema-design
python3 ~/projetos/inema-design/checks/preship.py guia/index.html
```

E no agente: *"Leia ~/projetos/inema-design/CLAUDE.md e siga a ordem de leitura antes de criar a peêÂ§a."*

## Etapas

1. **Kit base** ê¢â¬â feito (10/10/2026). SêÂ³ arquivos.
2. **VêÂ­deo** ê¢â¬â revisêÂ£o de 5 quadros e style.md de referêÂªncia no refazvideo, depois nos outros motores.
3. **PêÂ¡ginas e cursos** ê¢â¬â a skill de guia e os formatos de curso passam a ler o DESIGN.md.

## CrêÂ©ditos

MêÂ©todo e arquivos de base do **Claude Design Blueprint** (compartilhado para uso livre). Checklist e lista de sinais de IA do **Power Design** e do **SlopMonster** (ItsssssJack, MIT). Formato DESIGN.md do Google Labs. Texto simples inspirado no ASD-STE100.

---
Feito por [INEMA.CLUB](https://inema.club)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>