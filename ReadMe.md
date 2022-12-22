
# My CV

## Compilation

With TinyTex, like [here](https://github.com/tfiers/phd-thesis)\
but with XeLaTeX (for Unicode & modern fonts)
```
latexmk -pdf -xelatex -pvc resume.tex
```
(`pvc` = preview, continuously build)

..and with these packages additionally installed
```
tlmgr.bat install --with-doc moresize anyfontsize svn-prov import blindtext
```




## Attribution

This is an edited version of [this] Overleaf template.

[this]: https://www.overleaf.com/latex/templates/resume-cv/fbwkrgfrcsby.

The following is an edited copy of the attributions in that template:
```
%====================
% Original author:        https://github.com/TimmyChan 
%                         https://www.linkedin.com/in/timmy-l-chan/
% Last Updated: Nov 19, 2021
% Notes:        All formatting is done in TLCresume.sty
%               No need to touch that file. 
%               All actual content is in the sections/ folder.
%====================

%====================
% Modifying author1:       https://github.com/gobborg 
% Last Updated: Dec 26, 2021
% Notes:        I just made it prettier and better suited to
%               my needs.
%====================

%====================
% Modifying author2:        https://github.com/mengisok 
% Last Updated: Oct 29, 2022
% Notes:        I edited again on the version of @gobborg      
%====================
```
