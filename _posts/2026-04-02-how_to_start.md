---
member: soyee
title: How to start
---
_Here you can learn how to establish an ELN entry step-by-step._

## 1. Open your ELN

You can choose to log in directly with a Gmail address or any other E-Mail address of your choice. Simply click 
<img class="icon" alt="An icon of rounded bottom flask" src="{{ site.baseurl }}/assets/images/ELN.png"> to open a new tab for your ELN.

## 2. Add your reaction and reagents

This could be accomplished in two different manners: either first the drawing of the reaction equation in the chemical editor then fill in the <span class="module">Reagents</span> module, or

**first data input in the** <span class="module">Reagents</span> **module then add the chemicals into the chemical editor**.

The latter is more recommended as it saves more time afterwards (you'll see by the time you use the ELN more intensively.)

### 2.1 Input the CAS-Number of your reagents then add them to the chemical editor (recommended)

Simply look up the CAS-Number of your reagents and target product on [GESTIS](https://gestis.dguv.de/search) (in German) or on [CAS Sci Finder](https://scifinder-n.cas.org/) (in English). Paste the CAS-Number onto a cell in the column <span class="field">code</span> and press Enter. In the pop-up window click once onto the chemical of choice. Usually fields in <span class="field">Name</span>, <span class="field">mf</span> (molecular formula), <span class="field">mw</span> (molecular weight) and <span class="field">density</span> would be automatically filled up. Nevertheless for some molecules, of which relatively few literatures are currently available, it might require manual input of the data. 
\\
To add the required chemicals to the chemical editor simply click onto the 
<span class="icon"><svg style="margin: 0;" width="20" height="20" viewBox="0 0 300 300" xmlns="http://www.w3.org/2000/svg"><polygon points="150,10 280,85 280,215 150,290 20,215 20,85" fill="none" stroke="#000" stroke-width="10" stroke-linejoin="round"/></svg></span> 
icon on the right end of your chemical of choice. Drag your starting materials to the left side of the reaction arrow and products to the right side. Then click <img class="icon" alt="the second icon of the left side in the toolbar of the chemical editor" src="{{ site.baseurl }}/assets/images/clean_up.png"> to clean up your reaction equation.

### 2.2 Calculation of the amounts of reagents required (*Ansatztberechnung*)
*Please be aware the following instructions are given based on your OC2 Practical only. There is actually more room to play around with the ELN functions.*
In the column <span class="field">mmoles</span> put in the number of moles of the reagents and starting materials according to your *Anleitung*. Cells in <span class="field">equiv</span> as well as <span class="field">g</span> and <span class="field">ml</span> should be automatically updated. If not, check if the chemical is in solid state under standard conditions thus no available information for density. Manual input is always possible.

Next make sure your have the "Linked" checkbox on the right side checked. Fill in the desired yielding for your product (aka in <span class="field">g</span> 10 for liquid or 5 for solid compounds). The amount required according to the equation in the chemical editor would then be automatically updated. 

### 2.3 GHS Pictograms, H- and P-Statements
In the <span class="module">Reagents</span> it is possible to automatically generate the GHS Pictograms of the chemicals listed and furthermore retrieve their H- and P-Statements accordingly without manual searches.

First click onto the
<span class="hazard"><svg style="margin: 0; vertical-align: middle;" width="30" height="30" viewBox="0 0 680 600" xmlns="http://www.w3.org/2000/svg"><polygon points="340,60 560,480 120,480" fill="none" stroke="#222" stroke-width="20" stroke-linejoin="round"/><rect x="327" y="200" width="26" height="150" rx="6" fill="#222"/><circle cx="340" cy="410" r="18" fill="#222"/></svg></span> 
in the header row to activate the feature. Once the feature is activated the 
<span class="icon"><svg style="margin: 0; vertical-align: middle;" width="30" height="30" viewBox="0 0 680 600" xmlns="http://www.w3.org/2000/svg"><polygon points="340,60 560,480 120,480" fill="none" stroke="#222" stroke-width="20" stroke-linejoin="round"/><rect x="327" y="200" width="26" height="150" rx="6" fill="#222"/><circle cx="340" cy="410" r="18" fill="#222"/></svg></span> 
would appear in each of the rows of the chemicals. Click onto one to generate the GHS Pictograms which are shown in the module.

To browse the H- and P-Statements click onto the <span class="icon">i</span> next to the pictograms.

<video autoplay muted loop playsinline>
    <source src="{{ site.baseurl }}/assets/videoclips/2026-04-01 11-48-47.mp4" type="video/mp4">
</video>
