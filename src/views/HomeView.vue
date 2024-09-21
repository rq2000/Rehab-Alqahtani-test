<template>
  <div class="container-80">
    <div class="row">
      <!-- Sidebar -->
      <nav id="sidebar" class="col-md-3 col-lg-2 d-md-block bg-light sidebar">
  <div class="position-sticky">
    <ul class="nav flex-column">

      <img src="@/assets/nqq2.svg" alt="logo" class="me-5 mt-4" />
        
        <li class="nav-item">
        <a class="nav-link active text-warning" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
          <img src="@/assets/ja.svg" alt="Home" class="me-3" /> <img src="@/assets/homeT.svg" alt="Home" class="me-3" /> Home</a></li>

    <li class="nav-item ">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/orderT.svg" alt="Orders" class="ms-4" /> Orders</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/revT.svg" alt="Reviews" class="ms-4" /> Reviews</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/cliT.svg" alt="Clients" class="ms-4" /> Clients</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/compT.svg" alt="Companies" class="ms-4" /> Companies</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/truT.svg" alt="Trucks" class="ms-4" /> Trucks</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/brnT.svg" alt="Brands" class="ms-4" /> Brands</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/ciT.svg" alt="Cities" class="ms-4" /> Cities</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/orderT.svg" alt="Content Management" class="ms-4" /> Content Management</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <div class="d-flex align-items-center"><img src="@/assets/preT.svg" alt="Permissions" class="ms-4" />
          <span class="me-2">Permissions</span><i class="fas fa-chevron-down ms-2"></i></div></a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/sysT.svg" alt="System Management" class="ms-4" /> System Management</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/tranT.svg" alt="Translation" class="ms-4" /> Translation</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/conT.svg" alt="Contact" class="ms-4" /> Contact
</a></li>

    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left; padding: 18px; font-weight: bold;">
        <img src="@/assets/crT.svg" alt="Client Review" class="ms-4" /> Client Review
      </a>
    </li>
  </ul> 
  </div>
</nav>
      <!--  اعلى الصفحة -->
      <main class="col-md-9 ms-sm-auto col-lg-10 px-4">
        <div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-3 pb-2 mb-3">
        <div>
          <h5 style="font-weight: bold; color: #353535;">Dashboard Overview</h5>
          <div class="d-flex justify-content-start">
            <span class="text-start" style="color: #7e7e7e;">26 Sep 2023</span>
          </div>
        </div>
          <div class="btn-toolbar mb-2 mb-md-0">
            <div class="btn-group me-2">
              
              <div class="d-flex align-items-center">
  <span class="ms-2"></span>
  <img src="@/assets/grs.svg" alt="old mt-4" style="margin-right: 10px;" />
<img src="@/assets/line.svg" alt="old mt-4" style="margin-right: 10px;" />
<img src="@/assets/po3.svg" alt="old mt-4" />

<span data-bs-toggle="dropdown" role="button" class="d-flex align-items-center">
    INGOUDE COMPANY
    <span class="fas fa-chevron-down ms-2"></span>
</span>

</div>
</div>
 </div>
 </div>       
        <div class="d-flex justify-content-between mb-4 flex-row-reverse">
  <span></span>
  <div class="d-flex align-items-center">
    <div class="form-check form-check-inline">
      <input class="form-check-input" type="radio" id="all" name="filter" checked />
      <label class="form-check-label" for="all">All</label>
    </div>
    <div class="form-check form-check-inline">
      <input class="form-check-input" type="radio" id="" name="filter" />
      <label class="form-check-label" for="option2"></label>
    </div>
    <!--التاريخ 1-->
    <div class="input-group mx-2" style="width: 180px;">
  <span class="input-group-text" id="fromLabel" style="font-size: 12px;">From</span>
  <input class="form-control" type="date" id="dateFieldStart" aria-describedby="fromLabel" 
  style="font-size: 12px;" value="2023-09-26" lang="en" /></div>
<!--التاريخ 2 -->
<div class="input-group mx-2" style="width: 180px;">
  <span class="input-group-text" id="toLabel" style="font-size: 12px;">To</span>
  <input class="form-control" type="date" id="dateFieldEnd" aria-describedby="toLabel" 
       style="font-size: 12px;" value="2023-09-26" lang="en" />

  <button class="btn ms-2" style="height: 30px; font-size: 12px; background-color: #FBA81A; color: white; border: none;">Find</button>
</div>
</div>
        </div>
        <!--  الكارد الاربعه الاولى -->
        <div class="row mb-4">
          <div class="col-md-3">
  <div class="card custom-card text-left">
    <div class="card-body">
      <h5 class="card-title text-secondary" style="font-size: 16px; text-align: left;">
        <img src="@/assets/orderN.svg" alt="El" class="me-1" /> Order Number</h5>
      <p class="card-text" style="font-size: 24px;">
        <span style="color: black;font-size: 30px;">1000</span> <sub style="font-size: 10px; color: gray;">Orders</sub>
      </p>
    </div>
  </div>
</div>
<div class="col-md-3">
  <div class="card custom-card text-left">
    <div class="card-body">
      <h6 class="card-title text-secondary" style="font-size: 16px; text-align: left;">
        <img src="@/assets/compN.svg" alt="El" class="me-1" /> Company Number
      </h6>
      <p class="card-text" style="font-size: 24px;">
        <span style="color: black;font-size: 30px;">1000000</span> <sub style="font-size: 10px; color: gray;">SR</sub>
      </p>
    </div>
  </div>
</div>
<div class="col-md-3">
  <div class="card custom-card text-left">
    <div class="card-body">
      <h6 class="card-title text-secondary" style="font-size: 16px; text-align: left;">
        <img src="@/assets/dri.svg" alt="El" class="me-1" /> Drivers Number
      </h6>
      <p class="card-text" style="font-size: 24px;">
        <span style="color: black;font-size: 30px;">500</span> <sub style="font-size: 10px; color: gray;">Driver</sub>
      </p>
    </div>
  </div>
</div>
  <div class="col-md-3">
    <div class="card custom-card text-left">
      <div class="card-body">
        <h6 class="card-title text-dark" style="font-size: 16px; text-align: left;">
          <img src="@/assets/tot.svg" alt="El" class="me-1" style="color: gray;" />  
          <span style="color: gray;">Total Sales</span>
        </h6>
        <p class="card-text" style="font-size: 24px;">
          <span style="color: black;font-size: 30px;">500</span> <sub style="font-size: 10px; color: gray;">Driver</sub>
        </p>
      </div>
    </div>
  </div>
</div>
        <!-- الكارد الاربعه في الصف الثاني-->
        <div class="row mb-4">
  <div class="col-md-3">
    <div class="card text-center">
      <div class="card-body">
        <h5 class="card-title text-center mb-3" style="font-size: 20px;">Waiting For Loading</h5>
        <div class="d-flex justify-content-center align-items-center">
          <div class="position-relative">
            <img src="@/assets/rs.svg" alt="old mt-4" class="me-3n"/>
            <div class="position-absolute top-50 start-50 translate-middle">
              <span style="font-size: 20px;">80</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="col-md-3">
    <div class="card text-center">
      <div class="card-body">
        <h5 class="card-title text-center mb-3" style="font-size: 20px;">Waiting For Arrive</h5>
        <div class="d-flex justify-content-center align-items-center">
          <div class="position-relative">
            <img src="@/assets/rs.svg" alt="old mt-4" class="me-3n"/>
            <div class="position-absolute top-50 start-50 translate-middle">
              <span style="font-size: 20px;">80</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="col-md-3">
    <div class="card text-center">
      <div class="card-body">
        <h5 class="card-title text-center mb-3" style="font-size: 20px;">Completed</h5>
        <div class="d-flex justify-content-center align-items-center">
          <div class="position-relative">
            <img src="@/assets/rs.svg" alt="old mt-4" class="me-3n"/>
            <div class="position-absolute top-50 start-50 translate-middle">
              <span style="font-size: 20px;">80</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="col-md-3">
    <div class="card text-center">
      <div class="card-body">
        <h5 class="card-title text-center mb-3" style="font-size: 20px;">Canceled</h5>
        <div class="d-flex justify-content-center align-items-center">
          <div class="position-relative">
            <img src="@/assets/rs.svg" alt="old mt-4" class="me-3n"/>
            <div class="position-absolute top-50 start-50 translate-middle">
              <span style="font-size: 20px;">80</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
        <!-- الكارد الثلاثه الصف الاخير    -->

        <div class="row">
    <div class="col-md-6">
        <div class="card card-small h-80">
            <div class="card-body d-flex flex-column">
              <h5 class="card-title text-left mb-3" style="font-weight: 600; color: #353535; 
              font-family:sans-serif">TOP 5 Companies</h5>
              <div class="flex-grow-1">
                  <table class="table mt-0" style="line-height: 1;">
    <thead>
        <tr>
            <th style="color: gray; text-align: left;">Company Name</th>
            <th style="color: gray; text-align: left;">Order Qty</th>
            <th style="color: gray; text-align: left;">Amount</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="color: black; padding: 0.57rem;">Gillette</td>
            <td style="color: black; padding: 0.57rem;">5000</td>
            <td style="color: black; padding: 0.57rem;">50000 SR</td>
        </tr>
        <tr>
            <td style="color: black; padding: 0.57rem;">Louis Vuitton</td>
            <td style="color: black; padding: 0.57rem;">3000</td>
            <td style="color: black; padding: 0.57rem;">50000 SR</td>
        </tr>
        <tr>
            <td style="color: black; padding: 0.57rem;">Johnson & Johnson</td>
            <td style="color: black; padding: 0.57rem;">2000</td>
            <td style="color: black; padding: 0.57rem;">50000 SR</td>
        </tr>
        <tr>
            <td style="color: black; padding: 0.57rem;">Nintendo</td>
            <td style="color: black; padding: 0.57rem;">1000</td>
            <td style="color: black; padding: 0.57rem;">50000 SR</td>
        </tr>
    </tbody>
</table>

                </div>
            </div>
        </div>
    </div>
    <div class="col-md-3">
        <div class="card text-center h-80">
            <div class="card-body d-flex flex-column">
                <h5 class="card-title text-center mb-3" style="font-size: 20px;">Order repeated</h5>
                <div class="d-flex justify-content-center align-items-center flex-grow-1">
                    <div class="position-relative">
                        <img src="@/assets/rs.svg" alt="old mt-4" class="me-3n"/>
                        <div class="position-absolute top-50 start-50 translate-middle">
                            <span style="font-size: 20px;">80%</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="col-md-3">
        <div class="card text-center h-80">
            <div class="card-body d-flex flex-column">
                <h5 class="card-title text-center mb-3" style="font-size: 20px;">Commission</h5>
                <div class="d-flex justify-content-center align-items-center flex-grow-1">
                    <div class="position-relative">
                        <img src="@/assets/pr.svg" alt="old mt-4" class="me-3n"/>
                        <div class="position-absolute top-50 start-50 translate-middle">
                            <span style="font-size: 20px;">127k</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</main>
</div>
</div>
</template>

<script>
export default {
  name: 'HomeView',
};
function getFormattedDate() {
    const options = { day: '2-digit', month: 'short', year: 'numeric' };
    const today = new Date();
    return today.toLocaleDateString('en-GB', options);
}
console.log(getFormattedDate());
</script>

<style scoped>
body {
  background-color:aliceblue;
}
.sidebar {
  position: fixed;
  top: 0;
  bottom: 0;
  z-index: 100;
  height: 100%;
  overflow-y: auto;
}
.card {
  border: 1px solid #dee2e6;
}
.card {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.card-small {
  padding: 0px; /* زيادة حجم الحشو لزيادة حجم الكارد */
}
.card-title {
  margin-bottom: 0px;
  font-size: 15px;
  font-weight: none;
}
.table {
  font-size: 14px;
  border-collapse: collapse; /* إزالة تكرار الحدود بين خلايا الجدول */
}
.table th, .table td {
  text-align: left;
  border: none; /* إزالة الحدود من الخلايا */
  padding: 12px; /* إضافة مساحة padding لتحسين العرض */
}
.table thead {
  background-color:#f8f9fa;
}
.form-check-input:checked {
  background-color: #FBA81A; /* لون الخلفية عند التحديد */
  border-color: #f7f5f3; /* لون الحدود عند التحديد */
}
.card-title {
  text-align: left;
}
.card-body {
  text-align: left;
}
.custom-number {
  font-family: 'Arial', sans-serif; /* استبدل بـ 'خطك المفضل' */
}
.form-check {
  margin-bottom: 1rem;
}
</style>