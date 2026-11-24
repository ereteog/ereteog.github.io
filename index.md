---
layout: default
---

<div class="home">

<p>
I am a Technical Leader at Cisco, where I lead the backend design of the threat intelligence, incident and detection-coverage services of Cisco XDR. I have a special interest in search infrastructure, machine learning, agentic AI and functional programming.
</p>

<p>
My path goes through research, large companies and startups, with one common thread: knowledge management for risk, turning heterogeneous data into knowledge that helps assess and act on risk. I started with a Ph.D. at Orange Labs, with INRIA and Telecom ParisTech, on <a href="https://tel.archives-ouvertes.fr/tel-00586677/">semantic social network analysis</a> (<a href="#publications">publications</a>), then built a Semantic Web knowledge base for the Orange search engine. I then applied this to medical risk at Mnemotix, linking medical data sources for epidemiology; reputation risk at Vigiglobe, with real-time social media analytics; geographical risk at KCityLabs (Kinaxia Group), with machine learning on the urban environment; and now cybersecurity risk at Cisco. The details are in my <a href="{{ "/cv_guillaume_ereteo.pdf" | prepend: site.baseurl }}">CV</a>.
</p>

<p class="contact">
Reach me on <a href="https://www.linkedin.com/in/{{ site.linkedin_userid }}/">LinkedIn</a> · code on <a href="https://github.com/{{ site.github_username }}">GitHub</a>
</p>

<h2>Cisco, since 2019</h2>
<p>
I joined Cisco in January 2019 as a Senior Clojure Developer and became Technical Leader in 2021, working on the backend of Cisco Threat Response, then SecureX, now XDR.
</p>
<ul>
  <li>Designed and built the MITRE ATT&amp;CK Coverage Map, which shows how a customer's security stack covers adversary techniques.</li>
  <li>Built the metrics backend of the XDR Control Center dashboard, including the MTTx metrics (mean time to engage, contain and resolve).</li>
  <li>Designed and built an MCP server exposing XDR tools that let AI agents conduct incident analysis and prioritization.</li>
  <li>Led the search infrastructure from Elasticsearch 5 to 7 to OpenSearch 2.x/3.x, at up to 20 billion documents.</li>
  <li>Laid the foundations of risk-based incident scoring and built ML pipelines for incident prioritization with the data science team.</li>
</ul>

<h2>Open source</h2>
<ul>
  <li><a href="https://github.com/threatgrid/ctia">CTIA</a>, the Cisco Threat Intelligence API: core developer.</li>
  <li><a href="https://github.com/threatgrid/ctim">CTIM</a>, the Cisco Threat Intelligence Model for public and private threat intelligence and the incidents tied to it: co-author.</li>
  <li><a href="https://github.com/threatgrid/ductile">Ductile</a>, a Clojure Elasticsearch/OpenSearch client: author and maintainer.</li>
</ul>

<h2 id="publications">Selected publications</h2>
<ul class="pubs">
  <li><a href="https://tel.archives-ouvertes.fr/tel-00586677">Semantic Social Network Analysis</a><br>G Erétéo<br><em>Ph.D. thesis, Telecom ParisTech, 2011</em></li>
  <li><a href="https://hal.inria.fr/hal-01170978">SemTagP: semantic community detection in folksonomies</a><br>G Erétéo, F Gandon, M Buffa<br><em>IEEE/WIC/ACM Web Intelligence, Lyon, 2011</em></li>
  <li><a href="https://hal.archives-ouvertes.fr/hal-00562056">Semantic Social Network Analysis, a concrete case</a><br>G Erétéo, F Limpens, F Gandon, O Corby, M Buffa, M Leitzelman, P Sander<br><em>Handbook of Research on Methods and Techniques for Studying Virtual Communities, IGI Global, 2011</em></li>
  <li><a href="https://hal.archives-ouvertes.fr/hal-00562035">Analysis of a real online social network using Semantic Web frameworks</a><br>G Erétéo, M Buffa, F Gandon, O Corby<br><em>8th International Semantic Web Conference (ISWC'09), Washington DC, 2009</em></li>
  <li><a href="https://hal.archives-ouvertes.fr/hal-01154473">SweetWiki: A semantic wiki</a><br>M Buffa, F Gandon, G Erétéo, P Sander, C Faron<br><em>Journal of Web Semantics, Elsevier, 6(1), 2008</em></li>
</ul>

<h3>Acknowledged contribution</h3>
<ul class="pubs">
  <li><a href="https://doi.org/10.3390/urbansci3030100">A Machine Learning Approach to Study the Relationship between Features of the Urban Environment and Street Value</a><br>A Venerandi, G Fusco, A Tettamanzi, D Emsellem<br><em>Urban Science, 3(3), 100, 2019</em>. Implemented and tested the first version of the algorithm presented in the paper (credited in acknowledgements).</li>
</ul>

<details>
<summary>All publications</summary>

<h3>Book contributions</h3>
<ul class="pubs">
  <li><a href="http://www.pearson.fr/livre/?GCOI=27440100179400">Préface, Web de données, Méthodes et outils pour les données liées</a> (French)<br>G Erétéo<br><em>Pearson, 2012</em></li>
  <li><a href="https://hal.archives-ouvertes.fr/hal-00562056">Semantic Social Network Analysis, a concrete case</a><br>G Erétéo, F Limpens, F Gandon, O Corby, M Buffa, M Leitzelman, P Sander<br><em>Handbook of Research on Methods and Techniques for Studying Virtual Communities: Paradigms and Phenomena, IGI Global, pp. 122-156, 2011</em></li>
  <li>A wiki on the semantic web<br>M Buffa, G Erétéo, F Gandon<br><em>Emerging Technologies for Semantic Web Environments: Techniques, Methods and Applications, Fraunhofer IESE, 2007</em></li>
</ul>

<h3>Journals</h3>
<ul class="pubs">
  <li><a href="https://hal.archives-ouvertes.fr/hal-01154473">SweetWiki: A semantic wiki</a><br>M Buffa, F Gandon, G Erétéo, P Sander, C Faron<br><em>Journal of Web Semantics, Elsevier, Special issue on Semantic Web and Web 2.0, 6(1), 2008</em></li>
</ul>

<h3>International conferences and workshops</h3>
<ul class="pubs">
  <li><a href="https://hal.archives-ouvertes.fr/hal-01048737">Global Initiative for Sentinel e-Health Network on Grid (GINSENG): Medical Data Integration and Semantic Developments for Epidemiology</a><br>S Cipiere, G Erétéo, A Gaignard, N Boujelben, S Gaspard, et al.<br><em>Workshop on Clusters, Clouds and Grids for Health, IEEE/ACM CCGrid, Chicago, pp. 755-763, 2014</em></li>
  <li><a href="https://hal.inria.fr/hal-01171260">ISICIL: Semantics and Social Networks for Business Intelligence</a><br>M Buffa, N Delaforge, G Erétéo, F Gandon, A Giboin, F Limpens<br><em>SOFSEM 2013, 39th International Conference on Current Trends in Theory and Practice of Computer Science, Czech Republic, 2013</em></li>
  <li><a href="https://hal.inria.fr/hal-01170978">SemTagP: semantic community detection in folksonomies</a><br>G Erétéo, F Gandon, M Buffa<br><em>IEEE/WIC/ACM International Conferences on Web Intelligence and Intelligent Agent Technology, Lyon, 2011</em></li>
  <li><a href="https://hal.archives-ouvertes.fr/hal-00562035">Analysis of a real online social network using Semantic Web frameworks</a><br>G Erétéo, M Buffa, F Gandon, O Corby<br><em>8th International Semantic Web Conference (ISWC'09), pp. 180-195, Washington DC, 2009</em></li>
  <li><a href="https://hal.inria.fr/hal-01169909">ISICIL: Information Semantic Integration through Communities of Intelligence online</a><br>F Gandon, T Abdessalem, M Buffa, F Bugeaud, S Comos, O Corby, N Delaforge, G Erétéo, et al.<br><em>Workshop on Web Intelligence &amp; Virtual Enterprises, Pro-VE'09, Thessaloniki, 2009</em></li>
  <li><a href="http://arxiv.org/abs/0904.3701">Semantic social network analysis</a><br>G Erétéo, F Gandon, O Corby, M Buffa<br><em>First International Conference on Web Science (WebSci'09), 2009</em></li>
  <li><a href="http://ceur-ws.org/Vol-405/paper5.pdf">A state of the art on social network analysis and its applications on a semantic web</a><br>G Erétéo, M Buffa, F Gandon, P Grohan, M Leitzelman, P Sander<br><em>Social Data on the Web (SDOW'08), workshop at ISWC, 2008</em></li>
  <li><a href="https://www.w3.org/2008/09/msnws/papers/ereteo_et_al_2008_leveraging.html">Leveraging social data with semantics</a><br>G Erétéo, M Buffa, F Gandon, M Leitzelman, F Limpens<br><em>W3C Workshop on the Future of Social Networking, Barcelona, 2008</em></li>
</ul>

<h3>French conferences and reports</h3>
<ul class="pubs">
  <li>De l'utilité d'un outil de veille d'entreprise de seconde génération<br>M Leitzelman, G Erétéo, P Grohan, F Herledan, F Gandon, M Buffa<br><em>Ingénierie des Connaissances (IC'09), 2009</em></li>
  <li><a href="http://isicil.inria.fr/v1/res/docs/livrables/ISICIL-ANR-EA01-SNAetWS-0906.pdf">Analyse des réseaux sociaux et web sémantique : un état de l'art</a><br>G Erétéo, F Gandon, M Buffa, P Grohan<br><em>ANR ISICIL deliverable, 2008</em></li>
  <li>Wiki et Web Sémantique<br>M Buffa, G Erétéo, F Gandon<br><em>Ingénierie des Connaissances (IC'07), 2007</em></li>
</ul>

</details>

</div>
