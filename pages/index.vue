<template>
  <div class="ma-15">
    <v-row>
      <v-sheet
        :width="$vuetify.breakpoint.mdAndUp ? '50%' : '100%'"
        color="transparent"
        class="pt-15"
      >
        <div class="text-h2 grey--text text--darken-3">
          Decentralized Risk Scoring Protocol
        </div>
        <div class="my-5 mb-10 text-h4 grey--text text--darken-3">
          For DeFi 2.0
        </div>
        <div class="mb-5 text-body-1 black--text">
          Increase trust and reputation in DeFi transactions by using credit
          scores to evaluate user's eligibility. <br/>Verifiable score calculated on
          a decentralized network on nodes supporting data from multiple chains.
          Based on user's financial data such as payment history, credit
          utilisation ratio, age of credit, and much more.
        </div>
        <v-btn class="mt-5 mr-3" rounded x-large 
          >Get Started</v-btn
        >
        <v-btn class="mt-5" rounded outlined light x-large 
          >Read the whitepaper</v-btn
        >
      </v-sheet>

      <v-img src="credit-score.png"></v-img>
    </v-row>

<div class="mt-15">
    <div class="text-h4 pt-15 mb-5 black--text">Supported by</div>
    <div class="d-md-flex">
      <img class="logo" src="logo_nm.png"/>
      <img class="logo" src="https://assets.website-files.com/5ea98076e2f684f39f95888f/5ea98076e2f684b2239588a6_logo%20hoover.svg"/>
    </div>
    </div>
  </div>
</template>


<style scoped>
.logo{
  width: 300px;
  height: auto;
  margin-right: 40px;
  margin-top: 10px
}
</style>