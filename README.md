# HKUST PhD / MPhil Thesis Latex Template

<p align="center">
  ⭐️ If you like this repository, give it a star on GitHub! ⭐️
  <br>
  <a href="https://twitter.com/MUsmanMBhutta"><img src="https://img.shields.io/twitter/follow/MUsmanMBhutta.svg?style=social" alt="Twitter Follow" /></a>
  <a href="#license"><img src="https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000"></a>
</p>

Author: [Muhammad Usman Maqbool Bhutta](https://usmanmaqbool.github.io/)

Whole Ph.D. thesis structure is similar. Moreover, I've added all details with some templates related to inserting **signature**, **equations**, **tables**, **images**, **algorithms** in the tex files.

## Download and Run

Just clone / download using the zip file the [github repository](https://github.com/UsmanMaqbool/hkust-phd-thesis) . Make sure, you are `miktex` / `latex-live` pre-installed in your PC. For the editor, `Tex-Studio` or `VS-Code` is recommended.

If you are using Tex-Studio, use multiple times <kbd>F1</kbd>, and <kbd>F8</kbd> for the bibliography of the each chapter. You might need to compile aux files as well. See [Compilation Error](#compilation-error) below.

## Signature Page
You can add your digital signature. Just update the `includes/sig.png` file.
## Block Diagram
For creating the block diagram, I highly recommend **[Mathcha.io](https://www.mathcha.io/editor)**, it is a tool which convert your graphics to Latex.
## Graphs
For adding the graphs. I highly recommend using Tikz. You can find example in Section II of `Chapter.5.tex`.
## References

We used single bib file `Thesis.bib` which has all the references. Each chapter will have its own reference section.

### Compilation Error

If the references are not generated successfully, or you are facing problem with a particular chapter. 

**For example:** If chapter 2 references are not updating after the compilation. To fix this, you have to open the `chapter2.aux` in the tex studio, and press <kbd>F8</kbd>, so that the references could be updated. Afterwards you will be able to compile them easily.



## Thanks

M. Usman Maqbool Bhutta