---
layout: page
title: Publications
permalink: /publications/
description:
nav: true
nav_order: 2
hide_title: true
---

<style>
/* Publication buttons */
.publications .links .btn {
  color: var(--global-theme-color) !important;
  border: 1px solid var(--global-theme-color) !important;
  background-color: transparent !important;
  border-radius: 6px;
  padding: 0.25rem 0.6rem;
  margin-right: 0.3rem;
  margin-top: 0.25rem;
  transition: all 0.2s ease;
}

.publications .links a,
.publications .links a.btn,
.publications .links .bib,
.publications .links .abstract {
  cursor: pointer !important;
}

/* Make the journal badge look like the other buttons */
.publications abbr.badge {
  background: transparent !important;
  border: 1px solid var(--global-theme-color) !important;
  border-radius: 0;
  color: var(--global-theme-color) !important;
  font-weight: normal;
  font-size: 0.92rem;
  padding: 0.25rem 0.6rem;
}

.publications abbr.badge a {
  color: var(--global-theme-color) !important;
  text-decoration: none;
  display: block;
  width: 100%;
  height: 100%;
  font-size: inherit;
}

/* Hover exactly like DOI/PDF/Bib */
.publications abbr.badge:hover {
  background: var(--global-theme-color) !important;
}

.publications abbr.badge:hover a {
  color: white !important;
}

/* Hover effect */
.publications .links .btn:hover {
  background-color: var(--global-theme-color) !important;
  color: white !important;
  border-color: var(--global-theme-color) !important;
  text-decoration: none !important;
}

/* Click effect */
.publications .links .btn:active {
  transform: scale(0.97);
}

/* Keyboard focus */
.publications .links .btn:focus {
  box-shadow: 0 0 0 0.15rem color-mix(in srgb, var(--global-theme-color) 25%, transparent);
}

.publications {
  font-size: 0.92rem;
}

.publications h1,
.publications h2,
.publications h3,
.publications h4,
.publications h5,
.publications h6 {
  font-size: 1.35rem !important;
  font-weight: 300 !important;
  color: var(--global-text-color) !important;
  opacity: 1 !important;
  text-align: left !important;
  float: none !important;
  clear: both !important;
  display: block !important;
  margin: 1.2rem 0 0.6rem 0 !important;
  padding: 0 0 0.6rem 0 !important;

  border: none !important;
  border-bottom: 1px solid var(--global-divider-color) !important;
  box-shadow: none !important;
}

/* ---------- Author styling ---------- */

/* Remove underline from author links */
.publications .author a,
.publications .author a:link,
.publications .author a:visited,
.publications .author a:hover,
.publications .author a:active {
  color: inherit !important;
  text-decoration: none !important;
  border-bottom: none !important;
  box-shadow: none !important;
}
/* Remove underline from the main author (the emphasized one) */
.publications .author em {
  text-decoration: none !important;
  border-bottom: none !important;
  box-shadow: none !important;
  font-style: italic; /* keep italic if you want */
}
/* Remove underline from "more authors" */
.publications .more-authors,
.publications .more-authors:hover {
  text-decoration: none !important;
  border-bottom: none !important;
  box-shadow: none !important;
  color: inherit !important;
  cursor: pointer;
}
</style>

<div class="publications">
  {% bibliography %}
</div>