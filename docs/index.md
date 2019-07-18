<style>
    .container {
        position: relative;
        width: calc(100vw - 350px);
        height: 50vh;
        padding-bottom: 56.25%;
    }
    .container > iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>

# This is a nice view of all the images in GitHub

<div class="container">
    <iframe
        src='https://view.officeapps.live.com/op/view.aspx?src={{ site.github.repository_url | url_encode }}%2FSSW.PointBank.pptx' 
        frameborder='0'></iframe>
</div>


  TODO: add link to file in repo