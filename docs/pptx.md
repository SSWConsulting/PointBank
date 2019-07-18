{% include alert.html text="Add your feedback to the PPT specs through GitHub issues (on the left)" %}

<div class="row">
    <div class="col">
        <iframe style="height:50vh;width:100%;"
            src='https://view.officeapps.live.com/op/view.aspx?src={{ site.github.repository_url | url_encode }}{{ site.github_raw_root | url_encode }}%2Fassets%2FSSW.PointBank.pptx' 
            frameborder='0'></iframe>
        <p>
            This is a nice view of the <a href="{{ site.github.repository_url }}{{ site.github_source_root | attr_encode }}/assets/SSW.PointBank.pptx">PPTX in GitHub</a>
        </p>
    </div>
</div>
