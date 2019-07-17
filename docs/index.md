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

<div class="container">
    <iframe
        src='https://view.officeapps.live.com/op/view.aspx?src={{ site.github.repository_url | url_encode }}%2Fraw%2Fmaster%2FDocumentation%2FSSW.PointBank.pptx' 
        frameborder='0'></iframe>
</div>
