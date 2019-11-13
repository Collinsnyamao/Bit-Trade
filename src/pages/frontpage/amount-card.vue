<template>
  <card class="card" title="Buy BTC">
      <form @submit.prevent>
        <div class="row">
          <div class="col-md-12">
            <fg-input type="text"
                      label="Amount"
                      placeholder="Enter amount"
                      class="text-center centered-input"
            >
            </fg-input>
            <p>{{ amount }}</p>
          </div>
        </div>
      </form>
  </card>
</template>

<script>
    export default {
        name: "amount-card",
        data(){
            return{
                user: {
                    company: "Paper Dashboard",
                    username: "michael23",
                    email: "",
                    firstName: "Chet",
                    lastName: "Faker",
                    address: "Melbourne, Australia",
                    city: "Melbourne",
                    postalCode: "",
                    aboutMe: `We must accept finite disappointment, but hold on to infinite hope.`
                }
            }
        }
    }
</script>

<style scoped>
  .centered-input input {
    text-align: center
  }
</style>
