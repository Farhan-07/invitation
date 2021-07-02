<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invitation to Farhan's presentation</title>
    <link rel="icon" href="presentation.svg" type="image/x-icon">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Khand:wght@300;500&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');


        ::selection {
            color: white;
            background: #f9a826;
            font-size: 4rem;
        }

        /* width */
        ::-webkit-scrollbar {
            width: 20px;
        }

        /* Track */
        ::-webkit-scrollbar-track {
            background: transparent;
            border-radius: 10px;
        }

        /* Handle */
        ::-webkit-scrollbar-thumb {
            background: #F9A826;
            border-radius: 10px;
        }

        /* Handle on hover */
        ::-webkit-scrollbar-thumb:hover {
            background: #F9A820;
        }

        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #f7f7f7;
            font-family: sans-serif;
            color: #383838;
            text-align: center;
            overflow-x: hidden;

        }

        .head {
            height: 100vh;
            width: 100%;
            place-items: center;
        }

        h1 {
            font-family: Poppins;
            font-variant: small-caps;
            text-align: center;
            font-size: 70px;
            padding-top: 40px;
            line-height: 80px;
            animation-name: h1a;
            animation-duration: 1s;
            animation-fill-mode: initial;
            animation-iteration-count: infinite;
            -webkit-animation-duration: 1s;
        }

        @keyframes h1a {
            0% {
                padding-top: -40000px;
            }

            100% {
                padding-top: 40px;
            }
        }

        .head p {
            font-family: Poppins;
            text-align: center;
            padding-top: 20px;
        }

        .head img {
            align-items: center;
            height: 400px;
            display: block;
            margin-left: auto;
            margin-right: auto;
            padding-top: 20px;
        }

        .about {
            height: 30vh;
            color: #f7f7f7;
            background-color: #383838;
        }

        .about h2 {
            font-family: Khand;
            font-size: 13.250517598343686vh;
            text-align: center;
            float: middle;
            padding-top: 10px;
        }



        .about img {
            height: 70vh;
            float: right;
        }

        h3 {
            text-align: center;
            font-family: 'Rubik', sans-serif;
            padding-top: 5vh;
            font-size: 7vh;
            place-items: center;
        }

        .one {
            height: 100vh;
        }

        .one .ppt {
            justify-content: center;
            height: 10vh;
        }

        .one .ppt img {
            height: 80vh;
            position: relative;
        }

        .one .ppt .img1 {
            animation-name: a1;
            animation: a1 1s linear 0s infinite alternate;
        }

        @keyframes a1 {
            0% {
                top: 0;
            }

            100% {
                top: 50px;
            }
        }

        .one .ppt .img2 {
            animation-name: a1;
            animation: a2 1s linear 0.25s infinite alternate;
        }

        .one .ppt .img3 {
            animation-name: a1;
            animation: a3 1s linear 0.5s infinite alternate;
        }

        .one .ppt .img4 {
            animation-name: a1;
            animation: a4 1s linear 0.75s infinite alternate;
        }

        .one .ppt .img5 {
            animation-name: a1;
            animation: a5 1s linear 1s infinite alternate;
        }

        @keyframes a2 {
            0% {
                top: 0;
            }

            100% {
                top: 50px;
            }
        }

        @keyframes a3 {
            0% {
                top: 0;
            }

            100% {
                top: 50px;
            }
        }

        @keyframes a4 {
            0% {
                top: 0;
            }

            100% {
                top: 50px;
            }
        }

        @keyframes a5 {
            0% {
                top: 0;
            }

            100% {
                top: 50px;
            }
        }

        .card {
            color: white;
            width: 9cm;
            height: 10cm;
            font-family: Montserrat;
            text-align: center;
        }

        .cards {
            margin: 0 auto;
            display: grid;
            grid-gap: 1rem;
            padding-top: 20px;
            place-items: center;
        }

        .card img {
            width: 8cm;
            height: 8cm;
            margin-top: 1rem;
        }

        .wave {
            white-space: nowrap;
            display: flex;
            height: 60vh;
            width: 100%;
            align-items: center;
            justify-content: center;
        }

        .content {
            position: relative;
            font-family: Poppins;
        }

        .content h2 {
            color: #000;
            font-size: 5rem;
            position: absolute;
            transform: translate(-50%, -50%);
            text-transform: uppercase;
            ;
        }

        .content h2:nth-child(1) {
            color: transparent;
            -webkit-text-stroke: 0.5px #000;
        }

        .content h2:nth-child(2) {
            color: #03a9f4;
            animation: animate 4s ease-in-out infinite;
            -webkit-text-stroke: 0.5px #000;

        }

        @keyframes animate {

            0%,
            100% {
                clip-path: polygon(0% 45%,
                        16% 44%,
                        33% 50%,
                        54% 60%,
                        70% 61%,
                        84% 59%,
                        100% 52%,
                        100% 100%,
                        0% 100%);
            }

            50% {
                clip-path: polygon(0% 60%,
                        15% 65%,
                        34% 66%,
                        51% 62%,
                        67% 50%,
                        84% 45%,
                        100% 46%,
                        100% 100%,
                        0% 100%);
            }
        }


        .time {
            height: 50vh;
            width: 100%;
            color: #000;
            font-family: Rubik;
            width: 100%;
            text-align: center;
        }

        .time h4 {
            font-family: Khand;
            color: #000;
            font-size: 5rem;
        }

        .surprise h5 {
            font-size: 4rem;
            font-family: Rubik;
            padding-top: 1vh;

        }

        .card p {
            text-align: center;
            place-items: center;
            color: #383838;
        }

        .topics {
            height: 160vh;
            width: 100%;
        }


        footer {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 20px;
            padding-top: 1px;
            border-top: 1px solid #000;
        }

        footer h9 {
            padding-top: 1px;
        }

        .square1,
        .square2,
        .square3 {
            width: 40px;
            height: 40px;
            position: absolute;
            z-index: 1;
            background: #f9a826;
            animation: t1 infinite;
            -webkit-animation-duration: 10s;
            animation-duration: 10s;
            -webkit-animation-delay: 0s;
            animation-delay: 0s;
        }

        .square1 {
            bottom: 300px;
            left: 300px;
            animation-delay: 0.25s;
        }

        .square2 {
            bottom: 500px;
            left: 80px;
            z-index: -1;
            animation-delay: 0s;
        }

        .square3 {
            bottom: 100px;
            left: 1100px;
            animation-delay: 0.5s;
        }

        @keyframes t1 {
            0% {
                transform: rotate(0deg);
            }

            25% {
                transform: rotate(180deg);
            }

            50% {
                transform: rotate(360deg);
            }

            75% {
                transform: rotate(180deg);
            }

            100% {
                transform: rotate(0deg);
            }
        }

        @media (max-width: 500px) {
            .scratchpad {
                width: 90%;
                height: auto !important;
            }
        }

        @media (max-width: 1070px) {
            .square1 {
                bottom: 200px;
                left: 150px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 500px;
                left: 80px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 800px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 1039px) {
            .square1 {
                bottom: 200px;
                left: 150px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 500px;
                left: 80px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 900px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 1030px) {
            .cards {
                place-items: center;
            }
        }

        @media (max-width: 1024px) {
            .head img {
                height: 300px;
            }
        }

        @media (max-width: 970px) {
            .square1 {
                bottom: 200px;
                left: 150px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 500px;
                left: 80px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 800px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 920px) {
            .about h2 {
                font-size: 10vh;
            }
        }

        @media (max-width: 870px) {
            .square1 {
                bottom: 200px;
                left: 150px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 500px;
                left: 70px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 700px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 770px) {
            .square1 {
                bottom: 200px;
                left: 150px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 500px;
                left: 70px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 600px;
                animation-delay: 0.5s;
            }

        }

        @media (max-width:730px) {
            .topics {
                height: 300vh;
            }
        }

        @media (max-width: 710px) {
            .about h2 {
                font-size: 8vh;
            }


        }

        @media (max-width: 685px) {}

        @media (max-width: 670px) {
            .square1 {
                bottom: 200px;
                left: 150px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 70px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 500px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 670px) {
            .square1 {
                bottom: 200px;
                left: 150px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 70px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 450px;
                animation-delay: 0.5s;
            }
        }



        @media (max-width: 640px) {
            .head img {
                height: 200px;
            }

        }

        @media (max-width: 620px) {
            .one .ppt img {
                height: 65vh;
            }
        }

        @media (max-width: 520px) {
            .square1 {
                bottom: 200px;
                left: 90px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 70px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 400px;
                animation-delay: 0.5s;
            }

            .one .ppt img {
                height: 60vh;
            }

        }

        @media (max-width: 570px) {
            .head img {
                height: 175px;
            }

            .about h2 {
                font-size: 6vh;
            }

            .content h2 {
                font-size: 4rem;
            }
        }

        @media (max-width: 480px) {
            .content h2 {
                font-size: 3.5rem;
            }

            .one .ppt img {
                height: 50vh;
            }

            .one {
                height: 70vh;
            }
        }

        @media (max-width:470px) {
            .topics {
                height: 310vh;
            }

            .time h4 {
                font-size: 4rem;
            }

            .time {
                height: 70vh;
            }

            .card {
                height: 9cm;
                width: 8cm;
            }

            .card img {
                height: 7cm;
                width: 7cm;
            }

            .topics {
                height: 290vh;
            }

            .square1 {
                bottom: 200px;
                left: 90px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 70px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 350px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 430px) {
            .square1 {
                bottom: 190px;
                left: 60px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 70px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 330px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 430px) {
            .square1 {
                bottom: 190px;
                left: 50px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 60px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 300px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 410px) {
            .content h2 {
                font-size: 3rem;
            }

            .one .ppt img {
                height: 45vh;
            }

            .one {
                height: 70vh;
            }
        }

        @media (max-width: 380px) {
            .head h1 {
                font-size: 60px;
            }

            .square1 {
                bottom: 150px;
                left: 50px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 60px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 300px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 370px) {
            .head h1 {
                font-size: 60px;
            }

            .square1 {
                bottom: 150px;
                left: 50px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 60px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 280px;
                animation-delay: 0.5s;
            }

            .one .ppt img {
                height: 40vh;
            }

            .one {
                height: 70vh;
            }
        }

        @media (max-width: 360px) {
            .content h2 {
                font-size: 2.5rem;
            }
        }

        @media (max-width: 350px) {
            .head h1 {
                font-size: 60px;
            }

            .square1 {
                bottom: 150px;
                left: 50px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 60px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 100px;
                left: 250px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 340px) {
            .head h1 {
                font-size: 50px;
            }

            .card {
                height: 8cm;
                width: 7cm;
            }

            .card img {
                height: 6cm;
                width: 6cm;
            }

            .time h4 {
                font-size: 3rem;
            }

            .about h2 {
                font-size: 5vh;
            }

            .topics {
                height: 260vh;
            }
        }

        @media (max-width: 330px) {
            .one .ppt img {
                height: 30vh;
            }

            .one {
                height: 50vh;
            }
        }

        @media (max-width: 320px) {
            .head h1 {
                font-size: 60px;
            }

            .square1 {
                bottom: 150px;
                left: 20px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 60px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 90px;
                left: 250px;
                animation-delay: 0.5s;
            }
        }

        @media (max-width: 315px) {
            .head h1 {
                font-size: 60px;
            }

            .square1 {
                bottom: 150px;
                left: 20px;
                animation-delay: 0.25s;
            }

            .square2 {
                bottom: 400px;
                left: 60px;
                z-index: -1;
                animation-delay: 0s;
            }

            .square3 {
                bottom: 90px;
                left: 250px;
                animation-delay: 0.5s;
            }

            .head h1 {
                font-size: 50px;
            }
        }

        @media (max-width: 310px) {
            .topics {
                height: 240vh;
            }
            .one .ppt img {
                height: 30vh;
                padding-top: 10px;
            }

            .one {
                height: 50vh;
            }
            .topics {
                height: 260vh;
            }
        }

        @media (max-width: 300px) {
            .card {
                height: 7cm;
                width: 6cm;
            }

            .card img {
                height: 5cm;
                width: 5cm;
            }

            .content h2 {
                font-size: 2rem;
            }
        }

        @media (max-width: 270px) {
            .head h1 {
                font-size: 40px;
            }

            .head img {
                height: 140px;
            }
        }

        @media (max-width: 260px) {
            .time h4 {
                font-size: 2.5rem;
            }
        }

        @media (min-width: 730px) {
            .cards {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>

</head>

<body>
<div class="head">
        <h1>Invitation to Farhan's presentation</h1>
        <p>Farhan Tawfeeq is organizing a presentation and you are welcome!</p>
        <img src="https://lh3.googleusercontent.com/7HdcPfDj4blGJ6Qad9fWRtqe2ddCMo-FrZJUpNQj_wCYYlvi7GSAiq6zE0KxEBucj4yUqqF48KhvKbZ0Ix0-T5ff8j5Un35pgvmQWuWP_JjwJYHstAPO_nSAo3SAD7nxpdgcCtsdyqRznkKIDnMUMRdb_dd44TyIuUavvpxy1SureC702vOO_Gru8QD6JAxsUAqZDdCBlu_CVN3xv-E4sOwu82IkKdxrSh6o5hk-hejbMO8AJHsevMwyaDlWEgrv08u3RLkSJcBeQdecW0BbfiLnyIGsJAz-7VEatRm5DXihn-H9Ki4LCU9-q975A1RFTNyymcANw5Fuhr9niAj1A3VR_L2DlaRSCGdJ1_2NspeQ61D1sodxfdNKztI5KeMbve_UYNRcKWn_xfWCFjXMsTVPps_oww_5USHtaknMBxKGY2_Q1zNqIedhiuJ_Hyb3tLNiaMOaLJeu1__XuDIVJAHSUY11iBI28WmvicqqF4YoSiViB3qi-rwWchAxTc2WsedRtlgerpQyRQzJ0ZuY_sLyyJlCJyPVPpYaJkc6-iMBGyggDI8mdNPgJy3v377PFJi-dN59COQpsKO8xXOyskHAXhsOR1qqwm3ThpGCsVmZX4wh5I75HFnsFhwpK3rf77GpcsEEcOvuqxwTljN24clfEwgeU0-mxUcDBtq0tcwB4tl8QkGDvOy33uIrS3P6PJCJ0CG7lTdg3XpFUqDt1cFN=w341-h287-no?authuser=0" alt="">
        <div class="square1"></div>
        <div class="clip"></div>

        <div class="square2"></div>
        <div class="square3"></div>
    </div>
    <section class="about">
        <h2>What presentation this time?🤔</h2>
    </section>
    <section class="wave">

        <div class="content">

            <h2>Social Media</h2>
            <h2>Social Media</h2>

        </div>
    </section>
    <div class="topics">
        <h3>Topics Farhan is gonna cover this time</h3>
        <div class="cards">
            <div class="card">
                <img src="https://lh3.googleusercontent.com/4MNHh0xyYkrriNUEYLGMji9G4kIwZCctOqv2tXDr0TYJiVA5aAMlGXxztSPN2PBxDH0nDz7se0KxCkcxUEpcZ3rrTO9y6qkGdQ48TozZTvEgwhXA2u2MUSxObsmp0I3ADsT2gJKsRg_RPOR7Fwavg3uzllDeL-mdGsry6L1xoSrLR_CtLAvl80Jm3IZBK7rlzLfi_jMgte9GtdQqjAUY0rP59Rsxlm3FPDCi7kzYegj13N4RDuTx-iw4yuvQbRIBnlHCQ9-e_CFdvfHJCncrUc01W-g3rEl1a12slVBwYHxwmm11yjw-uHwv6La5pOYIRZMED9-3ciuaOEAXKl2NpbGMxN3URge6Cs3NpEAfiZvlqrjVImLQLTxGwD4frqMyrRMFgrroIJtQwU65Ur2Xi37opK59t2C8Q8hw14m0sJeGJWfh8AOxq_xLttFfDaxPENoTpxRzGPT3jWpFzGD4Eq-R1rT_gEjIi3wkA41W8d4KBkR9Wk1I2wvjHwN-NQr7nPEQmcp8qqbiy8e1z4IxjezPfzXsU6BDfmSNzyw11595beSQrq0DVc9-5Mo6sFOAbzfHuU3jAukCFTJLQ_A_mFiQZC0ERKiZB7LPMuY0UdI8mq9Qe484IRvES5efRfmMY3Dx9aiIqIYX6t9P1y4z4at-M3TIh7AX9l-g9Li4vgsUOJ8v-Q3peS9wIMqxEJMj4I1RxILeJKfSBbbelQAJanYR=s474-no?authuser=0" alt="">
                <p>SOME SOCIAL MEDIA APPS</p>
            </div>
            <div class="card">
                <img src="https://lh3.googleusercontent.com/uhzX8GtZtNJT55Acy8mSBwmEwXi8K_AGB0icyz1Vln_LnB3SE3tqF40kcgstMdARnd6weaf06ttZnEzuLpwjkAOQz56PH88toDqWam5SH2LkXMNh7BD89oRU1nknvMKBVQWJ57qx9m4hqsRM9y4CFiS1RkqTb-5B1Gm7zzYkMfXcgRQQ1fG5GYfbTbgbXwBv3ZNkR1YVhLJsRMwhDCymJbfY9ZT0rmuQCUw2PIX2AxkJKzwaS5eELN7KE3pi45PTKfdq31VWUgG1KKw1Bw3aav0QyxmBNgqHAxG7QUqsDN8fKaIH7FxE9xm-r7f54NwOSgKUkDeqs-PA07KX2td4hqY83lG_Ve2Fxr0zTb-8WZi9AT-2qN7KaSGSIgeaX_Mv89UryU3A2NDvFEJPV-2dW9HDAJg8dr-JxbgF9gb2xPghQgu63NiUY2shir3YhI6SAn34PiFezpuKGX4wa045MdjzZ5r6kQG_N4uvNRBvgV_p-9LXzHbN-ysdoOYLXHruWBaFAy6nUO90O623WjMxZNiTiVhtU4AHsQWrHMAd3EfF9uGRk6xPZiudgxUO0z0G9ZdZPdK75XpDXDG-STQpyRlpLJkf-UAUdQLX7cvk-bY9OIUr8NHt3DaKEXx4-3HmtMtjQgOPBQWde8GtyK8FcB7mYcxhZ_lxlTQF43666NKaqzYC3qGgnZByWnw7obSaj3VtalvRhuQhQhqGDXBKujuj=s474-no?authuser=0" alt="">
                <p>HISTORY OF SOCIAL MEDIA</p>
            </div>
            <div class="card">
                <img src="https://lh3.googleusercontent.com/WOjfeb7VZhN7C9W9AhEmj5t4BrLXz3ic5HVk13fwdHxj8sSyZpXH-va79SokrOUcVsN_QDiTs2u85HbMrlwChHYyLS2iUevoIFub7KDDUbh1FUhIcdIAM-EREHmhFiCyrdQpqS3HJIV5rOu5JoXc3WZvzXjH-FjIfivNOLDFHfYYhxaTfqOMxxqZ1JXDq5Fa2oOFajvw4PQPE1e7ACb4u_ePz50xDVnfB-zb1V6NKXhIZMN-8VN-kGanHJEaiQaHToI2KMP2pQn0JcXK9uRKOfym-CArfFAZQcLrUAJEOc3oaydWdCU2xoYMwCKB5FYgxBAT0gA5ITik2IH57RBZJYDVBjgqUIj_jg9hYlVDOULc15QPRClRcdyVQw2BkrSFaKEn7jasVYzopeYRoK6Z7xvvGz08ZDimwW0p7dBQwbXlIJpOcpKzxTpnlyHCgyDg6rWEWrh8fd7yDKGC8We3e6tSj1-ucPhxHI2Z4hjD0S5IncRXbKxGQug7rgkfGGFAwF8UK3Z-Nzg0IBPl9oYfOdV6nFAWZMPngm_pftYfeWsxA2BhYk4s70gHaHXtoqVFuB_kgIPf6L4WjCLOmiPu3A7aVHuFvQWJhqg50NN_D1m06xX7nAs0lwpiXj5m1FCAjvPlRWcoih98EPMymXNQiy8fd1oAoyhQimWWvUVnMD8viS-_IWGfs1p90RJgwVi0Wzsmq3J5S5N8v1YuMBfNn8l9=w290-h291-no?authuser=0" alt="">
                <p>RISE OF SOCIAL MEDIA</p>
            </div>
            <div class="card">
                <img src="https://lh3.googleusercontent.com/snucI0GK43IXLOPu1pXfRImCSAjDSUC9yJym01tDP7sebTSJB6W0YwBRT2dXVcyL9ZmAaDVHH7YrhncWw0iVQOjN-vgZbanhJD6oVePulyE3eC6tQRc1aGkf4AlTAijhXG8F4ycAK0p791wRxvZdZj6stvu1DWOEp3akTvot6JnV4EtEWlGqKbqoekhKggUsY2YqYhuGm1xXND6n0e9ir_U1awhHzscEg7dr45CNSnWIVubZwkTZM7sg6LMbqvqWZxmNSI-QET28CaSiPJXtkrFKTLByu5NaDUoBUW4c87UNAmkO782CsrB0EO2PV1nXcD1lWCreYDl3Bd59QqIjTGNtiqSbBB6Xdk2e8P8l1JXxErrBryf-3fIcE4ZMn9ziyfRv4j2CnayUy7K0dztjcgYzIB0ZRzbhT1-4NBQDAnvI6V-fR_m7YL5oCihQ0xJzUfwMmZRsm1UeA-NjEp9igEtsw_U3O-WYK1GqWPxa3m_x8FHHS_vGBwfRRnf0F9v3U0ScsM4gUFmmp4IcSIUn-mc3Mcq34hmLCgF-EJ0kmYIV23NkoAfDiqJ0xDJLpcqw8eQuypzYUwz2Mq5y6y9M9yJBMnW1vhx3zT7oJrLQ2FXvGNpOhVolk_PwBSv7BiyPC_VVKO3esPHtcd99znbW8rtL6UlpT0NhWLQ-rDnuz2QgUttdOGooqwsGRzt0jJMEkkvBnAHIkl_kr-ljr4I4mUIV=w305-h306-no?authuser=0" alt="">
                <p>IMPACT OF SOCIAL MEDIA</p>
            </div>
        </div>
    </div>
    <div class="one">
        <div class="ppt">
            <img src="https://lh3.googleusercontent.com/cx_5ZSoprbj3fxdbSgmaY6vn8CVTH5UbJ-MZH6rROyX1Ocb9mDYBR6IKCoZRmHaEWfYRfKWZh44KcJybfPfhLD0RYHfAdJPwDaUpp8SAyc-Ctd3btOVD2zStiWSQXoc0644d47Q0iUN9MiSSjHD0XlwxMJuDrdHsCWvVG3mpMqailE1Qh5GuBf3MPyrOm1fWKmF3l2M7iHTR_oNI5APlxJIVlmqw_Fu-sRvEFTxlUikc8p6_nTiO0e5dNsydghCV65i4AVBMb2jFoaMIXLA5NqdRF-LPC4U74bH5YKvD6-Xt7YNBgqRz1TIOq-SolCKgM0MSvaselMus0-ZXZHlQfhylnz2vCAg-EvKSciIiKCWodc2I53Q99ZBZuxFJXsfnveSTYPe1t_yPSVjQDxLaYbIhLapjkc69GPDMKLoj45i9_IQY8aSixU0MuAG11nMX9X6d9X0070g8AGP_iR3b2FOUmXoVnLNq7BJ02u49TiOaNFKJWxkr4nIZfyMVjIbKvuemkwc3a_gM0puxcdtp7kRg2UxM6OtGphLfQCDOQtcuvtljZSThiyQo4IA9nnR0RSs3RCcRQGR3AHcg0WKWkiWpnrXXhmawt6PY4onUifhTXOfg1B5orpyzzKNkaJxyog0qm60PuFKyg3fZExwFAmCHCjZJlMfWN5mGAEV_ciQDoDUBXrOsv4sQXSR85QU45b--_czkN40Z2au3oA7phZPS=w196-h785-no?authuser=0" class="img1" alt="">
            <img src="https://lh3.googleusercontent.com/g1kVbAZLVhm6Sx3evcy2d_aTR0mkaBZ6LuudBZhTx_LebK3vk_CmY9Vg7S3p3hq7biraihe1GNBslw97RDfPjqAwkVDvoU99L2p7UDzED2IbiPqtRCQGAiLplHX1qOrXflYfhkNOqqHijB9GEnMeW5Gcxo2IesfsbQmJcouAKiydGoY8E_TB8du9oXkh5BxM6TG7QKW3LUuQQgiao2zL8xV4kWcVO1TYTjkjXzitqTK8HbX1nxbuqNQfNDVg6GAw6fkbBaEFC8n1Xl4t9aF42Tm8KBBzay7HjBCrKqUCUNNxBsz8h7sofnyOMl1_3qVa2dBNOtjvACQlu0U4tXOTETkNfK4eWS_uYGkZB1helxyT35snGLa_rI0anHikksX39M6yltMM4UdECLsJCQT6SrQ8t0-Qvyyn9aTh___J3ZVmWxULZaCHc1ULckygnUKJnJVFvRIOKVD0Px80ZR6YmPXUfU792XItp6ARNc6Q_7Ql3xCFci1zzEhchU9j-6Lm3FQ60cjry1sca26J77hK-f7-VFISvGUCXg2-xmLkGG8tE2Npi-PexBCLck6S0NJGu5junfMvQxekpbeXLEUH2elsKk5Ds3kGhhPj6j0hBnNSl3Tc8x-qciDu0RNXUakqbEYiV8STvpWtIq16afQ7qB3BBBf4k9P7d5y4J_ajE8MRQJbZXA4o99YJ-W4DpxW8E8Y77aLbCBT1dAVESf7FDRSa=w68-h270-no?authuser=0" class="img2" alt="">
            <img src="https://lh3.googleusercontent.com/e7SD-T0rRupJPbJZ4AJPBeidc3x3jKSwYEBjiummxeZ19Lq4MWsVIlUUTKsVftjAERaqaKj3kikl8CCAx9xf6AvS92d2kJdP9zANq3vEBK1-Mrqrz2XwF1sfuvqRyJ9VJzuh1bj7ExW_AUKxzSHOoYpBNxxA7YCZWnuD4mxxAOtsT4vPHld-Iwa2hWE-CsGUjQEgj2cllMia810fZey0fp2EpxTYJTDrSLDrQxWoQfF0RaP-Qoh93WiwfTSdhz_q74Ucpc2ZN6mqFc-LvksiJaX-7rHU4-RZJkA9nII3ytJvi6pVHXpdATTIVCxrgvi34j9WsyP4PgH2NVFmTQW5kQepYtod7b-0-aakhVOgUESjpt1jiXse4IIdI5yjUtfqdq7oAo9gxe5QeRbFA7N171VX9lci-RIah43uuou44x0kqbZ6Hx4WnLrijnN0YxwK8-he6krEZ5BWge7GPK87A_DAY9FI133mIRgamgh5Ciz4bCnk08BGg-i-5mmg66drWoUqNKNTJ2WwpYyctMNmHSPexizA0X1XwY5AtPgmj_GWF78CZqjt-fKbKa4KiwNDv7mDonQOex3pf81iJWbriCC-lwirqogZZcTXDaV7ttphu1S1doaxlBZtMI8uOLR2enTKXZbqTryGuNOEhaqR-UW1zwayFSk88emKHsjUpUVHFlK-9u9dap1IWMX9KmRyyTiHf6ywpVsK-RlUyazPGL4l=w197-h785-no?authuser=0" class="img3" alt="">
            <img src="https://lh3.googleusercontent.com/GfIcT34aGNaofIMnqRoXEigpzo3x8W8-b-BdXA9Vkv4vMek-PMKx6Ce8K4BYbFwc0-PA-Vs1iyED9v_-DHsMstvdvxnp7_5SHAEZvddAiaXaAhvgchQLFF9mkmcu8xNrL0fgb9rQ7NmFfGa1kSQZe46y1uSG5vE_GSSFq8NWum-lnzx3KfkMw6T4-BecNPa_iYA-riZXcMSOGDYMz7X7YIX-xm2kb68RtNJCdA7TIGYRI2aK59-eVI0GwSS6BodBT4MfXuBZzRRSP6SK20MnqCWX2VOBUAXbcKkK45zLSoSl7HNAIKAKnBDhPRhEDmVTyzNqhpZeKbjN55SYG1UqyYvpTFcCDiCQJwUbiDF8oxki4niZP4yfboXil_Ufnz2j8sHghLEWi1W2VEXlMRMHojvMzPTQCrbE-OVpZBgdT5IrR9cVYfBTlw8H3UWk5NpW9YneFf0Qr0UixtKm9Fu8n7i3sE4Lei6wqU86otTqxM7O4DidsXxa_E1Q-Smuc5heS76MEMu3dye91lh-QZCPwNEyz4Nt_59Z3NFPG2PkCk6sQDnBrPMNcG_-X-l9t88THbun60B--JkoVIbQ-s2jVtLUF1ZNkcxBccfUwbmNFN9mIzc58rw5DshxhIUIjPe_yabDwPxOn_ywMuub5Ec9QHX8Ybcw7iF0qRjb4U_aUYtfMXhTrNqS4ao_xs6pQugHl81SqrhZX6i9j05KrkhP0QIb=w74-h296-no?authuser=0" class="img4" alt="">
            <img src="https://lh3.googleusercontent.com/2It3B1QvTo5l8rHle0v-OWqj3OOjGXqETF2sJnvTvh3OvYJuwGbcnSAfAObhw1jiuHr62z0uybxxyTiHqYbfoesSssZ_Ap_etYU32YNwh1Qv7VI5ldzsU28BvhBfD7MqGPkZh5nFxOEl4hRV9IUT3bVh_kb-Xbqrzmfw81FTIRuvHHhKWSOlj03nv48zJ2KF69SDaNZs0zrteLuoYLEUh0WiRDGc3_1VRdmcDy7g7eE658gfD_nzHpkW8Va6Unjy8PEtssewhv2NUBoxHzMd7dMcvl_M38GArGqS0dke-c_7qbMe_vd4InaPh39akb8kgmq9bWWzebVqBqNGVGH39sqI1f0Bc4Jkf2KURY5pQQPgXKb1opJdjTTV1CuIIPj-yTB3PG-msRvGw2Sdo5nt9GLZJOd5yMK15lJaqQc080IkvKwC-a3WPOhBCzXYjAJ6xoKcfXPP6HcXMMmgfi2Xx-5mQrlKlCiHd-PHmG9NzLDY6w6O8-OUn84iWlV98ANCaV7wUioLhTOcdF-Go1N5jTS11KwCsvwH0yCUDNLDz4V8sV3-1eaAlGr49HZRw9c0YJxHzmA357dglvzKbEtQscuN5NCCvZKRKLU3ueXVULesloNBFCrDcKGSzRM7ZJh5GfOWU52L3t2bElyCrnipAgjB-5E-zaS8rSYe_vjSkhpmHXFmqIllQpIfD8K_oztvm8T6cxTBb94PFxUT0rl-E61H=w197-h785-no?authuser=0" class="img5" alt="">
        </div>
    </div>
    <div class="time">
        <h4>TIMINGS FOR THE PRESENTATION</h4>
        <p>The presentation will be conducted on dd.mm.yyyy at time </p>

    </div>
</body>
<footer>
    <h9>Open Source Copyright Farhan Tawfeeq 2021-forever</h9>
    <a href="">Source Code</a>
</footer>
