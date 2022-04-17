| Ziddan Makarim | 312010063 |
|----------------|-----------|
|Pemrograman Web | Lab6Web   |

## Lab6Web
### 1). Framework Boostrap

Adalah framework css yang sudah tersedia dengan beberapa versi yang terbaru aalah versi 5. 

### 2). Membuat Layout

![layout](img/layout.png)

Ini adalah contoh hasil full layoutnya.

### 3). Contoh Coding

```html
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <title>Hello, world!</title>
</head>

<body>
    <div class="container-md shadow-lg p-3 mb-5 bg-body rounded">
        <div class="card-body">
            <h2 class="py-3 text-muted">Layout Sederhana</h2>
        </div>
        <nav class="navbar navbar-light" style="background-color: #e3f2fd;">
            <ul class="nav">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#" style="background-color: cyan;">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Artikel</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link">Kontak</a>
                </li>
            </ul>
        </nav>
        <div class="card py-3" style="border: 0;">
            <div class="card-body">
                <h2 class="card-title">Hello World</h2>
                <p class="card-text pb-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus quod ex
                    molestiae iure illum numquam odit qui mollitia, vel commodi deleniti, fuga tempora earum, officiis
                    consequatur dolorum omnis ea harum.</p>
                <a href="#" class="btn btn-primary">Learn More</a>
            </div>
        </div>
        <div class="row row-cols-4">
            <div class="col">
                <div class="card mt-4" style="width: 18rem; border: 0;">
                    <img src="https://dummyimage.com/120/db7d25/fff.png" style="width: 200px;"
                        class="card-img-top rounded-circle" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Heading</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                        <a href="#" class="btn btn-primary">view detail</a>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card mt-4" style="width: 18rem; border: 0;">
                    <img src="https://dummyimage.com/120/3e73e6/fff.png" style="width: 200px;"
                        class="card-img-top rounded-circle" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Heading</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                        <a href="#" class="btn btn-primary">view detail</a>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card mt-4" style="width: 18rem; border: 0;">
                    <img src="https://dummyimage.com/120/71e6d4/fff.png" style="width: 200px;"
                        class="card-img-top rounded-circle" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Heading</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                        <a href="#" class="btn btn-primary">view detail</a>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="list-group mt-4">
                    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
                        Widget Header
                    </a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                       
                </div>
                <div class="list-group mt-4">
                    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
                        Widget Text
                    </a>
                    <a href="#" class="list-group-item list-group-item-action"><p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Culpa rem error odit numquam impedit minus aperiam laudantium eius, excepturi dolore repellat hic fuga commodi quisquam eos voluptatem quae placeat quia!</p></a>
                    
                </div>
            </div>
        </div>
        <div class="raw">
            <div class="col-8-lg">
                <div class="card mb-3" style="width: 900px; border: 0;">
                    <div class="row g-0">
                      <div class="col-md-4">
                        <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start" alt="...">
                      </div>
                      <div class="col-md-8">
                        <div class="card-body">
                          <h5 class="card-title">First featurette Heading</h5>
                          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                          <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                        </div>
                      </div>
                    </div>
                  </div>
            </div>
        </div>
        <div class="raw">
            <div class="col-8-lg">
                <div class="card mb-3" style="width: 900px; border: 0;">
                    <div class="row g-0">
                      <div class="col-md-8">
                        <div class="card-body">
                          <h5 class="card-title">First featurette Heading</h5>
                          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                          <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                        </div>
                      </div>
                      <div class="col-md-4">
                        <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start" alt="...">
                      </div>
                    </div>
                  </div>
            </div>
        </div>
        <div class="card-footer" style="background-color: rgb(17, 19, 19);">
            <p><div class="text-light">2022 Universitas Pelita Bangsa</div></p>

        </div>
    </div>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
</body>

</html>
```