<template>
  <v-container>
    <v-layout wrap style="margin-top: 150px;">
      <v-flex sm12 md6 offset-md3>
        <v-card>
          <v-col md="12">
            <v-row>
              <div>
                <br />
                <br />
                <b-row class="my-1">
                  <b-col sm="3">
                    <label for="input-valid">Nama Lengkap :</label>
                  </b-col>
                  <b-col sm="3">
                    <b-form-input id="input-valid" :state="true" placeholder="Valid input"></b-form-input>
                  </b-col>
                </b-row>
                <b-row class="my-1">
                  <b-col sm="3">
                    <label for="input">Alamat Lengkap :</label>
                  </b-col>
                  <b-col sm="3">
                    <b-form-input id="input" :state="true" placeholder="input"></b-form-input>
                  </b-col>
                </b-row>
                <v-col md="12">
                  <v-row>
                    <v-btn>Simpan</v-btn>
                  </v-row>
                </v-col>
              </div>
            </v-row>
          </v-col>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>


<script>
export default {
  data() {
    return {
      text: "",
    };
  },
};
</script>

