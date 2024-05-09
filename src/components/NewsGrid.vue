<template>
    <div class="container news-grid">
        <div class="row">

            <div class="col-sm">
                <div class="card mb-3" bis_skin_checked="1">
                    <h3 class="card-header">Card header</h3>
                    <svg xmlns="http://www.w3.org/2000/svg" class="d-block user-select-none" width="100%" height="200" aria-label="Placeholder: Image cap" focusable="false" role="img" preserveAspectRatio="xMidYMid slice" viewBox="0 0 318 180" style="font-size:1.125rem;text-anchor:middle">
                        <rect width="100%" height="100%" fill="#868e96"></rect>
                        <text x="50%" y="50%" fill="#dee2e6" dy=".3em">Image cap</text>
                    </svg>
                    <div class="card-body" bis_skin_checked="1">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                    <div class="card-footer text-muted" bis_skin_checked="1">
                        2 days ago
                    </div>
                </div>
            </div>

            <div class="col-sm">
                <div class="card mb-3" bis_skin_checked="1">
                    <h3 class="card-header">Card header</h3>
                    <svg xmlns="http://www.w3.org/2000/svg" class="d-block user-select-none" width="100%" height="200" aria-label="Placeholder: Image cap" focusable="false" role="img" preserveAspectRatio="xMidYMid slice" viewBox="0 0 318 180" style="font-size:1.125rem;text-anchor:middle">
                        <rect width="100%" height="100%" fill="#868e96"></rect>
                        <text x="50%" y="50%" fill="#dee2e6" dy=".3em">Image cap</text>
                    </svg>
                    <div class="card-body" bis_skin_checked="1">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                    <div class="card-footer text-muted" bis_skin_checked="1">
                        2 days ago
                    </div>
                </div>
            </div>

            <div class="col-sm">
                <div class="card mb-3" bis_skin_checked="1">
                    <h3 class="card-header">Card header</h3>
                    <svg xmlns="http://www.w3.org/2000/svg" class="d-block user-select-none" width="100%" height="200" aria-label="Placeholder: Image cap" focusable="false" role="img" preserveAspectRatio="xMidYMid slice" viewBox="0 0 318 180" style="font-size:1.125rem;text-anchor:middle">
                        <rect width="100%" height="100%" fill="#868e96"></rect>
                        <text x="50%" y="50%" fill="#dee2e6" dy=".3em">Image cap</text>
                    </svg>
                    <div class="card-body" bis_skin_checked="1">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                    <div class="card-footer text-muted" bis_skin_checked="1">
                        2 days ago
                    </div>
                </div>
            </div>

            <div class="col-sm">
                <div class="card mb-3" bis_skin_checked="1">
                    <h3 class="card-header">Card header</h3>
                    <svg xmlns="http://www.w3.org/2000/svg" class="d-block user-select-none" width="100%" height="200" aria-label="Placeholder: Image cap" focusable="false" role="img" preserveAspectRatio="xMidYMid slice" viewBox="0 0 318 180" style="font-size:1.125rem;text-anchor:middle">
                        <rect width="100%" height="100%" fill="#868e96"></rect>
                        <text x="50%" y="50%" fill="#dee2e6" dy=".3em">Image cap</text>
                    </svg>
                    <div class="card-body" bis_skin_checked="1">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                    <div class="card-footer text-muted" bis_skin_checked="1">
                        2 days ago
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>

    var requestOptions = {
        method: 'GET',
    };

    fetch("https://elonmu.sh/api", requestOptions)
    .then(response => response.text())
    .then(result => console.log(result))
    .catch(error => console.log('error', error));

    export default {
        name: 'NewsGrid'
    }

</script>

<style>
    .news-grid{
        margin-top:25px;
        margin-top:25px;
    }
</style>