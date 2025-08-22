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


# Fall 2025

This seminar meets on Wednesdays 2:00-3:00 PM in Blocker 302.

The organizers are  [Simone Cecchini](https://simonececchini.org/), [Runije Hu](https://sites.google.com/view/runjiehu/home), [Qiaochu Ma](https://sites.google.com/view/qiaochu-ma), [Zhizhang Xie](https://people.tamu.edu/~xie/) and [Guoliang Yu](https://artsci.tamu.edu/mathematics/contact/profiles/guoliang-yu.html).


| Date         | Speaker | Affiliation| Title | Abstract |
|--------------|---------|------------|-------|-------|
| August 27, 2025   |  [Qiaochu Ma](https://sites.google.com/view/qiaochu-ma)  | Texas A&M  | Small Scale Index Theory, Scalar Curvature, and Gromov’s Simplicial Norm | <span class="abstract-link" onclick="showAbstract('Qiaochu-Ma')">View Abstract</span>  |
| September 3, 2025   | Ryo Toyota     | Texas A&M  | TBD     | TBD  |
| September 10, 2025 | [Simone Cecchini](https://simonececchini.org/) | Texas A&M  | TBD     | TBD      |
| September 17, 2025|      |   |      |       |
| September 24, 2025| |  |   |      |
| October 1, 2025   |      |   |      |       |
| October 8, 2025  |      |   |      |       |
| October 15, 2025  |      |   |      |       |
| October 22, 2025  |      |   |      |       |
| October 29, 2025  |      |   |      |       |
| November 5, 2025  | [Thomas Tony](https://ttony.eu)     | University of Muenster  | TBD      |  TBD     |
| November 12, 2025 |      |   |       |       |
| November 19, 2025 |      |   |       |       |
| November 26, 2025 |      |   |       |       |
| December 3, 2025  |      |   |       |       |


# Related Links

- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/noncommutative-geometry/index.html) (not working as of Aug 21, 2025)
- [Departmental website of the geometry and topology group](https://artsci.tamu.edu/mathematics/research/geometry-and-topology/) (very out of date of Aug 21, 2025)













<!-- Abstract content -->

<div id="Qiaochu-Ma" style="display:none;">
Scalar curvature encodes the volume information of small geodesic balls within a Riemannian manifold, making it, to some extent, the weakest curvature invariant. This raises a natural question: what topological constraints does scalar curvature impose on manifolds? In this talk, we shall show that for a manifold with a scalar curvature lower bound, the simplicial norm of certain characteristic classes can be controlled by its volume and isoperimetric constant. This is joint work with Guoliang Yu.
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
