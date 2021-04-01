<template lang="pug">    
body 
    div(class="login-container")
        div(class="login-panel block") 

            // login header 
            h2(class="login-header titular") WELCOME 

            // login body 
            div(class="login-body") 

                // email input 
                div(class="input-container") 
                    input(type="email" placeholder="email" class="email text-input")
                    div(class="input-icon envelope-icon-acount") 
                        span(class="fontawesome-envelope scnd-font-color")

                // password input 
                div(class="input-container")
                    input(type="password" placeholder="password" class="password text-input")
                    div(class="input-icon password-icon") 
                        span(class="fontawesome-lock scnd-font-color")
                        
            // login footer 
            div(class="login-footer") 
                a(class="sign-in button", href="../") SIGN IN
</template>
