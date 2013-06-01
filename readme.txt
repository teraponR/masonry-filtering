=======
How to use
=======
$('.projects').filteredMasonry({
       itemSelector: '.project-item',
       gutterWidth:  5,
       filtersGroupSelector:'.filters'
});

=====
What does the HTML look like
=====
<section class="filters">
    <a class="icon-th" data-filter="*">all</a>
    <a class="icon-th-list" data-filter=".opensource">open source</a>
</section>
<section class="projects">
  <div class="project-item opensource">
    <div>blah,blah</div>
  </div>
  <div class="project-item">
      <div>blah,blah</div>
 </div>
 <div class="project-item">
       <div>blah,blah</div>
 </div>
</section>