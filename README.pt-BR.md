<div align="center">

[🇺🇸 English](./README.md) · **🇧🇷 Português** · [🇪🇸 Español](./README.es.md)

# RedlineMD — Redesign de landing page

### Desafio de design mobile-first orientado à conversão

**UX/UI · Implementação web responsiva · Estratégia de conversão**

[Prévia na Vercel](https://redlinemd-challenge.vercel.app/) · [Perfil Marcus Castro](https://github.com/marcuscastrodev)

</div>

> **Desafio independente de design**, criado para um processo seletivo de web designer, não para o site oficial da RedlineMD. As decisões abaixo são hipóteses de UX baseadas no briefing, **não resultados comprovados de conversão**.

## Visão geral

| | |
| --- | --- |
| **Contexto** | Desafio de web designer para Foundey |
| **Objetivo** | Melhorar clareza, confiança e jornada de compra mobile de um serviço de revisão de contratos médicos |
| **Atuação** | Estratégia UX, direção visual, interface responsiva e interações |
| **Entrega** | Conceito interativo empacotado em `index.html` |
| **Status** | Prévia publicada, sem teste A/B real ou checkout integrado |

## O desafio

Segundo o briefing, **35% das visitas eram mobile, mas o desktop representava mais de 90% da receita**. Isso sugeria uma possível lacuna de conversão mobile, sem comprovar sua causa.

O visitante vindo do Google Ads precisava entender rapidamente qual era o serviço, o preço, como funcionava a análise do contrato e por que confiar no processo.

## Abordagem de design

```text
Intenção de busca → Oferta e preço claros
                 → Motivos para revisar o contrato
                 → Relatório interativo ilustrativo
                 → Uma ação principal
```

### 01 — Clareza desde o primeiro contato

Headline alinhada à busca por revisão de contratos médicos, preço próximo ao CTA e proposta objetiva.

### 02 — Conversão sem dispersão

Uma oferta prioritária, CTAs consistentes e navegação reduzida.

### 03 — Valor demonstrado

Prévia interativa com riscos, cláusulas e alterações sugeridas. Os exemplos são **ilustrativos**, não uma revisão jurídica real.

### 04 — Mobile-first

Oferta e preço visíveis cedo, barra de preço condicional, alvos de toque de pelo menos 44px como intenção de design e experiência simplificada do relatório.

### 05 — Menos atrito no envio

A interface simula a ação de anexar um contrato. **Nenhum documento é enviado nem processado** nesta demonstração.

## Sistema visual

| Elemento | Escolha |
| --- | --- |
| Azul-marinho | `#172B46`, base profissional |
| Vermelho | `#D42A2F`, CTAs e alertas |
| Tipografia | Geist e Geist Mono |
| Layout | Alternância de seções claras e escuras |
| Estilo | Bordas e sombras discretas, títulos em sentence case |

## Galeria

**01 — Hero desktop:** proposta, comparação de preço, CTA e prévia do relatório.

![RedlineMD hero desktop](screenshots/01-hero-desktop.webp)

**02 — Mobile:** navegação e hierarquia adaptadas.

<img src="screenshots/02-hero-mobile.webp" alt="Landing page RedlineMD mobile" width="360" />

**03 — Riscos contratuais:** cards educativos que contextualizam o serviço.

![Seção de riscos contratuais](screenshots/03-contract-risks.webp)

**04 — Relatório interativo:** cláusulas, riscos e sugestões ilustrativas.

![Relatório de exemplo RedlineMD](screenshots/04-sample-report.webp)

## Acessibilidade e implementação

O racional considera HTML semântico, foco visível para teclado, redução de movimento, contraste, alvos mobile e metadados SEO. **Não representa certificação nem auditoria completa de acessibilidade.**

## Código e execução

O repositório disponibiliza um [HTML exportado](./index.html), com runtime/bundler incorporado, e não a árvore original editável de componentes. É possível abrir o arquivo em um navegador moderno com JavaScript.

A [prévia da Vercel](https://redlinemd-challenge.vercel.app/) está registrada nos metadados do GitHub; seu funcionamento em tempo real não foi validado de forma independente nesta revisão.

## Limitações e próximos passos

- Impacto real em conversão exige analytics e teste A/B.
- O briefing apresentava referências divergentes entre entrega “instantânea” e “em 24 horas”.
- Checkout e upload reais exigiriam endpoints e proteção de dados.
- Exemplos do relatório precisariam de validação jurídica.
- Acessibilidade, navegadores e dispositivos exigem testes adicionais.
- Uma versão com código-fonte editável seria uma evolução separada.

---

**Desenvolvido e documentado por [Marcus Castro](https://github.com/marcuscastrodev)**.
