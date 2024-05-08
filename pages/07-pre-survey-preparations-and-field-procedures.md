---
layout: home
permalink: /pre-survey-preparations-and-field-procedures
title: "Pre-survey preparations and field procedures"
excerpt: "<br>"
image:
  feature: /microplastics.jpg
layout: home

---

<nav class="toc">
<ul id="markdown-toc">
  <li><a href="#water" id="markdown-toc-water">Water</a>    <ul>
      <li><a href="#pre-survey-preparations" id="markdown-toc-pre-survey-preparations">Pre-Survey Preparations</a></li>
      <li><a href="#field-procedures" id="markdown-toc-field-procedures">Field Procedures</a></li>
      <li><a href="#sample-processing-and-analyses" id="markdown-toc-sample-processing-and-analyses">Sample processing and analyses</a></li>
    </ul>
  </li>
  <li><a href="#sediment" id="markdown-toc-sediment">Sediment</a>    <ul>
      <li><a href="#pre-survey-preparations-1" id="markdown-toc-pre-survey-preparations-1">Pre-Survey Preparations</a></li>
      <li><a href="#field-procedures-1" id="markdown-toc-field-procedures-1">Field Procedures</a></li>
      <li><a href="#sample-processing-and-analyses-1" id="markdown-toc-sample-processing-and-analyses-1">Sample processing and analyses</a></li>
    </ul>
  </li>
  <li><a href="#biota" id="markdown-toc-biota">Biota</a>    <ul>
      <li><a href="#pre-survey-preparations-2" id="markdown-toc-pre-survey-preparations-2">Pre-Survey Preparations</a></li>
      <li><a href="#field-procedures-2" id="markdown-toc-field-procedures-2">Field Procedures</a></li>
      <li><a href="#sample-processing-and-analyses-2" id="markdown-toc-sample-processing-and-analyses-2">Sample processing and analyses</a></li>
    </ul>
  </li>
  <li><a href="#air" id="markdown-toc-air">Air</a>    <ul>
      <li><a href="#pre-survey-preparations-3" id="markdown-toc-pre-survey-preparations-3">Pre-Survey Preparations</a></li>
      <li><a href="#field-procedures-3" id="markdown-toc-field-procedures-3">Field Procedures</a></li>
      <li><a href="#sample-processing-and-analyses-3" id="markdown-toc-sample-processing-and-analyses-3">Sample processing and analyses</a></li>
      <li><a href="#microplastics-quantification-and-characterisation" id="markdown-toc-microplastics-quantification-and-characterisation">Microplastics quantification and characterisation</a></li>
      <li><a href="#microplastics-quantification" id="markdown-toc-microplastics-quantification">Microplastics quantification</a></li>
      <li><a href="#physical-characterisation" id="markdown-toc-physical-characterisation">Physical characterisation</a></li>
      <li><a href="#chemical-characterisation" id="markdown-toc-chemical-characterisation">Chemical characterisation</a></li>
    </ul>
  </li>
</ul>

</nav>



* This will become a table of contents (this text will be scrapped).
These methods will differ among environments so refer to the relevant section:

{:toc}

{% include toc.html class="toc-left" h_min=1 h_max=2 %} 

# Water

## Pre-Survey Preparations

The methods for the collection of microplastic in marine and coastal waters can have minor variations tailored to specific water compartments i.e., surface, sub-surface and at depth. These methods may also be adapted to collect microplastics within a specific size range. 

### Sampling design

Before commencing field sampling, it is essential to formulate the research question(s) (see: What are the goals of my research?). Different research questions may require different sampling designs and, likely, different sample collection methods. Furthermore, sampling designs should consider the post-survey requirements, including the time required to accurately process samples, the techniques to be used to analyse them and the units of reporting.

The next step is to define the spatial and temporal extent of the research question. Spatial studies can provide information on the presence of and changes in the distribution of microplastics across sites. Therefore, the sampling design must consider the number and spatial dispersion of the collection sites to answer the research question, site accessibility, and environmental characteristics that may influence results (e.g., the hydrodynamic and depth profile to be surveyed and the expanse of the water body). Temporal studies can provide information on changes in microplastic concentrations at a specific location over time; the sampling design must therefore consider site accessibility across seasons and during/after significant weather events. 

Research conducted across spatial and/or temporal scales requires a stratified sampling design that enables an estimate of the true microplastic density (or type, weight, volume) at different scales or “strata” representing clearly defined groups (Quinn and Keough, 2002). Samples should be collected randomly from each group. Stratified sampling should also be used when within-habitat variation is high, and it is not feasible to sample entire sites (CSIRO 2022). Refer to the [Survey Design SOP](https://survey-design-field-manual.github.io/) for further details.

Sampling design and approach is dependent on study objectives and will define limitations on the size class of microplastics that can be analysed. For water, sampling can be performed using tow nets, Niskin bottles, submersible pumps, underway vessel pumps or grab samples - see descriptions below. Each mode of water sampling offers a different capability (e.g., in situ filtration of large volumes vs collection of smaller volumes for later processing; the choice being dictated by downstream detection thresholds) and different representativeness  (e.g., horizontal vs vertical gradients of the water body, or specific microplastic sizes or types due to density), both of which need to be considered to ensure the research question can be satisfactorily answered (GESAMP, 2019). For example, many tow nets have a 350 µm aperture so smaller microplastics would only be opportunistically sampled, while submersible pumps, Niskin bottles and underway vessel pumps can collect microplastics across the full size range, including smaller microplastics. 

The number of samples collected will be determined by the research question as well as the budget, logistics and resources available; with the caveat that a high number of samples allows for greater accuracy (through power and replication) in the estimation of microplastic concentrations in the environment and will ensure greater statistical rigour. It is important to consider what would be an appropriate effect size (i.e. the acceptable difference between the estimate and the true density or volume of microplastics in the water). Before commencing sample collection, a power analysis can be performed to assist in this decision. G*Power (Faul et al, 2007) or pwr package in R (Champley et al., 2020) are suitable for simple sampling designs and can determine the number of samples required to achieve the desired effect size. 


## Field Procedures

### Materials and equipment for collection 

The materials and equipment required for collection of water samples varies depending on the type of sampling (Table 1). For volume reduced net tows, submersible pumps and bulk water, the aperture of the filter or net must be recorded. To accurately record the volume of the water sampled a flow meter is required for net and pump devices. GPS values and depth measurements provide additional important contextual information on the site location and details.

**Table 1.** List of field equipment and materials needed for collection of environmental samples in marine and coastal habitats. Three common methods are considered: volume-reduced net tow filtration, submersible pump filtration and bulk water bottling. Asterisks* indicate essential items.


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-co9i{background-color:#4F81BD;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1053px">
<colgroup>
<col style="width: 351px">
<col style="width: 351px">
<col style="width: 351px">
</colgroup>
<thead>
  <tr>
    <th class="tg-co9i"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Volume reduced net tow filtration</span></th>
    <th class="tg-co9i"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Submersible pump filtration </span></th>
    <th class="tg-co9i"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Bulk water bottling</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Nets (e.g., Manta trawl, Neuston net, AVANI trawl, Bongo net, Hydra-bios nets)*. Net aperture and mesh size must be considered and recorded</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pump device (e.g., built-in underway seawater intake system, portable pump; including pumps deployed in a Rosette device)*. Filter aperture must be considered and recorded.</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sampling bottle of known volume (e.g., glass or plastic bottle of 1 L or more, Niskin and Van-Dorn bottles, including deployed in a Rosette device)*.</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Volume of sampling bottle must be considered.</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Flow meter</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Flow meter</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Volume of water from sampling bottle must be considered and recorded</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">GPS start and end coordinates*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">GPS start (and end when applicable) coordinates*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">GPS*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Depth measurer</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Depth measurer</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Depth measurer</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal sieves (depending on the pump design)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal sieves (depending on the sampling bottle)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sampling jar*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sampling jar*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sampling jar</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Labels*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Labels*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Labels*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Field observation datasheet*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Field observation datasheet*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Field observation datasheet*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pencils, permanent marker*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pencils, permanent marker*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pencils, permanent marker*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal forceps and/or tweezers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal forceps and/or tweezers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal forceps and/or tweezers</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Reagents (ultrapure water, ethanol)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-        </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-        </span></td>
  </tr>
</tbody>
</table>


### General principles

Ocean and coastal environments are dynamic and are inherently highly variable, so it is recommended to sample over time (e.g., seasonally) if feasible, and related to research question (GESAMP, 2019). The rate and extent of seasonal change is a key factor to consider when sampling in the environment.  In Australia there are typically four seasons in temperate regions (summer, autumn, winter and spring) or two in tropical regions (wet and dry), but these may be further split based on the local microclimate and different cultural group definitions. When sampling over time is not feasible, recording and reporting information on weather and other environmental conditions at the time of sample collection is crucial for contextual information (see Reporting section).

Airborne and handling contamination is likely to occur during field sampling, so appropriate quality assurance and quality control (QA/QC) procedures must be consistently applied throughout sample collection (see Quality assurance and quality control section). This includes the use of positive controls and blanks during sample collection.

### Volume reduced net tows

The survey of water at the surface, sub-surface or at depth, requires the use of compartment-appropriate nets. The methods highlighted below are recommended for surface sampling although can be adapted for mid-column or near ocean floor sampling (Eriksen et al., 2018).

The most commonly used nets to assess surface water are the Manta trawl and the Neuston net, both towed from the side of the vessel, ideally downwind and at a speed of up to 4 knots (Kroon et al., 2018; Viršek et al., 2016). Ideally, sampling should be conducted during calm weather conditions. Manta trawls generally sample the top 15-25 cm while Neuston nets sample the top 50 cm, but both are considered surface tows. Another commonly used net is the AVANI trawl, generally deployed when surveying longer transects as the net can be towed at up to 8 knots. All three net types are relatively inexpensive and simple to operate. Data from all three trawl methods are comparable, as similar types (i.e., positively buoyant) and amounts of microplastic are collected. Whilst reporting information on net configuration is recommended, details on the mesh aperture size are essential and must be recorded against the sample as it defines the lower size category of collected microplastics (e.g., if mesh size is 330 μm, then microplastics greater than 330 μm will predominantly be collected and every item smaller than that should be considered as opportunistically sampled) (Hidalgo-Ruz et al., 2012). 

Net deployment procedures need to be tailored to avoid airborne contamination. For example, where possible, the net opening should be protected from air exposure before and post sampling. Along with vessel speed and net opening area, GPS coordinates should be recorded at the beginning and end of each tow to allow calculation of distance travelled, volume sampled, and estimate microplastic concentration (V = 	&Pi; * r <sup>2</sup> * h) where r = radius of the net and h = distance net towed). To ensure sampling provides an accurate representation of microplastics presence and distribution at the sea surface, at least 1 m<sup>3</sup> of water should be sampled – noting this will be dependent on the level of plastic pollution at the sampling site. Note that inferring volume solely based on distance travelled can lead to inaccurate estimations of the volume of water as water current flow is often not measured or accounted for. To achieve greater accuracy in volume estimation a flow meter can be attached to the bottom and/or centre of the net mouth. Replicates at each tow site should be conducted to report data variability. Where collection of replicates is not feasible (i.e., only one tow is conducted before conditions change), this should be clearly indicated, with the knowledge that no standard error or variance can be reported).

Following the sampling event, the entire net must be winched on board and rinsed from the outside using an on-board deck hose (either seawater or freshwater) to transfer trapped contents into the cod-end. Where feasible (e.g., logistically and following QA/QC), any large natural material captured should be removed using metal tweezers and, to dislodge any adhered microplastics, its surface should be rinsed liberally through the net into the cod-end container (the rinsed items can then be disposed of). Physical properties of the rinsed item should be documented. If the sample is dense and rich in organic material, this should be documented to guide the first step in the sample processing protocol, i.e., if chemical digestion is needed to remove smaller organic matter including biofilms (see Processing of microplastics section below). Large plastic debris items captured in the net can also be removed and rinsed through the net into the cod-end container, and stored separately for further analysis. The cod-end contents should then be transferred to a pre-cleaned bottle (e.g., 1-2 L), preserved and stored until analysis (e.g., fridge, 20% ethanol – see storage below). Additionally, the use of positive controls and blanks during sample collection is highly recommended (see Quality assurance and control section). 

Before starting the next tow, a clean cod-end, or a used one that has been liberally rinsed with filtered water, should be attached to the net.  


### Submersible pump sampling

Submersible pumps are another alternative to survey water bodies and are most commonly deployed just below the surface or in deeper water (Rodrigues et al., 2018). Usually, these pumps are systems retrofitted to vessels (e.g., already existing seawater intake systems that are adapted to suit microplastic collection) or portable and able to be deployed via a winch system (Karlsson et al., 2020). While fixed systems have the advantage of minimal handling and can sample along transects (e.g., while in transit or semi-continuously), these can only be used at one depth, and exclude surface microplastics (Schönlau et al., 2020). Portable systems, on the other hand, are suitable for depth profiling and can potentially be deployed from anywhere (i.e., not vessel dependent), but are not well suited to transect sampling. Portable pumps are, however, often expensive and may require skilled personnel to oversee their operation.

The likelihood of airborne contamination occurring while using submersible pumps depends on the pump design, and whether the pumped water is exposed to the air at any stage during collection. To prevent this, many submersible pump systems are designed so that specialised clean filters are only exposed to the air when being removed and replaced. However, some pumps might pump the water over an open sieve, and therefore these samples can be exposed to airborne contamination during collection. When samples are susceptible to airborne contamination during collection, blank controls should be used. These include vials containing ultrapure (e.g., Milli-Q) water that are exposed to air simultaneously with the exposure of samples; these are then passed through every procedural step. Regardless, the use of positive controls and blank controls during sample collection is highly recommended for submersible pump samplings (see Quality assurance and quality control). 

The GPS coordinates of the sampling site should be recorded at the beginning of the activity. If a transect is being collected, GPS coordinates should also be recorded at the end of each sampling event to allow for reporting on distance travelled and calculation of the total volume filtered. 

The volume of water sampled by submersible pumps is dependent on the system configuration and the depth at which it is deployed. Like for surface water sampling, at least 1 m<sup>3</sup> of water is recommended to be collected, allowing first and foremost for further vertical comparison. The use of a flow meter is advised where possible, however, if not available, the volume of water sampled can be calculated using the time the pump is operated (i.e., the sampling period) and the calibrated timeframe in which a given volume of water is pumped. Replicates at each sampling site should be completed to report data variability. Where the collection of replicates is not feasible (e.g., the pump is being used for semi-continuous surveys or technical issues have occurred), this should be recorded, noting that no standard error or variance can be reported. 

Samples collected on filters should be immediately removed from the pump and stored in clean containers (e.g., labelled petri dish) to avoid exposure to air. Filters with samples can be stored cold (e.g., -20°C, fridge, on ice – see storage below). When samples are collected over sieves, sampled material must be transferred (i.e., backwashed) into suitable clean containers (e.g., 150 mL vials) using ultrapure water or filtered seawater. These samples can then be preserved cold or in 20% ethanol (i.e., filtered ethanol is added to the sample). If more samples are to be collected via sieving, a new or cleaned sieve should be used.

Fixed submersible pumps are not always able to be thoroughly cleaned (nor visually inspected), especially vessel intake systems. For these pumps, it is important to flush the system well before the start of sampling to ensure any plastics trapped in the system do not cross-contaminate samples. 

### Bulk water bottling

Water quality sampling is traditionally undertaken with bulk water bottling (e.g., Niskin bottles attached to a Rosette sampler, or bottles directly) deployed in a specific location at a specific defined depth (Nan et al., 2020; Ogunola et al., 2023; Song et al., 2014). This same static sampling method is used to sample microplastics in water and across vertical gradients. When collecting surface water samples, the bottles should be deployed downwind or on the side of the vessel and ideally under calm weather conditions. Collection bottles must be appropriately cleaned before use (e.g., rinsed 3 times with ultrapure or filtered seawater and visually inspected). The configuration of the microplastic sampling system and bottle type can vary, so it is important to record the volume collected and time. The volume required is also dependent on the downstream analysis workflow. For example, if using pyrolysis-GC/MS to detect microplastics, 2 L is appropriate, whereas for other spectroscopy methods 10 L is advised. To limit the risk of airborne contamination, sampling bottles should remain sealed and only be opened and closed when underwater (Samandra et al., 2023). Additionally, the use of positive controls and blank controls during sample collection is highly recommended (see Quality assurance and quality control). 

Preliminary processing of these samples is often conducted on the vessel as storage of large volumes is often not possible. The Niskin sample is generally filtered (e.g., over a stainless-steel mesh under vacuum) and the filters are stored in a sealed container (i.e., labelled glass petri-dish) until analysis. When filtering on the vessel is not possible, collected water should be transferred to a pre-cleaned bottle (e.g., 1-2 L), preserved (e.g., fridge, 20% ethanol – see storage below) and stored until analysis.

### Storage

Following collection, and regardless of the collection method, all samples should be processed immediately or appropriately preserved until further processing.  Although plastic items do not themselves require preservation (i.e., many are expected to persist in the environment for many hundreds of years), organic material is often also part of the collected material. If samples are not preserved this organic matter can degrade and encourage the growth of microbes on the surface of the microplastics, which can impact their retrieval, identification and chemical analysis. 

Sample preservation methods include low temperature (e.g., ice, -4°C fridge, -20°C freezers), or chemical treatments (e.g., ethanol, 3% hydrochloric acid), the latter with the caveat that only chemicals that do not impact plastics should be used (Pfeiffer & Fischer, 2020). Where possible, preliminary processing to clarify samples and enhance their long-term storage should be applied. For example, filtration can reduce volume, washing with ultrapure water (e.g., Milli-Q), &lt;20% ethanol, or sonication (three cycles for five minutes each based on Kaiser et al., (2017)), can dislodge any biofilms attached to the microplastic surface, thereby enhancing buoyancy and contributing to more accurate and effective separation, identification and subsequent analyses.

In instances where immediate sample preservation or processing is not feasible, considerations need to be made for the influences that biological material can have on the retrieval and identification of microplastic particles. 


## Sample processing and analyses

After collection of the water samples, the microplastics need to be isolated for quantification and identification. Following good laboratory practice, a sample audit should be conducted, and all relevant environmental parameters and sample information entered into a project database or spreadsheet.

In this section, we briefly summarise the equipment and materials needed to process water samples. As well as briefly describe the steps to separate and quantify microplastics, physical and chemical characterisation and QA/QC. 


### Processing of microplastics (1 μm - 5 mm)

### Equipment

#### Material

- Glass Petri dishes and beakers
- Metal forceps/tweezers
- Stainless steel filters
- Millipore gridded membrane (nitrocellulose filters)
- Metal sieve (sieve diameter and mesh aperture size need to be reported; the latter to understand the lower size limit)
- Density meter (for testing the density of the separation reagent)


#### Reagents

- Ultrapure water (e.g., Milli-Q)
- Preservation reagent (e.g., 10-20% ethanol, 70% ethanol)
- Density separation reagent (e.g., sodium chloride, sodium iodide or other outlined below) 
- Chemical digestion reagents (e.g., 30% hydrogen peroxide, 10% potassium hydroxide or other outlined below)

_All reagents and solutions should be filtered (&lt;20 μm) before use, excluding the ultrapure water, which is already filtered._


#### Instruments

- Temperature controlled oven (optional)
- Orbital shaker (optional)
- Heated stirring plate (optional)
- Glass magnetic stirring rod (optional)
- Laminar flow (recommended)
- Filtration equipment (glass or stainless steel), including vacuum pump
- Stereomicroscope
- Polymer identification instrument (e.g., FTIR, μ-FTIR, ATR-FTIR, RAMAN, py-GC/MS)

### Pre-treatment and procedures for microplastic separation

#### Water samples with low organic content

Water samples that visually appear clear can be fast-tracked through the isolation process to either density separation or filtration, with no chemical digestion needed. If preserved frozen, samples (still covered) should first be defrosted at room temperature. If preserved in a chemical solvent (i.e., 20% ethanol), care should be taken following the chemical solvent’s Safety Data Sheet (e.g., regarding PPE and others).

#### Water samples with medium/high organic content

If the water sample contains phytoplankton, zooplankton or other organic matter that hinders the retrieval of microplastics, a clarification step is required prior to filtering. This clarification can be achieved using density separation (see below), but for samples with higher organic content, preliminary chemical digestion may be required (see below). 

#### Chemical digestion 

Chemical digestion can be applied as a first step to separate microplastics from seawater. There are a range of different chemicals that are appropriate, depending on research question, laboratory facilities and reagent availability (Table 2). The type of chemical digestion chosen is a compromise between efficiency, cost, and the known health and safety risks and potential for polymer degradation (Di Fiore et al., 2024; Miller et al., 2017; Pfeiffer and Fischer, 2020)(Table 2). 

As an example, described below is a procedure that has been applied to facilitate the chemical digestion of a surface water samples with a high algae content. Potassium hydroxide (10% KOH) was added directly into the filtered seawater samples and then heated to a maximum of 40°C in a controlled oven for up to 72 hours. Where the digestion rate of the organic matter was slow, i.e., there was still organic material present after 72 hours, a second digestion method using hydrogen peroxide (H<sub>2</sub>O<sub>2 </sub>30% w/v) was applied. The sample was again agitated at 40°C on a temperature-controlled magnetic stirrer in a fume hood and the reaction was allowed to go to completion (follow Safety Data Sheet for all chemicals). Thereafter, samples went through density separation.

 

**Table 2.** Summary table of digestion reagents, their concentrations, advantages and limitations. Based on: Di Fiore et al. (2024) and Pfeiffer and Fischer (2020).

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1055px">
<colgroup>
<col style="width: 185px">
<col style="width: 212px">
<col style="width: 106px">
<col style="width: 368px">
<col style="width: 184px">
</colgroup>
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Digestion</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Recommended concentration </span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Advantages</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Limitations</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Degradation of polymers?</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Hydrogen peroxide (H</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">O</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">15-30% </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient, cheap</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive, hazardous </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes, at high concentrations</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Hydrochloric acid (HCl)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">20%</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient, cheap</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive, hazardous, toxic, can degrade polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Nitric acid (HNO</span>3<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> Weak</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient, cheap</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive, hazardous, causes discolouration of plastics, can degrade some polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium hydroxide (NaOH)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1 M</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive, hazardous, can degrade some polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Potassium hydroxide (KOH)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">10%</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive, hazardous</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes, at high concentrations</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Enzymatic digestion</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Safe, efficient</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Expensive, time intense</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes</span></td>
  </tr>
</tbody>
</table>

#### Density separation 

For large water samples density separation can be applied as a first step to separate microplastics from seawater or following chemical digestion. Concentrated water samples are resuspended in the brine solution of choice with less dense materials (e.g., microplastics) floating and becoming separated from denser materials (sediment, debris, others) present in the matrix. There are a range of different reagents that can be used for density separation. These differ in their density, and each has advantages or limitations associated with efficiency for microplastic recovery, varying levels of toxicity, and price range  (Rani et al., 2023) (Table 3). Commonly used reagents include sodium chloride, sodium tungstate dihydrate, sodium bromide, sodium polytungstate, lithium metatungstate, zinc chloride, zinc bromide and sodium iodide. The effectiveness of reagents is polymer dependent, e.g., higher density reagents are more effective at removing more dense polymers. The density of the final solution used must be reported, as it will dictate which plastic polymers can or cannot be retrieved with this methodology.

Note, samples that have been preserved (e.g., 20% ethanol) or chemically digested, may still contain some of the reagents and there is a risk that these will react with the density separation reagents, therefore, it is important to first neutralise the sample. The preserved or digested sample must be rinsed liberally with ultrapure water onto a filter or sieve before the density separation step. Always refer to the Safety Disposal Sheet of the chemical reagents for appropriate use and disposal. 

To achieve density separation, the reagent should be added to the sample first, and then stirred (e.g., with a metal spoon or glass rod) and the solution allowed to settle. Stirring and settlement periods can vary based on sample complexity, and should be tailored with preliminary and spike recovery tests. Once a sample is completely stratified, the established supernatant should be poured over an appropriate filter (i.e., metal mesh, glass microfiber, silicon coated filter) using a filtration device (preferably metal or glass). The walls of the sample container should be rinsed liberally with ultrapure (e.g., Milli-Q) or filtered water to ensure all microplastic items are transferred. The filter should be stored in a labelled petri dish and covered with a glass lid. To identify microplastics, captured items should be observed under a microscope using any one of the microplastic quantification steps outlined below. 


**Table 3.** Commonly used density separation reagents, highlighting their advantages and limitations. 


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1209px">
<colgroup>
<col style="width: 150px">
<col style="width: 80px">
<col style="width: 180px">
<col style="width: 180px">
</colgroup>
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Density separation reagent</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Density of solution</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Advantages</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Limitations</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium chloride (NaCl)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.2 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers low density polymers (e.g., PE, PS, PP, PMMA, PC)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Readily available</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Less efficient at recovering high density polymers (e.g., PC, PU, PET, PVC, PTFE)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium tungstate dihydrate (H<sub>4</sub>Na<sub>2</sub>O<sub>6</sub>W)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.4 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers low density polymers (e.g., PE, PS, PP, PMMA, PC)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost-effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Less efficient at recovering high density polymers (e.g., PC, PU, PET, PVC, PTFE)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium bromide (NaBr)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.37 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Lithium metatungstate </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">(Li<sub>2</sub>O<sub>13</sub>W<sub>4</sub></span><sup>-24</sup><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.62 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Unknown effect on polymers</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Zinc chloride (ZnCl<sub>2</sub>)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.5 - 1.7 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Zinc bromide (ZnBr<sub>2</sub>)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.71 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium iodide (NaI)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.6 - 1.8 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Calcium chloride (CaCl<sub>2</sub>)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.5 - 3 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Potassium Iodide (KI)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.7 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span></td>
  </tr>
</tbody>
</table>


#### Filtration

Water can be poured through the filter or sieve and gravity will drain the sample, or a vacuum pump can be used to accelerate the filtration and if there is a high particulate content. The configuration of the filter or sieve can vary, i.e., an individual filter or sieve can be used, or a tiered filtration unit (Schlawinsky et al., 2022).  Either way, the smallest filter size must be recorded, as this will define the smallest microplastic sample that can be collected (e.g., if the sieve is 100 μm, microplastics smaller than 100 μm will not be accurately or consistently captured). 

For samples preserved in a chemical solvent, the dilution of the preservation chemical should be such that there is &lt;1% in the final washings. Crystallization and retention of inorganic salts in the sample solids can occur after filtering and may hinder both the physical and chemical analysis of microplastics. To prevent this, it is crucial to thoroughly and liberally rinse the filtrate with ultrapure water (e.g., Milli-Q). 

Following filtering, filters with solids can be stored in labelled glass jars or covered petri dishes until microscope examination. The filtration unit should then be thoroughly rinsed with ultrapure water (e.g., Milli Q) and carefully inspected to ensure no residual solids remain and to prevent cross-contamination of the next sample. 

# Sediment 

## Pre-Survey Preparations

The methods for the collection of microplastics in marine, coastal, and riverine sediment can vary depending on the sediment composition (i.e., grain size, organic content) and environment (i.e., subtidal - always submerged; intertidal - the area between high and low tide; and supratidal - the area above the high tide line and only flooded occasionally during storms).

### Sampling design 

Before commencing field sediment sampling, it is necessary to formulate the research question(s) (see What are the goals of my research?). Different research questions may require different sampling designs and, likely, different sample collection methods. Furthermore, sampling designs should consider the post-survey requirements, including the time required to accurately process samples, the techniques to be used to analyse them and the units of reporting.

The next step is to define the spatial and temporal extent of the research question. Spatial studies can provide information on the presence of and changes in the distribution of microplastics across sites. Therefore, the sampling design must consider the number and spatial dispersion of the collection sites to answer the research question, site accessibility, the zone to be surveyed (i.e., intertidal vs supratidal), the site profile, geographical and oceanographic features, accumulation dynamics, the expanse of the area, and other environmental characteristics that may influence results. Temporal studies can provide information on changes in microplastic concentrations at a specific location over time, therefore the sampling design must also consider site accessibility across seasons and during/after significant weather events. For example, coastal environments are prone to significant shifts and fluxes in features (i.e., coastal erosion or submergence) due to rises in sea levels (i.e., king tides) and changes in wave action and currents from events such as flooding and cyclones.

Research conducted across spatial and/or temporal scales requires a stratified sampling design that enables an estimate of the true microplastic density (or type, weight, volume) at different scales or “strata” that represent clearly defined groups (Quinn and Keough, 2002). Samples should be collected randomly from each group. Stratified sampling should also be used when within-habitat variation is high, and it is not feasible to sample entire sites (CSIRO 2022). Refer to the [Survey Design SOP](https://survey-design-field-manual.github.io/) for further details.

Sampling design and approach is dependent on study objective and the environment being sampled, e.g. quadrats or transects for intertidal habitats, grabs, quadrats, or cores for subtidal habitats (see descriptions below). Budget and logistical constraints also need to be considered as does the translation of methods for uptake by citizen science monitoring programs (which are now a key vehicle for conducting global surveys). Sampling approach can also define limitations on the size class of microplastics that can be analysed. 

The number of samples collected will be determined by the research question as well as the budget, logistics and resources available; with the caveat that a high number of samples allows for greater accuracy (through power and replication) in the estimation of microplastic concentrations in the environment and will ensure greater statistical rigour. It is important to consider what would be an acceptable difference between the estimate and the true density or volume of microplastics (i.e., the effect size). Before commencing sample collection, a power analysis can be performed to assist in this decision. G*Power  (Faul et al., 2007) or pwr package in R (Champley et al., 2020) are suitable for simple sampling designs and can determine the number of samples required to achieve the desired effect size.

There are two main approaches when examining transects for microplastic presence in subtidal, intertidal or beach environments (note this can include monitoring the entire transect, or quadrats along the transect, depending on the research question). The first is the parallel to shoreline, including the ‘strandline’ approach (which will record debris from the last high tide), where a set length of the beach is measured, and microplastic quantified (example in Figure 2, shows collection along the high tide line). The second is the perpendicular to shoreline approach, which records changes in microplastic density towards the tideline if/when the transect is surveyed in discrete sections. Both strandline and perpendicular methods are appropriate, and their use will depend on the research question. It is important to record details of environmental conditions, physical features at the site (e.g. sandy vs rocky beach, long beach vs small cove), and weather conditions (e.g., tides, storm surge, wind, wave action) (see environmental variables and the Reporting information section). 

It is essential to record information on sampling effort as this can create variability in the results. This is particularly important with community-led beach surveys (e.g., citizen science monitoring programs), where there is variation in the number of people participating across time, how many hours are spent searching, level of competency, and area searched. These are important aspects that should be considered during sampling design and prior to commencing collection. Whilst other methods (e.g., grabs) are not impacted by the number of surveyors, it is essential that the number of samples and replicates are clearly identified. 


<img src="images/figures/figure2.png" width="" alt="alt_text" title="image_tooltip">


**Figure 2.** Sampling approaches for microplastic monitoring in intertidal environments. 


## Field Procedures


### Materials and equipment for collection 


**Table 4.** List of equipment and materials required for field sample collection in intertidal/supratidal and subtidal habitats. Asterisks* indicate items that are essential for microplastic sampling.  


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-co9i{background-color:#4F81BD;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1102px">
<colgroup>
<col style="width: 551px">
<col style="width: 551px">
</colgroup>
<thead>
  <tr>
    <th class="tg-co9i"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Intertidal and supratidal</span></th>
    <th class="tg-co9i"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Subtidal </span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Measuring tape*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Grab or coring device (e.g., box corer, van Veen grab, sediment corer) *</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">GPS start and end coordinates*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">GPS start and end coordinates*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Quadrat*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Quadrat (for scuba diving survey)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal shovel or spoon*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal shovel or spoon</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Depth gauge </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Metal ruler</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Stainless steel sieves or filters</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Stainless steel sieves or filters</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Glass petri dishes </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Glass petri dishes</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-        </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Syringe and suction tube*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Glass jars, aluminium tray or sterile press-and-seal plastic bags or paper envelopes (for dry sediment samples) *</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Glass jars or zip lock plastic bags*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Labels*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Labels*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Field observation datasheet*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Field observation datasheet*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pencils, permanent marker*</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pencils, permanent marker*</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Camera</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Camera</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Glass filtering flask</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Glass filtering flask</span></td>
  </tr>
</tbody>
</table>


### General principles

Ocean and coastal environments are dynamic and can be highly variable, so it is recommended to sample over time (e.g., seasonally) if feasible. Seasons may vary depending on the region being sampled, in some areas of Australia there will typically be four seasons (summer, autumn, winter and spring) or two (wet and dry), but these may be further split based on local microclimates and different cultural group definitions. When sampling over time is not feasible, recording and reporting information on weather and other environmental conditions at the time of sample collection is important for contextual information (see Reporting section).

In the field during intertidal/supratidal, subtidal, and other environments, transects for perpendicular or strandline sampling (depending on the research question) should be measured for length. Additionally, GPS coordinates at both the beginning and end of the transect recorded. Photographs of the sampling transect should be taken. A randomised and stratified sampling design should be implemented, with a minimum of three replicate samples taken randomly along the transect. It is important to note, however, that the number of replications needed along the transect will depend on the microplastic load and the accumulation dynamics of the site. If there are large abundances of microplastic counted, three replications are needed, however, if there are low counts of microplastics, variations in the environmental conditions (e.g., variations in sediment type or grain size across transects), or other confounding factors, more replications are required. Likewise, sampling locations can be randomised (i.e., using a random number generator) along the transect. The GPS coordinates for each sampling location must be recorded. 

Airborne and handling contamination can occur during field sampling, so appropriate quality assurance and quality control (QA/QC) procedures must be consistently applied throughout sample collection (see Quality assurance and control section). This includes the use of positive controls and blanks during sample collection. 

### Intertidal/supratidal

The collection methods employed in the intertidal and supratidal zones are similar. There are two main approaches for investigating microplastics in these two zones - standing stock assessments, and accumulation assessments. The first (standing stock assessment) involves collecting or counting the microplastic pieces which are already present on the beach (Fisner et al., 2017). This type of survey method gives a value about the microplastics at a given time in a given area. The latter approach (accumulation assessment) involves clearing the plastic away from the tideline initially, and then counting and/or collecting the microplastics that are carried by the waves (Galgani et al., 2013; GESAMP, 2019). This allows for information on the microplastic accumulation from the water. 

There are a number of ways to count and/or collect microplastics, depending on the research objectives in intertidal and supratidal zones. Investigation of visible microplastics (1 mm - 5 mm) is usually done by counting the number of microplastics within a defined quadrat (e.g., 25 cm x 25 cm, 50 cm x 50 cm or other) often along a transect, with microplastics counted visually from standing height (estimated to be one metre directly above). This method does not require handling of the sediment, however, if desired, the top layer (1-5 cm) of sediment from the quadrat can be collected and sieved (i.e., using a 1 mm aperture metal sieve) to capture microplastics for subsequent chemical analysis.

If microscopic microplastics (1 μm - 1 mm) are to be counted the sediment will need to be collected and transported for further processing. The sediment can be collected in a number of ways and is dependent on the site accessibility and storage and transport capacity. Recommended approaches include, collecting the top layer of sediment (between 1 - 5 cm) within the entire quadrat using a metal shovel and depth gauge (Piperagkas et al., 2019; Wessel et al., 2016). The size and depth of the sample collected should be recorded, along with sample mass (can be measured retrospectively). Alternatively, a quadrat can be placed and randomised replicate samples within the quadrat collected (e.g., using a small corer, vial, or shovel). A minimum of three replicates are recommended to allow for variance to be calculated within each quadrat. 

### Subtidal

There are generally five approaches used to collect subtidal sediment – grab samplers, core samplers, dredge samplers, or quadrats via SCUBA and Remotely Operated Vehicles (ROVs).

The depth and sediment type to be collected, and the mode of collection, will depend on the research question. Where possible, retrospective sampling design needs to be optimised to collection mode, i.e., whether the mode of collection is manual or automated, and to the site. 

If using grab, core, dredge or ROV samplers, consideration must be given to the grain size, the sampling regime (i.e., top 5 cm of sediment surface vs subsurface cores), the effort required to sample, and the potential for incidental resuspension of microplastics, which can result in an underestimation of microplastic concentrations. In some cases, collections by grab can be further subsampled using a corer. 

### Other environments

The methods outlined above can be tailored and transferred to additional land and aquatic habitats, both freshwater, estuarine, and marine. For land habitats, (e.g., sand dunes beyond the supratidal zone, mudflats, riverbanks, mangroves) the intertidal/supratidal methods should be followed. While for aquatic habitats (e.g., river sediment, estuaries, coral reefs) the subtidal methods are likely more appropriate (Skalska et al., 2020). When tailoring these sample collection methods, the sampling design should always be considered, and the modified method validated. Likewise, the accessibility and features of the site may dictate the ability to perform transects, so changes may be required. Overall, providing detailed information on sample collection is an essential step to ensuring broad study comparisons (see Reporting information).

### Storage

Following collection, and regardless of the collection method, all samples should be processed immediately or preserved until post-survey processing procedures can be completed (see Quality assurance and quality control section). In specific circumstances samples may need to be frozen (e.g., for cores, and to minimise disturbance of layers) or dried to reduce the likelihood of microbial and algal growth (Adomat et al., 2022). Storage containers and vials should only be opened whilst transferring the sample to minimise any extraneous airborne contamination.

Where possible, preliminary processing either in the field or as soon as possible after collection should be applied to enhance their long-term storage. For example, elutriation and/or density separation methods can quickly reduce sediment mass, but note both require optimising to the sediment type. 

Although plastic items do not themselves require preservation (i.e., many are expected to persist in the sediment for many hundreds of years) organic matter is often also part of the collected material. If samples are not preserved, this organic matter can impact the processing, retrieval, identification and chemical analysis of microplastics. Where needed, samples should be stored cool at -4°C (limited time) or frozen at -20°C or -70°C (for cores). In instances where immediate sample preservation or processing is not feasible, considerations need to be made for the influences that biological organisms can have on the retrieval and identification of microplastic particles.

## Sample processing and analyses

After the collection of sediment samples, the microplastics need to be isolated for quantification and identification. Following good laboratory practice, a sample audit should be conducted, and all relevant environmental parameters and sample information entered into a project database or spreadsheet. 

This section briefly summarises the equipment and materials needed to process sediment samples and describes the steps to separate and quantify microplastics, including their physical and chemical characterisation and QA/AC considerations. These procedures can be undertaken either in the field or laboratory, depending on environment, safety considerations, and available facilities in the field.  

### Processing of visible microplastics (1 mm - 5 mm)

### Equipment 

#### Material

- Glass Petri dishes and beakers
- Metal forceps/tweezers
- Metal sieves [sieve diameter and mesh aperture sizes need to be reported; the latter to understand lower size limit (e.g., 1 mm)]

#### Reagents

- Density separation solutions (e.g., Sodium chloride, Potassium iodide, Zinc chloride). See Table 5 below for details
- Chemical digestion reagents (e.g., 30% hydrogen peroxide, 10% potassium hydroxide)
- Ultrapure water (e.g., Milli-Q) or filtered water 

#### Instruments

- Stereomicroscope (recommended, but will be essential for microplastics &lt;1 mm)
- Polymer identification instruments (e.g., FTIR, u-FTIR, ATR-FTIR, RAMAN, py-GC/MS, LDIR) (desirable for polymer type)

### Procedure

Sediment should be sieved through an appropriately sized metal sieve (e.g., 1 mm) and retained microplastics sorted, counted, and identified (see Microplastic characterisation and quantification). Larger natural debris (i.e., algae, shell, sticks, biota) should be removed with forceps or tweezers and liberally rinsed with ultrapure water (e.g., Milli-Q) or filtered water over the sieve to remove any microplastics adhering to their surface. It is recommended a microscope be used where feasible. 

Sediment type, range in grain size, and levels of organic matter can influence the ease of sieving and the downstream separation and identification of microplastic. In the case of finer sediments (i.e., silt, mud, clay), density separation or pre-treatments (i.e., chemical digestion) may assist in separating the microplastics from the sediment and/or organic matter. See below for more details on density separation and chemical digestion. While recommended, it may not always be feasible to include these steps, e.g., in field surveys associated with citizen science monitoring programs. In these and other circumstances, it is critical to accurately report collection information and the minimum size range of plastics that can be captured and visually detected (see Reporting section).

### Processing of microscopic microplastics (1 μm - 5 mm)

### Equipment 

#### Materials

- Glass Petri dishes and beakers
- Metal forceps/tweezers
- Stainless steel filters
- Metal sieves (varied sized, sieve diameter and mesh aperture size need to be reported; the latter to understand lower size limit (e.g., 1 µm))
- Acid-resistant plastic box with lid

#### Reagents

- 30% w/v hydrogen peroxide (H<sub>2</sub>O<sub>2</sub>) - for organic matter removal 
- Fenton’s reagent (H<sub>2</sub>O<sub>2</sub> and FeSO4)
- Density separation solutions (e.g., Sodium chloride, Potassium iodide, Zinc chloride. See Table 2 below for details on appropriateness of different reagents). 
- Ultrapure water (e.g., Milli-Q) or filtered water 

_All reagents and solutions should be filtered (&lt;20 μm) prior to use, excluding the ultrapure water, which is already filtered._


#### Instruments 

- Laminar flow cabinet (optional)
- Filtration equipment, including vacuum pump
- Stereomicroscope (essential for microplastics &lt;1 μm)
- Oven or freeze drier
- Polymer identification instruments (e.g., FTIR, μ-FTIR, ATR-FTIR, RAMAN, py-GC/MS, LDIR)


### Procedures

#### Sediment drying

Depending on the processing method and units of reporting, sediment samples may need to be dried, either in a freeze drier (loosely covered), or in a low heat oven (covered). The time and temperature required to dry the sample will vary depending on the sediment type, grain size, organic load, sample mass, and mode of drying. Caution should be taken when heating sediment samples as plastics may be impacted at temperatures above 40°C. Following drying and depending on the research question, the sample can be homogenised by sieving with a mechanical mixer or hand mixing (with care to ensure no fragmentation of plastic occurs). For larger samples, a subsample of a specific weight (e.g., 100 grams) can be collected (i.e., using a metal corer), ideally this should be done in triplicate to ensure sample representativeness. 

#### Chemical digestion

A pre-treatment to remove organic matter from organic-rich sediments is recommended. This aids in the clarification of the sample and means that the subsequent application of density separation solutions is likely to be more effective, it also allows for the use and re-use of more expensive density separation solutions which are often needed to isolate higher density microplastics. 

There are a number of methods that can be used to digest sediment bound organic matter including 30% w/v H<sub>2</sub>O<sub>2</sub> solution or Fenton’s reagent (H<sub>2</sub>O<sub>2</sub> and FeSO4; the ferric ions act as a catalyst). However, care should be taken when considering degradation of polymers when certain reagents are left for periods of time or temperatures (Di Fiore et al., 2024; Miller et al., 2017; Pfeiffer and Fischer, 2020). When using H<sub>2</sub>O<sub>2</sub> and Fenton’s reagent, the solution should be added to the sediment, mixed with a metal spoon or glass rod for one minute and left covered (e.g., watch glass) for up to 18 hours (depending on the amount of organic matter). To increase the efficiency of this reaction, the solution can be heated to 40 - 50°C to enhance the digestion process (note that temperatures above 40°C may impact and degrade particular polymers more than others). Based on time (i.e., 18 hours) or clarity (i.e., no visible organic matter remaining) or temperature (the reaction is exothermic and will cool once digestion is complete), the reaction should be quenched by washing thoroughly with ultrapure (e.g., Milli-Q) or filtered water (i.e., formation of carbon dioxide bubbles stops). Fenton’s reagent can be challenging with the efficiency of the digestion dependent on the pH of the sample, therefore prior to use further reading on the use of Fenton’s reagent is recommended (e.g., Tagg et al., 2017).  


#### Elutriation

Where organic content is not high, an elutriation pre-treatment to process larger masses of marine and coastal sediments is recommended. Elutriation is a process designed to separate lighter particles from heavier ones, using an upward stream of gas or liquid (Claessens et al., 2013; Hengstmann et al., 2018; Kedzierski et al., 2016; Zhu, 2015), thereby rapidly reducing the initial volume of the sediment sample and concentrating finer solids and debris for subsequent density separation. To separate microplastics from larger sediment samples (i.e., >500 g), samples can be transferred into a tall column (e.g., ~1 m, and preferably of glass or stainless steel) connected to a freshwater source (via a tap at the base of the column). The water flow is controlled through a valve handle and should be monitored by a flowmeter. To avoid the introduction of potential contaminants from the plumbing, the water must first pass through a filtering system (e.g., 1 µm cartridge filter)before entering the base of the column. The water then passes through a 26-µm mesh that ensures a homogeneous distribution of water flow inside the column. When the tap is open, the sand becomes fluidised and the lighter particles are carried to the top of the column. As the water flows over the outlet any floating solid material is collected on a metal sieve with the desired µm aperture (e.g., 10 µm). The optimal flowthrough is dependent on the sediment granulometry and should be determined by spiking experiments (e.g., for a 1 m column, a 1400 L per hour water flow for 3 minutes is optimal for beach sand). The loaded sieves should be covered (e.g., with aluminium foil) and transferred to the laboratory for further processing via density separation. 


#### Density separation 

To separate microplastics from sediments, samples are resuspended in a density separation solution (choice determined by the type of plastics likely to be present), where less dense materials (e.g., microplastics) will float and separate from denser materials (sediment, debris, others) present in the matrix. There are a range of different reagents that can be used for density separation. These differ in their density, and each has advantages or limitations associated with efficiency for microplastic recovery, 

varying levels of toxicity, and price ranges (Rani et al., 2023)(Table 5). These include sodium chloride, sodium tungstate dihydrate, sodium bromide, sodium polytungstate, lithium metatungstate, zinc chloride, zinc bromide, sodium iodide (Crutchett and Bornt, 2024). Higher density reagents are more effective at removing higher density polymers and are often employed when studying sediments, particularly those from intertidal and subtidal environments where heavier plastics sink and settle into the benthic zone. The density of the final solution used must be reported, as it will dictate which plastic polymers can or cannot be retrieved with this methodology.

To extract the microplastics using density separation reagents, the sediment should be transferred into a previously decontaminated glass beaker and the density separation reagent added. The sediment and density separation solution should be gently stirred with a metal spoon or glass rod and allowed to settle. Using a filtration kit (preferably glass or stainless steel), pour the supernatant over an appropriate filter (i.e., metal mesh, glass microfiber, silicon coated filter). The walls of the glass beaker should be rinsed liberally with ultrapure (e.g., Milli-Q) or filtered water to ensure all microplastic items are transferred to the filter. The loaded filter should be stored in a labelled Petri dish and covered with a glass lid. To identify microplastics, captured items should be observed under a microscope. 


**Table 5.** Commonly used density separation reagents, highlighting their advantages and limitations. 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1221px">
<colgroup>
<col style="width: 150px">
<col style="width: 80px">
<col style="width: 180px">
<col style="width: 180px">
</colgroup>
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Density separation reagent</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Density</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Advantages</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Limitations</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium chloride (NaCl)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.2 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers low density polymers (e.g., PE, PS, PP, PMMA, PC)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Readily available</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Less efficient at recovering high density polymers (e.g., PC, PU, PET, PVC, PTFE)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium tungstate dihydrate (H4Na2O6W)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.4 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers low density polymers (e.g., PE, PS, PP, PMMA, PC)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost-effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-        </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Less efficient at recovering high density polymers (e.g., PC, PU, PET, PVC, PTFE)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium bromide (NaBr)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.37 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Lithium metatungstate </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">(Li2O13W4</span>-24<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.62 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Unknown effect on polymers</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Zinc chloride (ZnCl2)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.5 - 1.7 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Zinc bromide (ZnBr2)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.71 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium iodide (NaI)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.6 - 1.8 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Calcium chloride (CaCl2)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.5 - 3 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Potassium Iodide (KI)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.7 g cm</span><sup>-3</sup></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span></td>
  </tr>
</tbody>
</table>

# Biota

**_<span style="text-decoration:underline;">IMPORTANT NOTE:</span> Prior to conducting any work on marine or coastal biota in relation to plastic and microplastic contamination, you must confirm what the permit, ethics, biosecurity, and work health safety requirements are for each specific species of interest. On confirming what is required, no work on marine and coastal organisms should begin until all relevant authorities have granted approval and formal documentation has been attained. Please assess both state and federal requirements._**


## Pre-Survey Preparations

The methods to acquire samples (i.e., capture, collection) of aquatic biota for microplastic assessment may vary according to the environment (e.g., pelagic vs benthic) and status (e.g., live vs dead) of the target species. The information in this section is organised into distinct sampling approaches tailored to major categories of marine and coastal biota. 

### Monitoring microplastic in marine and coastal biota

Analysis of microplastics in aquatic biota is generally conducted under one of the following overarching themes:

- To monitor microplastic presence in the aquatic environment. Bioindicator species, such as bivalves (e.g., mussels, oysters) or plankton, can accumulate microplastics and reflect the presence of contaminants in the ecosystem. Analysing these species over time and space, allows assessing the extent and variations in the presence of microplastics in coastal and marine ecosystems to be assessed. 

- To investigate microplastic  occurrence, accumulation and impacts on biota and across food webs. This involves examining, for instance, the ingestion, accumulation, and potential biological effects of microplastics on organisms, including bivalves, fish, marine mammals, and seabirds, among others. These investigations generally aim to assess the risks posed by microplastics to species and to provide valuable insights into the broader ecological implications of microplastics. This includes biota sampled opportunistically, such as carcasses of deceased individuals, and investigation of plastic presence in the gastrointestinal tract (GIT).

At the time of writing, microplastics have been detected in 1,565 species of wild animals (Santos et al., 2021) from aquatic and terrestrial ecosystems, and this number continues to grow as more species are assessed. However, approaches to monitor microplastics in different biota differ widely due to the inherent differences in size, morphology, digestion, the way the species interact with plastic, the species accessibility for research, animal ethics considerations and permissions, as well as the cultural norms/attitudes surrounding research on different taxa. This is especially the case when it comes to lethal sampling designs, which are sometimes utilised to achieve non (or less) biased sampling for plastic ingestion research, given that many species reduce or alter their feeding behaviour before death. Non-lethal and opportunistic sampling designs can also yield valuable information on microplastic exposure without the need to sacrifice living animals, although these designs are also prone to sampling biases, which will be explored later. 

Generally, it is more common to conduct targeted lethal microplastic exposure baseline and monitoring sampling designs on smaller organisms such as smaller invertebrates (non-cephalopods), although there are exceptions. Lethal sampling designs typically involve the collection or harvest of live animals for the explicit purpose of scientific research. These animals are sacrificed, and plastics contained within them are separated from the organic matter through chemical digestion of the entire animal, post necropsy, or from GIT contents (i.e., ingesta and digesta), and then microplastics quantified. Non-lethal sampling designs, on the other hand, are usually employed when investigating larger organisms (non-fish vertebrates). These often involve either the collection of scats/faeces or regurgitated material from living animals, which can be collected from the environment, or by capturing the animal to procure the sample (i.e., via gastric lavage, or as part of routine health assessments). 

Opportunistic sampling designs are common for larger vertebrates, especially those that are either logistically difficult to access (for example rare or dispersive species) or where ethical and cultural values would curtail permissions to disturb the animal or its habitat for microplastic research (e.g., threatened and otherwise protected species). Opportunistic sampling design often involves the collection of carcasses of animals that have died of natural/incidental causes, been euthanised for veterinary/welfare purposes, or killed for a purpose that is removed from research goals such as aquaculture, wild harvest or by-catch of harvest for human consumption.

While it is not feasible here to include a sampling design for all the species that are investigated for microplastic research, general principles of sampling design, microplastic separation and plastic characterisation and reporting apply. Included here are the main general principles and an overview of approaches for different taxa. 


### Species selection 

For vertebrates, most of the microplastic research around the world has used opportunistic samples, typically necropsy of animals that have died due to a variety of causes. Opportunistic samples are typically sourced from beach-cast individuals, euthanised for welfare purposes, or by-catch (and deceased) in fishing and other commercial activities. However, the number of animals that can be sourced this way in Australia is generally low, not only because of the low numbers of animals dying, but also a lack of organised, accessible centralised systems for reporting and collecting carcasses (e.g., centralised beach monitoring networks, though some jurisdictions have local, site-level or informal citizen-science monitoring networks), which is the case even if the scope of sampling effort is Australia-wide. For example, fisheries by-catch is only reported in specific fisheries, or when there are observers onboard, and carcasses of by-catch animals are typically discarded at sea rather than collected for scientific purposes. For cetaceans, it is unlikely that more than ten individuals are likely to be procured each year unless there is a mass mortality event, such as a mass stranding. It is important to note that permits are still required to investigate these animal carcasses. Therefore, for sampling wild organisms, it is important to plan ahead for the logistic reality of potential low sample numbers, difficulty achieving scientifically robust replication, stratification, and other best practice sampling goals.


The following criteria should be considered when selecting species to investigate and/or monitor:

- Naturally occurring species with a high abundance,
- Species for which robust sampling and processing methods are already established,
- Ease of sampling and laboratory processing,
- Species already commonly used as bioindicators in other areas of research, i.e., marine pollution and conservation monitoring programs,
- Species of ecological, socio-economic and cultural importance,
- Species with a broad coverage of ecological niches, and feeding types,
- Species that do not require ethics for sampling (e.g., those not considered sentient),
- Or, species for which structured/standardised sampling already occurs, and for which the addition of microplastic sampling is possible.

As an example, bivalves are a popular choice given that they fulfil most of these criteria (Ding et al., 2021; Li et al., 2019):

- they are not currently considered to be sentient, 
- do not require ethics,
- are common in intertidal zones and coastal locations globally,
- are relatively easy to collect from the wild, 
- can be sourced from commercial growers or raised in laboratory settings,
- have high economic and ecological value, and
- there is a plethora of literature describing validated methods and their successful implementation in biomonitoring programs.

Other species that have been used as indicator species include small fish (specifically, by sampling their GIT contents) and sediment-dwelling organisms (e.g., worms). A review of plastic bioindicator literature for the North Pacific identified a suite of 12 candidate bioindicator species covering a variety of ecosystem components and a wide range of plastic size classes, including two bivalves, three fish and two sea turtles species that are also present in Australia (Savoca et al., 2022).

#### Note on Listed marine wildlife (EPBC Act, Marine and Migratory or Threatened)

Marine mammals, marine turtles, sea snakes, and several species of seabirds and elasmobranchs are listed as Matters of National Environmental Significance (EPBC Act). This means they are subject to many levels of protection and there is a high barrier for entry for disturbance of these taxa for research generally. Due to this, lethal sampling methods for protected species are very unlikely to be permitted by any authority in Australia. Non-lethal sampling methods are difficult to apply to vertebrate marine wildlife that do not routinely regurgitate, and whose faeces are passed in the seawater, making scat collection logistically difficult. 


### Sampling design 

#### General principles

The first thing that must be considered before commencing field sampling is what question(s) are you trying to answer (see What are the specific goals of my research?). Different research questions may require different sampling designs and most likely different sample collection methods. Refer to the [Survey Design SOP](https://survey-design-field-manual.github.io/) for further details. Sampling designs should also ensure post-survey requirements are adequately considered, as well as the time required to accurately process microplastic samples from biota. Overall, sampling design principles are similar irrespective of whether you are seeking to use biota as a proxy to monitor for the presence of microplastic in the environment or whether you are specifically concerned with monitoring microplastic impacts on specific biota.

Sampling frequency is also dependent on the research question and species being investigated. If variations over time or between seasons are under question, then multiple sampling efforts across seasons or time are required. Ideally, replication is required within each spatial or temporal unit of interest. If simply trying to quantify whether microplastic is present, then a single targeted sampling effort may be appropriate. Notwithstanding, following these guidelines will ensure the comparability of microplastic data from biota.

### Pros and cons of designed vs opportunistic sampling

#### Designed sampling approaches

Biota can be sampled through structured designed sampling approaches - for example, the targeted harvest of a species through a well-planned sampling design.

Examples of designed sampling approaches include:

- Bivalves placed in sea cages at predetermined distances from a river mouth to monitor the reach of microplastic outflow.
- Microplastic loads in polychaete worms sampled in the intertidal zone every kilometre along a coastline of interest.
- Microplastic load in every 50<sup>th</sup> sardine harvested from wild-caught sardine fished commercially for human consumption.
- Microplastic frequency and loads in scats collected weekly over 12 months across a suite of pinniped colonies.

&nbsp;&nbsp; **Strengths**

- &nbsp;&nbsp; Careful control over sampling design means that robust sampling principles such as stratification, randomisation, replication and adequate sampling power can be built in at the design phase,
- &nbsp;&nbsp; Allows for standardisation and comparability,
- &nbsp;&nbsp; Often larger sample sizes, i.e., can assess multiple individuals of a population at any given sampling time,
- &nbsp;&nbsp; Can assess how representative the sample is of the wider population,
- &nbsp;&nbsp; Suitable for long-term monitoring to understand trends in microplastic concentrations, and
- &nbsp;&nbsp; Ideal for differentiating any observed trends.

&nbsp;&nbsp; **Weaknesses**

- &nbsp;&nbsp; Often inappropriate for studies involving whole-organism examination, such as the necropsy of vertebrates (except for fish harvested for human consumption) due to the ethical and legislative hurdles of collecting/harming/disturbing these species for a research purpose,
- &nbsp;&nbsp; Not suited to the investigation of threatened or endangered species in the event biota is sacrificed, and
- &nbsp;&nbsp; Sampling to achieve adequate replication likely to be resource intensive.

#### Opportunistic sampling approaches:

Biota can be sampled through structured or non-structured opportunistic sampling approaches, for example, the collection of carcasses as they become available.

Examples of opportunistic sampling approaches include:

- Microplastic frequency of occurrence, load and characteristics across a suite of by-catch species available through commercial fishing, 
- Microplastic frequency of occurrence, load and characteristics in pilot whales sampled during a mass stranding event,
- Microplastic frequency of occurrence, load and characteristics sampled in carcasses of seabirds and sea turtles that died in care at a marine animal rescue centre, and
- Microplastic frequency and loads in scats collected during a single trip to a pinniped colony.


**Strengths**

- &nbsp;&nbsp; Opportunistic access to rare species and species that move that are difficult or not possible to sample live in the wild, for example, beach-cast animals, stranding events and by-catch of cetaceans, sea turtles and seabirds,
- &nbsp;&nbsp; Opportunistic access to species that ethical permissions would not be granted for targeted disturbance or harvest, for example, threatened species and those covered by legislation for example, protected by the EPBC Act 1999,
- &nbsp;&nbsp; Can provide preliminary data on previously under investigated species, and
- &nbsp;&nbsp; Is often cheaper.

**Weaknesses**

- &nbsp;&nbsp; Prone to sampling biases such as single populations, discrete geographic areas, and other local conditions/contexts that may not be appropriate to generalise,
- &nbsp;&nbsp; Prone to biases affecting the behaviour of the animal before collection, for example, sick animals that become beach-cast may not be feeding normally before death,
- &nbsp;&nbsp; Often smaller sample sizes, i.e., can be a single individual, and
- &nbsp;&nbsp; Difficult to assess how representative the sample is of the wider population and to determine variability.

## Field Procedures

### Materials and equipment for sample collection 

The vast range in size (e.g., from invertebrates to whales), life cycles, anatomy and environment (pelagic vs benthic) of aquatic biota species means that the tissue or type of sample collected varies greatly (Table 6). Likewise, biota can be sampled directly from the environment or from fisheries and aquaculture. Therefore, specific consideration of taxa traits and their habitats is needed to determine the most appropriate collection method – some of these include trawl nets, cages, line, or hand collection by snorkel or SCUBA (Zantis et al., 2021) (Table 7). 

When collecting any sample from marine and coastal biota (from plankton to whales, and benthic to pelagic) or faeces, scat and regurgitate, whether in the field or captivity, it is essential to implement measures to reduce contamination during the collection (e.g., reducing risk of contamination from collection gear; rinsing of external bodies to remove adhered environmental microplastics) (Lusher et al., 2017). Where possible, organisms should be individually weighed, and size measurements taken prior to the dissection and/or extraction of any tissues. If specific dissected tissues are being analysed for microplastic content, these should also be weighed. Samples should be stored in clean, plastic-free containers (preferably in glass) in clean areas, and processed in a clean laboratory environment (see the Quality Assurance and Quality Control (QAQC) section below for more details). 

To correctly represent a population, an appropriate sample size that takes into account the research unit (e.g., species, food web, feeding type) needs to be selected. Power analysis is strongly recommended when planning collections and experimental designs. It is important to consider what would be an appropriate effect size. Before commencing sample collection, a power analysis can be performed to assist in this decision. G*Power (Faul et al, 2007) or pwr package in R (Champley_ et al._ 2020) are suitable for simple sampling designs and can determine the number of samples required to achieve the desired effect size. Sample sizes can be smaller if appropriately justified (e.g., organism availability, statistical power analysis, and monitoring constraints), e.g., see Lavers et al. (2021) for a power analysis calculated to sample microplastics in birds.

**Table 6.** The type of sample that can be collected for analysis of microplastics by organism type. This table is a reference only. Literature reviews and targeted preliminary and further research are required to confirm that the sampling method is appropriate for the organism of interest and suited to the downstream analyses. PPE - Personal Protective Equipment. The **✓**in the table indicates the method(s) that can be used for the aforementioned categories.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-j7cb{background-color:#DEEBF4;border-color:inherit;color:#313130;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-1f03{background-color:#4F81BD;border-color:inherit;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-5cf7{background-color:#DEEBF4;border-color:inherit;color:#313130;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1110px">
<colgroup>
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
<col style="width: 115px">
</colgroup>
<thead>
  <tr>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Sample Type</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Cetaceans &amp; Dugongs</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Pinnipeds</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Marine Turtles &amp; Marine Reptiles</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Marine Birds</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Fish &amp; Elasmobranchs</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Bivalves</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Larger Crustaceans</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Pelagic Invertebrates</span></th>
    <th class="tg-1f03"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Benthic Invertebrates</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-j7cb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Whole organism</span></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
  <tr>
    <td class="tg-j7cb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Trawl</span></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-j7cb"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"></td>
  </tr>
  <tr>
    <td class="tg-j7cb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Faeces</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
  </tr>
  <tr>
    <td class="tg-j7cb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Opportunistic necropsy</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
  </tr>
  <tr>
    <td class="tg-j7cb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Opportunistic regurgitation</span></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
    <td class="tg-5cf7"></td>
  </tr>
</tbody>
</table>
 

**Table 7.** Equipment that is required for field sampling of different aquatic biota groups. This table is a general guide as each sampling strategy will have variations in equipment and sampling requirements.


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-ct8j{background-color:#DEEBF4;border-color:#000000;color:#313130;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-7t3v{background-color:#4F81BD;border-color:#000000;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-kqvf{background-color:#DEEBF4;border-color:#000000;color:#313130;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-svl2{background-color:#DEEBF4;color:#313130;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-flis{background-color:#DEEBF4;color:#313130;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1230px">
<colgroup>
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
<col style="width: 123px">
</colgroup>
<thead>
  <tr>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Sampling Method</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Cetaceans &amp; Dugongs</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Pinnipeds</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Marine Turtles &amp; Marine Reptiles</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Marine Birds</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Fish &amp; Elasmobranchs</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Bivalves</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Larger Crustaceans</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Pelagic Invertebrates</span></th>
    <th class="tg-7t3v"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Benthic Invertebrates</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-ct8j"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Permits</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">*</span></td>
    <td class="tg-ct8j"></td>
  </tr>
  <tr>
    <td class="tg-ct8j"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ethics</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">*</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">*</span></td>
    <td class="tg-kqvf"></td>
  </tr>
  <tr>
    <td class="tg-ct8j"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">PPE</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
  <tr>
    <td class="tg-ct8j"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Trawl net</span></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"></td>
  </tr>
  <tr>
    <td class="tg-ct8j"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Fishing gear</span></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-kqvf"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
  <tr>
    <td class="tg-svl2"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Quadrant &amp; relevant equipment</span></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
  <tr>
    <td class="tg-svl2"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Coring equipment</span></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
  <tr>
    <td class="tg-svl2"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Netting</span></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
    <td class="tg-flis"></td>
  </tr>
  <tr>
    <td class="tg-svl2"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sample collection and storage equipment i.e. Glass jars (appropriately cleaned)</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
  <tr>
    <td class="tg-svl2"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">General field equipment (Datasheets, labels, pencils)</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
  <tr>
    <td class="tg-svl2"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Camera and GPS</span><br></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
    <td class="tg-flis"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">✓</span></td>
  </tr>
</tbody>
</table>


*Cephalopods require ethics approval and may need a permit in some jurisdictions.  


#### Common cross-taxa processing approaches and opportunities for harmonisation

Across the different taxa, there are several common approaches to sample processing and analysis. For general information on standard microplastic separation protocols, see the detailed post-survey sections below, which include details on visual inspection, separation of microplastics from organic matter using chemical/enzymatic digestion and/or density separation, and visual and chemical identification of microplastics. Many of these protocols are suitable for numerous species and tissue types and offer compelling starting points and significant opportunities to increase harmonisation in sample collection, processing, and reporting. These include:

- Necropsy procedures for large animals (cetaceans, sea lions and large sea turtles)
- Necropsy procedures for medium sized animals (sea birds, small sea turtles, large to medium fish)
- Chemical digestion of ingesta and digesta
- Chemical/enzymatic digestion of soft tissues (GI tracts of fish and large crustaceans, soft body of bivalves, soft-bodied pelagic and benthic invertebrates)
- Chemical digestion of chitinous species (small crustaceans, hard-bodied pelagic and benthic inverts)
- Chemical/enzymatic digestion of whole animal (small fish, fish larvae and sponges)
- Collection and digestion of faeces and scats 
- Microscopy protocols
- Polymer identification

However, given the diversity of taxa and sample types (e.g., tissues, faeces, scat, regurgitate) that are now being investigated for microplastics presence and quantification, specific considerations must be given to taxa- and sample-specific protocols for downstream sample processing. Furthermore, in many cases, published protocols are not available and there is a need to establish and validate methods before use (Santana et al., 2022). 

### Taxa-specific collection and processing strategies

#### Cetaceans and dugongs

**_Sampling cetaceans and dugongs_**

Notwithstanding their iconic status and protection in many jurisdictions globally, cetaceans and dugongs are not ideal candidates to monitor or research microplastic because they are large and logistically difficult to work with. 

Most microplastic sampling studies of cetaceans come from the collection and processing of faeces and gut contents from smaller live wild species (i.e., dolphins), and through the necropsy of by-catch, beach stranding and other cetacean carcasses (Lanyon, 2010). It should be noted that many cetacean species move, which means that the plastic data collected may not accurately represent the location of capture/sampling.

**_Separating plastic from organic matter_**

For cetaceans, necropsy is the primary method of separating plastic from organic matter, specifically, via post-mortem examination of the gastrointestinal tract (GIT). There are numerous cetacean post-mortem assessment protocols worldwide (Ijsseldijk et al., 2019; Mazzariol and Centelleghe 2017; Plön et al., 2015). For Australia, please refer to the Australian Government's standardised protocols (Australian Government, 2006). 

One of the challenges for studying plastics in cetaceans, especially larger species, is that when cetaceans are necropsied, often there are many other multidisciplinary samples sought for pathology and other purposes (i.e., pathological evaluation, microbiological and virological analyses, algal biotoxin detection, diet and parasitological investigations), that are collected from the carcass, though standard protocols vary by country. Given the size of cetaceans and the large volume of their GIT contents compared to other organisms, it is common practice to collect plastics of the visible size range (> 1 mm), and uncommon to separate plastics of the microscopic size range. However, when cetacean GIT contents are examined for microplastics &lt;1mm, they are found (e.g., Nelms et al., 2019a). Sieving of GIT contents through a series of sieves of decreasing mesh size, down to the desired minimum size range, is the standardised methodological approach (Corazzola et al., 2021) to investigate GIT contents of marine mammals, and allows for the simultaneous collection of samples for different disciplines, including plastics and microplastics. It also supports respective analyses and comparisons of multipurpose results.

For dugongs, faeces are commonly collected and processed for diet and health studies (Lanyon, 2010). There are no specific standard protocols for separating plastic from the organic matter in dugong faeces but chemical digestion and sieving and/or microscopic analysis are recommended (as detailed in post survey section below) (see also (Nelms et al., 2019b; Ortega-Borchardt et al., 2023).

There are no current standard protocols for GIT sample collection from dugong carcasses or GIT contents from lavaging. However, the general principles for cetacean sampling can be applied to dugongs. The Department of Foreign Affairs and Trade has a dugong necropsy protocol that must be followed (Eros et al., 2007). Following the removal of the GIT, if separate samples for different purpose are to be collected, including for quantification of (micro)plastics, the digesta should be treated following Corazzola_ _et al. (2021).

#### Pinnipeds

**_Sampling pinnipeds_**

Most microplastic sampling studies of pinnipeds come from the collection and processing of scats, which are easily accessible on land at haul out sites, and through the necropsy of by-caught and other deceased pinnipeds. 

**_Separating plastic from organic matter_**

Pinniped scats are widely collected and processed for diet and health studies, with plastic items separated from organic matter using a variety of methods; similar collection protocols can also be applied to microplastic assessments. Scats can be examined for either or both visible size range plastics and microscopic microplastics. 

Though there are no standard protocols for separating plastic specifically from the organic matter in pinniped scats, chemical digestion and sieving and/or microscopic analysis are the recommended approaches (see post survey section below). Additionally, a range of studies have methods that would be appropriate to follow (e.g., Nelms_ _et al. 2019b; Ortega-Borchardt_ _et al. 2023)

Like cetaceans, for pinnipeds, the GIT is often removed from the carcass (sealed at both ends) to examine for plastics, and (micro)plastics can be separated from organic matter via the same sieving method used for cetaceans, following Corazzola et al. (2021). 

#### Marine turtles and other marine reptiles

**_Sampling marine turtles_**

Study of microplastics in sea turtles relies primarily on the necropsy of deceased, by-catch, and beach cast animals and the removal of the GIT from mouth to cloaca. It is difficult to obtain scat in the environment or to sample faeces from live wild marine turtles, though faeces can be collected from animals kept in captivity, for example in rescue and rehabilitation facilities. Marine turtles do not regurgitate, so stomach lavage is the only method available to sample live wild turtle GIT contents. 

**_Separating plastic from organic matter_**

It is common to find macro- and meso-sized plastics during sea turtle necropsy, and these should be reported, following standard protocols such as (Provencher et al., 2019a). The methods for separating (micro)plastic from organic matter vary, depending if the aim is to quantify plastic visible to the naked eye only (more common for marine turtle research; items are hand-picked from the flayed GIT) or both visible size range and microscopic microplastics (less common in sea turtle plastic ingestion research; items are digested as per Caron et al. (2018). There are many other protocols available for microplastic separation from turtle GIT samples (Caron et al., 2016; Caron et al., 2018), many being similar to that of other larger taxa discussed above.

#### Marine birds 

**_Sampling marine birds_**

There are multiple methods to investigate microplastic ingestion by marine birds. Organisms are collected either as a beach-wreck (often opportunistic), by-catch (semi opportunistic), or have died in care (car strike or post fledging, semi opportunistic) or those that are harvested or culled for non-research purposes (e.g., indigenous harvest, culling at airports, euthanasia for other illnesses). Necropsy and removal of the GIT is the main approach for dead seabirds. 

For live birds, the collection of pellets (bolus) naturally regurgitated by some species may be possible, and for other species, other regurgitations (such as induced by birds' defensive behaviour or water-offloading technique) can be used. Scats can also be collected and inspected for microplastic presence, though this is only suitable for some species depending on the viscosity and ease of collection of the scat (Nelms et al., 2019b).  

**_Separating plastic from organic matter_**

The choice of method to separate plastic from sampled marine birds will be dependent on the sample type being investigated, i.e., tissues from necropsy, pellets (boluses), other regurgitations and scats (Provencher et al., 2019b). The method will also depend on whether the observer is quantifying visible-sized microplastics only (more common for seabirds) or visible and microscopic microplastics (while this approach is less common at present, it is gradually becoming more common). For visible size range plastic, necropsy of seabirds can involve examination of just the upper GIT (proventriculus and gizzard/ventriculus) or the entire GIT from oesophagus to cloaca, followed by the visual inspection and/or sieving of GIT contents, and chemical digestion, if needed. For pellets (boluses), typically research just focuses on visible size-range microplastics, which are obtained by dissection of the pellet either by eye or under a microscope. For other regurgitates (e.g., lavage/water offloading), research typically focuses on visible size-range microplastics, which are easily retrieved from the lavage/offloaded water sample by eye; analysis of microplastics requires microscopic analysis. For scats, research focusing on microscopic microplastics is more common (few birds pass visible size range microplastics); scat is generally processed using chemical digestion, followed by density separation (Keys et al., 2023) (see post survey procedures below).

#### Fish 

**_Sampling fish_**

Designed and opportunistic sampling of fish harvested for human consumption are popular methods to sample for microplastic assessment. Due to the widespread harvest of a large variety of fish species across the world, fish are among the easiest organisms to sample for microplastic research. There are numerous protocols to capture fish for microplastic research (Markic et al., 2019; Wootton et al., 2021). Fish can also be opportunistically sampled as by-catch in fishing targeting other species. The GIT and gills are the most commonly collected tissues for microplastic assessment.

**_Separating plastic from organic matter_**

For smaller fish, chemical digestion of the entire animal is common. For medium to large sized fish, the most common methods involve necropsy of the GIT, and depending on the GIT size, a choice of processing the entire GIT for medium species, or analysing anatomical sections of the GIT or the ingesta/digesta for larger fish species using chemical digestion methods. Due to the popularity of fish as a species to sample and concern for human health through secondary ingestion of microplastic when eating fish, there is a wide variety of literature and protocols for the separation of plastic from organic matter in fish (Dawson et al., 2020; Dehaut et al., 2016; Karami et al., 2017; Karlsson et al., 2017; Lusher et al., 2017; Wootton et al., 2021) (see post survey procedures below). 

#### Bivalves

**_Sampling bivalves_**

Bivalves are among the most popular taxa for microplastic monitoring and research, using both designed and opportunistic sampling approaches, with several countries running national microplastic monitoring programs using bivalves. For example, the Republic of Korea performs national monitoring using Pacific oyster (_Crassostrea gigas_), blue mussel (_Mytilus edulis_), and Manila clam _(Ruditapes philippinarum)_ (Cho et al., 2021). The use of bivalves for microplastic monitoring is growing in popularity. National biomonitoring programmes like the long-running 'Mussel Watch' initiative by NOAA in the United States of America, and by others in Europe use local mussel species to assess environmental contamination, and can incorporate microplastic assessments (National Oceanic and Atmospheric Administration, 2020; Provenza et al., 2022).  

There are a variety of sampling approaches used to sample microplastics from bivalves.  Sampling is typically repeated over time given that environmental microplastics may vary across four seasons (Summer-Autumn-Winter-Spring) or rainy (wet/monsoon) and dry seasons in tropical regions. Given that Australia spans latitudinally from the tropics to temperate zone, seasonality should also be factored into bivalve microplastic monitoring efforts in Australia.

Bivalves (e.g., mussels, oysters, pipis) can be sourced from wild populations or commercial growers (e.g., aquaculture). Methods of collection include manual removal by twisting (mussels), hammer and chisel to remove from substrate (mussels, oysters) and trowel/spade and sediment pumps (pipis). Bivalves should be euthanised in an ice-slurry and transferred to -20°C freezer for storage. For the explicit purpose of biomonitoring, cages of selected bivalve species can be deployed in select locations (e.g., following the Mussel Watch approach). Five families of bivalve have been typically monitored. In order of popularity at the time of publishing, these are: mussels, oysters, clams, scallops, and cockles (Ding et al., 2022). 

**_Separating plastic from organic matter_**

Given the small size of most bivalves, to quantify plastics within organisms, chemical or enzymatic digestion of the entire soft tissue (not usually including the shell) of the organism is the most popular (Catarino et al., 2017). Given the small size of microplastics ingested by these organisms, microplastics that are visible to the naked eye are rare, and microscopy and polymer identification are necessary (see post survey procedures). Other research objectives, include investigating rates of ingestion and depuration, and the consequences of microplastic exposure in live animals held in tanks in the laboratory (Hamm et al., 2022; Yap et al., 2020).


#### Large crustaceans (e.g., crabs, lobsters, prawns)

**_Sampling crustaceans_**

Crustaceans, many being detritus feeders, are becoming increasingly popular taxa for microplastic research, using both designed and opportunistic sampling approaches, especially for species that are commercially harvested for human consumption. Crustaceans are collected usually by traps and nets, or by hand via snorkelling or SCUBA .

**_Separating plastic from organic matter_**

Depending on the size of the crustacean, removal and chemical digestion of the GIT only (for larger crustaceans) or chemical digestion of the whole organism (for smaller organisms) are prevalent (Lusher et al., 2017). The crustacean exoskeleton and chitinous lining, however, represents a significant challenge for the digestion of the whole animal, and standard chemical and enzymatic methods are not always suitable (Li et al., 2022). Given the small size of microplastics ingested by these organisms, microplastics that are visible to the naked eye are rare, and microscopy and polymer identification are necessary (Dehaut et al., 2016).  

#### Pelagic invertebrates (including plankton)

**_Sampling pelagic invertebrates_**

Sampling pelagic invertebrates is commonly performed simultaneously with sampling plastics in seawater, either at the sea surface or in subsurface waters. Given the relatively passive or small-scale movement of many pelagic invertebrates with the ocean currents and their large geographic ranges, they serve as valuable subjects for research aiming to establish connections between plastic concentrations in waters (exposure) and in organisms (load). Sampling pelagic invertebrates is often conducted using net-based trawls (typically with a mesh size of 335 mm, but this can vary depending on the target species), such as manta trawl nets, bongo nets, hydra bios nets, and multi-depth samplers, but also with niskin bottles. These methods are used to effectively collect plastics at the sea surface as well (see marine and coastal water section), and consequently, the abundance of plankton and plastics in water samples is often measured concurrently. 

**_Separating environmental plastic from organic matter_**

The method used to separate environmental microplastics from the plankton is dependent on the abundance of organic material present in the sample. Samples with low plankton (and other organic material) abundance can be manually sorted using Bogorov chambers and dissection scope, or (with rinsing) over sieves with aperture size suited to the target species. Samples with high plankton abundance will require complete chemical digestion. 

**_Separating ingested plastic from the organism_**

Given the small size of most pelagic invertebrates, quantifying plastics within (i.e., ingested by) these organisms necessitates chemical digestion of the entire specimen or community of organisms (Egger et al., 2022). Chemical digestions require a sequential process involving the density separation of microplastics from the pelagic community and/or visual inspection of the external surfaces of the sampled community. This precaution ensures that the plastics detected post-digestion originated from within the organisms, as opposed to being present in the environment or adhered to the external surfaces of the organisms. Given the small size of microplastics ingested by these organisms, microplastics that are visible to the naked eye are rare, and microscopy and polymer identification are necessary (see post survey procedures).

#### **Benthic invertebrates**

**_Sampling benthic invertebrates_**

Sampling benthic invertebrates can be, and is often, done at the same time as sampling sediment (e.g., via grabs, see [grab field manual](https://grabs-and-boxcorers-field-manual.github.io/)). As many benthic invertebrates have limited geographic ranges, they are popular in research seeking to link plastic concentrations in sediments (exposure) and in invertebrates (load). Benthic invertebrates can also be collected by hand, and via snorkelling or SCUBA. Larger benthic invertebrates (i.e., sea cucumber, gastropods, tunicates) can be further dissected and relevant tissues removed for microplastics processing (Santana et al., 2022).

**_Separating plastic from organic matter_**

Many benthic invertebrates are small in size (i.e., coral polyps, marine worms), therefore, to quantify plastics within these organisms, chemical digestion of the entire organism followed by polymer confirmation are recommended (Dehaut et al., 2016; Lusher et al., 2017; Santana et al., 2022). Dissected tissues, including the whole GIT, from larger invertebrates (i.e., sea stars, sea cucumber, gastropods) are routinely digested whole (Santana et al., 2022).

## Sample processing and analyses 

### Storage

To ensure sample integrity and to reduce the possibility of extraneous contamination during storage, samples should be placed in appropriately sized, clean storage containers (preferably glass, where possible). 

For whole organisms, individuals or populations (i.e., plankton) can be immediately frozen following collection (ideally at -20<sup>o</sup>C), thereby effectively stopping all body processes including gut clearance. Where possible, whole organisms should be stored flat to minimise the likelihood of internal fluids leaking or draining out. Other preservation methods may be preferred, aligned with research questions (e.g., associated with impacts of microplastic on biota), although to align contamination with endpoints, understanding of the impacts of the different preservation methods on microplastic retrieval or decomposition may be required (see Quality assurance and quality control section).

If analysing the gastrointestinal tract (GIT) for the presence of microplastics in either whole organisms or dissected GIT, it is important to reduce, or preferably stop, gut clearance prior to sample processing and analysis. 

For dissected GIT, the two ends of the GIT should be sealed (e.g., tied closed) and stored flat (to prevent draining from one GIT compartment to others) and immediately frozen (ideally at -20<sup>o</sup>C). For larger GIT, the GIT may be cut into smaller compartments (according to the animal’s anatomy); again, the two ends of each compartment should be sealed and stored flat and immediately frozen. 

### Sample processing 

Once the biota samples have been collected, the microplastics need to be separated for quantification and identification. Following good laboratory practice, a sample audit should be conducted, and all relevant environmental parameters and sample information entered into a project database or spreadsheet. This is particularly important if working with species that are collected under ethics and/or permits, as there will be periodic reporting requirements to meet.

A brief summary of methods used to process biotic samples and a description of the equipment and materials needed to process biotic samples is provided. 

#### Materials

- Glass petri dishes and beakers
- Metal forceps/tweezers
- Metal mesh or glass microfiber filter
- Metal sieve (sieve diameter and mesh aperture size need to be reported; the latter to understand lower size limit (e.g., 1 mm))
- Separating funnel

#### Reagents

- Digestion reagent, commonly H<sub>2</sub>O<sub>2</sub> or KOH (see Table 8, and respective section below). Concentration will depend on the type of organic matter, mass of the biotic samples being digested, and other factors such as whether a shaker or heat bath are being utilised. 
- Enzymes for enzymatic digestion
- Ultrapure water (e.g., Milli-Q)

_All reagents and solutions should be filtered (&lt; 20 μm) prior to use, excluding the ultrapure water, which is already filtered._

#### Equipment 

- Temperature controlled oven 
- Filtration equipment, including vacuum pump
- Stereomicroscope
- Heat bath and/or shaker
- Polymer identification instruments (e.g., FTIR, μ-FTIR, ATR-FTIR, RAMAN, py-GC/MS)

#### Chemical and enzymatic digestion procedures for microplastic separation

Although the literature is being updated frequently as microplastic research advances and matures, it is highly recommended that, where feasible and before starting sample processing, the literature for the specific tissue type being examined be thoroughly reviewed and tissue digestion methods carefully assessed for suitability. Also, because different digestion reagents can impact polymers differently, this should be taken into account when selecting the digestion method, the caveat being that no single method is best or safe for all polymer types.

A digestion step is strongly recommended when investigating microscopic microplastics in biotic samples, to ensure all microplastics can be released from the organic matrix and to achieve a suitable level of clarification to easily identify microplastics under the microscope. There are a range of different chemical and enzymatic reagents that are suited to tissue digestion, the choice dependant on research question, laboratory facilities, availability of reagents and, most importantly, tissue type (Table 8). Ultimately, the chemical digestion method used is a compromise between efficiency, cost, and the known risks and possibilities of polymer degradation (Table 8).

Three ‘general approach’ chemical digestion methods are recommended: 15% hydrogen peroxide, 10% potassium hydroxide under 40<sup>o</sup>C heat, and enzymatic digestion. Recommendations are broadly based on the balance between the advantages they impart, the limitations they introduce, and the impact on polymers (Table 8). 

**Table 8:** Summary table of digestion reagents, their concentrations, advantages and limitations. Based on: Di Fiore et al. (2024) and Pfeiffer and Fischer (2020). 

 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Digestion</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Suggested concentration </span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Advantages</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Limitations</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Degradation of polymers?</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Hydrogen peroxide (H</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">O</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">15-30% </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient, cheap</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes, at high concentrations</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Hydrochloric acid (HCl)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">20%</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient, cheap</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Can degrade polymers, corrosive, toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Nitric acid (HNO</span>3<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> Weak</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient, cheap</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive, discolouration of plastics, degradation of some polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium hydroxide (NaOH)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1M</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive, can cause degradation of some polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Potassium hydroxide (KOH)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">10%</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Efficient</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Corrosive</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Yes, at high concentrations</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Enzymatic digestion</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Safe, efficient</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Expensive, time intense</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">No</span></td>
  </tr>
</tbody>
</table>

# Air

## Pre-Survey Preparations

The methods required for the collection of microplastics from the air are the same for all microplastic sizes and environments?. 

### Sampling design 

Before commencing field sampling, it is necessary to formulate the research question(s) (see What are the goals of my research?). Different research questions may require different sampling designs and, likely, different sampling methods. Sampling designs should also consider post-survey requirements, including the techniques to be used to analyse them and the units of reporting.

The main issues of interest when addressing the presence of microplastics in the air are: 

- Where, what or how much microplastic is there?
- Are there variations in microplastic in space or time?
- What are the sources of microplastic?

Sampling design and approach are dependent on the study objective and the environment being sampled. There are two main approaches when sampling the air for microplastics, namely active and passive monitoring. Active monitoring involves drawing in air through a collection system to capture microplastics. This is typically done using sampling devices that allow for controlled and continuous airflow and collection of airborne particles. Active monitoring provides real-time or near-real-time data on microplastic concentrations and can be useful for monitoring specific sources or events, such as industrial emissions or urban areas with high microplastic pollution. It is also suitable for studying the dynamics of microplastics in the atmosphere. Active sampling is often set up to collect air at the height of the human mouth, so can measure the potential exposure of humans, and therefore assists in assessing human health risks upon inhalation of microplastics. Passive monitoring involves leaving a collection substrate or device in a specific location to capture airborne microplastic deposition over a specific period of time. These substrates can then be analysed in a laboratory to determine the concentration and types of microplastics present. Passive monitoring is useful for understanding long-term trends and assessing microplastic presence in specific environments. Passive sampling is often more applicable for sampling remote areas, as there is no need for access to power. 

Sampling frequency also depends on the research question. If variations over time or between seasons are under question, then multiple sampling efforts across seasons or over time are required. In addition, replication is required within each spatial or temporal unit. Further, research conducted across spatial and/or temporal scales requires a stratified sampling design that enables an estimate of the true microplastic density (or type, weight, volume) at different scales or “strata” representing clearly defined groups (Quinn and Keough, 2002). Samples should be collected randomly from each group. Stratified sampling should also be used when within-habitat variation is high, and it is not feasible to sample entire sites (CSIRO 2022). 

Despite this, if simply trying to quantify whether microplastic is present, then a single sampling effort may be appropriate. Notwithstanding, following these guidelines will allow new data that is collected down the track to be compared. 

The number of samples collected will be determined by the research question as well as the budget, logistics and resources available; with the caveat that a high number of samples allows for greater accuracy (through power and replication) in the estimation of microplastic concentrations in the environment and will ensure greater statistical rigour. It is important to consider what would be an appropriate effect size (i.e. the acceptable difference between the estimate and the true density or volume of microplastics in the air). Before commencing sample collection, a power analysis can be performed to assist in this decision. G*Power (Faul et al., 2007) or pwr package in R (Champley et al., 2020) are suitable for simple sampling designs and can determine the number of samples required to achieve the desired effect size. 

## Field Procedures

### Materials and equipment for collection 

The materials and equipment required for collection of air samples depends on the type of monitoring occurring, that being either active or passive.

#### Active monitoring 

- Air sampling device with vacuum pump and airflow meter (Figure 3)
- Source of electricity 
- Metal forceps
- Metal mesh filter
- Glass Petri dish
- GPS
- PPE (avoid polyester and other plastic fibres)
- Pencils, datasheet, labels, permanent markers

#### Passive monitoring 

- Glass collection device or filter holder
- Metal mesh filter
- Glass fiber filter
- Glass Petri dish
- Metal forceps
- GPS
- PPE (avoid polyester and other plastic fibres)
- Pencils, datasheet, labels, permanent marker


<img src="images/figures/figure3.png" width="" alt="alt_text" title="image_tooltip">

**Figure 3.** Diagram of the set-up of an active monitoring air sampling device.

#### Active monitoring 

For both outdoor and indoor sampling, the sampling device should be placed at a specific, pre-defined height depending on the objective of the study (Perera et al., 2022). If the aim of the study is to test human exposure, it is recommended the device is set between 1.2 m (child standing height, or mouth height of a sitting adult) and 1.6 m. The flow rate must be consistent, and recorded. The recommended flow rate is 100 L/min, which is most commonly used. However, this rate can vary depending on the type of the sampling device used and the capacity of the machine.  

When sampling indoors, it is recommended that less than 10% of the total indoor volume is collected for the sample. To allow for appropriate replication, three independent samples should be collected at each location being tested, but consider study design and power analysis, as described above. Appropriate Quality Assurance and Quality Control procedures must be followed, including the use of blanks (See QAQC section). 

#### Passive monitoring 

For passive sampling, it is important to examine the quantity of airborne microplastics in both wet and dry atmospheric deposition to gauge the overall presence of microplastics in the environment. The wet collection sampler could include a cleaned open beaker with a glass funnel (Azari et al., 2023). For dry sampling, an open glass petri dish, or a glass funnel attached to a beaker would be appropriate. 

For passive monitoring, the sampling device is placed in a specific predefined location in either an indoor or outdoor environment. To allow for appropriate replication, three independent samples should be collected at each location being tested, but consider study design and power analysis, as described above. The time over which the sample is exposed will depend on the research question (Chen et al., 2020; Knobloch et al., 2021).

#### Storage

Following collection, the mesh filter should be placed in a labelled glass Petri dish, and stored until analysis. This can be stored at room temperature if no biological material is included. If biological material is included, it should be refrigerated at 4°C until further analysis (Dong et al., 2021; Huang et al., 2021). 

## Sample processing and analyses

Once the air samples have been collected, the microplastics need to be isolated for quantification and identification. Following good laboratory practice, a sample audit should be conducted and all relevant environmental parameters and sample information should be entered into a project database or spreadsheet. 

In this section, we briefly summarise the equipment and materials needed to process air samples, as well as briefly describe the steps to separate and quantify microplastics, their physical and chemical characteristics, and quality assurance and quality control. 

The following digestion and density separation procedures may not be required if the samples are collected from relatively clean environments, which is commonly the case with active sampling. However, if samples are collected from polluted areas (e.g., industrial sites, near highways), further sample processing, including separating organic material, and density separation may be required. These are outlined below. 

### Equipment 

#### Materials

- Glass Petri dishes and beakers
- Metal forceps/tweezers
- Stainless steel metal filters
- Metal sieve (varied sized, sieve diameter and mesh aperture need to be reported to understand lower size limit (e.g., 20 µm))
- Acid-resistant plastic box with lid
- Aluminium tray

#### Reagents

- 30% hydrogen peroxide (H<sub>2</sub>O<sub>2</sub>) (w/v) - for organic matter removal 
- Density separation reagent (e.g., sodium chloride, sodium iodide or other chemicals outlined below in Table 9) 
- Ultrapure (e.g., Milli-Q) water

_All reagents and solutions should be filtered (&lt;20 μm) prior to use, excluding the ultrapure water, which is already filtered._


#### Instruments

- Filtration equipment, including vacuum pump
- Stereomicroscope

Pre-treatment and procedures for microplastic separation

#### Organic matter removal

A pre-treatment to remove organic material from organic-rich samples is recommended. This helps subsequent processing steps, and means that the subsequent application of density separation solutions is likely to be more effective, it also allows for the use and re-use of more expensive density separation solutions which are often needed to isolate higher density microplastics. First, the sampled material should be transferred to a glass beaker. The H<sub>2</sub>O<sub>2</sub> solution (30% w/v) should be added, mixed with a metal spoon or glass rod for one minute and left in a fume hood until all organic matter is digested (i.e., no organic matter remaining). A reaction will occur degrading the organic matter, and once complete (formation of carbon dioxide bubbles stops) the reaction should be quenched by washing thoroughly with ultrapure water (e.g., Milli Q). 

#### Density separation 

Before the addition of density separation chemicals, samples must be thoroughly washed with ultrapure water to ensure there is no reaction between H<sub>2</sub>O<sub>2</sub> and the chemicals used for density separation. Ultrapure water can be filtered first, prior to adding the density separation solution. 

Air samples should be resuspended in the density separation solution of choice, where the less dense materials (e.g., microplastics) will float and separate from the denser materials (sediment, debris, others) in matrix. There are a range of different reagents that can be used for density separation. These differ in their density, and each has advantages or limitations associated with efficiency for microplastic recovery, varying levels of toxicity, and price ranges (Table 9). These include sodium chloride, sodium tungstate dihydrate, sodium bromide, sodium polytungstate, lithium metatungstate, zinc chloride, zinc bromide, sodium iodide. Different reagents work better for different densities of polymers, with higher density reagents more effective at removing denser polymers. The density of the final solution used must be reported, as it will dictate which plastic polymers can or cannot be retrieved with this methodology.

To extract the microplastics using density separation reagents, first, combine the liquid and the density separation reagent in a previously decontaminated glass beaker. Stir the solution with a metal spoon or glass rod and allow it to settle. Using a filtration kit, filter the supernatant using the chosen filtration device (i.e., metal mesh, glass microfiber, silicon coated filter). After filtering all the liquid contents of your jar, rinse all of the walls of the container to ensure all microplastic items are on the filter. Store the metal filter paper in a labelled cover Petri dish until microscope examination. 

**Table 9.** Summary table of density separation reagents and their advantages and limitations. Post-survey Procedures


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1212px">
<colgroup>
<col style="width: 150px">
<col style="width: 80px">
<col style="width: 180px">
<col style="width: 180px">
</colgroup>
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Density separation reagent</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Density</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Advantages</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Limitations</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium chloride (NaCl)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.2 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers low density polymers (e.g., PE, PS, PP, PMMA, PC)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Readily available</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Less efficient at recovering high density polymers (e.g., PC, PU, PET, PVC, PTFE)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium tungstate dihydrate (Na</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">WO</span>4<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">.2H</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">O</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.4 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers low density polymers (e.g., PE, PS, PP, PMMA, PC)</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost-effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Less efficient at recovering high density polymers (e.g., PC, PU, PET, PVC, PTFE)</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium bromide (NaBr)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.37 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Lithium metatungstate (Li</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">O</span>13<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">W</span>4-24<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.62 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Unknown effect on polymers</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Zinc chloride (ZnCl</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.5 - 1.7 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Zinc bromide (ZnBr</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.71 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Sodium iodide (NaI)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.6 - 1.8 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Calcium chloride (CaCl</span>2<span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.5 - 3 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Toxic to the environment </span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Potassium iodide (KI)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.7 g cm</span>-3</td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Recovers a wide range of polymers </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-toxic</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Expensive</span></td>
  </tr>
</tbody>
</table>


## Microplastics quantification and characterisation 

Microplastic characterisation is usually conducted at three levels (Figure 4), all of which provide key defining information on the microplastic. If the sample contains larger meso and macro plastics, these can often be readily identified visually without isolation, although polymer type still requires chemical confirmation. Similarly, if the experimental design requires that large microplastics (1 to 5 mm) are to be counted, as pieces are visible to the naked eye, the procedures applied at each level are less intensive – although the use of a binocular lens or similar is highly recommended. If small microplastics (1 µm to 1 mm) are also being quantified, a more thorough microscopic procedure is essential. The workflow for processing microplastic samples needs to be tailored to the research question, considering the nature of the sample at the time of collection (i.e., relatively clear vs organic rich), collection method, preservation method, available equipment, level of expertise and finally how the data is to be reported.

![alt_text](images/figures/figure4.png "image_tooltip")


**Figure 4**. The three levels of microplastic characterisation and identification and the type of data produced. Figure adapted from[ Lynch et al 2023](https://setac-au-2023.p.asnevents.com.au/days/2023-08-08/abstract/94523)


## Microplastics quantification 

### Visible microplastics (1 mm - 5 mm)

Quantifying visible microplastics does not necessarily require a microscope and they can often be counted using the naked eye, or weighed. Where further morphological information is required (i.e., texture, surface uniformity), a microscope is recommended. To count microplastics in the visible category the filter or sieve can be investigated by using the naked eye. 

### Microscopic microplastics (1 μm – 1 mm)

There are several ways to quantify microscopic microplastics (i.e., not discernible to the naked eye) once they have been isolated using methods described above (e.g., filter, sieve). Some approaches require manual counting under a microscope, while others rely on microphotography and specific software for semi-automated counting. Table 10 highlights a number of these methods and their advantages and limitations. 

**Table 10.** Table of the different quantification methods for microplastics including their advantages and limitations.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-i6rb{background-color:#DEEBF4;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Microplastic quantification method</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Advantages</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Limitations </span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-i6rb" colspan="3"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Manual counting methods</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Gridded method</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost-effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Straight-forward process</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Time intensive </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Requires experienced operators</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Observer bias</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Fluorescent dyes (e.g., Nile Red)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Cost-effective</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       User friendly </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Added processing steps and chemical considerations</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Does not bind to all polymers</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Dyes biological material (false positive)</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb" colspan="3"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Automated counting methods</span></td>
  </tr>
  <tr>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Image analysis software (e.g., Image J, CellSense image analysis) </span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Highly accurate</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Saves time</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Automated </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Removes human error</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Requires setup and calibration</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Requires specific software</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Requires high resolution microphotographs</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent"> </span></td>
  </tr>
</tbody>
</table>

**Gridded method**

Under a microscope, the gridded method involves examining and counting the microplastics in each square of a real or virtual grid (Brandt et al., 2021). If the microplastics are too numerous a subset could be counted in each square of two diagonals throughout the filter (see Figure 5 below as an example). However, it should be noted that this latter method may not always be representative of the sample. 

![alt_text](images/figures/figure5.png "image_tooltip")

**Figure 5.** An example of the counting technique that could be used to quantify a subset of microplastics. 


**Fluorescent Dyes**

Fluorescent dyes can be chosen based on their properties, including compatibility with the microplastics of interest, stability, and fluorescence characteristics. Nile Red is the most commonly used dye, however, Rhodamine B, Acridine Orange, Propidium Iodide and others can also be used. It is important to note that the choice of fluorescent dye depends on the research objectives, the specific polymers of interest, and the available instrumentation for detection. The dye is mixed with the environmental sample, processed following the post-survey procedures above, and examined using a fluorescence microscope. When illuminated with a specific wavelength of light (excitation wavelength), the fluorescent dye attached to the microplastics absorbs the light energy and re-emits it at a longer wavelength (emission wavelength), producing visible fluorescence, and highlighting the microplastics. 


**Image analysis software**

Software such as ImageJ (Fiji), a free Java-based image processing program (U.S. NIH, MD, USA [https://imagej.nih.gov/ij](https://imagej.nih.gov/ij)), CellSense, Saturna Imaging System ([https://oceandiagnostics.com/microplastics-imaging-technology](https://oceandiagnostics.com/microplastics-imaging-technology)) and others enable semi-automated counting of microplastics. The data can be automatically exported from these software packages into a spreadsheet.  

Once counted, the microplastics should be categorised primarily by shape (fibre, fragment, film, foam, bead, etc) and colour, with other visual factors that support the identification of microplastics recorded, i.e., structure homogeneity, absence of cell structure or glossy surface (see Physical characterisation). All items categorised as putative microplastics should be chemically assessed to confirm their identity (see Chemical characterisation). If there are too many items, chemical assessment of a subset should be undertaken, documenting how the subset was selected and its representativeness determined. For microplastics treated with fluorescent dye, it is also important to identify the chemical signature of the dye, as this needs to be accounted for in later chemical analysis. 

## Physical characterisation

Accurate physical characterisation lies at the heart of understanding the nature and impact of microplastics in environmental samples. This section discusses the methodologies and considerations essential for characterising microplastic contamination based on their physical attributes. Plastic characterisation provides valuable insights into the size distributions, shapes, and other key physical properties of microplastic. Accurately reporting this information can allow researchers to further investigate the complexities of microplastic contamination and investigate trends. The methodologies outlined herein are designed to enhance the accuracy and consistency of microplastic analysis, contributing to a more comprehensive understanding of their presence and potential effects in various environmental matrices.

Reporting of microplastics physical data should be standardised by their size, shape and colour. There are several pre-existing methods for reporting microplastic characteristics, therefore, to ensure comparability, particularly with long-standing datasets, it is recommended that photographs of the different types of microplastic, along with a scale bar, are included in reporting, e.g., as supplementary information in published material. 

### Physical properties

Reporting on the physical properties of microplastics is essential in the identification and confirmation of microplastics, while also providing important information on potential sources of contamination. However, care must be taken to avoid human error or bias when measuring the size, shape, and colour of individual microplastics. Automated image analysis methods can be much faster and more reliable than human assessment, but require photographs/images taken under consistent lighting conditions at a known scale and of suitable resolution to ensure accurate and reproducible measurements of physical parameters. Automated image analysis requires plastics to be photographed on a background that is sufficiently distinct in terms of colour and brightness so that each object can be reliably detected, or under different light sources (i.e., UV light). The use of these resources should be considered to mitigate observer bias, however, they may not be readily available to all.

#### Size

Plastic size is an essential physical attribute for reporting, as it will dictate how plastic interacts with the environment and wildlife. The size of objects can be described in many ways, but for plastics size usually refers to the length of the longest axis (the maximum Feret diameter) and is grouped into different size ranges (Table 2). The simplest method is to categorise the plastic object using visual assessment against a scale bar. For larger objects (> 1mm) length can be measured more precisely using callipers, but this can be time-consuming for large quantities of plastics. If photographs or microscopy images with a known scale are available, automated image analysis software can be used to instantly and precisely measure multiple different size parameters for each detectable object in the image. When reporting size parameters, always specify which parameter was used (e.g. maximum Feret diameter, or major diameter from elliptical approximation) and present size distributions as well as category counts, where possible. It is essential to report the minimum size category in which the approaches used can accurately detect, in line with the size categories in Table 11.


**Table 11.** Size classifications used to categorise plastic, from macroplastics (> 2.5 cm) to microplastics (1 μm* - 5 mm), as well as nanoplastics (&lt; 1μm), which require specialised procedures for detection.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-i6rb{background-color:#DEEBF4;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 923px">
<colgroup>
<col style="width: 614px">
<col style="width: 309px">
</colgroup>
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Plastic category</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Size range</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Macroplastics</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">&gt;2.5 cm</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mesoplastics</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">0.5 - 2.5 cm</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Visible microplastics</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1 - 5 mm</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Microscopic microplastics</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1 μm<sup>*</sup> - 1 mm</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Nanoplastics (outside of the scope of this manual)</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">&lt; 1 μm</span></td>
  </tr>
</tbody>
</table>
<sup>* Note: This field manual only focuses on microplastics > 20 µm. </sup>

 


#### Type

Plastic type is potentially indicative of its original form and function (e.g., pellets used as raw material vs fibres from textiles), though many microplastics are highly fragmented, degraded and show little physical resemblance to the original object. Defining the plastic type is dictated by the apparent shape and texture, both visually assessed, as well as tactility (Table 12). If photographs/images are available, automated image analysis software can provide some indication by measuring various shape parameters of each object (Valente et al., 2023), however, this approach is generally limited to differentiating pellets (small, round) from fragments (small, angular) from fibres (long, thin). The specific shape parameters and the thresholds for differentiating each type must be reported.

 

**Table 12.** Classification of various plastic types observed in environmental samples. Shapes include fibres, fragments, films, beads, and others, providing insights into the diverse forms of plastic pollution. Photo credit: Thomas Crutchett.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-i6rb{background-color:#DEEBF4;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1063px">
<colgroup>
<col style="width: 83px">
<col style="width: 761px">
<col style="width: 219px">
</colgroup>
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Type</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Description</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Photo example </span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pellets</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Small, bead-like plastic particles, from raw materials in industrial plastic production. Normall bigger in size. </span></td>
    <td class="tg-qblk"><img src="https://lh7-us.googleusercontent.com/931sIej2or7wFp1Qei-ERQ0MSzI4aqQDdTUekstJQcK2YusvhvdC8FR357dIqoaHmi4tuFsMroeUaPV9PWm_6KmcWrVoHb3iIvt_qBUSKZ8O01NjOVZWUvELL7M9yxMQiwDnbqyErnEZ60OZZMWs654" width="208" height="147"></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Fragments</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Originate from the breakdown of larger hard plastic objects, like bottles or containers. These fragments can take various shapes and sizes, often with irregular edges. </span></td>
    <td class="tg-qblk"><img src="https://lh7-us.googleusercontent.com/K5yz2oN16iRGiw6Qxtb0auyC9ojHVpBEmuYUkRK5FAr0U7f3bFGpBLwXfB6unBP7VbVCJhOkE7v76o-3J7WLSUc_-miRYIws6wTLsmJ7f76zijqrV7U-Wg5hcX28aTe2Zaruh24MfV3s5XblnqVM9KU" width="208" height="147"></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Filaments</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Strands of synthetic materials. These are often shed from clothing, textiles, and fabrics during washing and wear (fibres) or strands of fishing line which may be in monofilament or braided forms (line). Filaments can generally bend and are of uniform thickness across their length. </span></td>
    <td class="tg-qblk"><img src="https://lh7-us.googleusercontent.com/SBFfVbfks09VEmRU0tkLya1r95_2ftbGnXor9JH2FiG3HN2qOF1mnW0PQhgIoMc1J67xEtUlPCcWXTJpvHs1z6eDjtG0aISnXRA7M5wXgkNsiOxMUsTcZ08S2Um3Nz3M4RJ62JHs8MekvHUSkX58aNk" width="208" height="147"></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Foams</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Expanded plastic foam materials, like foam cups, packaging, rubbers and insulation. These particles are lightweight and will compress if squeezed.</span></td>
    <td class="tg-qblk"><img src="https://lh7-us.googleusercontent.com/87o0sSmr9w6A9rw-pvxul4sB50U5EYqx5dkfq2gFCQL9QvXesKfUf739s2TAMmlpYQzeoX-PXyNCW-X3RgTCs46DzCaKfvd3enpgngi61pG4AdP9hcJLf5d3DF_mjzfLJ50ensHEqZLjv9L0zi6At28" width="208" height="147"></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Films</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Originate from larger soft plastic materials, such as plastic bags and packaging. They are typically thin (and often transparent) and flexible, resembling miniature sheets or layers of plastic. </span></td>
    <td class="tg-qblk"><img src="https://lh7-us.googleusercontent.com/wiGfD6g1rgEhgRDijSvJpBlcZnlnvIizk4AIqNLeupNnOAauQswbzCBkBrK0SLdo4ZNnfustQzF8NhIev80tO5Rq5Bgkp-C1xZ9Bbh7vrYn9uaPhudEJtQhC4G_2Jzm88AB2XbqdxTGJs2KwAQR560Q" width="208" height="147"></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Tyre dust</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Shavings of pieces of tyre, commonly composed of rubber. These plastics are commonly soft to the touch and will compress if squeezed. Further validation using chemical characterisation is often needed to accurately identify. </span></td>
    <td class="tg-qblk"><img src="https://lh7-us.googleusercontent.com/-MAcoH7Si3zRGwIV5hZYniPAXDQ8AI_tw13cRVuOPKDXjpMy7tGO-Hngmz6cyHA8ZmF6OxJM5aeM0ERAPnuevDxXNZTF22fFo2zLgaAAWoxgZq4pJaj-_mMVQNU-xZRQyb605qOSjbz1gpcB9X8I6z0" width="208" height="147"></td>
  </tr>
</tbody>
</table>

#### Colour

The colour of microplastics may be indicative of the original object or the extent of weathering or contamination (e.g., absorption of contaminants and biofilm), and may also influence the likelihood of ingestion by wildlife. Colour has conventionally been reported by assigning each plastic to a colour category based on visual assessment, but human judgment of colour is extremely subjective and the list of colour categories used is far from consistent between different studies. Recent efforts to standardise the reporting of plastic colour recommend using the following six categories: white, yellow, red, green, blue, and black (Provencher et al., 2017), or by comparison to 120 standard Pantone colours (Martí et al., 2020).  These standard categories are inherently imprecise and can still be inconsistently applied by different human observers. If photographs/images are available, the average colour of a plastic object should instead be measured in terms of red, green, and blue (RGB) values or hue, saturation value (HSV) as acquired by the camera. RGB values are more precise and less subjective than colour categories and provide semi-continuous data (e.g. suitable for studying trends such as discolouration), but care must be taken to ensure the images are taken under consistent white lighting to correctly reproduce true colours. For larger (>1 mm) plastics that can be imaged using conventional photography, a photographic colour reference card imaged alongside the plastics can provide a point of calibration ensuring greater consistency in colour reproduction. If a colour reference card cannot be included, it is essential to report the lighting used (source, colour, temperature, etc.). It is important to note that for transparent and semi-transparent plastics, apparent colour may also be affected by the colour of the background.


## Chemical characterisation 

Due to challenges in identifying some microplastics using visual methods, especially small and/or transparent items, chemical analysis should be used to validate the identification of plastic, and confirm polymer composition and the anthropogenic nature of the particles. Importantly, polymer identification can also help identify the potential sources of microplastic, which in turn can influence regulation and policy. To confirm and validate that all retrieved particles were plastics, the preference should be that 100% of items are assessed. In instances where the number of putative microplastics is high and resources are not commensurate, then subsampling should match the resources available. If subsampling does occur, it is essential that the percentage of microplastics tested is reported, as well as the method used to select this subset and how representative this may be of the entire sample. This is an essential step to validating that the retrieved putative microplastics are indeed plastic, particularly for smaller microplastics. 

There are several spectroscopy and spectrometry options for the chemical identification of plastics, with the method employed often dependent on the available equipment and the research question (Table 13). Although any chemical information about the microplastic is useful, Fourier-Transform Infrared Spectroscopy (FTIR) and Raman spectroscopic techniques are routinely used. 

The chemical identification of microplastics involve comparisons of measured spectroscopic/spectrometric data compared to reference libraries of known materials. Reference libraries are usually a built-in functionality of commercial software used to operate the equipment, but the selection and breadth of available libraries vary between manufacturers and equipment. Furthermore, identification of plastics by spectroscopic FTIR and Raman methods can be complicated by chemical weathering, which alters the signature of the base material, and by biological and chemical contamination, which may introduce substantial secondary peaks in FTIR measurements and background fluorescence in Raman measurements (Fernández-González et al., 2021; Phan et al., 2022). Because library matching is a mathematical comparison, it may be misled by the appearance of altered or additional peaks, or by changes in background. To avoid erroneous assignments of weathered/degraded/contaminated plastics to inappropriate materials, matches should be assessed by an expert. Always consider whether the closest matching material spectrum is appropriate given the observed peaks, as well as the shape, colour, and texture of the sample.

**Table 13.** Summary table of polymer identification instrumentation and their advantages, limitations, and minimum size that can be sampled. 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-dzaw{background-color:#4F81BD;color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-i6rb{background-color:#DEEBF4;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-qblk{background-color:#DEEBF4;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1068px">
<colgroup>
<col style="width: 84px">
<col style="width: 182px">
<col style="width: 401px">
<col style="width: 401px">
</colgroup>
<thead>
  <tr>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Machine</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Size limit</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Advantages</span></th>
    <th class="tg-dzaw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#FFF;background-color:transparent">Limitations</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">μ-FTIR</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">20 μm</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Sample retained</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Broadly applicable to a range of samples</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Commercial and open-source libraries of polymer spectra available</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Time intensive</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">ATR-FTIR</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">20 μm</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Sample retained </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Broadly applicable to a range of samples</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Commercial libraries of polymer spectra available</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Time intensive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Soft/brittle samples may be damaged </span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Can only be done efficiently for larger microplastics (&gt; 500 um)</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Raman</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1 μm</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       No contact and sample retained</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Broadly applicable to a range of samples</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Background fluorescence from plastic additives and/or contaminants can increase identification complexity</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Time intensive</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Pyr-GC/MS</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Independent of particle size</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Broadly applicable to a range of samples</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Suitable for simultaneous identification and mass quantification of plastics</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-        Reduces sample treatment</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Polymer types and abundance cannot be associated with particle size, color, shape, or numbers</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Costly</span></td>
  </tr>
  <tr>
    <td class="tg-i6rb"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">LDIR</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">20 μm</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Non-destructive</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Quicker analysis</span></td>
    <td class="tg-qblk"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">-       Costly</span></td>
  </tr>
</tbody>
</table>