<template>
   <v-app>
       <v-main>
           <v-container class="fill-height" fluid>
               <v-row align="center" justify="center" dense>
                   <v-col cols="12" sm="8" md="4" lg="4">
                       <v-card elevation="0">
                           <a href="https://edu-fedorae.netlify/app" name="Kisich laravel" title="Kisich laravel" target="_blank">
                           <v-img src="@/assets/logo2.png" alt="Kisich laravel" contain height="200"></v-img>
                           </a>
                         <v-card-text>
                             <v-form>
                                 <v-text-field label="Enter your Email" 
                                 name="Email" prepend-inner-icon="mdi-mail" type="email" class="rounded-0" outlined></v-text-field>
                                 <v-text-field label="Enter your password" name="passowrd" prepend-inner-icon="mdi-lock" type="password" 
                                 suffix="Forgot password" rounded="0" outlined></v-text-field>
                                 <v-btn class="rounded-0" color="#000000" x-large block dark>Login</v-btn>
                                 <v-card-actions class="text--secondary">
                                    <v-checkbox color="#000000" label="Remember me"></v-checkbox>
                                    <v-spacer></v-spacer>
                                    <!-- <router-link :to="{name: 'Sign up' }">Sign up</router-link> -->
                                    No Account? <a href="#" class="pl-2" color=" #000000" >Sign up</a>

                                 </v-card-actions>
                             </v-form>
                         </v-card-text>
                         <v-card-actions class="ml-6 mr-6 text center">
                             <p>By continuing,you agree to <a href="#">Kisich Laravel policies</a></p>

                         </v-card-actions>
                       </v-card>
                   </v-col>

               </v-row>

           </v-container>
       </v-main>

    </v-app> 
</template>

<script>
export default {

}
</script>

<style lang="css" scoped>

</style>