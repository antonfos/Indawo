# Indawo
## Indawo Javascript Library 


#### Usage

In your web page define a div on your page with an ID

example:
`<div id="map_canvas" style="height:800px"></div>` 

with a minimum height of 350px;
  
After loading the indawo.min.js file

Add the following JavaScript
```
<script>
if (typeof idw === 'object') {
    url = "Supplied URL;
    apikey = "Supplied API Key";
    idw.init(url, apikey, 'DIV_id');
}
</script>
```

That is all you need to do to initialise the map.


  
