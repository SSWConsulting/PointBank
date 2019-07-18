{% include alert.html text="Add your feedback to the video through GitHub issues (on the left)" %}

<div class="container">
    <div class="row">
        <div class="col">
            <div class="embed-responsive embed-responsive-16by9">
                <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/mZQHj91sHiQ" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
    </div>    
    <div class="row">
        <div class="col">
            <p>
                {{ site.description | default: site.github.project_tagline }}
            </p>
        </div>
    </div>    
</div>