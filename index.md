---
layout: default
title: Tikri
description: "Home page of Tikri Project — photographic and documentary archive of Tikri, India"
categories: [Project pages]
created: 2026-05-14
---

# Tikri

**Tikri** is a photographic and community documentation project focused on preserving visual, cultural, and everyday histories connected to Tikri, India.

The project documents streets, homes, neighbourhoods, markets, places of worship, landscapes, objects, memories, and local stories through photographs and open digital archives.

Tikri explores collaborative and low-cost approaches to digital preservation, storytelling, and local documentation using open platforms, lightweight infrastructure, and AI-assisted workflows.

<div id="map"></div>

<link
  rel="stylesheet"
  href="https://unpkg.com/leaflet/dist/leaflet.css">

<script
  src="https://unpkg.com/leaflet/dist/leaflet.js">
</script>

<script>

const map = L.map('map').setView(
  [28.83353, 76.98769],
  14
);

L.tileLayer(
  'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
  {
    attribution:
      '&copy; OpenStreetMap contributors'
  }
).addTo(map);

L.marker([28.83353, 76.98769])
  .addTo(map)
  .bindPopup('<strong>Tikri</strong><br>Community documentation project');

</script>

## Project Team

- Rafika Pravin — Project Lead
- Moina — Project Lead
- [Sunil Abraham](https://sunilabraham.in/sunil/) — Advisor

## Triple Under Utilisation Theory

Tikri is an application of **Triple Under Utilisation Theory**, conceived by Sunil Abraham.<sup><em>Details to be added</em></sup>

The theory examines how existing digital infrastructure, community knowledge, and human capability often remain underused despite being widely available. The project explores how accessible technologies can support documentation, archiving, storytelling, public participation, and collaborative knowledge creation.

The project also examines how smartphones, open platforms, and AI-assisted tools can help support local documentation efforts, including photography, oral history, mapping, and community archiving.

## Planned Areas

- Photographs
- Streets and neighbourhoods
- Markets and everyday life
- Architecture and old houses
- Oral histories and memories
- Local stories and narratives
- Maps and location-based documentation

<style>
#map {
  width: 100%;
  height: 520px;
  margin: 2rem 0;
  border-radius: var(--radius);
  overflow: hidden;
  box-shadow: var(--shadow);
  border: 1px solid var(--border);
}

iframe {
  width: 100%;
  max-width: 100%;
  border: 0;
}

.table-wrapper {
  overflow-x: auto;
  margin: 2rem 0;
}

table {
  width: 100%;
  min-width: 600px;
  border-collapse: collapse;
}
</style>
