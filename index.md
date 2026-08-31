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


# Fall 2026

This seminar usually meets on Wednesdays 2:00-3:00 PM in Blocker 302.

The organizers are  [Simone Cecchini](https://simonececchini.org/), [Runije Hu](https://sites.google.com/view/runjiehu/home), [Qiaochu Ma](https://sites.google.com/view/qiaochu-ma), [Zhizhang Xie](https://people.tamu.edu/~xie/) and [Guoliang Yu](https://artsci.tamu.edu/mathematics/contact/profiles/guoliang-yu.html).


[current seminar schedule](https://sites.google.com/view/ncgseminartamu/home).



# Past Seminars

- [Fall 2025](2025_fall.md)
- [Spring 2026](2026_spring.md)


# Related Links

- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/noncommutative-geometry/index.html) (not working as of Aug 21, 2025)
- [Departmental website of the geometry and topology group](https://artsci.tamu.edu/mathematics/research/geometry-and-topology/) (very out of date of Aug 21, 2025)






<!-- Abstract content -->

<div id="Runjie-Hu" style="display:none;">


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
