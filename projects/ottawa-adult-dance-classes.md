---
layout: page
title: Ottawa Adult Dance Classes Repository
permalink: /projects/ottawa-adult-dance-classes/
---

<link rel="stylesheet" href="{{ "/assets/css/custom.css" | relative_url }}">

# List of Adult Dance Classes in Ottawa

The welcome message will go here one day :)

![Project image](https://placehold.co/600x300?text=Project+1)

## Filters

<form class="form">

				

<div class="form-group row">
<label for="selectedArea" class="col-sm-2 col-form-label">Select Area(s):</label>
<div class="col-sm-10">
<div class="checkbox">
<label><input type="checkbox" id="centralCheckbox" class="areaCheckbox" value="Central" checked=""> Central</label>
</div>
<div class="checkbox">
<label><input type="checkbox" id="eastCheckbox" class="areaCheckbox" value="East" checked=""> East</label>
</div>
<div class="checkbox">
<label><input type="checkbox" id="southCheckbox" class="areaCheckbox" value="South" checked=""> South</label>
</div>
<div class="checkbox">
<label><input type="checkbox" id="westCheckbox" class="areaCheckbox" value="West" checked=""> West</label>
</div>
</div>
</div>


</form>

<div class="mt-3">
<button class="btn btn-secondary" onclick="clearAllFilters()">
Reset filters to default
</button>
</div>
<div class="mt-3">
<a href="#csvData" class="btn btn-primary">
View dance classes
</a>
</div>


<h2>Dance classes</h2>
<p>Please <a href="https://forms.gle/uYWN8SJGCwrpU3249" target="_blank">fill this form if you would like to submit a dance class / teacher to be added to the list</a>. </p>
<div id="csvData"></div>

<!-- Include PapaParse library -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/PapaParse/5.3.0/papaparse.min.js"></script>
<script src="{{ "/assets/js/ottawa-adult-dance-classes.js" | relative_url }}"></script>
