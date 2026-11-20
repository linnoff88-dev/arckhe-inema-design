# ðŸŽ¨ INEMA Design

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![INEMA Design](guia/assets/banner.jpg)](https://inematds.github.io/inema-design/guia/)

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## O que Ã©

O INEMA Design Ã© uma pasta de arquivos de texto com as regras visuais do ecossistema INEMA: cores, fontes, jeito de escrever, cÃ¢mera de vÃ­deo e a lista do que o Nei jÃ¡ reprovou. Serve para quem cria pÃ¡ginas, guias, cursos, banners, explicavideos, shorts e reels com agentes como Claude Code e Codex. O agente lÃª a pasta antes de comeÃ§ar e a peÃ§a sai no padrÃ£o da marca, sem repetir erro antigo. Para usar, basta copiar a pasta e pedir ao agente que leia o CLAUDE.md dela primeiro.

## ðŸ“– Guia de uso

Guia completo (landing + passo a passo): **https://inematds.github.io/inema-design/guia/**

## Estrutura

```
inema-design/
  CLAUDE.md                 ordem de leitura e jeito de trabalhar
  DESIGN.md                 a marca: nÃºcleo comum + uma seÃ§Ã£o por linha (guia, curso v2/v5/v6, banner, thumb, vÃ­deo)
  DECISOES.md               conflitos entre fontes e lacunas â€” o dono escolhe
  MAPA-PROJETOS.md          onde cada recurso entra em cada projeto
  regras/
    pagina-20.md            20 pontos antes de publicar pÃ¡gina + pontos INEMA
    texto.md                texto com cara de gente (PT)
    bar.md                  modelo "o que a referÃªncia faz bem" + loop de crÃ­ticos
  video/
    style.md                padrÃ£o INEMA 16:9 e 9:16 + modelo para extrair de uma referÃªncia
    camera.md               palavras de cÃ¢mera com nÃºmero e limites INEMA
    revisao-5-quadros.md    quadros 0/25/50/75/100% com nota de 0 a 10
  memoria/correcoes.md      tudo o que jÃ¡ foi reprovado, uma linha por regra
  checks/preship.py         checagem estÃ¡tica de HTML
  fonte/blueprint/          os arquivos originais do Claude Design Blueprint (EN)
  guia/                     esta pÃ¡gina (PT/EN/ES)
```

## Uso rÃ¡pido

```bash
git clone https://github.com/inematds/inema-design ~/projetos/inema-design
python3 ~/projetos/inema-design/checks/preship.py guia/index.html
```

E no agente: *"Leia ~/projetos/inema-design/CLAUDE.md e siga a ordem de leitura antes de criar a peÃ§a."*

## Etapas

1. **Kit base** â€” feito (10/10/2026). SÃ³ arquivos.
2. **VÃ­deo** â€” revisÃ£o de 5 quadros e style.md de referÃªncia no refazvideo, depois nos outros motores.
3. **PÃ¡ginas e cursos** â€” a skill de guia e os formatos de curso passam a ler o DESIGN.md.

## CrÃ©ditos

MÃ©todo e arquivos de base do **Claude Design Blueprint** (compartilhado para uso livre). Checklist e lista de sinais de IA do **Power Design** e do **SlopMonster** (ItsssssJack, MIT). Formato DESIGN.md do Google Labs. Texto simples inspirado no ASD-STE100.

---
Feito por [INEMA.CLUB](https://inema.club)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>