---
layout: default
---

<img src="https://camfort.github.io/tvcs2017/kent-logo.jpg" style="height:100px;float:right:" />

Complex models in modern science and are now routinely expressed as software. The PLAS4Sci lab (Programming Languages and Systems
for Science) at the [School of Computing](https://www.cs.kent.ac.uk/), [University of Kent](https://www.kent.ac.uk/) is a sub-group
of the [PLAS group](https://research.kent.ac.uk/programming-languages-systems/) focussed on improving the state-of-the-art in programming languages, programming systems, and programming tools to support the daily work of scientists.

## People

* [Dominic Orchard](https://dorchard.github.io/) - Lab lead
* [Benjamin Orchard](https://github.com/raehik) - Research Assistant and Research Software Engineer
* [Laura Bocchi](https://www.kent.ac.uk/computing/people/3119/bocchi-laura) - Reader in Programming Languages
* [Vilem-Benjamin Liepelt](https://github.com/buggymcbugfix/not-not-a-blog#blog) - PhD student

## Partners

<a href="https://iccs.cam.ac.uk/">
<img src="https://plas4sci.github.io/assets/images/iccs-logo.jpg" style='width:350px;' />
</a>
&nbsp;
&nbsp;
&nbsp;
<img src="https://upload.wikimedia.org/wikipedia/commons/5/56/Bloomberg_logo.svg" style='width:150px;' />

## Projects

* [CamFort](https://camfort.github.io), a tool for verification and static analysis of Fortran, with a particular focus on verification techniques for numerical computation. Includes the [fortran-src](https://github.com/camfort/fortran-src) static-analysis framework for Fortran, written in Haskell.

## News

<ul>
  {% for post in site.posts %}
    <li>
	    {{ post.date | date: "%-d %B %Y" }} - <i><a href="{{ post.url }}">{{ post.title }}</a></i>
    </li>
  {% endfor %}
</ul>

## Publications

<table id="pubs">
<tr>
    <th><a
      href="https://cambridge-iccs.github.io/climate-informatics-2023/assets/pdfs/Reducing_the_overhead_of_coupled_ML_models.pdf">pdf</a>,
      <a href="https://dorchard.github.io/assets/bibtex/2023-coupling.txt">bib</a>
    </th>
      <td><b>Reducing the overhead of coupled ML models between Python and Fortran: an application to Gravity Wave Parameterizations</b>,
  Jack Atkinson, Simon Clifford, David Connelly, Chris Edsall, Athena Elafrou, Ed Gerber, Laura Mansfield, Dominic Orchard, Aditi Sheshadri, Y. Qiang Sun, Minah Yang
	<i>Extended abstract at
	(<a href="https://cambridge-iccs.github.io/climate-informatics-2023/">Climate Informatics 2023</a>)</i>
      </td>
      </tr>
<tr>
    <th><a
      href="https://meetingorganizer.copernicus.org/EGU23/EGU23-11187.html?pdf">pdf</a>,
      <a href="https://dorchard.github.io/assets/bibtex/2023-oneflux.txt">bib</a>
    </th>
      <td><b>Fostering collaboration through improved software development practices for the ONEFlux eddy covariance data processing pipeline</b>,
  Gilberto Pastorello, Carlo Trotta, Alessio Ribeca, Keith Beattie, Sy-Toan Ngo, Housen Chu, You-Wei Cheah, Danielle Christianson, Giacomo Nicolini, Sigrid Dengel, Diego Polidori, Peter Isaac, Matthew Archer, Dominic Orchard, Deb Agarwal, Sebastien Biraud, Margaret Torn, Dario Papale.
	<i>Presentation at
	(<a href="https://egu23.eu/">EGU 2023</a>)</i>
      </td>
      </tr>
  <tr>
    <th><a
      href="https://arxiv.org/abs/2011.06094">pdf</a>,
      <a href="https://dblp.org/rec/journals/corr/abs-2011-06094.html?view=bibtex">bib</a>
    </th>
      <td><b>Guiding user annotations for units-of-measure verification</b>,
  Dominic Orchard, Mistral Contrastin, Matthew Danish, Andrew Rice,
	<i>Workshop on Human Aspects of Types and Reasoning Assistants
	(<a href="https://2020.splashcon.org/home/hatra-2020?plenary=Hide%20plenary%20sessions">HATRA 2020</a>)</i>
      </td>
      </tr>
  <tr>
    <th><a
      href="https://www.cl.cam.ac.uk/~mrd45/se4science19.pdf">pdf</a>,
      <a href="assets/bib/DanishABRO19.bib">bib</a>
    </th>
      <td><b> Learning units-of-measure from scientific code</b>,
  Matthew Danish, Miltiadis Allamanis, Marc Brockschmidt, Andrew Rice,
	 Dominic Orchard,
	<i>Software Engineering for Science, 2019</i>
      </td>
      </tr>

    <tr>
    <th><a href="https://www.sciencedirect.com/science/article/pii/S0304397517301263">pdf</a>, <a href="assets/bib/Bocchi2017.bib">bib</a>
    </th>
    <td><b>Monitoring networks through multiparty session types</b>, Laura Bocchi, Tzu-Chun Chen, Romain Demangeon, Kohei Honda, Nobuko Yoshida, Theoretical Computer Science 669 (2017): 33-58
    </td>
  </tr>

    <tr>
      <th><a href="http://dorchard.co.uk/publ/reprinter2017.pdf">pdf</a></th>
      <td><b>Scrap Your Reprinter: A Datatype Generic Algorithm for
	Layout-Preserving Refactoring</b>,
	Harry Clarke, Dominic Orchard, IFL 2017</td>
    </tr>

    <tr>
      <th><a href="https://kar.kent.ac.uk/60506/1/art%253A10.1007%252Fs00165-017-0420-8.pdf">pdf</a>, <a href="assets/bib/Neykova2017.bib">bib</a>
    </th>
      <td><b>Timed runtime monitoring for multiparty conversations</b>,
	Rumyana Neykova, Laura Bocchi, Nobuko Yoshida, Formal Aspects Comput. 29(5): 877-910 (2017)</td>
    </tr>

    <tr>
      <th><a
	href="https://www.repository.cam.ac.uk/bitstream/handle/1810/267779/oopsla-proof.pdf?sequence=5">pdf</a>,
	<a href="assets/bib/OrchardCDR17.bib">bib</a></th>
      <td><b>Verifying Spatial Properties of Array Computations</b>,
	Dominic Orchard, Mistral Contrastin, Matthew Danish, Andrew
	Rice, OOPSLA 2017</td>
    </tr>
    <tr>
    <th><a
      href="http://ceur-ws.org/Vol-1686/WSSSPE4_paper_23.pdf">pdf</a>,
       <a href="assets/bib/ContrastinDOR16.bib">bib</a></th>
    <td><b>Supporting software sustainability with lightweight
  specifications</b>, Mistral Contrastin, Matthew Danish, Dominic
  Orchard, Andrew Rice, WSSSPE4 (2016)
    </td>
  </tr>

  <tr>
    <th><a href="http://www.cl.cam.ac.uk/~acr31/pubs/contrastin-units.pdf">pdf</a>, <a href="assets/bib/ContrastinRDO16.bib">bib</a></th>
    <td><b>Units-of-Measure Correctness in Fortran
      Programs</b>, Mistral Contrastin, Andrew C. Rice, Matthew Danish, Dominic
      Orchard, Computing in Science and Engineering 18(1): 102-107 (2016)
    </td>
  </tr>

  <tr>
    <th><a
      href="https://www.cs.kent.ac.uk/people/staff/dao7/publ/iccs15-fortran-units.pdf">pdf</a>, <a href="assets/bib/OrchardRO15.bib">bib</a></th>
    <td><b>Evolving Fortran types with inferred units-of-measure</b>,
      Dominic Orchard, Andrew C. Rice, Oleg Oshmyan, J. Comput. Science 9:
      156-162 (2015)
    </td>
  </tr>

  <tr>
    <th><a
    href="https://www.cs.kent.ac.uk/people/staff/dao7/publ/iccs14-orchard-rice.pdf">pdf</a>, <a href="assets/bib/OrchardR14.bib">bib</a>
    </th>
    <td><b>A Computational Science Agenda for Programming Language
      Research</b>, Dominic Orchard, Andrew C. Rice, ICCS 2014: 713-727
    </td>
  </tr>


  <tr>
    <th><a
      href="https://www.cs.kent.ac.uk/people/staff/dao7/publ/wrt13-orchard-rice.pdf">pdf</a>, <a href="assets/bib/OrchardR13.bib">bib</a>
    </th>
    <td><b>Upgrading Fortran source code
      using automatic refactoring</b>,
      Dominic Orchard, Andrew C. Rice, WRT@SPLASH 2013: 29-32
    </td>
  </tr>
</table>
