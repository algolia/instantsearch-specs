---
title: GeoSearch
type: widget
html: |
  <div class="ais-GeoSearch">
    <div class="ais-GeoSearch-map">
      <!-- Map element here -->
    </div>
    <div class="ais-GeoSearch-control">
      <label class="ais-GeoSearch-label">
        <input class="ais-GeoSearch-input" type="checkbox">
        Search as I move the map
      </label>
    </div>
    <button class="ais-GeoSearch-reset">
      Clear the map refinement
    </button>
  </div>
alt1: Search as I move the map disabled
althtml1: |
  <div class="ais-GeoSearch">
    <div class="ais-GeoSearch-map">
      <!-- Map element here -->
    </div>
    <div class="ais-GeoSearch-control">
      <button class="ais-GeoSearch-redo">
        Redo search here
      </button>
    </div>
    <button class="ais-GeoSearch-reset">
      Clear the map refinement
    </button>
  </div>
alt2: Control disabled
althtml2: |
  <div class="ais-GeoSearch">
    <div class="ais-GeoSearch-map">
      <!-- Map element here -->
    </div>
    <button class="ais-GeoSearch-reset">
      Clear the map refinement
    </button>
  </div>
classes:
  - name: .ais-GeoSearch
    description: the root div of the widget
  - name: .ais-GeoSearch--noRefinement
    description: the root div of the widget with no refinement
  - name: .ais-GeoSearch-map
    description: the map container of the widget
  - name: .ais-GeoSearch-control
    description: the control element of the widget
  - name: .ais-GeoSearch-label
    description: the label of the control element
  - name: .ais-GeoSearch-input
    description: the input of the control element
  - name: .ais-GeoSearch-redo
    description: the redo search button
  - name: .ais-GeoSearch-redo--disabled
    description: the disabled redo search button
  - name: .ais-GeoSearch-reset
    description: the reset refinement button
  - name: .ais-GeoSearch-reset--disabled
    description: the disabled reset refinement button
---
