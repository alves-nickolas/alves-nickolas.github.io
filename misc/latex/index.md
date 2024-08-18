# LaTeX Templates

Writing LaTeX is one of my hobbies. I don't like sharing all of my templates, because I grow quite attached to some of them. Nevertheless, some might make it to here. Notice the titles of the projects are hyperlinks to somewhere where the code is available. 

## [Tengwar Thesis Template](https://github.com/alves-nickolas/Tengwar-Thesis-Template-)

This is a simplified version of the template I used to write my [MSc thesis](https://arxiv.org/abs/2305.17453). It is partially inspired by (and a bit of the structure and the older code were adapted from) Martin Helsø's [UiO Mathematics Master's Thesis template](https://www.overleaf.com/latex/templates/uio-mathematics-masters-thesis/dhbqpjyhjmgd). The name "Tengwar Thesis" is simply because I find Garamond somewhat similar to Tolkien's tengwar alphabet, and decided to go for the joke.

The template is configured mainly for Brazilian students who want to write their thesis in English, and hence expects some input in Portuguese and some in English. This version, however, also gives the user the option to turn off the Portuguese text and keep a thesis entirely in English (as long as you don't fill in the Portuguese code).

Quite notably, this version differs from my thesis by the choice of "Garamond flavor", so to speak. My thesis used Duffner's [EB Garamond](http://www.georgduffner.at/ebgaramond/), while this version is a bit simpler and uses the package [ebgaramond](https://ctan.org/pkg/ebgaramond) (although the actual code is currently configured to be compiled with LuaTeX). If you liked the long stylish Q, you'll need to download Duffner's EB Garamond from his website and use it directly with LuaTeX. [This TeX.SE post gives an example of how to do it](https://tex.stackexchange.com/q/114223/144146).

This template is also available in [Overleaf](https://www.overleaf.com/latex/templates/tengwar-thesis-template/xpkdstnvfsgg).

## [Research Journal](https://github.com/alves-nickolas/Research-Journal-Template)

For a while now I have kept a research journal to keep track of my progress in my MSc, which papers and books I checked, and so on. The idea is mainly to have a document with simple entries that can later help me when writing reports or when trying to remember a reference I checked months ago. Recently I've decided to update my template and make it available online. This is it.

This template is also available in [Overleaf](https://www.overleaf.com/latex/templates/research-journal-template/hkbkxvmtzhzq).

## [Mood Tracker](https://github.com/alves-nickolas/Mood-Tracker-Template)

This is a simple model for a mood tracker calendar in LaTeX, originally created as an addition to my [Research Journal](https://github.com/alves-nickolas/Research-Journal-Template) template. It implements the calendar by using [pgfcalendar](https://www.ctan.org/pkg/pgf) and defines new commands to allow for a simple user interface. Colors, legend, and date range are customizable.

I thank [Betânia C. T. Backes](https://github.com/b-backes) for the suggestion of allowing more than one mood on the same day. Hopefully, future versions of this template will allow for more than two.

This template is also available in [Overleaf](https://www.overleaf.com/latex/templates/mood-tracker-template/pqsvxnstssmh).
