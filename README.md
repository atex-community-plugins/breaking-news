Breaking News Plugin
===============
This is Breaking News Plugin for Polopoly

Steps to install: 
<br />
1. Add a new field in standard.Article template	
<br />
```<field name="breakingNews" input-template="p.Checkbox" label="Breaking News" />```
2. Add new component in standard.Article.Mapping
<br />
```<component group="mapping" name="breakingNews.checked">breakingNews_b</component>```

## Polopoly Version
10.16.0-fp1

## Code Status
The code in this repository is provided with the following status: **EXAMPLE**

Under the open source initiative, Atex provides source code for plugin with different levels of support. There are three different levels of support used. These are:

- EXAMPLE  
The code is provided as an illustration of a pattern or blueprint for how to use a specific feature. Code provided as is.

- PROJECT  
The code has been identified in an implementation project to be generic enough to be useful also in other projects. This means that it has actually been used in production somewhere, but it comes "as is", with no support attached. The idea is to promote code reuse and to provide a convenient starting point for customization if needed.

- PRODUCT  
The code is provided with full product support, just as the core Polopoly product itself.
If you modify the code (outside of configuraton files), the support is voided.


## License
Atex Polopoly Source Code License
Version 1.0 February 2012

See file **LICENSE** for details
