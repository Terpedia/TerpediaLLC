---
theme: default
background: https://source.unsplash.com/1920x1080/?business
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Terpedia, LLC Pitch Deck
  
  Company Overview and Vision
drawings:
  persist: false
transition: slide-left
title: Terpedia, LLC
mdc: true
---

# Terpedia, LLC

## Pitch Deck

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: section
---

# The Problem

---
layout: default
---

# The Problem

<div class="text-lg">

- **Fragmented Terpene Data**: Terpene research scattered across PubMed, databases, and proprietary systems
- **No Unified Platform**: Scientists must query multiple databases (ChEBI, PubChem, UniProt, RHEA) separately
- **Missing Functional Connections**: No systematic way to connect flavor compounds to therapeutic functions
- **Aromatherapy Knowledge Gap**: Traditional aromatherapy lacks molecular-level evidence and structure-function relationships
- **Limited AI Integration**: No intelligent search connecting molecular structure to biological effects
- **Knowledge Silos**: Terpene-protein interactions, clinical trials, and research articles disconnected
- **Time-Consuming Research**: Hours spent manually correlating terpene structures with therapeutic effects

</div>

---
layout: section
---

# Our Solution

---
layout: default
---

# Terpedia: The Solution

<div class="text-lg">

- **Unified Knowledge Base**: SPARQL-powered biochemical database integrating 70,000+ compounds
- **Functional Flavors**: Connect terpenes, flavonoids, and aromatic compounds to therapeutic functions
- **Aromatherapy Intelligence**: Map molecular structures to therapeutic benefits and applications
- **Federated Queries**: Single query across ChEBI, PubChem, UniProt, RHEA, and more
- **AI-Powered Analysis**: LLM integration for intelligent terpene research and insights
- **Molecular Intelligence**: RDKit API for structure analysis, similarity search, and drug-likeness
- **Research Integration**: Automated PubMed/article collection with NLP relationship extraction

</div>

---
layout: section
---

# Market Opportunity

---
layout: default
---

# Market Opportunity

<div class="grid grid-cols-2 gap-4">

<div>

## Market Size

- **Cannabis Market**: $57B by 2030
- **Essential Oils**: $15B+ market
- **Aromatherapy**: $4.2B market, 8.5% CAGR
- **Functional Foods**: $275B+ market
- **Pharmaceutical R&D**: $200B+ industry
- **Research Tools**: $10B+ market

</div>

<div>

## Growth Drivers

- Cannabis legalization expanding globally
- Natural product research increasing
- Functional flavors trend in food & beverage
- Evidence-based aromatherapy demand
- AI/ML adoption in drug discovery
- Precision medicine demand
- Terpene therapeutic research growth

</div>

</div>

---
layout: section
---

# Product & Features

---
layout: default
---

# Functional Flavors & Aromatherapy

<div class="text-lg space-y-4">

- **Functional Flavors Concept**
  - Connect flavor compounds (terpenes, flavonoids, phenols) to therapeutic functions
  - Map molecular structure → biological activity → therapeutic benefit
  - Enable precision formulation based on desired outcomes

- **Aromatherapy Intelligence**
  - Terpene-aroma-therapeutic effect relationships
  - Evidence-based aromatherapy recommendations
  - Molecular basis for traditional practices
  - Safety and efficacy data integration

- **Therapeutic Associations**
  - Anti-inflammatory, analgesic, anxiolytic, antimicrobial properties
  - Mood enhancement, cognitive function, sleep quality
  - Pain management, stress relief, immune support

</div>

---
layout: section
---

# Our Platforms

---
layout: default
---

# terpedia.com

<div class="text-lg space-y-4">

- **WordPress-Based Platform**
  - Content management and publishing system
  - Case management and documentation
  - User-friendly interface for content creators
  - Integration with knowledge base APIs

- **Key Features**
  - Article publishing and content management
  - Case study management system
  - User authentication and profiles
  - Content search and discovery
  - SEO optimization

- **Use Cases**
  - Publishing terpene research articles
  - Managing case studies and documentation
  - Content marketing and education
  - Community engagement

</div>

---
layout: default
---

# kb.terpedia.com

<div class="text-lg space-y-4">

- **Biochemical Knowledge Base**
  - **SPARQL Endpoint**: Apache Jena Fuseki with federated database queries
  - **RDKit API**: Molecular property calculation, similarity analysis, drug-likeness
  - **Functional Flavors Engine**: Structure-to-function mapping for therapeutic applications
  - **Aromatherapy Database**: Curated therapeutic associations and evidence
  - **PubMed Integration**: Automated article collection with AI NLP processing
  - **Knowledge Graph**: Terpene-protein-disease-therapeutic relationship visualization
  - **Chat Interface**: Real-time querying via MCP tools

- **Data Sources**
  - 70,000+ compounds (FooDB, FlavorDB, Phenol-Explorer, HMDB)
  - Terpene-protein docking data
  - Clinical trials integration
  - Essential oils databases (EssOilDB, TeroKit, COCONUT)
  - Aromatherapy research and traditional medicine data

- **Key Differentiators**
  - Only platform connecting flavors to therapeutic functions
  - Evidence-based aromatherapy recommendations
  - AI-powered relationship extraction
  - Federated query across major databases
  - Open-source, extensible architecture

</div>

---
layout: section
---

# Business Model

---
layout: default
---

# Business Model

<div class="grid grid-cols-2 gap-4">

<div>

## Revenue Streams

- **API Access**: Pay-per-query or subscription tiers
- **Functional Flavors API**: Premium access to structure-function mappings
- **Aromatherapy Database**: Subscription for therapeutic recommendations
- **Enterprise Licenses**: White-label knowledge base solutions
- **Research Partnerships**: Collaboration with pharma/cannabis/wellness companies
- **Data Licensing**: Curated datasets for ML/AI training
- **Consulting Services**: Custom terpene research and formulation projects

</div>

<div>

## Pricing Strategy

- **Free Tier**: Basic SPARQL queries, limited API calls
- **Researcher**: $99/month - Full API access, functional flavors data
- **Aromatherapist**: $49/month - Therapeutic associations database
- **Enterprise**: Custom pricing - Dedicated infrastructure, SLA, white-label
- **Data Licensing**: Per-dataset or annual contracts
- **Consulting**: Project-based or retainer model

</div>

</div>

---
layout: section
---

# Traction & Milestones

---
layout: default
---

# Traction & Milestones

<div class="text-lg space-y-4">

- **Data Integration**: 70,000+ compounds from multiple databases
- **Database Coverage**: FooDB, FlavorDB, Phenol-Explorer, HMDB, ChEBI, PubChem
- **Functional Flavors**: Structure-to-function mapping framework developed
- **Aromatherapy Data**: Therapeutic associations curated from research literature
- **Infrastructure**: AWS-deployed, containerized microservices
- **API Services**: RDKit API, SPARQL endpoint, PubMed/News collectors
- **Technology Stack**: Production-ready with Docker, Terraform, S3
- **MCP Integration**: Model Context Protocol server for AI assistants

</div>

---
layout: section
---

# Team

---
layout: default
---

# Our Team

<div class="grid grid-cols-2 gap-4">

<div>

## Leadership

- **Founder/CEO**: [Your Name]
- **Technical Team**: Full-stack developers
- **Scientific Advisors**: Biochemistry experts

</div>

<div>

## Expertise

- **Biochemical Knowledge**: Deep terpene research background
- **Technical Stack**: SPARQL, RDF, Python, FastAPI, Docker
- **Data Engineering**: Large-scale database integration
- **AI/ML**: LLM integration, NLP, knowledge graphs

</div>

</div>

---
layout: section
---

# Financials & Ask

---
layout: default
---

# Financial Projections

<div class="grid grid-cols-3 gap-4 text-center">

<div>

## 2026 (Year 1)
- **Revenue**: $180K
- **Members**: 500
- **Enterprise**: 2
- **Q1 Launch**: Website + memberships
- **Q2-Q4**: API access, data licensing

</div>

<div>

## 2027 (Year 2)
- **Revenue**: $850K
- **Members**: 2,500
- **Enterprise**: 8
- **Growth**: 372%
- **Profitability**: Q4 2027

</div>

<div>

## 2028 (Year 3)
- **Revenue**: $2.8M
- **Members**: 8,000
- **Enterprise**: 25
- **Growth**: 229%
- **ARR**: $3.2M run rate

</div>

</div>

---
layout: default
---

# Revenue Breakdown (2026-2028)

<div class="grid grid-cols-2 gap-4">

<div>

## 2026 Revenue Streams
- **Memberships**: $120K (67%)
  - 500 members × $20/month avg
- **API Access**: $30K (17%)
  - Researcher tier subscriptions
- **Enterprise**: $20K (11%)
  - 2 enterprise customers
- **Data Licensing**: $10K (5%)
  - Initial dataset contracts

</div>

<div>

## 2028 Revenue Streams
- **Memberships**: $1.9M (68%)
  - 8,000 members × $20/month avg
- **Enterprise**: $600K (21%)
  - 25 enterprise customers
- **API Access**: $200K (7%)
  - Premium API subscriptions
- **Data Licensing**: $100K (4%)
  - Expanded licensing deals

</div>

</div>

---
layout: default
---

# Investment Ask

<div class="text-lg space-y-4">

- **Amount**: $2-3 Million Seed Round
- **Use of Funds**:
  - **Product Development (40%)**: Enhanced AI features, mobile app, visualization tools, Functional Flavors engine
  - **Data Acquisition (25%)**: Additional database licenses, full-text article access, aromatherapy datasets
  - **Team Expansion (20%)**: Data scientists, biochemists, sales/marketing, customer success
  - **Infrastructure (10%)**: AWS scaling, CDN, monitoring tools, security
  - **Marketing (5%)**: Content marketing, conference presence, partnerships, SEO

- **Expected Outcomes** (18 months - by Q2 2027):
  - Website launched Q1 2026 with membership revenue
  - 1,000+ active members using platform
  - 8+ enterprise customers
  - $850K ARR (2027 projection)
  - Series A readiness with proven revenue model

</div>

---
layout: section
---

# Next Steps

---
layout: default
---

# Next Steps

<div class="text-lg space-y-4">

1. **Product Enhancement**
   - Expand Functional Flavors database with more therapeutic associations
   - Build Aromatherapy recommendation engine
   - 3D molecular visualization
   - Advanced AI chat features
   - Mobile app development
   - User authentication & profiles

2. **Data Expansion**
   - Clinical trials database integration
   - Real-time research article updates
   - User-contributed data validation
   - Traditional medicine and ethnobotanical data integration

3. **Go-to-Market**
   - Beta launch with research institutions
   - Cannabis industry partnerships
   - Wellness and aromatherapy practitioner partnerships
   - Conference presentations (ACS, SfN, aromatherapy conferences)

4. **Fundraising**
   - Complete seed round
   - Establish advisory board (biochemists, aromatherapists, wellness experts)
   - Prepare Series A materials

</div>

---
layout: center
class: text-center
---

# Thank You

## Questions?

<div class="pt-8 text-lg">

**Contact Information**

Email: dan@terpedia.com | susan@terpedia.com  
Website: www.terpedia.com | kb.terpedia.com

</div>
