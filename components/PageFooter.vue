<template>
  <div class="mt-5">
    <footer class="page-footer">
      <b-container>
        <b-row>
          <b-col sm="12" md="4" class="mt-3">
            <b-row>
              <b-col offset="3" cols="6" class="footer-image"></b-col>
            </b-row>
            <b-row class="mb-3">
              <b-col
                cols="12"
                class="text-center mt-2"
              >We help accelerate agriculture transformation in Tanzania through agricultural development initiatives to increase productivity and improve access to inputs and finance for value chain actors.</b-col>
            </b-row>
          </b-col>
          <b-col sm="12" md="4" class="mt-3">
            <h3>Contact Us</h3>
            <b-row class="mt-3">
              <b-col cols="2">
                <b-img width="30" src="../static/icons/location.png" fluid alt="location"></b-img>
              </b-col>
              <b-col cols="10">457 Mikocheni Street, Mikocheni B</b-col>
            </b-row>
            <b-row class="mt-3">
              <b-col cols="2">
                <b-img width="30" src="../static/icons/call.png" fluid alt="call"></b-img>
              </b-col>
              <b-col cols="10">+255 22 2780 504</b-col>
            </b-row>
            <b-row class="mt-3">
              <b-col cols="2">
                <b-img width="30" src="../static/icons/email.png" fluid alt="email"></b-img>
              </b-col>
              <b-col cols="10">info@britentz.org</b-col>
            </b-row>
          </b-col>
          <b-col sm="12" md="4" class="mt-3">
            <h3>Social Links</h3>
            <b-row class="mt-3">
              <b-col cols="2">
                <b-img width="30" src="../static/icons/social/linkedin.png" fluid alt="linkedin"></b-img>
              </b-col>
              <b-col cols="10"> <p class="lead">LinkedIn</p> </b-col>
            </b-row>
            <b-row class="mt-3">
              <b-col cols="2">
                <b-img width="30" src="../static/icons/social/instagram.png" fluid alt="Instagram"></b-img>
              </b-col>
              <b-col cols="10"> <p class="lead">Instagram</p> </b-col>
            </b-row>
            <b-row class="mt-3">
              <b-col cols="2">
                <b-img width="30" src="../static/icons/social/twitter.png" fluid alt="Twitter"></b-img>
              </b-col>
              <b-col cols="10"> <p class="lead">Twitter</p> </b-col>
            </b-row>
            <b-row class="mt-3">
              <b-col cols="2">
                <b-link to="https://youtu.be/cS3v3DuhWqE">
                  <b-img width="30" src="../static/icons/social/youtube.png" fluid alt="YouTube"></b-img>
                </b-link>
              </b-col>
              <b-col cols="10"> <p class="lead">Youtube</p></b-col>
            </b-row>
          </b-col>
        </b-row>
      </b-container>
    </footer>
    <div class="copyright">
      <p class="text-center">Copyright &copy;{{date}} All rights reserved</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "pagefooter",
  data() {
    return {
      date: new Date().getFullYear()
    };
  }
};
</script>

<style>
.page-footer {
  padding: 2.5rem;
  color: #fafafa;
  background-image: url("../static/img/footer.jpg");
  background-size: cover;
  background-position: top;
  background-repeat: no-repeat;
}

.footer-image {
  height: 5rem;
  background-image: url("../static/img/Logo.png");
  background-color: #f7941c;
  background-position: center;
  background-size: 9rem;
  background-repeat: no-repeat;
}

.copyright {
  padding: 1rem;
  padding-bottom: 0.4rem;
  color: #fafafa;
  background-color: #026939;
  font-weight: bold;
}
</style>