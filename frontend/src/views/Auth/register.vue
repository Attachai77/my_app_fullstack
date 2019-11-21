<template>
  <mdb-container>
    <mdb-row class="mt-5 align-items-center justify-content-start">
      <h4 class="demo-title"><strong>Forms</strong></h4>
      <a href="https://mdbootstrap.com/docs/vue/forms/basic/?utm_source=DemoApp&utm_medium=MDBVueFree" waves-fixed class="border grey-text px-2 border-light rounded ml-2" target="_blank"><mdb-icon icon="graduation-cap" class="mr-2"/>Docs</a>
    </mdb-row>
    <hr />
    <mdb-container>
      <section class="demo-section">
          <mdb-row>
            <mdb-col md="6">
              <mdb-card>
                <mdb-card-body>
                  <form>
                    <p class="h4 text-center py-4">Sign up</p>
                    <div class="grey-text">
                      <mdb-input label="Your name" icon="user" group type="text" validate error="wrong" success="right"/>
                      <mdb-input label="Your email" icon="envelope" group type="email" validate error="wrong" success="right"/>
                      <mdb-input label="Confirm your email" icon="exclamation-triangle" group type="text" validate error="wrong" success="right"/>
                      <mdb-input label="Your password" icon="lock" group type="password" validate/>
                    </div>
                    <div class="text-center py-4 mt-3">
                      <mdb-btn color="cyan" type="submit">Register</mdb-btn>
                    </div>
                  </form>
                </mdb-card-body>
              </mdb-card>
            </mdb-col>
          </mdb-row>
      </section>
    </mdb-container>
  </mdb-container>
</template>

<script>
import { mdbContainer, mdbRow, mdbCol, mdbInput, mdbBtn, mdbIcon, mdbCard, mdbCardBody } from 'mdbvue';

export default {
  name: 'FormsPage',
  components: {
    mdbContainer,
    mdbRow,
    mdbCol,
    mdbInput,
    mdbBtn,
    mdbIcon,
    mdbCard,
    mdbCardBody
  },
  data() {
    return {
      showModal: false,
      guests: 4
    };
  }
};
</script>

<style scoped>
</style>
