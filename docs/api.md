---
layout: default 
title: API Specification
---

# Live API Specification

This documentation is automatically generated from our OpenAPI Specification (OAS) file. Use the interface below to explore all endpoints and try out requests directly.

<div id="swagger-ui"></div>

<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/swagger-ui-dist@5/swagger-ui.css" >
<style>
    .swagger-ui {
        padding-top: 20px;
    }
    .swagger-ui .topbar {
        /* Hide the default Swagger top bar to have a cleaner look. */
        display: none;
    }
</style>

<script src="https://cdn.jsdelivr.net/npm/swagger-ui-dist@5/swagger-ui-bundle.js"></script>
<script src="https://cdn.jsdelivr.net/npm/swagger-ui-dist@5/swagger-ui-standalone-preset.js"></script>
<script>
    window.onload = function() {
      // **IMPORTANT:** Replace 'path/to/your/openapi.yaml' with the correct URL
      // This is the file you uploaded to your GitHub Pages site.
      const ui = SwaggerUIBundle({
        url: "/sofarkotta.yml", 
        dom_id: '#swagger-ui',
        deepLinking: true,
        presets: [
          SwaggerUIBundle.presets.apis,
          SwaggerUIStandalonePreset
        ],
        plugins: [
          SwaggerUIBundle.plugins.DownloadUrl
        ],
        layout: "StandaloneLayout"
      })

      window.ui = ui
    }
</script>
