<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/RezareSystems/moa-platform-output-ecosystem-api">
    <img src="img/logo.png" alt="Logo" height="100">
  </a>

  <h1 align="center">Pure Farming - Schema</h1>

  <p align="center">
    JSON Schema for Resource Types and Data.
    <br />
    <a href="https://github.com/Pure-Farming/Schema"><strong>Explore the docs »</strong></a>
  </p>
</p>

# Introduction
This is the home of the JSON Schemas that define how Pure Farming represents the data that it deals with, whether that is spatial data, crop data, or rainfall data.  

Wherever possible we have made the most possible use of international standards that exist and have either used them wholesale, or built on them if they were not a direct fit, for example some of the standards we have used are:  
- ICAR
- GeoJSON
- OGC Core

## Structure of the Schemas
The schemas are split up based on the groupings of the Resource Types, principally this means that they are grouped by a domain, for example "crop".