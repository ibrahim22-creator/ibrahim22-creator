@keyframes cursor{
    to{
        border-left: 3px solid #b74b4b;
    }
}

@keyframes words{
    0%, 20%{
        content: "SMIT student";
    }
    21%, 40%{
        content: "Developer";
    }
    41%, 60%{
        content: "Web developer";
    }
    61%, 80%{
        content: "student";
    }
    81%, 100%{
        content: "MUSLIM";
    }
}

@media (max-width: 1000px){
    .home{
        gap: 4rem;
    }
}

@media(max-width:995px){
    .home{
        flex-direction: column;
        margin: 5rem 4rem;
    }

    .home .home-content h3{
        font-size: 2.5rem;
    }

    .home-content h1{
        font-size: 5rem;
    }

    .home-img img{
        width: 70vw;
        margin-top: 4rem;
    }
}
