---
layout: default
---

<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    },
    svg: { fontCache: 'global' }
  };
</script>
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js" async></script>


# Spring 2026

This seminar meets on Wednesdays 2:00-3:00 PM in Blocker 302.

The organizers are  [Simone Cecchini](https://simonececchini.org/), [Runije Hu](https://sites.google.com/view/runjiehu/home), [Qiaochu Ma](https://sites.google.com/view/qiaochu-ma), [Jesus Sanchez Jr](https://sites.google.com/view/jstheory/home),  [Zhizhang Xie](https://people.tamu.edu/~xie/) and [Guoliang Yu](https://artsci.tamu.edu/mathematics/contact/profiles/guoliang-yu.html).


| Date         | Speaker | Affiliation| Title | Abstract |
|--------------|---------|------------|-------|-------|
| January 14, 2026   |  [Jintao Deng](https://sites.google.com/view/jintaodengspersonalpage/home)  | - | The Coarse Baum–Connes Conjecture and Group Extensions | <span class="abstract-link" onclick="showAbstract('Jintao-Deng')">View Abstract</span>  |
| January 14, 2026   |  [Liyuan Chen](https://scholar.google.com/citations?user=s1p6dPsAAAAJ&hl=en) | Harvard University | Toward useful quantum computation: from near term to fault tolerance | <span class="abstract-link" onclick="showAbstract('Liyuan-Chen')">View Abstract</span>  |
| January 21, 2026   |  |  |   |  |
| January 28, 2026 |  |  |   |    |
| January 30, 2026 | [Luca Di Cerbo](https://people.clas.ufl.edu/ldicerbo/) |  TBD | TBD  |  TBD  |
| February 04, 2026|   |  |    |    |
| February 11, 2026|  |  |  |    |
| February 18, 2026   |      |   |      |       |
| February 25, 2026 |      |   |      |       |
| March 04, 2026  |    |  |     |    |
| March 11, 2026  |     |  |    |    |
| March 18, 2026  |    |  |    |      |
| March 25, 2026|   |  |       |      |
| April 01, 2026|     |   |      |      |
| April 08, 2026 |      |   |       |       |
| April 15, 2026  |      |   |       |       |
| April 22, 2026  |      |   |       |       |
| April 29, 2026  |      |   |       |       |
| May 06, 2026  |      |   |       |       |

# Past Seminars

- [Fall 2025](2025_fall.md)


# Related Links

- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/noncommutative-geometry/index.html) (not working as of Aug 21, 2025)
- [Departmental website of the geometry and topology group](https://artsci.tamu.edu/mathematics/research/geometry-and-topology/) (very out of date of Aug 21, 2025)






<!-- Abstract content -->

<div id="Jintao-Deng" style="display:none;">
The coarse Baum–Connes conjecture is a central problem in noncommutative geometry, capturing deep connections between operator algebras and the large-scale geometry of metric spaces. While the conjecture is inherently coarse-geometric in nature, understanding its behavior under group extensions presents significant challenges, as extensions often obscure large-scale geometric properties. In this talk, I will discuss recent progress on the coarse Baum–Connes conjecture for groups arising from extensions, highlighting the techniques used to analyze their coarse geometry.
</div>

<div id="Liyuan-Chen" style="display:none;">
Two central goals in quantum science are (i) near-term simulation of many-body physics and (ii) scalable, fault-tolerant quantum computation in the long term. I will present two recent advances toward both aims. For (i), we present theoretical and experimental studies of globally controlled analog simulators, positioning them as principled platforms for quantum simulation. For (ii), we develop a non-Abelian topological framework in two dimensions that provides a route to fault-tolerant universality and remains compatible with current devices. Together, these results outline a practical trajectory from near-term simulation to scalable quantum computation.
</div>


<!-- Code that makes the pop-up windows -->

<style>
/* Modal background */
#abstract-modal-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.5);
  display: none;
  z-index: 1000;
}

/* Modal box */
#abstract-modal {
  background: white;
  width: 80%;
  max-width: 700px;
  margin: 5% auto;
  padding: 20px;
  border-radius: 8px;
  position: relative;
  overflow-y: auto;
  max-height: 90vh;
  font-family: Arial, sans-serif;
}

/* Close button */
#abstract-modal-close {
  position: absolute;
  top: 10px;
  right: 15px;
  font-size: 20px;
  cursor: pointer;
}
</style>

<!-- Modal structure -->
<div id="abstract-modal-overlay" onclick="closeAbstractModal(event)">
  <div id="abstract-modal" onclick="event.stopPropagation()">
    <span id="abstract-modal-close" onclick="closeAbstractModal()">&times;</span>
    <h2>Abstract</h2>
    <div id="abstract-modal-content"></div>
  </div>
</div>

<script>
function showAbstract(id) {
  const content = document.getElementById(id).innerHTML;
  document.getElementById('abstract-modal-content').innerHTML = content;
  document.getElementById('abstract-modal-overlay').style.display = 'block';
}

function closeAbstractModal(event) {
  if (!event || event.target.id === 'abstract-modal-overlay' || event.target.id === 'abstract-modal-close') {
    document.getElementById('abstract-modal-overlay').style.display = 'none';
  }
}
</script>
