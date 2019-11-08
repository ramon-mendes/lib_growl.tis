![](https://github.com/ramon-mendes/lib_growl.tis/blob/master/demo.gif?raw=true)

## Usage

Include 'lib_growl.tis' in script and 'lib_growl.css' in CSS:

```HTML
<script type="text/tiscript">
	include "lib_search/lib_search.tis";
</script>

<style>
	@import url(lib_search/lib_search.css);
</style>
```

Call grow() function in TIScript:

```JS
Growl("Hello World from growl.tis library!");
Growl("A #error message", #error);
Growl("A #success message", #success);
```