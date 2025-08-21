<!-- Provisional container to keep the background -->
<main class="bg-secondary">
  
  <!-- Logos section -->
  <!-- TODO: Responsive behavior -->
  <section class="bg-light" id="partners-logos">
    
    <div class="container py-4">
      
      <div class="row align-items-center justify-content-center">
        <div class="col-auto">
          <h2 class="fs-6 text-muted">Proud partner of</h2>
        </div>
        <!--/col-->
        <div class="col-auto d-flex-inline">
          <img class="px-3" src="https://placehold.co/140x48?text=PODS" alt="Partner logo">
          <img class="px-3" src="https://placehold.co/140x48?text=Budget" alt="Partner logo">
          <img class="px-3" src="https://placehold.co/140x48?text=U-Pack" alt="Partner logo">
          <img class="px-3" src="https://placehold.co/140x48?text=Penske" alt="Partner logo">
          <img class="px-3" src="https://placehold.co/140x48?text=PackRat" alt="Partner logo">
        </div>
        <!--/col-->
      </div>
      <!--/row-->
    </div>
    <!--/container-->
    
  </section>
  
  <hr>
  
  <!-- Feature section -->
  <!-- TODO: Figure out responsive stacking and image horizontal alignment -->
  <section class="container-lg bg-white py-4">
    
    <div class="row align-items-center gx-lg-5">
      
      <div class="col-auto col-lg-6 py-3">
        
        <header>
          <h2>Top-Rated Movers Ready to Help, In Your Local Area</h2>
          <p>Moving in San Diego is an adventure — and we're here to guide you through. Whether you’re heading across town or just a few blocks over, we'll connect you with reliable local movers who know every twist and turn of this vibrant hub of culture and sunshine.</p>
          <p>Our full-service and labor-only options promise affordable pricing, an easy process, and dependable support 7 days a week.</p>
        </header>
        
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#">Local Full-Service vs. Labor-Only: Which Is Right for You?</a></li>
          <li class="list-inline-item"><span class="text-muted">&middot;</span></li>
          <li class="list-inline-item"><a href="#">The Cost of Moving in San Diego, CA</a></li>
          <li class="list-inline-item"><span class="text-muted">&middot;</span></li>
          <li class="list-inline-item"><a href="#">Moving Services in San Diego, CA</a></li>
          <li class="list-inline-item"><span class="text-muted">&middot;</span></li>
          <li class="list-inline-item"><a href="#">HireAHelper's Moving Guide for San Diego, CA</a></li>
          <li class="list-inline-item"><span class="text-muted">&middot;</span></li>
          <li class="list-inline-item"><a href="#">Frequently Asked Diego</a></li>
          <li class="list-inline-item"><span class="text-muted">&middot;</span></li>
          <li class="list-inline-item"><a href="#">Resources for Your Move</a></li>
        </ul>
        
      </div>
      <!--/col-->
      
      <div class="col-auto col-lg-6 d-flex">
        <img class="img-fluid rounded-3" src="https://placehold.co/600x400" alt="Image alt text">
      </div>
      <!--/col-->
      
    </div>
    <!--/row-->
    
  </section>
  
  <hr>
  
  <!-- Card comparison section -->
  <section class="container-lg bg-white py-4">
    
    <header class="mb-4">
      <h2 class="text-start text-sm-center">The HireAHelper Advantage</h2>
    </header>
    
    <div class="row gy-3 justify-content-center align-items-sm-stretch">
      <!-- TODO: Stacking in tablet vertical (sm?) -->
      <div class="col-12 col-sm-10 col-md-5 d-flex align-items-sm-stretch">
        <div class="card w-100 p-3 rounded-5 card-red-border">
          <h3 class="h4 text-center">The Traditional Move</h3>
          <ul class="list-unstyled">
            {#each Array(3) as _}
            <li class="d-flex pt-2">
              <div class="pe-2"><span class="fa-regular fa-thumbs-up text-danger"></span></div>
              <div>Waste hours calling around and filling out forms — just to compare prices.</div>
            </li>
            {/each}
          </ul>
        </div>
      </div><!--/col-->
      
      <div class="col-12 col-md-auto d-flex justify-content-center align-items-center">
        <span class="h4">vs.</span>
      </div>
      <div class="col-12 col-sm-10 col-md-5 d-flex align-items-sm-stretch">
        <div class="card w-100 p-3 rounded-5 card-green-border">
          <h3 class="h4 text-center">Moving With HireAHelper</h3>
          <ul class="list-unstyled">
            {#each Array(3) as _}
            <li class="d-flex pt-2">
              <div class="pe-2"><span class="fa-regular fa-thumbs-up text-success"></span></div>
              <div>Navigate unreliable customer service and unclear expectations on your own.</div>
            </li>
            {/each}
          </ul>
        </div>
      </div>
    </div>
    
  </section>
  
  <hr>
  
  <!-- Sample section with a header and a table -->
  <section class="container-lg bg-white py-4">
    
    <header class="mb-4">
      <h2 class="text-center">The Cost of Labor-Only Movers in San Diego</h2>
      <p>If you're happy to drive your own moving truck or already have a storage container but need a hand with the heavy lifting, labor-only is the way to go. Hourly rates for labor-only movers in San Diego are typically around $92.20.
      </p>
      <p>The total cost depends on the size of your place and how long the move takes. You can save even more by booking your move on a Sunday or during August — the cheapest day and month to move in San Diego. Avoid weekends and the end of the month if you can, as those are usually the busiest and most expensive times.</p>
      
      <p>Check out the table below for more details about how the size of your home affects costs:</p>
    </header>
    
    <table class="table table-seo-geo-pages">
      <thead>
        <tr>
          <th class="text-center" scope="col"></th>
          <th class="text-center" scope="col"># of Movers</th>
          <th class="text-center" scope="col">Move Duration</th>
          <th class="text-center" scope="col">Average Cost</th>
        </tr>
      </thead>
      <tbody>
        
        <tr>
          <th scope="row">Studio Apartment</th>
          <td class="text-center">2.0</td>
          <td class="text-center">2.2</td>
          <td class="text-center">$381.19</td>
        </tr>
        
        <tr>
          <th scope="row">1 Bedroom Apartment</th>
          <td class="text-center">2.0</td>
          <td class="text-center">2.2</td>
          <td class="text-center">$381.19</td>
        </tr>
        
        <tr>
          <th scope="row">2 Bedroom Apartment</th>
          <td class="text-center">2.0</td>
          <td class="text-center">2.2</td>
          <td class="text-center">$381.19</td>
        </tr>
        
      </tbody>
    </table>
    
  </section>
  
  <hr>
  
  <!-- Reviews section-->
  <section class="container-fluid py-4 bg-blue-50">
    <header class="mb-4">
      <div class="average-star-rating d-flex justify-content-center my-3 fs-5">
        <i class="fa fa-star text-green-500"></i>
        <i class="fa fa-star text-green-500"></i>
        <i class="fa fa-star text-green-500"></i>
        <i class="fa fa-star text-green-500"></i>
        <i class="fa fa-star-half-alt text-green-500"></i>
      </div>
      <h2 class="text-center">Top-Rated Moving Services According to Real Customer Reviews</h2>
      <p class="text-center">On average, customers rate Moving Companies through HireAHelper 4.8 stars out of 5 after 267,052 customer reviews. Our trusted movers are committed to delivering outstanding service, making your move smooth, affordable, and completely hassle-free.</p>
    </header>
    
    <div class="swiper d-flex gap-3 overflow-auto">
      
      {#each Array(5) as _, i (i)}
      
        <div class="card border-0" style="min-width: 24rem;">
        
          <div class="card-body d-flex flex-column pb-0">
          
          <!-- Card header -->
          <div class="d-flex gap-2">

            <!-- Card title -->
            <div class="d-flex flex-column">

                <!-- Title -->
                <div>
                  <strong class="">Valeria T</strong> from <a class="fw-bold" href="/movers/las-vegas_nv/">Las Vegas, NV</a>
                </div>

                <!-- Provider -->
                <div class="text-small">
                  <span class="text-muted">Reviewing:</span> <a href="/movers/north-las-vegas_nv/transportation-movers/#reviews">Transportation Movers</a>
                </div>
                
                <!-- Rating-->
                <div class="d-flex align-items-center">
                  <div class="star-rating me-2 small">
                    <i class="fas fa-star text-primary"></i>
                    <i class="fas fa-star text-primary"></i>
                    <i class="fas fa-star text-primary"></i>
                    <i class="fas fa-star text-primary"></i>
                    <i class="fas fa-star text-primary"></i>
                  </div>
                  <span class="align-middle">(5 out of 5 rating)</span>
                </div>

            </div><!--/title-->

            <!-- Card thumbnail -->
            <div>
                <img width="100" height="100" alt="Transportation Movers Profile Image" style="height:100px;" class="img-fluid rounded border border-2 border-success ms-auto" src="https://www.hireahelper.com/_static/img/public/geopages/stock-photos/moving-service-provider-02.jpg" loading="lazy">
            </div>

          </div>

          <div class="mt-2 position-relative d-flex flex-column flex-grow-1">
            <p class="card-text small text-overflow-clamp-4 mb-0">
              My helpers were outstanding. On-time, polite, and professional. They packed a 26’ UHAL into a 10x15 space. Incredible talent of organization. Both man worked really hard from the first minute until the last. I’m recommending them as much as I can.
            </p>
            <div class="row align-items-end flex-grow-1">
              <div class="col"><a href="/movers/north-las-vegas_nv/transportation-movers/#reviews" class="small">Read more</a></div>
              <div class="col-auto text-end small text-muted">Reviewed on: 5/26/2025</div>
            </div>
          </div>
        </div>
        <div class="card-footer bg-white border-top-0">
          <div class="row g-0">
            <div class="col-6">
              <div class="small py-1">
                Cost: <span class="fw-bold text-cool-grey-700">$411</span>
              </div>
            </div>
            <div class="col-6">
              <div class="small py-1">
                Helpers: <span class="fw-bold text-cool-grey-700 js-hahtip js-hahtipapplied">3 / 3hr</span>
              </div>
            </div>
            <div class="col-6">
              <div class="small pb-1">
                Vehicle: <span class="fw-bold text-cool-grey-700">        <span><a class="fw-bold text-cool-grey-700" href="/moving/semi-freight-trailer/">Freight Trailer</a></span>
              </span>
            </div>
          </div>
          <div class="col-6">
            <div class="small pb-1">
              Service: <span class="fw-bold text-cool-grey-700">        <span><a class="fw-bold text-cool-grey-700" href="/move-help/unloading-help/">Unloading</a></span>
            </span>
          </div>
        </div>
      </div>
        </div><!--/card-->
        </div>
      
      {/each}
      
    </div><!--/swiper-->
    
  </section><!-- /reviews-->
  
  
  <!-- Sample section with a header and multiple "articles" -->
  <section class="container-lg bg-white py-4">
    
    <header class="mb-4">
      <h2 class="text-center">Moving Services in San Diego</h2>
    </header>
    
    <!-- Article 1-->
    <article class="py-4">
      
      <h3>How Full-Service Moving With HireAHelper Works</h3>
      
      <p>After booking online with HireAHelper, your movers will handle every aspect of moving day so you don’t have to lift a finger. Your moving company will take care of loading, transportation, and unloading at your destination. Want even more support? Many full-service movers offer optional packing and unpacking services to help you settle in faster.</p>
      
      <p>
        <strong>Full-Service Advantages:</strong>
      </p>
      
      <ul>
        <li><strong>Less Planning:</strong> Skip the headache of coordinating truck rentals, parking permits, and loading help—your movers handle everything.</li>
        <li><strong>Less Moving-Day Stress:</strong> No need to worry about driving or parking a bulky moving truck—professionals take care of it.</li>
        <li><strong>Peace of Mind:</strong> Trust experienced movers to handle your belongings safely from start to finish. Plus, when you book with HireAHelper, you get our <a href="#">$1,000 service guarantee</a>.</li>
      </ul>
      
    </article>
    
    <!-- Article 2 -->
    <article class="py-4">
      
      <h3>How Full-Service Moving With HireAHelper Works</h3>
      
      <p>After booking online with HireAHelper, your movers will handle every aspect of moving day so you don’t have to lift a finger. Your moving company will take care of loading, transportation, and unloading at your destination. Want even more support? Many full-service movers offer optional packing and unpacking services to help you settle in faster.</p>
      
      <p>
        <strong>Full-Service Advantages:</strong>
      </p>
      
      <ul>
        <li><strong>Less Planning:</strong> Skip the headache of coordinating truck rentals, parking permits, and loading help—your movers handle everything.</li>
        <li><strong>Less Moving-Day Stress:</strong> No need to worry about driving or parking a bulky moving truck—professionals take care of it.</li>
        <li><strong>Peace of Mind:</strong> Trust experienced movers to handle your belongings safely from start to finish. Plus, when you book with HireAHelper, you get our <a href="#">$1,000 service guarantee</a>.</li>
      </ul>
      
    </article>
    
  </section>
  
  <hr>
  
  <!-- Real advice section (banner image, header and card grid) -->
  <section class="container-lg bg-white py-4">
    
    <!-- Banner row -->
    <div class="row mb-4">
      <img class="img-fluid rounded-3" src="https://placehold.co/800x450" alt="Image alt text">
    </div><!--/row-->
    
    <!-- Section header -->
    <div class="row">
      <header class="mb-4">
        <h2 class="text-center">Real Advice From San Diego Movers</h2>
        <p class="text-center">We asked local movers about what you should know about moving in San Diego. (They’re really nice!)</p>
      </header>
    </div>
    
    <!-- Cards grid -->
    <div class="row gy-4">
      
      <!-- Column -->
      <div class="col-3">
        <div class="card p-3">
          <p>"Parking is tough in San Diego, so having a loading zone nearby and available will save a lot of time. Also, if you are moving into a space with an elevator, you may need to reserve it."</p>
          <div class="pt-2 d-flex-inline">
            <img class="rounded-circle" src="https://placehold.co/48x48" alt="User avatar">
            <span><a href="#">Card link</a></span>
          </div>
        </div>
      </div><!--/col-->
      
      <!-- Column -->
      <div class="col-3">
        <div class="card p-3">
          <p>"We recommend scheduling your move as far in advance as possible. The farther out you can plan your move, the greater the availability you will have in choosing a date and time that is convenient for you. Our busiest times of the year are June-September, Saturdays throughout the year, and the end of each month."</p>
          <div class="pt-2 d-flex-inline">
            <img class="rounded-circle" src="https://placehold.co/48x48" alt="User avatar">
            <span><a href="#">Card link</a></span>
          </div>
        </div>
      </div><!--/col-->
      
      <!-- Column -->
      <div class="col-3">
        <div class="card p-3">
          <p>"Colorado is expanding exponentially it seems and that means the sooner you can book, schedule, and /or reserve your necessary vehicles for the day of the move the better off you will be. If at all possible mon- Friday avoid big commutes between 3:00-3:30pm through about 7:30-8:00pm the weekends are pretty much good all day though. Weather changes are fast and drastic, if you're in warm weather wear you should have cold weather attire on hand because it can go from sun to snow in 20 minutes or less. "</p>
          <div class="pt-2 d-flex-inline">
            <img class="rounded-circle" src="https://placehold.co/48x48" alt="User avatar">
            <span><a href="#">Card link</a></span>
          </div>
        </div>
      </div><!--/col-->
      
      <!-- Column -->
      <div class="col-3">
        <div class="card p-3">
          <p>"Parking is tough in San Diego, so having a loading zone nearby and available will save a lot of time. Also, if you are moving into a space with an elevator, you may need to reserve it."</p>
          <div class="pt-2 d-flex-inline">
            <img class="rounded-circle" src="https://placehold.co/48x48" alt="User avatar">
            <span><a href="#">Card link</a></span>
          </div>
        </div>
      </div><!--/col-->
      
    </div><!--/row-->
    
  </section>
  
  <hr>
  
  <!-- Card grid section -->
  <section class="container-lg bg-white py-4">
    
    <header class="mb-4">
      <h2 class="text-center">HireAHelper’s Moving Guide for Brookings, SD</h2>
    </header>
    
    <div class="row justify-content-center align-items-stretch gx-3 gy-3">
      
      <div class="col-12 col-sm-8 col-md-6 col-lg-4 d-flex justify-content-center align-items-sm-stretch">
        <div class="card w-100 border-0 p-3 rounded-5 bg-light">
          <header class="mb-2">
            <h3 class="fs-6 fw-bold lh-base">On average, most people in San Diego need:</h3>
          </header>
          <p class="h2">2 movers</p>
          <p>Read more about <a href="#">hiring the right number of movers</a>.</p>
          
        </div>
      </div><!--/col-->
      
      <div class="col-12 col-sm-8 col-md-6 col-lg-4 d-flex justify-content-center align-items-sm-stretch">
        <div class="card w-100 border-0 p-3 rounded-5 bg-light">
          <header class="mb-2">
            <h3 class="fs-6 fw-bold lh-base">The most popular truck size is a:</h3>
          </header>
          <p class="h2">16' truck</p>
          <p>Read our guide to choosing the <a href="">right rental truck</a> for your move.</p>
          
        </div>
      </div><!--/col-->
      
      <div class="col-12 col-sm-8 col-md-6 col-lg-4 d-flex justify-content-center align-items-sm-stretch">
        <div class="card w-100 border-0 p-3 rounded-5 bg-light">
          <header class="mb-2">
            <h3 class="fs-6 fw-bold lh-base">On average, most people in Brooklyn need:</h3>
          </header>
          <p class="h2">2 movers</p>
          <p>Pro tip: Book ahead as far as possible to get the best rates!</p>
          
        </div>
      </div><!--/col-->
      
    </div>
    
  </section>
  
  <hr>
  
  <section id="related-cities--container" class="expanding-cities container-lg bg-white py-4">
    
    <div class="row justify-content-center align-items-center gx-5 mx-auto">
      
      <!-- Illustration column -->
      <div class="map-frame col-4 d-flex justify-content-center rounded-3">
        <img width="300" height="300" alt="IL State Image" class="img-fluid" src="https://www.hireahelper.com/_static/img/public/geopages/city-region/state-svgs/IL.svg?ver=pfHFCCE90Pkueosx0E1RPznPRdeYXco5fkxb4spy15M%3D" loading="lazy">
      </div>
      
      <!-- List column -->
      
      <div class="col-4 order-md-0">
        <header class="pb-3">
          <h2 class="mb-0">We also have movers in</h2>
        </header>
        
        <div class="row row-cols-2 justify-content-center">
          
          <div class="col city-cols">
            <ul class="list-unstyled">
              <li class="py-1">
                <a class="" href="/movers/cicero_il/"><span class="fa fa-map-pin me-1"></span>City one</a>
              </li>
              <li class="py-1">
                <a class="" href="/movers/cicero_il/"><span class="fa fa-map-pin me-1"></span>City two</a>
              </li>
              <li class="py-1">
                <a class="" href="/movers/cicero_il/"><span class="fa fa-map-pin me-1"></span>City three</a>
              </li>
            </ul>
          </div>
          
          <div class="col city-cols">
            <ul class="list-unstyled">
              <li class="py-1">
                <a class="" href="/movers/cicero_il/"><span class="fa fa-map-pin me-1"></span>City one</a>
              </li>
              <li class="py-1">
                <a class="" href="/movers/cicero_il/"><span class="fa fa-map-pin me-1"></span>City two</a>
              </li>
              <li class="py-1">
                <a class="" href="/movers/cicero_il/"><span class="fa fa-map-pin me-1"></span>City three</a>
              </li>
            </ul>
          </div>
          
        </div>
        
        <div class="row">
          <div class="pt-2" id="view-more-cities-col">
            <a href="javascript:void(0);" id="view-more-cities" class="fw-bold">View More Cities<i class="fa fa-chevron-down ms-1"></i></a>
          </div>
        </div>
        
      </div>
      <!--col-->
    </div>
    <!--row-->
  </section>
  <!--container section-->
  
</main>

<style>
  /* Custom styles for this page */
  
  .rounded-5 {
    border-radius: 1rem !important;
  }
  
  .bg-blue-50 {
    background-color: #F0F7FE;
  }
  .text-green-500 {
    color: hsla(108, 55%, 50%, 1);
  }
  
  .map-frame {
    border-radius: 16px;
    background: radial-gradient(
    54.78% 50% at 50% 49.98%,
    rgba(178, 209, 255, 0.6) 0%,
    rgba(255, 255, 255, 0.5) 100%
    );
  }
  
  .table-seo-geo-pages thead th {
    background-color: #f0f7fe; /* blue-50 */
  }
  
  /* Replicating Bootstrap's selector's specificity for their default table styling */
  .table-seo-geo-pages > :not(:last-child) > :last-child > * {
    border-bottom-color: #2b73de; /* blue-600 */
  }
  .table-seo-geo-pages > :not(caption) > * > * {
    padding-top: 0.75rem;
    padding-bottom: 0.75rem;
  }
  
  .card-red-border {
    border-top-color: var(--bs-danger);
    border-top-width: 4px;
  }
  .card-green-border {
    border-top-color: var(--bs-success);
    border-top-width: 4px;
  }
</style>
