# Guide of styles from the route directory

 ## Grid content and example of use
 + Container  
 > Creates a container perfectryl centered and adaptable to mobile devices  

 + Grid System based on flexbox and a 12 columns based as well as row
 > 
    <div class="container">
        <h2 class="mb-2">Grid System</h2>
        <div class="row gap-2 justify-center">
            <div class="col-12 col-xs-6 col-sm-6 col-md-6">
                <div class="card">
                    <h3 class="card-title">Hello, ninjas</h3>
                    <p class="card-body">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col-12 col-xs-6 col-sm-6 col-md-6">
                <div class="card">
                    <h3 class="card-title">Hello, ninjas</h3>
                    <p class="card-body">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>
        </div>
    </div>




 ## Utilities content and example of use
 CONTENT : 
 ***
 ***
+ PADDING : .p[0-5]  
    - left :  ` .pl[0-5]  `
    - right:  ` .pr[0-5]  `
    - top:` .pt[0-5]  `
    - bottom: ` .pb[0-5]  `
    ***
+ OPACITY : .o[10 - 100]  
    ***
+ MARGIN : m:.m[0-5]
    - left :` .ml[0-5]`
    - right:` .mr[0-5]`
    - top:` .mt[0-5]`
    - bottom:` .mb[0-5]`
    ***
+ BORDER-RADIUS
    - `.br-none`
    - `.br-xs`
    - `.br-sm`
    - `.br-lg`
    - `.br-full`
    ***
+ DISPLAY
    - `n => .display-none`
    - `b => .display-block`
    - `f => .display-flex`
    - `i => .display-inline`
    - `i-b => .display-inline-block`
    ***
+ FONT-SIZE
    - `.font-sm`
    - `.font-md`
    - `.font-lg`
    - `.font-xl`
    - `.font-xxl`


# Customizing
Si quieres realizar cambios a las variables edita directamente el archivo de scss/index.scss y coloca previamente las variables que quieres sobreescribir

> 
    $primary: red;
    $secondary: lightpink;
    @import '../personal-library';  

