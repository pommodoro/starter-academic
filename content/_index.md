---
# Leave the homepage title empty to use the site title
title:
date: 
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  #- block: portfolio
    #id: projects
    #content:
    #  title: Research
    #design:
    #  columns: '2'
  - block: markdown
    id: research
    content:
      title: Research
      text: |
        <section class="accordion">

        <details>
          <summary><strong>Climate Frictions and the Market for Climate Adaptation</strong> <em>Job Market Paper </em></summary>
          <div class="abstract">
            Climate change poses significant risks to smallholder farmers across the developing world. Index insurance could provide risk mitigation, but has demonstrated persistently weak demand despite high theoretical value. In this paper I develop a modern behavioral framework to separately identify two key barriers to technology adoption: low average trust of unfamiliar products versus difficulty evaluating them. With a framed field experiment with smallholder coffee farmers in Cauca, Colombia, I elicit incentivized demand across parametric rainfall contracts that vary orthogonally in payout probability and covariance with farm income. Farmers exhibit substantial difficulties in evaluating products: approximately 75% show extremely low responsiveness to product quality, with over 10% exhibiting positive demand for dominated products and 25% not purchasing products that pay out with probability one. I test two interventions targeting these different mechanisms: one designed to reduce evaluation difficulty and another to target average beliefs. A climate literacy treatment—providing rain gauges, WhatsApp-based rainfall monitoring, and historical correlation summaries—significantly increases quality responsiveness by improving farmers' mapping from contract terms to value by over 50%. Conversely, an advertising treatment does not affect average quality sensitivity while decreasing average demand by over 10%  consistent with low insurer reputation. Finally, I develop a model that characterizes how limited quality responsiveness creates incentives for firms to offer low-quality products, potentially ``poisoning'' the market and sustaining persistent underdevelopment despite possible welfare gains.
          </div>
        </details>

        <details>
          <summary><strong>Climate Maladaptation and the Commons: Groundwater Management in India</strong> (with <a href = https://nikhilbasavappa.github.io/> Nikhil Basavappa)</a></summary>
          <div class="abstract">
            Groundwater enables agricultural activity in areas with low and variable rainfall. However, agricultural expansion has led to highly stressed aquifers throughout India. We show how a popular policy intervention, increasing irrigation efficiency, can lead to welfare losses. We show theoretically that marginal productivity gains can widen the gap between private and socially optimal extraction when stock externalities are strong. Empirically, we leverage a multi-state groundwater management scheme that improved irrigation efficiency as well as variation in externality due to physical aquifer properties. Although the policy appears to have a null effect on aggregate, this hides significant heterogeneity: high-externality areas <it>increase</it> extraction both relative to low-externality areas and in absolute terms. This increase in extraction is accompanied by more multi-cropping, as well as more volatile evapotranspiration. Finally, these areas that have further depleted their groundwater reserves, are less able to use groundwater to smooth over drought periods. In all, we show that although efficiency improvements can increase welfare during high rainfall periods, these areas are effectively maladapting by increasing total water need and becoming more vulnerable to climate variability.
          </div>
        </details>

        <details>
          <summary><strong>Depositor Preferences and Climate Finance </strong> (with <a href=https://sites.google.com/view/jinglu/> Jing Lu </a> and <a href = https://www.edward-shore.com/> Edward Shore </a>)</summary>
          <div class="abstract">
            We study whether depositors’ social preferences discipline banks’ lending to environmentally intensive (“brown”) firms and how exposed banks manage the resulting funding risk through loan structure, especially syndication. We construct a bank-level index of deposit sensitivity by combining FDIC Summary of Deposits branch footprints with county-level presidential vote shares to proxy the local depositor base’s “green” tilt. Merging this measure with loan-level data from the syndicated market (Dealscan), we build a lender–loan panel with lender and year fixed effects to isolate within-bank variation over time in both the extensive margin of participation and the intensive margin of deal design. Two predictions guide the analysis: banks with more deposit-sensitive funding should (i) be less likely to participate in loans to brown borrowers and (ii) when they do lend, share exposure more aggressively—retaining smaller shares, assembling larger syndicates, and adjusting maturities, pricing grids, and covenant packages to mitigate risk. Using sectoral and emissions-based definitions of “brown,” we document patterns consistent with both predictions. Substantively, the results show that retail funding composition—beyond wholesale markets or regulation—disciplines climate-relevant credit allocation. Methodologically, they demonstrate that a simple geography-based proxy for depositor preferences explains meaningful cross-sectional and temporal variation in banks’ lending choices and in the design of syndicated deals.
          </div>
        </details>

        <details>
          <summary> <strong>Public Information Provision: Subsidy and Bureaucratic Eﬃciency </strong> (with <a href= https://nanoochoa.github.io/>Fernando Ochoca</a><a href = https://www.olab.berkeley.edu/graduate-students-1/daniela-paz> Daniela Paz Cruzat </a> and Marcela Zapata) </summary> 
        </details>
   
        <details>
          <summary> <strong> The Salesperson as an Educator: Incentives, Persuasion, and Financial Literacy </strong> (with <a href = https://www.brianjonghwanlee.com/home> Brian Jonghwan Lee </a>) </summary>
        </details>
        
        <details>
          <summary> <strong> Insurance and Crop Choice: Experimental Evidence from Zambia </strong> (with <a href = https://www.econ.uzh.ch/en/people/faculty/casaburi.html> Lorenzo Casaburi </a> and <a href = https://sites.google.com/view/jwillis/> Jack Willis </a>) </summary>
        </details>

        </section>

    design:
      columns: '1'

    
    
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: Shiny, Spatial Analysis, ML
          icon: r-project
          icon_pack: fab
        - name: Python
          description: oTree, Spatial Analysis, PyTorch
          icon: python
          icon_pack: fab
        #- name: Statistics
        #  description: 100%
        #  icon: chart-line
        #  icon_pack: fas
  
---
