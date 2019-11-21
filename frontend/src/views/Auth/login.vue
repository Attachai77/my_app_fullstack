<template>
  <mdb-container>
    <mdb-row class="mt-5 align-items-center justify-content-start">
      <h4 class="demo-title"><strong>Fullstack App</strong></h4>
      <a href="https://mdbootstrap.com/docs/vue/forms/basic/?utm_source=DemoApp&utm_medium=MDBVueFree" waves-fixed class="border grey-text px-2 border-light rounded ml-2" target="_blank"><mdb-icon icon="graduation-cap" class="mr-2"/>Docs</a>
    </mdb-row>
    <hr />
    <mdb-container>
      <section class="demo-section">
        <mdb-row>
          <mdb-col md="12" offset-md="0" lg="6" offset-lg="3">
            <mdb-card>
              <mdb-card-body>
                <form>
                  <p class="h4 text-center mb-4">Sign in</p>
                  <div class="grey-text">
                    <mdb-input label="Your username or email" icon="envelope" type="text"/>
                    <mdb-input label="Your password" icon="lock" type="password"/>
                  </div>
                  <div class="text-center">
                    <mdb-btn>Login</mdb-btn>
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
      
    };
  }
};
</script>

<style scoped>
</style>
