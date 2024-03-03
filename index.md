<iframe width="800" height="470" src="https://www.youtube.com/embed/_xoNNTyFxpk?si=pLBbGQXjsRpuY6AA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

![group photo in front of tree](images/group1.jpeg)

Workshop outcomes
1. 27 interviews, 10 guest speakers, and 2 field trips
1. A problem bank with 150 challenges related to bottlenecks in five “buckets” 
1. 80 of those challenges were developed into a brief description of the problem
1. A letter to the MJC president
1. A presentation and slide set about what we did and learned
1. A documentary video

The workshop grew out of MJC’s engagement in the Stanislaus2030 initiative which identified strategies for strengthening our regional economy including growing local bioindustrial manufacturing activities. MJC is now a collaborator in the BioEconomy, Agriculture, and Manufacturing (BEAM) Initiative catalyzed by this planning effort and is working with others across the region to advance innovations that transform biomass into valuable and sustainable products.

## Powerpoint Slideshow
<script type="text/javascript" src="https://raw.github.com/mozilla/pdf.js/gh-pages/build/pdf.js"></script>
<script type="text/javascript">
function renderPDF(url, canvasContainer, options) {
    var options = options || { scale: 1 };

    function renderPage(page) {
        var viewport = page.getViewport(options.scale);
        var canvas = document.createElement('canvas');
        var ctx = canvas.getContext('2d');
        var renderContext = {
          canvasContext: ctx,
          viewport: viewport
        };

        canvas.height = viewport.height;
        canvas.width = viewport.width;
        canvasContainer.appendChild(canvas);

        page.render(renderContext);
    }

    function renderPages(pdfDoc) {
        for(var num = 1; num <= pdfDoc.numPages; num++)
            pdfDoc.getPage(num).then(renderPage);
    }
    PDFJS.disableWorker = true;
    PDFJS.getDocument(url).then(renderPages);
}   
</script> 

<div id="holder"></div>

<script type="text/javascript">
renderPDF('pdfs/slideshow.pdf', document.getElementById('holder'));
</script>  

# For more information, contact:
Debbie Gilbert
gilbertd@yosemite.edu