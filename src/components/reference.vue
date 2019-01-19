<template>
  <div class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-12 language-set">
          <h4 data-aos="fade-right"><i class="fa fa-star py-2"></i> Testimonials</h4>
          <div class="row">
            <div class="card col-md-6">
              <div id="carouselTestimonialsControls" class="carousel slide" data-ride="carousel" data-interval="2000">
                <div class="w-100 carousel-inner" role="listbox">
                  <div class="carousel-item active">
                    <div class="carousel-caption">
                      <div class="row">
                        <div class="col-sm-12">
                          <h3><a target="_blank" href="https://www.zbw.eu/forschung/science-2-0/anja-busch/">Anja Busch</a></h3>
                          <small>Ms. Anja Busch is the Project manager of project GeRDI(Generic Research Data Infrastructure) at ZBW-Leibniz-Informationszentrum Wirtschaft, Kiel. For 9 months, I had worked as a front-end developer under project management of Anja Busch in Project GeRDI.</small>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <div class="carousel-caption">
                      <div class="row">
                        <div class="col-sm-12">
                          <h3><a href="http://www.zbw.eu/de/forschung/zbw-labs/timo-borst/" target="_blank">Dr. Timo Borst</a></h3>
                          <small>Dr. Timo Borst is the Head of Innovative Information Systems and Publication Technologies (IIPT) Department at ZBW-Leibniz-Informationszentrum Wirtschaft, Kiel. I had done my master thesis under the supervision of Dr. Timo Borst. </small>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <div class="carousel-caption">
                      <div class="row">
                        <div class="col-sm-12">
                          <h3><a href="https://www.concept.one/impressum.html" target="_blank">Oliver Gstir</a> </h3>
                          <small>Mr. Oliver Gstir is the Executive Director of Concept one GmbH, Hamburg. For more then Two years, I had worked as software developer under the management of Mr. Gstir </small>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="float-right navi">
                  <a class="" href="#carouselTestimonialsControls" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon ico" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                  </a>
                  <a class="" href="#carouselTestimonialsControls" role="button" data-slide="next">
                    <span class="carousel-control-next-icon ico" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: 'reference'
    }
</script>

<style scoped>
  .card.bg-primary,.card.bg-primary .text-muted,.card.bg-primary a{
    color: white !important;
  }
  .card.bg-primary .card-title{
    font-weight: 700;
  }

  .card {
    margin: 0 auto;
  }
  .card .carousel-item {
    height: 200px;
  }
  .card .carousel-caption {
    padding: 0;
    right: 0;
    left: 0;
    color: #3d3d3d;
  }
  .card .carousel-caption h3 {
    color: #3d3d3d;
  }
  .card .carousel-caption p {
    line-height: 30px;
  }
  .card .carousel-caption .col-sm-3 {
    display: flex;
    align-items: center;
  }
  .card .carousel-caption .col-sm-9 {
    text-align: left;
  }
  .navi a {
    text-decoration:none;
  }
  a > .ico {
    background-color: grey;
    padding: 10px;

  }
  a:hover > .ico {
    background-color: #666;
  }
</style>
