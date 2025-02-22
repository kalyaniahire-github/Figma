# Figma


<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Breeze Admin</title>
    <!-- plugins:css -->
    <link rel="stylesheet" href="assets/vendors/mdi/css/materialdesignicons.min.css">
    <link rel="stylesheet" href="assets/vendors/css/vendor.bundle.base.css">
    <!-- endinject -->
    <!-- Plugin css for this page -->
    <link rel="stylesheet" href="assets/vendors/font-awesome/css/font-awesome.min.css" />
    <link rel="stylesheet" href="assets/vendors/bootstrap-datepicker/bootstrap-datepicker.min.css">
    <!-- End plugin css for this page -->
    <!-- inject:css -->
    <!-- endinject -->
    <!-- Layout styles -->
    <link rel="stylesheet" href="assets/css/vertical-light-layout/style.css">
    <!-- End layout styles -->
    <link rel="shortcut icon" href="assets/images/favicon.png" />
  </head>
  <body>
    <div class="container-scroller">
   
      <!-- partial:partials/_sidebar.html -->
      <nav class="sidebar sidebar-offcanvas" id="sidebar">
  <div class="text-center sidebar-brand-wrapper d-flex align-items-center">
    <a class="sidebar-brand brand-logo" href="index.html"><img src="assets/images/trip.png" alt="logo" /></a>
    <a class="sidebar-brand brand-logo-mini ps-4 pt-3" href="index.html"><img src="assets/images/trip.png" alt="logo" /></a>
  </div>
  <ul class="nav">
    <li class="nav-item nav-profile">
      <a href="#" class="nav-link">
        <div class="nav-profile-image">
          <img src="assets/images/treepzy.jpg" alt="profile">
          <span class="login-status online"></span>
          <!--change to offline or busy as needed-->
        </div>
        <div class="nav-profile-text d-flex flex-column pe-3">
          <span class="font-weight-medium mb-2">Treepzy</span>
       
        </div>
       
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="index.html">
        <i class="mdi mdi-home menu-icon"></i>
        <span class="menu-title">Dashboard</span>
      </a>
    </li>  
    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#drivers-details" aria-expanded="false" aria-controls="drivers-details">
        <i class="mdi mdi-crosshairs-gps menu-icon"></i>
        <span class="menu-title">Drivers Details</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="drivers-details">
        <ul class="nav flex-column sub-menu">
          <li class="nav-item"> <a class="nav-link" href="driver_registration.html"> Registration</a></li>
          <li class="nav-item"> <a class="nav-link" href="driver_datatable.html">App Register Driver</a></li>
          <li class="nav-item"> <a class="nav-link" href="driver.html">Driver list</a></li>
          <li class="nav-item"> <a class="nav-link" href="driver_table.html">Driver History</a></li>
          <li class="nav-item"> <a class="nav-link" href="ride_management.html">Ride Management</a></li>
       
        </ul>
      </div>
    </li>
   
    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#passengers-list" aria-expanded="false" aria-controls="passengers-list">
        <i class="mdi mdi-crosshairs-gps menu-icon"></i>
        <span class="menu-title">Passengers List</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="passengers-list">
        <ul class="nav flex-column sub-menu">

          <li class="nav-item"> <a class="nav-link" href="passenger.html">View Passangers</a></li>
          <li class="nav-item"> <a class="nav-link" href="passengerslist.html">Passenger list</a></li>
         
          <li class="nav-item"> <a class="nav-link" href="total_ridesToday.html">Total Rides</a></li>
        </ul>
      </div>
    </li>
   
    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#trip-management" aria-expanded="false" aria-controls="trip-management">
        <i class="mdi mdi-crosshairs-gps menu-icon"></i>
        <span class="menu-title">Trip Management</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="trip-management">
        <ul class="nav flex-column sub-menu">
          <li class="nav-item"> <a class="nav-link" href="trip_management.html">Trip Logs</a></li>
          <li class="nav-item"> <a class="nav-link" href="trip_management2.html">Current & Past Ride</a></li>
          <li class="nav-item"> <a class="nav-link" href="trip_manegement3.html">Cancel Rides</a></li>
        </ul>
      </div>
    </li>

    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#report&analysis" aria-expanded="false" aria-controls="trip-management">
        <i class="mdi mdi-crosshairs-gps menu-icon"></i>
        <span class="menu-title">Report & Analysis</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="report&analysis">
        <ul class="nav flex-column sub-menu">
          <li class="nav-item"> <a class="nav-link" href="reports.html">Financial Report</a></li>
          <li class="nav-item"> <a class="nav-link" href="ride_analysis.html">Ride_Analysis</a></li>
          <li class="nav-item"> <a class="nav-link" href="Geographical.html">Geographical_Report</a></li>
          <li class="nav-item"> <a class="nav-link" href="driver_performance.html">Driver_performance</a></li>
          <li class="nav-item"> <a class="nav-link" href="passbehaviour.html">Passenger_behaviour</a></li>
       
        </ul>
      </div>
    </li>


    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#payment&earning" aria-expanded="false" aria-controls="trip-management">
        <i class="mdi mdi-crosshairs-gps menu-icon"></i>
        <span class="menu-title">Payment&Earning</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="payment&earning">
        <ul class="nav flex-column sub-menu">
          <li class="nav-item"> <a class="nav-link" href="payment&earning.html">Revenue Dashboard </a></li>
          <li class="nav-item"> <a class="nav-link" href="driver_payouts.html">Driver Payout</a></li>
       
          <li class="nav-item"> <a class="nav-link" href="passenger_billing.html">Passanger Billing</a></li>
     
 
        </ul>
      </div>
    </li>

     
    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#alertnotification" aria-expanded="false" aria-controls="alertnotification">
        <i class="mdi mdi-crosshairs-gps menu-icon"></i>
        <span class="menu-title">Alert & Notification</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="alertnotification">
        <ul class="nav flex-column sub-menu">
          <li class="nav-item"><a class="nav-link" href="driver_alert.html">Driver Alert</a></li>
          <li class="nav-item"><a class="nav-link" href="passenger_alert.html">Passenger Alert</a></li>
          <li class="nav-item"><a class="nav-link" href="sch_alert.html">Schedule Notification</a></li>
          <li class="nav-item"><a class="nav-link" href="pay_settings.html">payment Setting</a></li>
        </ul>
      </div>
    </li>
   

       
    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#promocode" aria-expanded="false" aria-controls="alertnotification">
        <i class="mdi mdi-crosshairs-gps menu-icon"></i>
        <span class="menu-title">PromoList</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="promocode">
        <ul class="nav flex-column sub-menu">
          <li class="nav-item"><a class="nav-link" href="review_form.html">Review Form</a></li>
          <li class="nav-item"><a class="nav-link" href="transaction.html">Transaction Form</a></li>
          <li class="nav-item"><a class="nav-link" href="promocode.html">Promocode</a></li>
     
        </ul>
      </div>
    </li>
    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#icons" aria-expanded="false" aria-controls="icons">
        <i class="mdi mdi-contacts menu-icon"></i>
        <span class="menu-title">Helpdesk</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="icons">
        <ul class="nav flex-column sub-menu">
          <li class="nav-item"> <a class="nav-link" href="helpdesk.html">Helpdesk</a></li>                            
        </ul>
      </div>
    </li>


    <li class="nav-item">
      <a class="nav-link" data-bs-toggle="collapse" href="#auth" aria-expanded="false" aria-controls="auth">
        <i class="mdi mdi-lock menu-icon"></i>
        <span class="menu-title">User Pages</span>
        <i class="menu-arrow"></i>
      </a>
      <div class="collapse" id="auth">
        <ul class="nav flex-column sub-menu">
       
          <li class="nav-item"> <a class="nav-link" href="pages/samples/login.html"> Login </a></li>          
          <li class="nav-item"> <a class="nav-link" href="pages/samples/register.html"> Register </a></li>                    
        </ul>
      </div>
    </li>
   
    <li class="nav-item sidebar-actions">
      <div class="nav-link">
        <div class="mt-4">
          <div class="border-none">
           
          </div>
          <ul class="mt-4 ps-0">
            <li>Sign Out</li>
          </ul>
        </div>
      </div>
    </li>
  </ul>
</nav>
 <!-- partial -->
 <div class="container-fluid page-body-wrapper">        
  <!-- partial:partials/_navbar.html -->
  <nav class="navbar col-lg-12 col-12 p-lg-0 fixed-top d-flex flex-row">
<div class="navbar-menu-wrapper d-flex align-items-stretch justify-content-between">
<a class="navbar-brand brand-logo-mini align-self-center d-lg-none" href="index.html"><img src="assets/images/logo-mini.svg" alt="logo" /></a>
<button class="navbar-toggler navbar-toggler align-self-center me-2" type="button" data-toggle="minimize">
<i class="mdi mdi-menu"></i>
</button>
<ul class="navbar-nav">
<li class="nav-item dropdown">
  <a class="nav-link count-indicator dropdown-toggle" id="notificationDropdown" href="#" data-bs-toggle="dropdown">
    <i class="mdi mdi-bell-outline"></i>
    <span class="count count-varient1">7</span>
  </a>
  <div class="dropdown-menu navbar-dropdown navbar-dropdown-large preview-list" aria-labelledby="notificationDropdown">
    <h6 class="p-3 mb-0 ">Notifications</h6>
    <a class="dropdown-item preview-item">
      <div class="preview-thumbnail">
        <img src="assets/img/cab.png" alt="" class="profile-pic">
      </div>
      <div class="preview-item-content">
        <p class="mb-0">Dany Miles <span class="text-small text-muted">commented on your photo</span></p>
      </div>
    </a>
    <a class="dropdown-item preview-item">
      <div class="preview-thumbnail">
        <img src="assets/img/cab.png" alt="" class="profile-pic">
      </div>
      <div class="preview-item-content">
        <p class="mb-0">James <span class="text-small text-muted">posted a photo on your wall</span></p>
      </div>
    </a>
    <a class="dropdown-item preview-item">
      <div class="preview-thumbnail">
        <img src="assets/img/cab.png" alt="" class="profile-pic">
      </div>
      <div class="preview-item-content">
        <p class="mb-0">Alex <span class="text-small text-muted">just mentioned you in his post</span></p>
      </div>
    </a>
    <div class="dropdown-divider"></div>
    <p class="p-3 mb-0 ">View all activities</p>
  </div>
</li>
<li class="nav-item dropdown d-none d-sm-flex">
  <a class="nav-link count-indicator dropdown-toggle" id="messageDropdown" href="#" data-bs-toggle="dropdown">
    <i class="mdi mdi-email-outline"></i>
    <span class="count  count-varient2">5</span>
  </a>
  <div class="dropdown-menu navbar-dropdown navbar-dropdown-large preview-list" aria-labelledby="messageDropdown">
    <h6 class="p-3 mb-0 ">Messages</h6>
    <a class="dropdown-item preview-item">
      <div class="preview-item-content flex-grow">
        <span class="badge badge-pill badge-success">Request</span>
        <p class="text-small text-muted ellipsis mb-0"> Suport needed for user123 </p>
      </div>
      <p class="text-small text-muted align-self-start">4:10 PM</p>
    </a>
    <a class="dropdown-item preview-item">
      <div class="preview-item-content flex-grow">
        <span class="badge badge-pill badge-warning">Invoices</span>
        <p class="text-small text-muted ellipsis mb-0"> Invoice for order is mailed </p>
      </div>
      <p class="text-small text-muted align-self-start">4:10 PM</p>
    </a>
    <a class="dropdown-item preview-item">
      <div class="preview-item-content flex-grow">
        <span class="badge badge-pill badge-danger">Projects</span>
        <p class="text-small text-muted ellipsis mb-0"> New project will start tomorrow </p>
      </div>
      <p class="text-small text-muted align-self-start">4:10 PM</p>
    </a>
    <h6 class="p-3 mb-0 ">See all activity</h6>
  </div>
</li>
<li class="nav-item nav-search border-0 ms-1 ms-md-3 ms-lg-5 d-none d-md-flex">
  <form class="nav-link form-inline mt-2 mt-md-0">
    <div class="input-group">
      <input type="text" class="form-control" placeholder="Search">
      <div class="input-group-append">
        <span class="input-group-text">
          <i class="mdi mdi-magnify"></i>
        </span>
      </div>
    </div>
  </form>
</li>
</ul>
<ul class="navbar-nav navbar-nav-right ml-lg-auto">
<li class="nav-item dropdown d-none d-xl-flex border-0">
  <a class="nav-link dropdown-toggle" id="languageDropdown" href="#" data-bs-toggle="dropdown">
    <i class="mdi mdi-earth"></i> English </a>
  <div class="dropdown-menu navbar-dropdown" aria-labelledby="languageDropdown">
    <a class="dropdown-item" href="#"> French </a>
    <a class="dropdown-item" href="#"> Spain </a>
    <a class="dropdown-item" href="#"> Latin </a>
    <a class="dropdown-item" href="#"> Japanese </a>
  </div>
</li>
<li class="nav-item  nav-profile dropdown border-0">
  <a class="nav-link dropdown-toggle" id="profileDropdown" href="#" data-bs-toggle="dropdown">
    <img class="nav-profile-img me-2" alt="" src="assets/img/cab.png">
    <span class="profile-name">codeft Tech</span>
  </a>
  <div class="dropdown-menu navbar-dropdown w-100" aria-labelledby="profileDropdown">
    <a class="dropdown-item" href="#">
      <i class="mdi mdi-cached me-2 text-success"></i> Activity Log </a>
    <a class="dropdown-item" href="#">
      <i class="mdi mdi-logout me-2 text-primary"></i> Signout </a>
  </div>
</li>
</ul>
<button class="navbar-toggler navbar-toggler-right d-lg-none align-self-center" type="button" data-toggle="offcanvas">
<span class="mdi mdi-menu"></span>
</button>
</div>
</nav>
<style>
    body {
    background: linear-gradient(to right, #6a11cb, #2575fc);
    font-family: 'Poppins', sans-serif;
    color: #fff;
  }
  .card {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    border: none;
    border-radius: 15px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    color: #fff;
  }
 
  .form-control, .form-select {
    background: rgba(255, 255, 255, 0.2);
    border: none;
    border-radius: 10px;
    color: #fff;
    padding: 10px;
  }
  .form-control:focus, .form-select:focus {
    background: rgba(255, 255, 255, 0.3);
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
  }
  .btn-primary {
    background: #2575fc;
    border: none;
    border-radius: 30px;
    padding: 10px 20px;
    transition: 0.3s;
  }
  .btn-primary:hover {
    background: #6a11cb;
    box-shadow: 0 5px 15px rgba(106, 17, 203, 0.5);
  }
  .btn-light {
    background: rgba(255, 255, 255, 0.3);
    border: none;
    border-radius: 30px;
    padding: 10px 10px;
    color: #fff;
  }
  .btn-light:hover {
    background: rgba(255, 255, 255, 0.5);
  }
  h3, h4 {
    text-shadow: 0 3px 5px rgba(0, 0, 0, 0.3);
  }
  .form-select {
    background: rgba(255, 255, 255, 0.2);
    border: none;
    border-radius: 10px;
    color: #fff;
    padding: 10px;
    font-weight: normal;
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    position: relative;
    background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="white"><path d="M7 10l5 5 5-5z"/></svg>');
    background-repeat: no-repeat;
    background-position: right 10px center;
    background-size: 15px;
    padding-right: 30px;
}

.form-select option {
    color: black;
    font-weight: normal;
}

.form-select:focus {
    background: rgba(255, 255, 255, 0.3);
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
}
@media (max-width: 576px) {
  .card {
    backdrop-filter: none; /* Remove blur */
    background: rgba(255, 255, 255, 0.2); /* Slightly increase background opacity */
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2); /* Reduce shadow */
  }
 
  .form-control, .form-select {
    background: rgba(255, 255, 255, 0.4); /* Increase contrast */
  }
 
}
.text-center button {
    margin: 0 10px; /* Adds 20px gap between buttons (10px left + 10px right) */
}
.input-group-text {
            background: transparent !important; /* Removes white background */
            border: none; /* Removes border */
        }


</style>
</head>
<body>
  <div class="container py-5">
    <div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card p-4">
          <h3 class="text-center mb-4" style="margin-top: 25px;">Treepzy Booking System</h3>
          <h4 class="text-center mb-4">Driver Registration Form</h4>
          <form>
            <div class="mb-3">
              <label for="driverName" class="form-label">Driver Name</label>
              <input type="text" class="form-control" id="driverName" placeholder="Enter Driver Name" required>
            </div>
           
            <div class="mb-3">
              <label for="contactNumber" class="form-label">Contact Number</label>
              <input type="tel" class="form-control" id="contactNumber" placeholder="Enter Contact Number" required>
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email Address</label>
              <input type="email" class="form-control" id="email" placeholder="Enter Email Address" required>
            </div>
            <div class="mb-3">
              <label for="address" class="form-label">Residential Address</label>
              <textarea class="form-control" id="address" rows="3" placeholder="Enter Full Address" required></textarea>
            </div>
            <div class="mb-3">
              <label for="vehicleNumber" class="form-label">Vehicle Number</label>
              <input type="text" class="form-control" id="vehicleNumber" placeholder="Enter Vehicle Number" required>
            </div>
            <div class="mb-3">
              <label for="vehicleType" class="form-label">Vehicle Type</label>
              <select class="form-select" id="vehicleType" required>
                <option value="">Select Vehicle Type</option>
                <option value="Hatchback">Auto</option>
                <option value="Sedan">Sedan</option>
                <option value="SUV">SUV</option>
                <option value="Hatchback">Hatchback</option>
               
              </select>
            </div>
           
            <div class="mb-3">
              <label for="vehicleNumber" class="form-label">Driver's License Expiry Date</label>
              <input type="text" class="form-control" id="vehicleNumber" placeholder="Enter License Expiry Date" required>
            </div>
            <div class="mb-3">
              <label for="pucDate" class="form-label">PUC Last Updated Date</label>
              <input type="date" class="form-control" id="pucDate" required>
            </div>
           
         
            <div class="mb-3">
              <label for="generateId" class="form-label">Generate ID</label>
              <div class="input-group">
                  <div class="position-relative w-100">
                      <input type="text" class="form-control pe-5" id="generateId" placeholder="Click to Generate ID" readonly onclick="generateUniqueId()">
                      <div class="position-absolute top-50 end-0 translate-middle-y me-2">
                          <i class="spinner-border spinner-border-sm text-primary d-none" id="loadingIcon"></i>
                      </div>
                  </div>
              </div>
          </div>
         
          <script>
              function generateUniqueId() {
                  let idField = document.getElementById("generateId");
                  let spinner = document.getElementById("loadingIcon");
         
                  // Show spinner
                  spinner.classList.remove("d-none");
         
                  // Simulate an ID generation process
                  setTimeout(() => {
                      idField.value = "DR-" + Math.floor(100000 + Math.random() * 900000); // Generates a unique 6-digit ID
                      spinner.classList.add("d-none"); // Hide spinner after generating ID
                  }, 1500);
              }
          </script>
         
         
         
            <div class="text-center">
              <button type="reset" class="btn btn-light">Clear Form</button>
              <a href="upload_docs.html" class="btn btn-primary" onclick="return true;">Next</a>


       
            </div>
          </form>
        </div>
      </div>

      <!-- partial:partials/_footer.html -->
      <footer class="footer">
        <div class="d-sm-flex justify-content-center justify-content-sm-between">
          <span class="text-muted text-center text-sm-left d-block d-sm-inline-block">Copyright © 2025 <a href="" target="_blank">Treepzy</a>. All rights reserved.</span>
     
        </div>
      </footer>
                <!-- partial -->
              </div>
       
            </div>
            <!-- page-body-wrapper ends -->
          </div>
          <!-- container-scroller -->
          <!-- plugins:js -->
          <script src="assets/vendors/js/vendor.bundle.base.js"></script>
          <!-- endinject -->
          <!-- Plugin js for this page -->
          <script src="assets/vendors/chart.js/Chart.min.js"></script>
          <script src="assets/vendors/bootstrap-datepicker/bootstrap-datepicker.min.js"></script>
          <script src="assets/vendors/flot/jquery.flot.js"></script>
          <script src="assets/vendors/flot/jquery.flot.resize.js"></script>
          <script src="assets/vendors/flot/jquery.flot.categories.js"></script>
          <script src="assets/vendors/flot/jquery.flot.fillbetween.js"></script>
          <script src="assets/vendors/flot/jquery.flot.stack.js"></script>
          <script src="assets/vendors/flot/jquery.flot.pie.js"></script>
          <script src="assets/js/jquery.cookie.js" type="text/javascript"></script>
          <!-- End plugin js for this page -->
          <!-- inject:js -->
          <script src="assets/js/off-canvas.js"></script>
          <script src="assets/js/hoverable-collapse.js"></script>
          <script src="assets/js/misc.js"></script>
          <script src="assets/js/settings.js"></script>
          <script src="assets/js/todolist.js"></script>
          <!-- endinject -->
          <!-- Custom js for this page -->
          <script src="assets/js/dashboard.js"></script>
          <script src="assets/js/proBanner.js"></script>
          <!-- End custom js for this page -->
        </body>
      </html>
