<template>
  <div class="opensidebar">
    <div class="logo_details">
      <i class="bx bxl-audible icon"></i>
      <div class="logo_name">Aktron</div>
      <i class="bx bx-menu" id="btn"></i>
    </div>
    <ul class="nav-list">
      <li>
        <i class="bx bx-search"></i>
        <input type="text" placeholder="Search..." />
        <span class="tooltip">Search</span>
      </li>

      <li>
        <a href="#">
          <i class="bx bx-grid-alt"></i>
          <span class="link_name">Dashboard</span>
        </a>
        <span class="tooltip">Dashboard</span>
      </li>
      <li>
        <a href="#">
          <i class="bx bx-user"></i>
          <span class="link_name">User</span>
        </a>
        <span class="tooltip">User</span>
      </li>
      <li>
        <a href="#">
          <i class="bx bx-chat"></i>
          <span class="link_name">Message</span>
        </a>
        <span class="tooltip">Message</span>
      </li>
      <li>
        <a href="#">
          <i class="bx bx-pie-chart-alt-2"></i>
          <span class="link_name">Analytics</span>
        </a>
        <span class="tooltip">Analytics</span>
      </li>
      <li>
        <a href="#">
          <i class="bx bx-folder"></i>
          <span class="link_name">File Manger</span>
        </a>
        <span class="tooltip">File Manger</span>
      </li>
      <li>
        <a href="#">
          <i class="bx bx-cart-alt"></i>
          <span class="link_name">Order</span>
        </a>
        <span class="tooltip">Order</span>
      </li>
      <li>
        <a href="#">
          <i class="bx bx-cog"></i>
          <span class="link_name">Settings</span>
        </a>
        <span class="tooltip">Settings</span>
      </li>

      <li class="profile">
        <div class="profile_details">
          <img src="../assets/img/logomain.png" alt="profile_image" />
          <div class="profile_content">
            <div class="name">Vincent</div>
            <div class="designation">Admin</div>
          </div>
        </div>
        <i class="bx bx-log-out" id="log_out"></i>
      </li>
    </ul>
  </div>

  <!-- top navigation -->
  <div id="homesectionnav" class="home-section">
    <div class="container-fluid bg-secondary py-2">
      <!-- {/* sticky header section */} -->
      <div class="row">
        <div class="col-8">
          <div class="d-flex">
            <a href="#" class="navbar-brand mt-2 mt-lg-0">
              <img
                src="../assets/img/logomain.png"
                alt="logo"
                loading="lazy"
                height="15"
                class="px-2"
              />
              AIMS
            </a>
          </div>
        </div>
        <div class="col-4 d-flex flex-row-reverse">
          <!-- {/* right links */} -->
          <div class="d-flex align-items-center">
            <a href="#!" class="text-reset me-3">
              <i class="bx bx-shopping-bag"></i>
            </a>

            <!-- {/* notifications */} -->
            <div class="dropdown">
              <a
                href="#!"
                class="text-reset me-3 dropdown-toggle hidden-arrow"
                role="button"
                id="navbarDropdownMenuLink"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                <i class="bx bxs-bell-ring"></i>
                <span class="badge rounded-pill badge-notification bg-danger">1</span>
              </a>
              <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="navBarDropdownMenuLink">
                <li>
                  <a href="#!" class="dropdown-item">View Cart</a>
                </li>
                <li>
                  <a href="#!" class="dropdown-item">Checkout</a>
                </li>
                <li>
                  <a href="#!" class="dropdown-item">Continue Shopping</a>
                </li>
              </ul>
            </div>

            <!-- {/* Profile Avatar */} -->
            <div class="dropdown">
              <a
                href="#!"
                class="dropdown-toggle d-flex align-items-center hidden-arrow"
                id="navbarDropdownMenuAvatar"
                role="button"
                aria-expanded="false"
                data-bs-toggle="dropdown"
              >
                <img
                  src="../assets/img/logomain.png"
                  alt="profile_image"
                  class="rounded-circle"
                  height="25"
                  loading="lazy"
                />
              </a>
              <ul
                class="dropdown-menu dropdown-menu-end"
                aria-labelledby="navbarDropdownMenuAvatar"
              >
                <li>
                  <a href="#!" class="dropdown-item">Profile</a>
                </li>
                <li>
                  <a href="#!" class="dropdown-item">Settings</a>
                </li>
                <li>
                  <hr class="dropdown-divider" />
                </li>
                <li>
                  <a href="#!" class="dropdown-item">Log Out</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- body section -->
  <div class="home-section">
    <!-- {/* cards */} -->
    <div class="row pt-5 px-4 w-100">
      <div class="col-xl-4 col-md-6 pt-4">
        <div class="card text-white bg-success mb-3">
          <div class="card-header">Header</div>
          <div class="card-body py-5">
            <h5 class="card-title">Success card</h5>
            <p class="card-text">Something quick and easy</p>
          </div>
          <div class="card-footer d-flex align-items-center justify-content-between">
            <a href="#!" class="small text-white stretched-link">View Details</a>
            <div class="small text-white">
              <i class="bx bx-chevrons-right"></i>
            </div>
          </div>
        </div>
      </div>
      <div class="col-xl-4 col-md-6 pt-4">
        <div class="card text-white bg-danger mb-3">
          <div class="card-header">Header</div>
          <div class="card-body py-5">
            <h5 class="card-title">Success card</h5>
            <p class="card-text">Something quick and easy</p>
          </div>
          <div class="card-footer d-flex align-items-center justify-content-between">
            <a href="#!" class="small text-white stretched-link">View Details</a>
            <div class="small text-white">
              <i class="bx bx-chevrons-right"></i>
            </div>
          </div>
        </div>
      </div>
      <div class="col-xl-4 col-md-6 pt-4">
        <div class="card text-white bg-dark mb-3">
          <div class="card-header">Header</div>
          <div class="card-body py-5">
            <h5 class="card-title">Success card</h5>
            <p class="card-text">Something quick and easy</p>
          </div>
          <div class="card-footer d-flex align-items-center justify-content-between">
            <a href="#!" class="small text-white stretched-link">View Details</a>
            <div class="small text-white">
              <i class="bx bx-chevrons-right"></i>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- {/* tablechart */} -->
    <div class="row pt-5 px-4 w-100">
      <div class="col-xl-6 pt-4">
        <div class="card mb-4">
          <div class="card-header">
            <i class="bx bx-line-chart p-2"></i>
            Area Chart(Bar)
          </div>
          <div class="card-body">
            <BarChart />
          </div>
        </div>
      </div>
      <div class="col-xl-6 pt-4">
        <div class="card mb-4">
          <div class="card-header">
            <i class="bx bx-line-chart p-2"></i>
            Area Chart(Line)
          </div>
          <div class="card-body">
            <LineChart />
          </div>
        </div>
      </div>
    </div>

    <!-- {/* datatable */} -->
    <div class="row pt-5 px-4 w-100">
      <div class="col-12 pt-4">
        <div class="card mb-4">
          <div class="card-header">
            <i class="bx bx-table p-2"></i>
            Users DataList
          </div>
          <div class="card-body">
            <div class="table-responsive">
              <table
                id="dtBasicExample"
                class="table table-striped table-sm"
                cellSpacing="0"
                width="100%"
              >
                <thead>
                  <tr>
                    <th>Name</th>
                    <th>Position</th>
                    <th>Office</th>
                    <th>Age</th>
                    <th>Start date</th>
                    <th>Salary</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>Tiger Nixon</td>
                    <td>System Architect</td>
                    <td>Edinburgh</td>
                    <td>61</td>
                    <td>2011-04-25</td>
                    <td>$320,800</td>
                  </tr>
                  <tr>
                    <td>Garrett Winters</td>
                    <td>Accountant</td>
                    <td>Tokyo</td>
                    <td>63</td>
                    <td>2011-07-25</td>
                    <td>$170,750</td>
                  </tr>
                  <tr>
                    <td>Ashton Cox</td>
                    <td>Junior Technical Author</td>
                    <td>San Francisco</td>
                    <td>66</td>
                    <td>2009-01-12</td>
                    <td>$86,000</td>
                  </tr>
                  <tr>
                    <td>Cedric Kelly</td>
                    <td>Senior Javascript Developer</td>
                    <td>Edinburgh</td>
                    <td>22</td>
                    <td>2012-03-29</td>
                    <td>$433,060</td>
                  </tr>
                  <tr>
                    <td>Airi Satou</td>
                    <td>Accountant</td>
                    <td>Tokyo</td>
                    <td>33</td>
                    <td>2008-11-28</td>
                    <td>$162,700</td>
                  </tr>
                  <tr>
                    <td>Brielle Williamson</td>
                    <td>Integration Specialist</td>
                    <td>New York</td>
                    <td>61</td>
                    <td>2012-12-02</td>
                    <td>$372,000</td>
                  </tr>
                  <tr>
                    <td>Herrod Chandler</td>
                    <td>Sales Assistant</td>
                    <td>San Francisco</td>
                    <td>59</td>
                    <td>2012-08-06</td>
                    <td>$137,500</td>
                  </tr>
                  <tr>
                    <td>Rhona Davidson</td>
                    <td>Integration Specialist</td>
                    <td>Tokyo</td>
                    <td>55</td>
                    <td>2010-10-14</td>
                    <td>$327,900</td>
                  </tr>
                  <tr>
                    <td>Colleen Hurst</td>
                    <td>Javascript Developer</td>
                    <td>San Francisco</td>
                    <td>39</td>
                    <td>2009-09-15</td>
                    <td>$205,500</td>
                  </tr>
                  <tr>
                    <td>Sonya Frost</td>
                    <td>Software Engineer</td>
                    <td>Edinburgh</td>
                    <td>23</td>
                    <td>2008-12-13</td>
                    <td>$103,600</td>
                  </tr>
                  <tr>
                    <td>Jena Gaines</td>
                    <td>Office Manager</td>
                    <td>London</td>
                    <td>30</td>
                    <td>2008-12-19</td>
                    <td>$90,560</td>
                  </tr>
                  <tr>
                    <td>Quinn Flynn</td>
                    <td>Support Lead</td>
                    <td>Edinburgh</td>
                    <td>22</td>
                    <td>2013-03-03</td>
                    <td>$342,000</td>
                  </tr>
                  <tr>
                    <td>Charde Marshall</td>
                    <td>Regional Director</td>
                    <td>San Francisco</td>
                    <td>36</td>
                    <td>2008-10-16</td>
                    <td>$470,600</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- {/* footer */} -->
    <div class="row w-100">
      <div class="container-fluid bg-success">
        <div class="row pt-2">
          <div class="col-6 d-flex align-items-end flex-column text-white">
            <p>Copyright: 2023</p>
          </div>
          <div class="col-6 d-flex align-items-end flex-column text-white">
            <p>Developed by: KV</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import '../assets/js/main.js'
import BarChart from '../components/Charts/BarChart.vue'
import LineChart from '../components/Charts/LineChart.vue'

export default {
  //   name: 'BarChart',
  components: { BarChart, LineChart }
}
</script>
