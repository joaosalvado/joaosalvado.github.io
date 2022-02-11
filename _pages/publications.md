---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




* [Contingency Planning for Automated Vehicles]( https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7759442 "Download pdf").               
    **João Salvado**, Luís M. M. Custódio, Daniel Hess      
    <i>AAAI Conference on Artificial Intelligence (**AAAI**)IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i>, 2016.     
    A [pdf versinm](https://aaai.org/ocs/index.php/SOCS/SOCS19/paper/view/18379 "Download pdf")     
      [<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-LiAAAI19a');">bibtex</a>]
<div id="bibtex-salvado2016contingency" style="display:none">
<pre>@inproceedings{salvado2016contingency,
  title={Contingency planning for automated vehicles},
  author={Salvado, Joao and Cust{\'o}dio, Lu{\'\i}s MM and Hess, Daniel},
  booktitle={2016 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={2853--2858},
  year={2016},
  organization={IEEE}
}
</pre></div>


<!--  * [Symmetry-Breaking Constraints for Grid-Based Multi-Agent Path Finding](https://aaai.org/ojs/index.php/AAAI/article/view/4565 "Download pdf").               
    **Jiaoyang Li**, Daniel Harabor, Peter J. Stuckey, Hang Ma and Sven Koenig.    
    <i>AAAI Conference on Artificial Intelligence (**AAAI**)</i>, pages 6087-6095, 2019.     
    A [short version](https://aaai.org/ocs/index.php/SOCS/SOCS19/paper/view/18379 "Download pdf") appeared at <i>Symposium on Combinatorial Search (**SoCS**)</i>, pages 184-185, 2019.     
    [[poster](https://jiaoyang-li.github.io/files/posters/rectangle-poster.pdf "Download poster")] [[slides](https://jiaoyang-li.github.io/files/slides/rectangle-slides.pdf "Download slides")] [[code](https://github.com/Jiaoyang-Li/CBSH2 "Source code")]   [<a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-LiAAAI19a');">bibtex</a>]
<div id="bibtex-LiAAAI19a" style="display:none">
<pre>@inproceedings{LiAAAI19a,
  author    = {Jiaoyang Li and Daniel Harabor and Peter J. Stuckey and Hang Ma and Sven Koenig},
  title     = {Symmetry-Breaking Constraints for Grid-Based Multi-Agent Path Finding},
  booktitle = {Proceedings of the 33rd {AAAI} Conference on Artificial Intelligence (AAAI)},
  pages     = {6087--6095},
  year      = {2019}
}
</pre></div>-->
