---
layout: base
title: Home
---

<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <!-- Hoofd-cirkels -->
    <circle cx="65" cy="130" r="25" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="135" cy="150" r="30" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="100" cy="70" r="25" stroke="black" stroke-width="5" fill="white"/>

    <!-- Extra cirkel buiten de driehoek -->
    <circle cx="160" cy="90" r="15" stroke="black" stroke-width="5" fill="white"/>
</svg>

<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">

    <!-- Aangepaste lijnen tussen de middelpunten van de cirkels -->
    <line x1="65" y1="130" x2="135" y2="150" stroke="black" stroke-width="5"/>
    <line x1="100" y1="70" x2="65" y2="140" stroke="black" stroke-width="5"/>

    <!-- Hoofd-cirkels -->
    <circle cx="65" cy="130" r="25" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="135" cy="150" r="30" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="100" cy="70" r="25" stroke="black" stroke-width="5" fill="white"/>

    <!-- Extra cirkel buiten de driehoek -->
    <circle cx="160" cy="90" r="15" stroke="black" stroke-width="5" fill="white"/>
</svg>

<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <!-- Aangepaste lijnen tussen de middelpunten van de cirkels -->
    <line x1="65" y1="130" x2="135" y2="150" stroke="black" stroke-width="5"/>
    <line x1="100" y1="70" x2="65" y2="140" stroke="black" stroke-width="5"/>

        <!-- Lijnen naar de extra kleine cirkel -->
    <line x1="160" y1="90" x2="100" y2="70" stroke="black" stroke-width="5"/>

    <!-- Hoofd-cirkels -->
    <circle cx="65" cy="130" r="25" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="135" cy="150" r="30" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="100" cy="70" r="25" stroke="black" stroke-width="5" fill="white"/>

    <!-- Extra cirkel buiten de driehoek -->
    <circle cx="160" cy="90" r="15" stroke="black" stroke-width="5" fill="white"/>
</svg>



<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <!-- Lijnen tussen alle cirkels -->
    <line x1="65" y1="140" x2="135" y2="150" stroke="black" stroke-width="5"/>
    <line x1="135" y1="150" x2="100" y2="70" stroke="black" stroke-width="5"/>
    <line x1="100" y1="70" x2="65" y2="140" stroke="black" stroke-width="5"/>
    
    <!-- Lijnen naar de extra kleine cirkel -->
    <line x1="160" y1="90" x2="100" y2="70" stroke="black" stroke-width="5"/>
    <line x1="160" y1="90" x2="135" y2="150" stroke="black" stroke-width="5"/>


    <!-- Hoofd-cirkels -->
    <circle cx="65" cy="130" r="25" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="135" cy="150" r="30" stroke="black" stroke-width="5" fill="white"/>
    <circle cx="100" cy="70" r="25" stroke="black" stroke-width="5" fill="white"/>

    <!-- Extra cirkel buiten de driehoek -->
    <circle cx="160" cy="90" r="15" stroke="black" stroke-width="5" fill="white"/>
</svg>

<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <!-- Lijnen tussen de cirkels, getekend eerst zodat ze achter de cirkels blijven -->
    <line x1="65" y1="130" x2="135" y2="150" stroke="black" stroke-width="5">
        <animate attributeName="x1" values="65; 70; 65" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="y1" values="130; 125; 130" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="135; 140; 135" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="y2" values="150; 155; 150" dur="2s" repeatCount="indefinite"/>
    </line>
    <line x1="100" y1="70" x2="65" y2="140" stroke="black" stroke-width="5">
        <animate attributeName="x1" values="100; 105; 100" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="y1" values="70; 75; 70" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="65; 70; 65" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="y2" values="140; 135; 140" dur="2s" repeatCount="indefinite"/>
    </line>
    <line x1="160" y1="90" x2="100" y2="70" stroke="black" stroke-width="5">
        <animate attributeName="x1" values="160; 165; 160" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="y1" values="90; 85; 90" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="100; 105; 100" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="y2" values="70; 75; 70" dur="2s" repeatCount="indefinite"/>
    </line>
    
    <!-- Definieer animatie van de hoofd-cirkels -->
    <circle id="circle1" cx="65" cy="130" r="25" stroke="black" stroke-width="5" fill="white">
        <animate attributeName="cx" values="65; 70; 65" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="130; 125; 130" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle id="circle2" cx="135" cy="150" r="30" stroke="black" stroke-width="5" fill="white">
        <animate attributeName="cx" values="135; 140; 135" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="150; 155; 150" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle id="circle3" cx="100" cy="70" r="25" stroke="black" stroke-width="5" fill="white">
        <animate attributeName="cx" values="100; 105; 100" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="70; 75; 70" dur="2s" repeatCount="indefinite"/>
    </circle>
    <!-- Extra kleine cirkel buiten de driehoek -->
    <circle id="circle4" cx="160" cy="90" r="15" stroke="black" stroke-width="5" fill="white">
        <animate attributeName="cx" values="160; 165; 160" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="90; 85; 90" dur="2s" repeatCount="indefinite"/>
    </circle>


</svg>

