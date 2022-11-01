<div class="contact">
    <h1>Vibrate with Your Fellow Music Lovers</h1>
    <div class="btns">
        
        <div class="btn">
            <a id="contact" href="mailto:matt@polp.app" target="_blank" rel="noreferrer">
                <img src="./contact.png" alt="contact us at matt@polp.app">
            </a>
        </div>
        <div class="btn">
            <a id="twtr" href='https://twitter.com/POLP_app' target="_blank" type="button" rel="noreferrer">
                <img src="./twtr.png" alt="twitter">
            </a>
        </div>
        <div class="btn">
            <a id="join" href="https://docs.google.com/forms/d/e/1FAIpQLScfZlyDLwCOQYIVWgBqh2HJEJYtDOKV6JiPsk4o1O8mvk-w_g/viewform" target="_blank" rel="noreferrer">
                <img src="./join.png" alt="Join Us">
            </a>
        </div>
    </div>
</div>

<style>
   
    img {
        width: 150px;
        height: 150px;
        /* padding: 10px; */
    }
    .btns {
        display: flex;
        margin: 0;
        padding-top: 80px;
        height: 0;
        align-items: center;
        justify-content: center;
    }
    .contact {
        background: url(/contact-bgd.png);
        min-height: 400px;
    }
    
    h1 {
        margin: 0;
        padding: 25px;
        line-height: 1;
        font-size: 2em;

    }
    .btn {
        min-width: 20%;
        /* display: flex; */
    }
    #contact {
        cursor: pointer;
        border: none;
        background-color: transparent;
       /*  width: 150px;
        height: 150px; */
    }
    #twtr {
        cursor: pointer;
        border: none;
        background-color: transparent;
        
    }
    #join {
        cursor: pointer;
        border: none;
        background-color: transparent;
        /* width: 150px;
        height: 150px; */
    }
    @media (max-width: 800px) {
        .btns {
            flex-direction: columns;
        }    
        img {
            width: 100px;
            height: 100px;
        }
    }
</style>