<template>
  <div>
       <footer>
      <div class="lux2 text-center mt-5">
        <img src="../assets/img/logo.png" />
      </div>

      <div class="list mt-5 justify-content-around d-flex mb-5">
        <div class="d-flex flex-column">
          <li><b>Overview</b></li>
          <br />
          <a class="text-dark" href="./shipping.html"><li>Shipping</li></a>
          <li>Refund</li>
          <li>Promotion</li>
        </div>
        <div class="d-flex flex-column">
          <li><b>Company</b></li>
          <br />
          <li>About</li>
          <li>Career</li>
          <li>Contact Us</li>
        </div>
        <div class="d-flex flex-column">
          <li><b>Explore</b></li>
          <br />
          <li>Terms & Condition</li>
          <li>Privacy Policy</li>
          <li>For Developer</li>
        </div>
        <div class="d-flex flex-column">
          <li><b>Special Letter</b></li>
          <br />
          <form class="form-inline my-2 my-lg-0" id="formEmail">
            <input
              id="inputEmail"
              class="form-control mr-sm-2"
              name="inputNama"
              type="email"
              placeholder="Your Email Addres"
              aria-label="Search"
              required
            />
            <button
              class="btn btn-outline-success my-2 my-sm-0"
              type="submit"
              id="btnAlert"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-send"
                viewBox="0 0 16 16"
              >
                <path
                  d="M15.854.146a.5.5 0 0 1 .11.54l-5.819 14.547a.75.75 0 0 1-1.329.124l-3.178-4.995L.643 7.184a.75.75 0 0 1 .124-1.33L15.314.037a.5.5 0 0 1 .54.11ZM6.636 10.07l2.761 4.338L14.13 2.576 6.636 10.07Zm6.787-8.201L1.591 6.602l4.339 2.76 7.494-7.493Z"
                />
              </svg>
            </button>
          </form>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'FooterComponent',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
