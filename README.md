## Imlement Semantic ui

* Install packages\

  - yarn add semantic-ui-css jquery



* Copy CSS/JS into app/assets (Propshaft requirement)



  - mkdir -p app/assets/builds
  - cp node_modules/semantic-ui-css/semantic.min.css app/assets/builds/
  - cp node_modules/semantic-ui-css/semantic.min.js app/assets/builds/
  - cp node_modules/jquery/dist/jquery.min.js app/assets/builds/

* Import in application layout



  <%= stylesheet_link_tag "semantic.min", "data-turbo-track": "reload" %>
 


  <%= javascript_include_tag "jquery.min" %>
  <%= javascript_include_tag "semantic.min" %>
