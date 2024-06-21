<template>
  <div class="fitur" style="background-color: #222831; min-height: 100vh; padding-top: 150px; justify-content: center; align-items: center">
    <div class="container">
      <div class="card" style="background-color: #222831; box-shadow: 1px 1px 20px 2px black; height: 55vh; width: 500px; margin-left: 360px">
        <div class="card-header text-center" style="font-weight: 600; color: orangered; font-size: 30px; letter-spacing: 2px">Fitur</div>
        <div class="card-body">
          <div class="Container">
            <div class="input-group mb-3">
              <input type="text" class="form-control" placeholder="Nama anda" aria-label="Name" aria-describedby="basic-addon1" style="box-shadow: 0px 0px 0px orangered; border: none" />
            </div>
            <div class="input-group mb-3">
              <input type="text" class="form-control" placeholder="Merek" aria-label="Merek" aria-describedby="basic-addon2" style="box-shadow: 0px 0px 0px orangered; border: none" />
            </div>
            <div class="input-group mb-3">
              <div class="row" style="color: white">
                <div class="col">
                  <div class="form-check">
                    <input class="form-check-input" type="checkbox" value="" style="background-color: orangered; border: 1px solid orangered; box-shadow: 1px 1px 1px orangered" />
                    <label class="form-check-label" for="flexCheckDefault"> Matic </label>
                  </div>
                </div>
                <div class="col">
                  <div class="form-check">
                    <input class="form-check-input" type="checkbox" value="" style="background-color: orangered; border: 1px solid orangered; box-shadow: 1px 1px 1px orangered" />
                    <label class="form-check-label" for="flexCheckChecked"> Manual </label>
                  </div>
                </div>
                <div class="col">
                  <div class="form-check">
                    <input class="form-check-input" type="checkbox" value="" style="background-color: orangered; border: 1px solid orangered; box-shadow: 1px 1px 1px orangered" />
                    <label class="form-check-label" for="flexCheckDefault"> Listrik </label>
                  </div>
                </div>
              </div>
            </div>
            <div class="input-group mb-3">
              <input type="text" class="form-control" placeholder="CC" aria-label="CC" aria-describedby="basic-addon2" />
            </div>
          </div>
          <div class="row">
            <div class="col"></div>
          </div>
          <div class="dropdown mb-3">
            <button class="btn dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false" style="background-color: orangered; color: white">Tahun</button>
            <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
              <li><a class="dropdown-item" href="#">2019-2024</a></li>
              <li><a class="dropdown-item" href="#">2013-2018</a></li>
              <li><a class="dropdown-item" href="#">2008-2012</a></li>
            </ul>
          </div>
          <a href="#" class="btn" style="background-color: orangered; color: white; margin-left: 365px">Lihat Hasil</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
