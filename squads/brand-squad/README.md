# 🏗️ Brand Squad

Professional branding agency squad with complete workflow from discovery through implementation.

## Overview

**Brand Squad** is a specialized AIOS squad that replicates the structure and processes of a professional branding agency. It brings together 7 distinct specialists working in synergy to create extraordinary brands.

### Team Composition

- **Isabella Rossi** (Chief) — Brand Strategist Sênior, 15+ years experience
- **Marcus Chen** — Brand Strategist (Research & Strategy)
- **Sofia Moreno** — Creative Director (Concepts & Ideation)
- **Ahmed Hassan** — Visual Designer (Identity & Design)
- **Elena Kovacs** — Copywriter (Tone & Voice, Naming)
- **James Wilson** — Brand Manager (Guidelines & Implementation)
- **Priya Patel** — Account Manager (Client Relations)

## Workflow

### Phase 1: Briefing & Discovery
**Responsible:** Account Manager (Priya) + Brand Strategist (Marcus)

- Initial client conversations and brief collection
- Market and competitive analysis
- Stakeholder interviews
- **Output:** Briefing Document + Competitive Analysis Report

### Phase 2: Strategy
**Responsible:** Brand Strategist (Marcus) + Chief (Isabella)

- Brand positioning development
- Target audience definition
- Unique value proposition
- Strategic recommendations
- **Output:** Brand Strategy Document (approval by Chief)

### Phase 3: Creativity
**Responsible:** Creative Director (Sofia) + Copywriter (Elena)

- Creative brainstorming sessions
- Concept development
- Mood boards and visual directions
- Tone of voice and naming workshops
- **Output:** Creative Concepts + Naming Recommendations

### Phase 4: Design & Execution
**Responsible:** Visual Designer (Ahmed) + Copywriter (Elena)

- Logo design and variations
- Color palette development
- Typography selection
- Asset creation
- Final copy and messages
- **Output:** Logo, Paleta, Tipografia, Assets Digitais

### Phase 5: Implementation & Guidelines
**Responsible:** Brand Manager (James) + Account Manager (Priya)

- Brand guidelines documentation
- Implementation manual
- Templates and examples
- Presentation preparation
- **Output:** Documentação Completa + Arquivos de Entrega

### Phase 6: Delivery & Handoff
**Responsible:** Chief (Isabella) + Account Manager (Priya)

- Final presentation to client
- Guidelines walkthrough
- File handoff and training
- Post-launch support coordination
- **Output:** Marca Pronta para Implementação

## Tasks (Task-First Architecture)

| Task | Lead | Phase | Duration |
|------|------|-------|----------|
| Collect Brief | Priya | 1 | 2-3 days |
| Competitive Analysis | Marcus | 1 | 3-5 days |
| Brand Strategy | Marcus + Isabella | 2 | 5-7 days |
| Creative Brainstorm | Sofia | 3 | 3-4 days |
| Naming Workshop | Elena | 3 | 2-3 days |
| Logo Design | Ahmed | 4 | 5-7 days |
| Color Palette | Ahmed | 4 | 2-3 days |
| Typography Selection | Ahmed | 4 | 2-3 days |
| Brand Guidelines | James | 5 | 3-5 days |
| Prepare Presentation | Priya | 5-6 | 2-3 days |

## File Structure

```
squads/brand-squad/
├── squad.yaml                          # This manifest
├── README.md                           # This file
├── config/
│   ├── agents-list.md                  # Team details
│   ├── workflow-overview.md            # Process documentation
│   └── tools-stack.md                  # Required tools
├── agents/
│   ├── brand-chief.yaml
│   ├── brand-strategist.yaml
│   ├── creative-director.yaml
│   ├── visual-designer.yaml
│   ├── copywriter.yaml
│   ├── brand-manager.yaml
│   └── account-manager.yaml
├── tasks/
│   ├── collect-brief.md
│   ├── competitive-analysis.md
│   ├── brand-strategy.md
│   ├── creative-brainstorm.md
│   ├── naming-workshop.md
│   ├── logo-design.md
│   ├── color-palette.md
│   ├── typography-selection.md
│   ├── brand-guidelines.md
│   └── prepare-presentation.md
├── workflows/
│   ├── brand-discovery-workflow.yaml
│   ├── brand-creation-workflow.yaml
│   └── brand-finalization-workflow.yaml
├── templates/
│   ├── briefing-template.md
│   ├── strategy-template.md
│   ├── guidelines-template.md
│   └── presentation-template.md
├── checklists/
│   ├── discovery-checklist.md
│   ├── strategy-approval-checklist.md
│   ├── design-approval-checklist.md
│   └── brand-ready-checklist.md
└── data/
    └── brand-elements-schema.json
```

## How to Use

### Starting a Brand Project

```bash
# 1. Use Account Manager to collect brief
@account-manager *collect-brief

# 2. Brand Strategist conducts analysis
@brand-strategist *competitive-analysis

# 3. Chief and Strategist develop strategy
@brand-chief *approve-strategy

# 4-6. Continue through remaining phases...
```

### Required Input (Briefing)

To start any brand project, ensure you have:

- Client company background and history
- Product/service overview
- Target audience definition
- Competitive landscape
- Brand objectives and goals
- Timeline and budget
- Preferred style/inspiration

### Deliverables

Each phase produces specific deliverables:

1. **Discovery Phase:** Briefing + Competitive Analysis
2. **Strategy Phase:** Brand Strategy Document
3. **Creative Phase:** Concepts + Naming
4. **Design Phase:** Logo, Colors, Typography
5. **Implementation Phase:** Brand Guidelines
6. **Delivery:** Complete Brand Identity Kit

## Integration with AIOS

This squad integrates with:

- **@dev** — For implementing brand guidelines into code
- **@qa** — For validating brand consistency
- **@devops** — For publishing brand assets

## Specifications

- **Team Size:** 7 specialists
- **Difficulty:** Intermediate
- **Estimated Duration:** 8-12 weeks per project
- **AIOS Version:** 2.1+
- **License:** MIT

## Notes

- All tasks follow the task-first AIOS architecture
- Chief (Isabella) has final approval authority
- Account Manager coordinates all client communication
- Workflows are sequential but can have parallel tasks
- All deliverables are documented and templated

---

**Created:** March 4, 2026  
**Version:** 1.0.0  
**Status:** Ready for Use
