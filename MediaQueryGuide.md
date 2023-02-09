# Media Query 

    $breakpoint : (xs: "480px",
        ss: "620px",
        sm: "768px",
        md: "1024px",
        lg: "1200px",
        xl: "1700px",
    );

## Uso : 
    $primary: red;
    $secondary: lightpink;
    @import '../personal-library';
    @include xs {
        .trialContainer{
            background-color: deeppink;
            width: 200px;
            height: 200px;
        }
    }

    @include ss {
        .trialContainer{
            background-color: red;
            width: 100px;
            height: 100px;
        }
    }
